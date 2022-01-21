# Adminer Plugin: No password
A plugin for adminer.org, that allows you to login without using a password. Useful for example, if you are running xampp with default credentials. Be very careful. It is not a good idea, to run mysql without a password, anyway. Use at your own risk. Don't try this at home.

## Installation
1. Download files
2. Copy contents of src folder to the folder you want to run adminer in 
(for example: in the htdocs part of your xampp installation for example)
4. Download current adminer from adminer.org.
5. Copy current adminer into folder.
6. Rename current adminer to adminer-script.php.
7. Installation done.

## Usage
1. Call [installation-url-and-path]/adminer.php
(for example: http://localhost/adminer/adminer.php, when you installed in xampp in c:\xampp\htdocs\adminer\)

2. Enter valid username
(in xampp root is a default username)

3. Enter any password you like -> you cannot leave the field empty, but you can enter whatever you like. It accepts any password.

4. Be careful. Have fun.

## Credits
The work is based on the very good job that Jakub Vrana does with adminer:
Jakub Vrana, https://www.vrana.cz/

The licenses the work is underlying:
* @license https://www.apache.org/licenses/LICENSE-2.0 Apache License, Version 2.0
* @license https://www.gnu.org/licenses/gpl-2.0.html GNU General Public License, version 2 (one or other)
