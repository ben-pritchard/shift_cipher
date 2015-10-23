### DESCRIPTION

This is Drupal website features a module that encrypts a phrase.

The user is asked for the phrase, whether each character should be "shifted" to the right or to the left, and by how much. Punctuation and spaces are ignored.

For example, if "a" were the phrase, and we shifted to the right by 1, the result would be "b". If we shifted to the left by 2, the result would be "y".

You will seriously be like: **"zebbpb!"**

### Setup

|Note:|
|---|
|The username and password for both the database (named: "ben_cipher") and the Drupal Site Maintenance account are:
|- username: epicodus
|- password: epicodus
|Please don't tell anyone though!|

1. Clone the repository
2. Set the MAMP root directory to the project folder
3. Open PHPMyAdmin and import the SQL file in the db-backup folder
4. Select "Privileges" tab.
5. Click "Add user".
6. Enter a username into the "User name" field.
7. In the "Host" field, select "Local".
8. Enter a password and retype it. Leave the "Password generate" field blank.
9. Under the "Database for User" section, select only "Grant all privileges on database yourdatabasename".
10. Click the "Go" button in the lower right.
11. Visit localhost:8888 in your browser
12. Select the "Standard" install, click "Save and Continue".
13. Select "English" as the language, click "Save and Continue".
14. Under the "Set up database" tab, select "MySQL, MariaDB, or equivalent" and then fill in the name of your database, and the username and password you just created in phpMyAdmin.
15. On the same tab, click on "Advanced Options". Under "Database host" enter "127.0.0.1" and under "Database port" enter "8889". This allows your Drupal installation to work with an important command line tool named Drush that we will learn about later.
16. Then click "Save and Continue". This links your Drupal site to the database - this is not the account you will use to login and administer your site. After this step Drupal may take a moment to configure.
17. On the next page, labelled "Configure site", pick a site name (like "My First Drupal Site") and enter your email address. This can be changed later.
18. Enter details to create a site maintenance account, and make sure to save this Drupal username and password too with your database username and password. Thisis the account you will use to log in and administer your Drupal site.
19. At the bottom select the country and timezone. Then click "Save and Continue".
20. Click on the "Shift Cipher" link in the "Navigation" menu.
21. qbpq fq lrq!

### COPYRIGHT INFORMATION

GPL v2

### LICENSE INFORMATION

GPL v2

### AUTHOR

Ben Pritchard

ben.s.pritchard@gmail.com
