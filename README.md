# Elevate_Labs_Task_4_Firewall
## Firewall Configration Using UFW
## install UFW Tool
1. Sudo apt install ufw
## Check Ufw Status active/inactive
### Here is Output
![Screenshot From 2025-06-27 21-25-37](https://github.com/user-attachments/assets/1f8bb89e-b30f-46f6-b4ad-69eb586ccf9c)
## View Existing Rules
### If No Any Existing Rule---Status is None
![Screenshot From 2025-06-27 21-31-07](https://github.com/user-attachments/assets/86e5bb6e-d555-4044-8d61-d32bfb08afc0)
## Add a rule to block inbound traffic of port 23/telnet
![Screenshot From 2025-06-27 21-39-55](https://github.com/user-attachments/assets/879611d5-cbe9-4885-b961-5003f4953ae2)
## Test the rule--- If the port is blocked, it will show:
![Screenshot From 2025-06-27 21-42-41](https://github.com/user-attachments/assets/ad518339-d9b8-4a85-86bd-1524ddb01860)
## Remove Test Block Rule
![Screenshot From 2025-06-27 21-45-42](https://github.com/user-attachments/assets/25b950b9-7732-400d-9f96-62dca52e5915)



## Firewall Configration on Windows
### Step of Open firewall setting<br>
1. Open Control Panel<br>
2. Click On System And Security<br>
3. Click on window defender firewall<br>
4. Click on advanced setting<br>
      ### OR <br>
Press Win + R, type wf.msc, and press Enter
## Home Page
![image](https://github.com/user-attachments/assets/05196867-de2e-4999-bacc-ca2146a3f205)
## Current Rule List
![image](https://github.com/user-attachments/assets/9215b9b6-c0c7-4f42-87ba-362d250af328)

## You Can use following step for Blocking 23/telnet port
In the Inbound Rules section, click New Rule on the right pane.

Select Port, then click Next.

Choose TCP, specify port 23, and click Next.

Select Block the connection, then click Next.

Choose the profiles this rule applies to (Domain, Private, Public), then click Next.

Name the rule then click Finish.

## After Blocking 23/telnet port  result
![image](https://github.com/user-attachments/assets/d76e7954-0235-46f7-ba01-19ed744c7c3b)

## Testing The Rule Result of Using Telnet 
![image](https://github.com/user-attachments/assets/c811fd48-b161-4d7e-81a7-654ab96bfbd8)

## Allow 22/SSH Rule Added 
![image](https://github.com/user-attachments/assets/0912abdd-22c9-4d88-bebd-57a19bbaea0a)

## Document commands
Open Firewall with Advanced Security<br>
Block port 23 via TCP Block <br>
Allow port 22 via TCP Allow <br>
Delete the Block Telnet rule when done.<br>

## Summary of How Firewalls Filter Traffic<br>
Windows Defender Firewall monitors network traffic and applies rules to allow or block connections. By defining rules based on ports, programs, or protocols, it ensures that only authorized traffic is permitted, enhancing system security.




