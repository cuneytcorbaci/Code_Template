# Code Template

Welcome my Code Template Repository.

## Error Reporting in PHP

To enable detailed error reporting in PHP, include the following code at the beginning of your script:

```php
ini_set('display_errors', 1);
ini_set('display_startup_errors', 1);
error_reporting(E_ALL);
