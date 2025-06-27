# Elevate_Labs_Task_4_Firewall
## Windows Firewall Configration 
## Home Page
![image](https://github.com/user-attachments/assets/05196867-de2e-4999-bacc-ca2146a3f205)
## Current Rule List
![image](https://github.com/user-attachments/assets/9215b9b6-c0c7-4f42-87ba-362d250af328)

## You Can use following step for BLocking 23/telnet port
In the Inbound Rules section, click New Rule... on the right pane.

Select Port, then click Next.

Choose TCP, specify port 23, and click Next.

Select Block the connection, then click Next.

Choose the profiles this rule applies to (Domain, Private, Public), then click Next.

Name the rule (e.g., "Block Telnet"), then click Finish.

After Blocking 23/telnet port  result
![image](https://github.com/user-attachments/assets/d76e7954-0235-46f7-ba01-19ed744c7c3b)

##Testing The Rule Result of Using Telnet 
![image](https://github.com/user-attachments/assets/c811fd48-b161-4d7e-81a7-654ab96bfbd8)

Allow 22/SSH Rule Added 
![image](https://github.com/user-attachments/assets/0912abdd-22c9-4d88-bebd-57a19bbaea0a)

Open Firewall with Advanced Security
Block port 23 via TCP Block 

Allow port 22 via TCP → Allow 

Delete the "Block Telnet" rule when done.





