## PHP Coding Standard

[Learn More About PHPCS](https://github.com/squizlabs/PHP_CodeSniffer)

#### Installing PHPCS with Composer
<code>composer require --dev "squizlabs/php_codesniffer=*"</code>

- Copy the phpcs.xml file and paste it to the root of your project.
- You can set your custom rules in phpcs.xml file

##### Running phpcs and adding an alias (macOS, Linux)
<code>./vendor/bin/phpcs</code><br>
<code>alias phpcs="./vendor/bin/phpcs"</code>

##### Running phpcs and adding a shortcut (Windows)
<code>php vendor/bin/phpcs</code><br>
<code>echo @php "%~dp0vendor/bin/phpcs" %* > phpcs.cmd</code>

#### Code Editor: =============================================================
- PHPStrom automatically detects the phpcs errors after setting the phpcs.xml file

  <img width="772" alt="screenshot-1" src="https://user-images.githubusercontent.com/29582239/184235991-5770682f-c480-466b-b5b1-0bab671acb12.png">
- For Visual Studio Code, you need to install an extension called [phpcs](https://marketplace.visualstudio.com/items?itemName=shevaua.phpcs) for detect the errors

  <img width="772" alt="screenshot-2" src="https://user-images.githubusercontent.com/29582239/184236018-0e294d7c-4184-47ed-bfda-e4f772bbb536.png">

