Download Link: https://assignmentchef.com/product/solved-prog2110-lab-3-asp-net-mysql-connection
<br>
<ul>

 <li>Demonstrate the ability to connect to a remote MySQL database</li>

 <li>Demonstrate the ability to use a remote MySQL database</li>

 <li>Complete the exercise and demonstrate before the end of the lab period</li>

</ul>

Requirements:

<ol>

 <li>You must use two computers.

  <ol>

   <li>Computer A runs the MySQL database and will be used to query the database.</li>

   <li>Computer B runs a program to query or populate the MySQL database on Computer A.</li>

  </ol></li>

 <li>On Computer A

  <ol>

   <li>Create a database called SampleDb</li>

   <li>Create a table called Sample in the SampleDb database with the following columns:</li>

   <li><strong>SampleId</strong> (integer) as a <strong>key</strong> with <strong>auto numbering</strong> ii. <strong>SampleData</strong> as a variable character string of up to <strong>10 characters</strong> (should be validated)</li>

   <li>Create a user called “<strong>superuser</strong>” with access from any host, and with full privileges. This user should be used to connect to db. This can be done by issuing the following command in the MySQL  command environment:</li>

  </ol></li>

</ol>

<strong>CREATE USER ‘superuser’@’%’ IDENTIFIED BY ‘Password1’;  </strong>

<strong>GRANT ALL PRIVILEGES ON SampleDb.* TO ‘superuser’@’%’; </strong>




<ol start="3">

 <li>On Computer B, run a program (Look the sample app provided to you in Module 06 called <strong>MySQL .NET Demo</strong>. )      that you write with the following specifications:

  <ol>

   <li>Create new app called <strong>SampleApp</strong> (ASP.NET web app) similar to <strong>MySQL .NET Demo </strong>windows app</li>

   <li>User should be able to list all, list specific record or to insert new.</li>

  </ol></li>

</ol>

When inserting new duplicates should not be allowed. Also, after record is inserted display all records including new one.   c. When list all is specified data should be sorted in ascending order by SampleData.

<ol>

 <li>Use appropriate ADO.NET objects to retrieve and insert data. You will be asked questions why did you used certain objects.</li>

</ol>


