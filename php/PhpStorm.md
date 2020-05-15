# PHPStorm Setup 

## PHPUnit

### Using Symfony PHPUnit Bridge 

1.  `composer install symfony/phpunit-bridge`
2.  Do an initial run of `.vendor/bin/simple-phpunit`
3.  Go to .vendor > bin > .phpunit > phpunit-{version}
4.  Copy absolute path of `.vendor/bin/.phpunit/phpunit-{version}/phpunit`
5.  Open (In PHPStorm) Preferences > Languages & Frameworks > PHP > Test Frameworks.
6.  Select “Path to phpunit.phar"
7.  Paste copied link into “Path to phpunit.phar"
8.  Under “Test Runner”, check “Default configuration file and choose path to main phpunit config.