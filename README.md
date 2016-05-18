**Personal repo for RANCID tool**

RANCID is a tools initially developed by Shrubbery Inc. (http://www.shrubbery.net/rancid/)

This repo contains some add used inside my company:
* A hierarchy inside repo (a field is added in the .db file to know the directory to place the backup file)
* Add the ability to treat some command inside the clogin script
	* copy running-config startup-config
	* hostname 
	* banner 
* Add some commands for the ios and nxos modules
	* show cdp
	* show np 3 acl count
	* show ft group brief
* Include some patch found for H3C switches and to connect to cisco device through a management context (useful for FWSM or ACE device)
* Add ability to include directory content in cloginrc file
* Change the F5 module to take in count correctly the BigIP v11 type

and some others modification

Create a ticket if you have any issues and don't hesitate to check the mailing list of Shrubbery Inc.:
http://www.shrubbery.net/pipermail/rancid-discuss/
