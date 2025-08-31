## ! Brick-Cats Setup Guide for ct8.pl ! ##
      Needs to extract the src first
              Made by 0lvt
-------------------------------------------



[DB Setup (required)]
---------------------
1. Go to the 'SiT_3' Folder and find the PHP file named 'config.php'.
2. In https://panel.ct8.pl/, create a new mysql DataBase (name it whatever you want and a secured pass you won't lose
3. In the file 'config.php', you will find the following line:

  -> $conn = mysqli_connect( "mysql.ct8.pl" , "m40457_modbc", "BrickCatsFR1!" , "m40457_brickymod");
  change "m40457_modbc" to the database username, "BrickCatsFR1!" to the database pass and "m40457_brickymod" to the database name.

4. Then connect to the db in 'https://pma.ct8.pl/' with your db credidentials
5. Go to your database and click import then download the file 'database.sql' in the site files.
6. Import it and you are all done !



[PHPHELPER Setup (required)]
----------------------------
1. Go to the folders '/SiT_3/PHP/' and open the file 'helper.php'
2. You will see this line:

  -> include("/usr/home/lvtkr/domains/ogbc.ct8.pl/public_html/SiT_3/config.php");

  change 

  '/usr/home/lvtkr/domains/ogbc.ct8.pl/' 

  to 

  '/usr/home/{Your CT8.pl Username}/domains/{your domain}/'.

3. You are all done with this step !



[Change banners (optional)]
---------------------------
1. Go to the folder 'assets' in the site files
2. Change the images: 'Banner.png', 'BH_HeadNight.png', 'BH_HeadSummer.png' to your banners
3. Done !



