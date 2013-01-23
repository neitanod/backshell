backshell
=========

Shell simulation in PHP
(for our cheap servers that don't allow shell access)

Goals
-----

The previous description says it all.  It's just a quick and dirty 
hack to allow you to explore and run commands on your server.

It's security is IP based but current version lacks XSRF security checks, 
so use at your own risk.

Usage
-----

1. Edit backshell.php.  Add your current public IP.
2. Upload the file backshell.php into a folder in your PHP server.
3. Open it in your browser and use it as a non interactive shell.
   (i.e., don't run interactive programs like vim, mc, etc.)
4. Delete it when you're done.
