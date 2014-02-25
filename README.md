Setup
========================

```
$ sudo apt-get install apache2

$ sudo apt-get install mysql
```

enable [mod_rewrite](http://askubuntu.com/a/48363/37643)
----------------------------------------------------------


change db config
------------------------

```
$ vi application/config/development/database.php
```

Install Dependencies
========================

[CI-payments library](http://getsparks.org/packages/codeigniter-payments/versions/HEAD/show)

 `php tools/spark install -v0.1.6 codeigniter-payments`

TOOLS
==========
  [Sparks](http://getsparks.org/install) - a package management system for Codeigniter
     `php -r "$(curl -fsSL http://getsparks.org/go-sparks)"`


  [Getter setter generator for eclipse ide](http://pdt.plugins.e-surf.pl/features.php)


DATABASE MIGRATION
======================

 `http://localhost/birthdayforest-web/index.php/Migration_Control/create`
