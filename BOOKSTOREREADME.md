# JB's Books

A small business website for a bookstore using Drupal.

The site contains:
An "About" page, and a "Locations" page.

A Contact form with a "Contact" link in the main menu. Anyone, regardless of their user role, can use the form to send you website feedback.

This site also features: The views, strongarm, and features modules.

Features tracks Strongarm variable names: site_name, site_slogan, theme_default and site_frontpage.  Features also tracks the book review content type.

A reviewer may submit a book review with "Book Title". It should also include fields for "Book Author", "Rating", and a "Review Body".  All fields are required.

A "Book Review" content type with a block displaying the three newest book reviews.  This will also be tracked in the "Book Review" feature.

A custom "Reviewer" role.  The Reviewer role has all the same permissions as an authenticated user. They may also create new book reviews, edit, and delete their own book reviews, but not anyone else's.

The front page contains a coupon displayed as a block offering 25% off all Dr. Seuss books.  

## Technologies used:
- Local Drupal development environment.
- MAMP

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [MAMP/LAMP/or WAMP](https://www.mamp.info/en/) (for Macs)
* [Drupal](https://www.drupal.org/)


### Usage

* Go to my Github repository
(https://github.com/Evan-Alexander/bookstore)

* From your terminal:

* `git clone` this repository to your Desktop
* `cd bookstore`

### Start MAMP

* Click on Preferences in your MAMP window and set your document root to the top level of your repository.

### Import the Database Dump
* Open phpMyAdmin and click on the "Import" tab.

* Leave all the default settings and make sure the character set is "utf-8".

* Click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file located in sites/db-backup folder.

### Create the Database User
* Create the database username/password that Drupal uses to store things in the database.

* After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

* Select username and password.  Think Bookstore.

* After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.

* Then click the "Go" button on the bottom left.


* Visit your app at [http://localhost:8888](http://localhost:8888).





&nbsp;
## Known Bugs
* No known bugs

Copyright (c) 2017 Jason Brown

This software is licensed under the GPL license
