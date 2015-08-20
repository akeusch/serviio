# serviio
Startupscript for the serviio media server 1.5.2 with CentOS 6.7 by arthur@gmx.ch

Serviio is developed by Petr Nejedly, who currently lives in London and works as a freelance Java consultant.
http://serviio.org

This Git project was started to discover GitHub.

Excurse for the following error:

I got the following error when I tried: # git push -u origin master
error: The requested URL returned error: 403 Forbidden while accessing https://github.com/akeusch/serviio.git/info/refs
fatal: HTTP request failed

and no password was asked.

The solution was: #unset SSH_ASKPASS
