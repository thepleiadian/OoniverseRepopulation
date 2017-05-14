# OoniverseRepopulation

In order to make this work, you will need a few things:

- Webserver capable of serving and processing PHP
- MySQL database
- My conversion to SQL of planetinfo.plist (planetinfo.sql)

Once you downloaded this repo, insert the planetinfo.sql into a new database. Open and edit the ooniverse.php file, and make changes as required in the database config section, so that the script can connect to your local database. Place the ooniverse.php into your webserver where you can access it.

Call and run the oonoverse.php file on your server. Processing the data will take a moment.

!! MAKE A BACKUP OF THE ORIGINAL PLANETINFO.PLIST FILE IN THE RESOURCES/CONFIG FOLDER OF YOUR OOLITE INSTALLATION !!

As soon as it's completed, you will see the output in your browser window. Copy the entire content into a text editor of your choice (Notepad++ for example), and save this as planetinfo.plist in the Resources/Config folder of your Oolite installation.

Start the game as normal. When docked, go to the F6 screen, select a system at random, and then switch to the F7 screen (info about system), where you can see the amended race information.

Fly safe!
