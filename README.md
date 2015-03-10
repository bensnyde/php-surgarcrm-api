php-surgarcrm-api
=================

PHP Library for SugarCRM's SOAP API

    http://support.sugarcrm.com/02_Documentation/04_Sugar_Developer/Sugar_Developer_Guide_6.5/02_Application_Framework/Web_Services/

- Author: Benton Snyder
- Website: http://bensnyde.me
- Created: 5/19/13
- Revised: 3/10/15


Usage
======

```
include('sugarcrm.php');

$a = new SugarCRM('crm.example.com', 'user1', 'strongpassword1');
var_dump($a->getServerInfo());
```
