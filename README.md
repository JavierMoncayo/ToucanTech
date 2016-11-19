# ToucanTech
Demo for ToucanTech.

For this demo I used CodeIgniter framework.
It's running under ubuntu serve and with MySQL database engine.

There is not intallation requierements, only, if you are going to use it in you owns machine, 
in the "database" file under "APPLICATION->CONFIGURATION(->database.php)" folder, please change the lines 78,79,80 to setup your envirorment.

About the database, I attach a .sql file to run under MySQL. The structure is only two tables, one of them with the
members information: (ID, name, email, id_school) and other with school information: (ID, name). With the column of
"id_school" in members table, we have the ralation to "schools" table.

About the way of programming, is based in MVC model.
  -Controller: Javi_Controller.
  -Model: Javi_Model.
  -Views:
    -Common:
        top.php
        bottom.php
    -Main view:
        demoToucanTech.php
    -Auxiliar views (for AJAX implementation):
        D_MemberList.php
        D_SchoolDetails.php
