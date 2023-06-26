1) Create Custom Extension with name MageChimp_PostCode

2) Backend In Admin
A) Create Custom Grid in Magento admin under menu:
MageChimp -> PostCodes ( It should show list of Postcode List)
B) Add/Update/Delete - Button for PostCodes

3) Frontend:

A)Add one Text box on the product detail page before the 'Add to Cart' button. One Submit button beside that textbox. It should take PostCode as input and submit.
B) Ajax functionality to check whether PostCode already exists or not. Once the Customer hits the Submit button, ajax functionality should trigger and cross check if PostCode entered by customer is there or not. (From the list where admin do add/update/delete postcodes in admin panel). Based on the result it should display an error or success message.



Create a Magento module that will sync customer data into a third-party system. Extension should have the capability to automatically sync the data for a new customer created or existing updated through Magento events, also admin users should be able to trigger a manually sync though mass action on the customer grid from the Magento admin panel. Create a dummy php API on local what will act as a third-party system.

Logging feature is good to have -- Add logs of all the activities happening while code execution 
Make use of Inheritance, dependency injection, interface, abstract class and static methods 
Organized code base using helper/libraries will be a plus point 
Standard PHP code guidelines should be followed 
