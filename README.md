Download Link: https://assignmentchef.com/product/solved-csis-3280-lab-8-book-o-rama-pdo-remix
<br>
Visual Studio Code

<ol>

 <li>Download the lab template from Blackboard</li>

 <li>Extract it</li>

 <li>Fill in the relevant code to create the solution and meet the requirements</li>

</ol>

Solution

Based on the Demo Code and the bookorama database. Create a Web application that allows you to add and delete Customers to/from the database.

You may use the demo code from Week 9 as reference to this part of the Lab, create the application so the following list of customers is presented and the Delete link works for each Customer. The add form should always be present unless you are editing, in which case the edit form should always be present, and the message should come up as to which customer was added.

<h1>Requirements</h1>

<ol>

 <li>You must use a database called “Lab08″, your username should be ‘root’ and your password should be ” just like the lab computers.</li>

 <li>You must use the PDO class we created based on the template provided.</li>

 <li>You must use classes you should not alter the PDO class we have created.</li>

 <li>You must list all the customers in the database and provide the provisions to add and delete Customers</li>

 <li>By default the Add form should be displayed, if the user clicks on the “Edit” action or link you must allow them to edit the entry they clicked on.</li>

 <li>You may only use one controller file.</li>

 <li>You must employ a static “Mapper” class to support your CRUD operations. Your Mapper class must use the Customer Class. You may not use any array elements that are not objects.</li>

</ol>

<h1>Structure</h1>

<strong>FileName                                                  Description</strong>

<table width="0">

 <tbody>

  <tr>

   <td width="263">inc/config.inc.php</td>

   <td width="417">Database configuration information</td>

  </tr>

  <tr>

   <td width="263">inc/Utility/PDOAgent.class.php</td>

   <td width="417">PDO Wrapper Class</td>

  </tr>

  <tr>

   <td width="263">inc/Utility/Page.class.php</td>

   <td width="417">Page Class</td>

  </tr>

  <tr>

   <td width="263">inc/Utility/CustomerMapper.class.php</td>

   <td width="417">Static Customer Mapper responsible for CRUD operations</td>

  </tr>

  <tr>

   <td width="263">inc/Entities/Customer.class.php</td>

   <td width="417">Customer Entity with getters and setters.</td>

  </tr>

 </tbody>

</table>

The controller class for your application, should be used to

Lab08_SWh-56789.php support All the CRUD operations

Hints:

Use the hidden input type to post hidden data such as the id.

Use the hidden input type to specify which action you are doing.

There are alot of moving parts in this assignment <strong>USE XDEBUG</strong> it will save you time!

Appendix:

<ol>

 <li>List</li>

 <li>Add Form</li>

 <li>Edit Form</li>

</ol>

STOP! – This is a pre-assignment submission checklist!

Did you remove any <strong>debug output such as var_dump</strong>