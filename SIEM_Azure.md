# SIEM-Azure

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

SENTINEL Lab Custom:




