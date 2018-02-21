# LexiconDatabase

The releases of this repository contains that latest version of the Arabic-English Lexicon database.


From time to time users report errors/omissions; when problems are fixed, a new version is released.

To get the newest database, download the latest release. 

The contents of the downloaded file are as follows (in this example,for release 1.0.5): 
```
Archive:  LexiconDatabase-1.0.5.zip
  Length     Date   Time    Name
 --------    ----   ----    ----
        0  02-21-18 09:45   LexiconDatabase-1.0.5/
    35147  02-21-18 09:45   LexiconDatabase-1.0.5/LICENSE
      436  02-21-18 09:45   LexiconDatabase-1.0.5/README.md
 61122690  02-21-18 09:45   LexiconDatabase-1.0.5/lexicon.sqlite.zip
 ```
You should unzip to extract the embedded file "lexicon.sqlite.zip" and then unzip that file to get the database "lexicon.sqlite". (This somewhat convoluted process is necessary because of Github's file size limitations.)

Once you have "lexicon.sqlite", copy this file over your existing version.

(For Windows and \*nix users, the database is found in the Resources folder , underneath the application folder.

For OSX/macOS users it is found in the Resources folder of the application bundle.)

