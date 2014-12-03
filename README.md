code-xerox-php Readme
==============

This code is used to post issue on github/bitbucket repository via php server. Here is the step to run this code with server requirements


A) System Requirements:

1. Linux Server
2. Apache 2.0+ Server
3. PHP 5.2+
4. Enable curl extension
5. Enable register_argc_argv


B) How to Install:

1. Need to upload all the script file on the server via FTP or any other file uploader.

   a) issue.php

   b) inc/Auth.php

   c) inc/AuthException.php


2. Need to trigger below given URL on browser to post repository issue on the github|bitbucket (Please add your github|bitbucket login credentials in place of username and passowrd)

   e.g. http://example.com/issue.php?user=username&pass=password&repo_url=http://github.com/arjundevdev/code-xerox-php&title=Issue Title&desc=Issue Desciption
   
   e.g. http://example.com/issue.php?user=username&pass=password&repo_url=http://bitbucket.org/arjundevdev/code-xerox-php&title=Issue Title&desc=Issue Desciption
