demande.tn
==========

The source code of http://demande.tn


Configuration
=============


Under /data you should add a new file called application.ini

~~~~
[general]
environment = "production"
use_url_rewriting = false
sel_application = "28607941e7d967b6a65e6546ca5a87b7"
base_url = "/"
title = "Demande.tn"
default_user = ""
[db]
type = "mysql"
host = "localhost"
user = "db_user"
password = "password"
base = "database"
prefix = "freshrss_"
~~~~

Database
========

demande_dev.sql
