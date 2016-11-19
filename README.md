# ToucanTech
Demo for ToucanTech.

For this demo I used CodeIgniter framework.
It's running under ubuntu serve and with MySQL database engine.
Installation
------------------------------------------------------------------------------------------------------------------------
1 -> Unzip the file "ToucanTech_JavierMoncayo.zip" where is all the frame.
2 -> Execute "ToucanTech.sql" to create the database structure and some example data.

There is not intallation requierements, only, if you are going to use it in you owns machine, 
in the "database" file under "APPLICATION->CONFIGURATION(->database.php)" folder, PLEASE CHANGE the lines 78,79,80 to setup your envirorment.

Exaplanation.
------------------------------------------------------------------------------------------------------------------------
About the database, I attach a .sql file to run under MySQL. The structure is only two tables, one of them with the
members information: (ID, name, email, id_school) and other with school information: (ID, name). With the column of
"id_school" in members table, we have the ralation to "schools" table.

About the way of programming, is based in MVC model. All the files I made are commented and has explanations.
  -Controller: Javi_Controller.
  -Model: Javi_Model.
  -Views:
    -Common:
        top.php
        bottom.php
     demoToucanTech.php -> Main view
     D_MemberList.php -> For AJAX implementation
     D_SchoolDetails.php -> For AJAX implementation
