Calculating Credit Score:
=========================

Traditional Credit Score Calculation:
-------------------------------------

 * 35 percent of the score is based on your payment history
 * 30 percent of the score is based on outstanding debt.
 * 15 percent of the score is based on the length of time you've had credit.
 * 10 percent of the score is based on new credit. 
 * 10 percent of the score is based on the types of credit you currently have

Mapping to iamwhoi.am
---------------------

### Payment History:

This is probably best emulated by reviews.

### Outstanding Debt:

Not sure how this applies. It is possible that 3rd party sites could use a transaction system in order to add ratings.

Essentially if a was accepted to complete a stay on AirBnb, it would be outstanding until AirBnB were to close the loop with either a review, or a successful completion. A timeout should probably be implemented and hence an expected date of completion would need to be required by the API.

### Length of credit

This could either be the amount of time the user has been on iamwhoi.am or more appropriately, the amount of time they've owned the accounts they're relying on for credit. We want to ensure that recent adoption of iamwhoi.am doesn't negatively affect the user if their credit would otherwise be good.

### New Credit

With the traditional credit score, users are only penalized for *hard inquiries*. A hard inquiry is one that the user authorizes. A soft inquiry should not affect the user. I see this working almost exactly the same way.

#### Hard Inquiry:

When a user is actively applying for something (e.g. a Couch Surfing stay) and authorizes CS to do a iamwhoi.am inquiry.

#### Soft Inquiry:

Shown best as an example: When a user's profile is being browsed by another user on Couch Surfing in order to find a host.

### Types of Credit

"It will help your score to show that you have had experience with several different kinds of credit accounts, such as revolving credit accounts and installment loans." - The more services that the user uses after an inquiry, the more this section goes up.

## Collateral

If the credit score were to be considered the goodness rating of the person, the breadth of the rating would be considered the number of sources. We are still missing the depth. The collateral in this case could be considered the weight of each credit provider. It's a reasonable assumption that a facebook user who interacts with a large number of friends is more invested in it than one with few friends or many trivial friends (those without interactions).

