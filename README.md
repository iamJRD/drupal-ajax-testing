# Ajax and Testing
## By: Jared Beckler | Epicodus | May 13th, 2016
This site is to show the use of Ajax with displaying articles and to provide practice with testing on a module designed to take a user input of half a DNA strain and return the other half.

## Prerequisites
You will need the following things properly installed on your computer.
- [Git](http://git-scm.com/)
- [MAMP](https://www.mamp.info/en/)
- [PHP](http://php.net/manual/en/install.php)

## Installation
- `git clone https://github.com/jaredbeckler/drupal-ajax-testing`
- open MAMP and click "Preferences"
- go to the "Web Server" tab and change the document root to the project folder and start the MAMP server
- under phpMyAdmin click on the "Import" tab
- select the zipped database file from `sites/backup_db/` and click go
- after the database imports, click on `ajax_testing` in the database list and then click the "Privileges" tab
- next click the "Add User" link on the bottom and enter the username `ajax_admin`, change the dropdown menu in host to `localhost`, then enter the password `ajaxtesting`, and then click "Go" on the bottom of the page
- to view the site, use your web browser to navigate to localhost:8888
- admin username: `admin`
- admin password: `ajax`

## Known Bugs
**The database is currently correupted.**

## Support and contact details
If you have any issues, questions, ideas, or concerns contact me through GitHub. If you would like to make a contribution to the code, feel free to do so and notify me by e-mail.

## Technologies Used
- GIT
- Drupal 7
- PHP
- Drush

### License
Copyright © 2016  |  Jared Beckler  |  Epicodus  |  Portland, OR
