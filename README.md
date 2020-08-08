   OpenVPN New Client Notification Script

   This script will act on information found on OpenVPN status log file, to call IFTTT thru Webhooks
   It will keep an output file as a database of connected clients, and has a log output for new clients
   On IFTTT create a recipe from webhoots to notification, get the maker Key and recipe name.

   This program is free software; you can redistribute it and/or
   modify it under the terms of the GNU General Public License
   version 2 as published by the Free Software Foundation.

   Dependencies: ipapi - geolocation, carefull that they have a limit for free use
   
		 ifttt_webhook - calls for ifttt
		 
                 tested on python 3.6

   Use: manual ./connected_clients
   Create a cron entry to call script every minute for example.

   Version: 1.0 - 08/2020
   Autor: ArgusR <@argusro>
