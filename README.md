# Customer-webpage
https://moodle.savonia.fi/pluginfile.php/1476006/mod_assign/intro/customer.html and make a html page that can be used to search customer data and show it. Customers can be searched by name, street address, postal code, post office. The user enters the search criteria (or no search criteria) and presses the Search button. Data is fetched from http://animalhospital.freemyip.com/customerbase/Customer using jQuery ajax and displayed in the data table element with each field in its own column.

Example http://animalhospital.freemyip.com/customerbase/Customer?name=test&address=test finds all customers that starts with word test and address starts with word test

2. Add a functionality to previous to search by customer type by adding a drop down menu to it. Customer types can be fetched from http://animalhospital.freemyip.com/customerbase/Types. Types has to be fetched with jQuery ajax and added to drop down menu using JavaScript. NOTE! Service returns "customertypeid", which must be used to search the "customertype" from customers.

3. Create a html page that can be used to add customers to database. Customers can be added to same address as in task 1 http://animalhospital.freemyip.com/customerbase/Customer with post method.

4. Familiarize yourself with jQuery UI's dialog and add task 3 to 1 and 2 by putting creating customer information inside dialog.

This will continue previous tasks. If you haven't been able to do those, you can use this https://moodle.savonia.fi/mod/resource/view.php?id=839662&redirect=1 as basis.

1. Add autocomplete to postal code and postal office fields in search. Fetch and use autocomplete data dynamically from http://animalhospital.freemyip.com/customerbase/Customer.

2. Add a functionality to delete customers by adding a button to each row that can be used to delete customer. Deleting customers can be done by using delete method with jQuerys ajax command to address http://animalhospital.freemyip.com/customerbase/Customer/id.

Example calling http://animalhospital.freemyip.com/customerbase/Customer/4 with delete method will delete customer with customerid=4



3. Add a functionality to edit customer data in a a jQuery UI dialog by adding a edit button to each row. Updating customers can be done by using put method with jQuerys ajax command to address http://animalhospital.freemyip.com/customerbase/Customer/id, where id is the customerid of single customer.

You can get single customer data with either using http://animalhospital.freemyip.com/customerbase/Customer/7 or  http://animalhospital.freemyip.com/customerbase/Customer?customerid=7
