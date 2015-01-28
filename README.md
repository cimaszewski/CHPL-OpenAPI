Certified Health Product List (CHPL) OpenAPI 
============================================

This application design to provide the HHS/ONC open data for CHPL into a Open API standards as JSON/XML


DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources


REQUIREMENTS
------------

	LAMP Stack
	Yii MVC Enterprise Scalable Architecture


INSTALLATION
------------

Install the application by moving into a web server and connect the database where the CHPL is. 

Application can be access via the following URI
http://localhost/basic/web/


CONFIGURATION
-------------

### Database

Edit the file `config/db.php` with real database configurations, for example:

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=chpl',
    'username' => 'root',
    'password' => '1234',
    'charset' => 'utf8',
];
```

Help
----
gajen.sunthara@post.harvard.edu