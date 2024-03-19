# Description
  The project was built upon a RPA intern interview using Uipath Studio Community. The project is shaped for Instagram web, and it implements the full process of content posting on the social media. It takes all the photos and information needed, and the bot can post different content everyday by being scheduled.

# Informations
--The "Account.txt" file will contain the information of the account to which the posts will be made. It needs an username on the first line and a password on the second.

--The "Description.txt" file will contain the texts with the Description wanted to be written on every post. First line will be written to the first post, the second one to the second post and so on.

--The "Hashtags.txt" file will contain the texts with the Hashtags wanted to be written on every post. First line will be written to the first post, the second one to the second post and so on.

--And finally the "nrPozaCurenta.txt" and "nrPostareCurenta.txt" will act as helpers for the process to run correctly on every run. They will contain the number of the current photos that need to be posted,
  and also the number of the post (for description and hashtags). Those have to be set to one after all the posts have been made. And it will be ready for another cycle.
  
# Notes
   ~The process is currently configured to post 2 photos on every post, a description and a succesion of hashtags.                          
   
   ~For the program to run scheduled, it has to be set up in the Uipath Studio Orchestrator after being published on the platform or in Windows Task scheduler.

   ~A video example of the automation can be seen at the link in the "RPA_Project_Video_Example.txt" file
