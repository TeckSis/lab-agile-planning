---
name: User Story
about: This user story requests a list of customers emails that have successfully
  opted in to email promotions
title: ''
labels: ''
assignees: ''

---

**As a**  Marketing Manager
**I need** a list of customer names and emails
**So that** I can notify them of marketing promotions

### Details and Assumptions
* We maintain customer details
* Customers have opted-in to promotions

### Acceptance Criteria
```
Given there are 100 customers in the database
And 90 have opted in to email promotions
When I request a customer email list
Then I should see a list of 90 customer emails
```
