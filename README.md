Provides a foundation for developing with Magento Commerce in a Vagrant box. The machine is based on CentOS 5.5. 

The manifest cent.pp has some variables that control the installation as shown below:

* `document_root`, The database password to use for the site database.
* `db_root_password`, The root database password.
* `db_magento_password`, The magento user database password.  Used by Magento to connect to the database. 

List of installed software.
* Magento Community Edition - 1.5.1.0
* Mysql
* Zend Server Community Edition - PHP 5.3
* xdebug
* phpunit


[Ruby](http://ruby-lang.org) and [Vagrant](http://vagrantup.com) and VirtualBox are prerequisites.