# cnt-4714---project-three-solved
**TO GET THIS SOLUTION VISIT:** [CNT 4714 – Project Three Solved](https://www.ankitcodinghub.com/product/cnt-4714-project-three-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;40676&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CNT 4714 – Project Three Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<strong>Title:</strong>&nbsp; “Project Three:&nbsp; Two-Tier Client-Server Application Development With MySQL and JDBC”

&nbsp;

<strong>Objectives:</strong>&nbsp; To develop a two-tier Java based client-server application interacting with a MySQL database utilizing JDBC for the connectivity.&nbsp; This project is designed to give you some experience using the various features of JDBC and its interaction with a MySQL DB Server environment.

&nbsp;

<strong>Description:</strong>&nbsp; In this assignment you will develop a Java-based GUI front-end (client-side) application that will connect to your MySQL server via JDBC.

&nbsp;

You are to develop a Java application that will allow any client (the end-user) to execute commands against the database.&nbsp; You will create a Java GUI-based application front-end that will accept any MySQL DDL or DML command, pass this through a JDBC connection to the MySQL database server, execute the statement and return the results to the client.&nbsp; Note that while technically your application must be able to handle any DDL or DML command, we won’t actually use all of the commands available in these sublanguages.&nbsp; For one thing, it would be quite rare to allow a client to create a database or a table within a database.&nbsp; Note too, that the only DML command that uses the executeQuery() method of JDBC is the Select command, all other DML and DDL commands utilize executeUpdate().&nbsp; Some screen shots of what your Java GUI front-end should look like are shown below.&nbsp; Basically, this GUI is an extension of the GUI that was developed in the lecture notes and is available on WebCourses as DisplayQueryResults.java.&nbsp; Your Java application must give the user the ability to execute any SQL DDL or DML command for which the user has the correct permissions.&nbsp;&nbsp; Note also, that if the user wishes to change databases in the middle of a session, they must reconnect to the new database. Their user information can remain in the proper window, but you must click the reconnect button to establish a connection to the new database. You do not need to support simultaneous connections from your application to more than one database in this assignment.&nbsp; However, you will be able to start multiple instances of your Java application and allow different clients to connect simultaneously to the MySQL server, since the default number of connection is set at 151 (see your Workbench options file under the networking tab).

&nbsp;

Once you’ve created your application, you will execute a sequence of DML and DDL commands and illustrate the output from each in your GUI for two different users.&nbsp; For this project you will create, in addition to the root user, a client user with limited permissions on the database (see below).&nbsp; The root user is assumed to have all permissions on the database, any command they issue will be executed.&nbsp; The client user will be far more restricted.

<strong>&nbsp;</strong>

<strong>References for this assignment:&nbsp; </strong>

Notes:&nbsp; Lecture Notes for MySQL and JDBC.

&nbsp;

<strong>Input Specification:</strong>

The <strong>first step</strong> in this assignment is to login to the MySQL Workbench as the root user and execute/run the script to create and populate the backend database.&nbsp; This script is available on the assignment page and is named “project3dbscript.sql”.&nbsp; This script creates a database named <strong>project3</strong>.&nbsp; You can use the MySQL Workbench for this step, or the command line whichever you prefer.

&nbsp;

The <strong>second step</strong> is to create authorizations for a client user (in addition to the root user) named client.&nbsp; By default your root user has all permissions on the <strong>project3</strong> database.&nbsp; Use either SQL Grant statements from the command line or the MySQL Workbench (see separate document for details on how to accomplish this task) to check and set permissions for the client as follows:

&nbsp;

Register the new user named <strong>client</strong> (assign them the password <strong><em>client</em></strong> – ignore the MySQL warning on weak password setting) and assign to this user only selection privileges on the <strong>project3</strong> schema.

&nbsp;

<strong>Output Specification:&nbsp; </strong>There are two parts for the output for this project.&nbsp; Part 1 is to provide screen shots from your application which clearly show the complete query/command expression and results for each of the commands that appear in the script named: <strong>project3rootuserscript.sql</strong> available on the course website.&nbsp;&nbsp; There are eight different commands in this script and some of the commands will have more than one output capture (see below).&nbsp;&nbsp; Part 2 is to provide screen shots from your application which clearly show the complete query/command expression and results for each of the commands that appear in the script named: <strong>project3clientuserscript.sql</strong> available on the course website.&nbsp; There are three different commands in this script and some of the commands will have more than one output capture (see below).&nbsp; To produce your final output, first recreate the database, then run the root user commands followed by the client commands.

&nbsp;

<strong>Deliverables: </strong>

Zip up all of the .java files associated with your application as well as the screen shots from each of the commands specified in both the <strong>project3rootuserscript.sql</strong> and <strong>project3clientuserscript.sql</strong> files via WebCourses no later than 11:59pm Sunday

October 15, 2017.&nbsp; Be sure to clearly label each screen shot.

&nbsp;

&nbsp;

<strong>Details: </strong>

Shown below is a screen shot of the initial GUI.&nbsp; Notice that there are drop-down lists for selecting the JDBC driver and database URL that the client must select.&nbsp; The client must also specify a username and password (MySQL option) before connecting to the database.

&nbsp;

You should provide buttons for the user to clear the command window as well as the result window.&nbsp;&nbsp; The status of the connection should be returned to the GUI and displayed in the connection area.

&nbsp;

The output of all SQL commands should be returned to the SQL Execution Result window.&nbsp; Please note that only SQL commands can be executed via this application, we will not go to the effort of making the application display the results of MySQL-specific commands.&nbsp; (When a MySQLspecific command is executed, the SQL Execution Result window does not need to display any results, if you wanted to you could display the line “MySQL command executed” in the results window, but this is not required.)

&nbsp;

&nbsp;

Note that for non-query DML and DDL commands, before and after screen shots must be taken to illustrate the basic effect of the command.&nbsp; See pages 7-8 for an illustration of this.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/585.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

The GUI areas defined.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Screen shot illustrating an initial client connection.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/749.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

Illustrating the drop-down list of possible drivers that could be selected.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/949.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

Illustrating the drop-down list of possible database URLs available.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/444.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">User has connected to a database and issued a select command.&nbsp; Results are displayed in the SQL Execution window.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/429.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

A more complicated query:

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/977.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

When the user makes a mistake entering a SQL command:

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/762.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

The following two screen shots illustrate that your application should be able to handle non-query commands from the users.

&nbsp;

<strong>Before screen shot</strong> of a subset of the riders relation:

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/746.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">Insert command issued:

&nbsp;

&nbsp;

&nbsp;

<strong>After screen shot</strong> of subset of riders relation after insert command was issued:

&nbsp;

&nbsp;

&nbsp;

Screen shot illustrating the client user issuing a command for which they do not have permission:

&nbsp;

&nbsp;

&nbsp;

&nbsp;
