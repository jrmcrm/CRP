This document contain fllowing info about "NOR Customer Risk Profile" 

1. WHAT IS the "NOR Customer Risk Profile"
2. REQUIREMENTS 
3. INSTALLATION STEPS
4. USER GUIDE


************************************************************************************************

1.  WHAT IS the "NOR Customer Risk Profile"

The "NOR Customer Risk Profile" is solution paackage for Dynamics 365 CE done by Jakub Malecki. 
This extension allow user to easy prepare and maintain Customer Risk Profile.  

************************************************************************************************ 

2. REQUIREMENTS

#SYSTEM

This package is fully supported on Dynamics 365 Customer Engagement - version 9.1.

NOTE: Dynamics 365 version 8.2 is potentially supported but not tested. 


#SECURITY

Administrator rights are necessary to import solution. 

To use this solution following privileges are required:	
	
	Account - Create/ Read / Write / Append / Append to - at least user level

	User - Read / Append / Append to - at least user level

	Activity - Create/ Read / Write / Append / Append to - at least user level
	
	Execute Workflow Job - YES 


************************************************************************************************ 

3. INSTALATION STEPS

Iport manage solution: 

Go to Settings=> Solutions=> Import => Select Solution package "nor_crp_2019_02_28_3_managed"
 

************************************************************************************************ 

4. USER GUIDE

#Create Customer Risk Profile (CRP) for existing Account 

a) Open an existing Account 
b) Go to form selector 
c) Select Customer Risk Profile form
d) Fill in answer fields 
e) If necesserey go to section Notified user and select Notified user // this user will be notified if CRP will changed 
e) Save // Account owner and Related user will get email with notification abour changes in CRP  

 
#Copy answers from other Account

a) Open an existing Account 
b) Go to form selector 
c) Select Customer Risk Profile form
d) Go to section Get answers from other account and sellect Account which will be a source for answers  
e) If necessery select  related user // he will be notified if CRP will changed
e) Save //Answers will appear on CRP. Account owner and Related user will get email with notification abour changes in CRP 



#Create Customer Risk Profile (CRP) for new Account 

a) Create new Account by fulfil all required fields
b) Go to form selector 
c) Select Customer Risk Profile form
d) Fill in answer fields or copy answers from other account
e) If necessery select  related user // he will be notified if CRP will changed
e) Save //Answers will appear on CRP. Account owner and Related user will get email with notification abour changes in CRP 
