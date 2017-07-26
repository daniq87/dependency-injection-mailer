Finished Code
=============

This directory holds the final finished code at the end of the
tutorial. To get things running:

    chmod 777 -R data
    php data/setupDb.php
    mkdir logs
    chmod 777 logs

You can also run Composer, though the `vendor/` directory should already
have everything it needs:

    php composer.phar install

Run the App
-----------

To run the app, just execute the `app.php` file from the command line:

    php app.php

The application shouldn't have any output, but if you tail the log file,
you should see content added to it:

    tail -f logs/mail.log

Have fun!
