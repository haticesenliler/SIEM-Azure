# SIEM-Azure
-* https://www.youtube.com/watch?v=g5JL2RIbThM *-

1st Step:
- Create a resource group in Azure
- create a VM in that resource group
    - choose East 2 for student account
    - most settings are default
    - set up an adminsitrator account
    - choose allow seelcted ports and rdp 3389
    - in networking group, choose advanced and create a new inbound rules
          - we want to allow any inbound so do any
    - create
 
2nd step: 
  - create a log analytics workspace
  - ingest events and logs. for discovering where the attacks comes from
  - so it will display the geo data on the map


3rd step: 
- Microsoft Defender for Cloud
- enable the abilty to gather logs from the vm into the log analytics workspace
- turn servers on anddefender on.
- in data collections click all events
- go back to log analystc workspace
- connect the vm
- go to Sentinel: this is where SIEM visualize the attack data
- create one by adding the vm


Go to VM and copy IP address
with windows app add the pc and use your login credentials for login

IPGEolocation 
- posting ip address to here and it will pop up informations about that ip and we will send these data to our log
- close all firewalls in vm

SENTINEL Lab Custom: code is included in the another file
- have your own API key from the geolocation

  when you run the code, the thing it will do is taking the audit failure from the secuirty of the computer's system and send these ip addresses to the ipgeolocation and get these information and save these failued logins in another file

  when someone tries to login and it will save their data to file called 'log.exporter' on vm pc.


4st step: creating  a custom log
- GO to log analytics workshop and create a customized table custom log
- add your file from the vm, copypaste the logs and create a text file in your pc and upload it in your customized log and create it

  




