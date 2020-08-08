   OpenVPN New Client Notification Script

   This script will act on information found on OpenVPN status log file, to call IFTTT thru Webhooks<br/>
   It will keep an output file as a database of connected clients, and has a log output for new clients<br/>
   On IFTTT create a recipe from webhoots to notification, get the maker Key and recipe name.<br/>

   This program is free software; you can redistribute it and/or<br/>
   modify it under the terms of the GNU General Public License<br/>
   version 2 as published by the Free Software Foundation.<br/>

   Dependencies: <br/>
    - ipapi - geolocation, carefull that they have a limit for free use<br/>
    - ifttt_webhook - calls for ifttt<br/>
    - tested on python 3.6<br/>

   Use: manual ./connected_clients<br/>
   Create a cron entry to call script every minute for example.<br/>

   Version: 1.0 - 08/2020<br/>
   Autor: ArgusR <@argusro>
