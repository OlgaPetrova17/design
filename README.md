### Example Test Design Techniques

1. **Testing the registration form using equivalence partitioning**  
   Based on the validation requirements for the "Login" and "Password" fields on the registration page of the web application https://demoshopping.ru/, I created test data to verify these fields using equivalence partitioning and boundary value analysis.
   
   https://docs.google.com/spreadsheets/d/1m6-g1t1UTB0j--_spIMlZ785ieygOOAh5QJ_HXkIsmQ/edit?usp=sharing

3. **Testing filtering and sorting functionality using pairwise testing**  
   Based on the filtering and sorting requirements, and using the tool https://pairwise.teremokgames.com/, I generated test data for testing using the Pairwise algorithm as part of the course.
   
   https://docs.google.com/spreadsheets/d/19gt_udtANMW84m1MDBf3upMeo8tg1lQOBRrFcZhUElQ/edit?usp=sharing

5. **Testing the PayPal payment module using a decision table**  
   The actions were carried out according to the specified conditions. A PayPal account can have three statuses: valid, invalid, and blocked, as well as a balance attribute, which can be zero or positive. If the account status is valid and the balance is sufficient for the purchase, the user is allowed to complete the transaction. In all other cases, the transaction will be declined.
   
   https://docs.google.com/spreadsheets/d/1r6HogqnNIb8fbRzO6nFJzeuYiw3EvsjmyInTyiJvIYY/edit?gid=0#gid=0
