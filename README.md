# eShopBrowser
Redirects the eShop's error page (when using a dns to block Nintendo's servers, for example 90DNS) to google.com

Here's a little mod I made to be able to enjoy and use the internal browser. This probably is only for people who block Nintendo's servers. 
This just replaces one out of three errorpages with a page that rediricts to google.com, and replaces the original eShop domain whitelist to allow all domains.

* The eShop unfortunately still starts loading until it times out. I'll see if there's a fix for that in the future.
* Screenshots cannot be taken
* No cursor, only the select box.

Installation: Put the two folders in your sdmc://[your cfw]/titles folder and make sure you have LayeredFS enabled.
You can change the icon of the eShop by modifying __Combined.bntx in ResidentMenu.szs.
See https://gbatemp.net/threads/tutorial-qlaunch-custom-menue-icons.519249/ for more info.
It is also possible to change the launch sound, but for that you'd have to edit qlaunch.bfsar and replace qlaunch_0000004B.bfwav.
