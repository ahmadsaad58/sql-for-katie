# SQL Practice

To practice SQL queries, you can use [SQL Zoo](https://sqlzoo.net/wiki/SQL_Tutorial)

To set up a local SQL Server (this is a database on your laptop) let's use SQLite.

Here is a tutorial for [Mac](https://www.prisma.io/dataguide/sqlite/setting-up-a-local-sqlite-database#setting-up-sqlite-on-macos)

It may seem daunting but you got this! 

First, we download the zip file (it is a compressed file -- better for transferring over the internet).
The file is in this folder (or repository -- repo for short). Here is the [link](https://www.sqlite.org/download.html) to the download page too in case you are having issues. 

Once you have downloaded it, double click on it to expand the file. A new folder should show up in your files app. 

Now we need to visit the folder in our `Terminal`. The terminal is a way to run commands on our laptop. You can search your apps for the terminal app. Usually, it is in `Utilities` folder in our `Applications` folder. 

Open up terminal!

Let's try some simple commands. First type `echo Hello`.

The command is `echo` and `Hello` is the argument. You are telling the computer to repeat Hello back to you! 

WOW SO COOL!

Now we need to get to our SQLite app that we downloaded. We need to `cd` or change directories (directories are basically folders) to the folder where we downloaded and unzipped SQLite earlier.

The command is `cd` and the argument will be whatever folder you want to go to. 

So, for example if you downloaded the zip in the `Downloads` folder, we would type `cd Downloads`.

Folders are in a path, so if folder2 is inside folder1 then you need to enter folder1 first by typing `cd folder1`.

If you ever get lost, you can use `cd` to go back to the home or `root` directory. You can also see which folder you are in by using `pwd` (present working directory). 

Once you get to the SQLite folder, you will need to type `./sqlite3`. This will run the SQLite application in your terminal! (`./` runs scripts and applications so you are running the sqlite3 application in your terminal)

NOTE: If there is an error: 
`Apple could not verify “sqlite3” is free of malware that may harm your Mac or compromise your privacy.`

You may need to go to settings -> privacy & security -> scroll down to Allow applications and allow sqlite3 to run. This is a security precaution.

WOW! We are there. We are using SQLite!! 

In this state, we are only using SQLite in its memory mode -- once we close the app (by using `.quit`) we lose our tables and everything. 

You can make a persistent database (one that does not get deleted after you exit) by using `.open --new test.db`. This will add a new file to your folder called `test.db`. 

WOW! We are done, we can add tables and run queries and do all sorts of stuff. 

Happy SQL-ing!! 











