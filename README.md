litebackup
=========

Authors - Misko_2083, Jerry Bezencon

![](http://i.imgur.com/VvxXMwq.png)

Lite Back Up has 3 components/executables: lite-backuplaunch, lite-backup and lite-restore.
lite-backuplaunch when first clicked on asks the user if they would like to 'back-up' or 'restore' The program then launches the appropriate executable (lite-backup or lite-restore)

What Lite Back Up should do
========================

Documents example:

1) Asks the user what locations the program should look for documents (check boxes zenity dialogue).

2) Look for all file types within that/those location/s.

3) Asks the user where they would like to store the back up file, also performs a check to ensure that location has enough space.

4) Proceeds to back up those file types.

5) Completes with either an error or a success dialogue.

What the restore tool should do
===========================

Music example:

1) Asks the user where the location of the back up file is.

2) Asks the user where the program should extract all the music files to.

3) Proceeds to extract those file types to the chosen location.

4) Completes with either an error or a success dialogue.
