Tastydir - an AJAX file manager and directory listing
===================

Introduction
------------
I originally made this script in 2010 and [sold it on CodeCanyon](http://codecanyon.net/item/tastydir-an-ajax-file-manager-and-dir-listing/117167).
However, I've decided to make it open source, so that everyone will be able to use it and play with it.

**A note about code quality:** Tastydir works great, but I was 16 when I wrote it, so the code quality isn't amazing (it *does* come with lots of documentation though).

Installation
------------
Simply upload everything to a directory of your choice.
	
Documentation
------------
Look at the /doc directory in your browser for detailed documentation.
	
Permission problems?
------------
Your PHP scripts may be running as the 'nobody' user (you can check this in the info tooltip in Tastydir).
This is common on many shared hosts, and it means that Tastydir won't be able to edit files created with FTP.
SOLUTION: when you upload files with FTP or via cPanel, make sure you chmod them to 777.

Contact
-------
Found a bug? Have a suggestion? Contact me.
Contact:	vlad@vladh.net

Credits
--------
Copyright Vlad-Ștefan Harbuz (vladh.net)

Additional credits:

- Icons:
	* Silk icons 					cc-by 2.5		http://www.famfamfam.com/lab/icons/silk/
	* LED icons  					-				http://led24.de/iconset/
- jQuery:
	* jQuery						MIT license		http://jquery.com/
	* jQuery hashchange event		MIT, GPL		http://benalman.com/projects/jquery-hashchange-plugin/
	* Tipsy						MIT				http://plugins.jquery.com/project/tipsy
- Other:
	* jQuery UI CSS framework		MIT, GPL		http://jqueryui.com/themeroller/
