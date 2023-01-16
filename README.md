<h1>Microsoft Azure MFA, Conditional Access and Identity Protection</h1>


<h2>Description</h2>
This project walks the user through enhacing Microsoft Azure Active Directory through:<br>
1. Multi-factor Authentification.<br>
2. Conditional Access.<br>
3. Identity Protection
<br />

<h2>Walk-through:</h2>
Sign in https://portal.azure.com/ and follow the steps outlined below:<br>
<h3>1. Creating a Virtual Machine.</h3> <br>
I. Search for Virtual Machine in the search box and press enter.<br>
II. Create a Virtual Machine by filling out all required fields
<p align="center">
<img src="https://i.imgur.com/MpYUW4a.png" height="80%" width="80%" alt="Deploy Virual Machine"/>
<br />
<br />
  
<h3>2. Creating a new tenant</h3><br>
I. Search for Azure Active Directory in the search box and press enter.<br>
II. Click on 'Manage tenants'
<p align="center">
<img src="https://i.imgur.com/kmZB1NA.png" height="80%" width="80%" alt="Manage Tenants tab in Azure Active Directory"/>
<br />
<br />
  
III. Click on 'Create'<br/>
<p align="center">
<img src="https://i.imgur.com/l081XJp.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
III. Select 'Azure Active Directory' and follow the 'Next' tab to proceed. Fill in the deatils<br/>
<p align="center">
<img src="https://i.imgur.com/h4y0Hqr.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/VVDliXy.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
<h3>3. Activating Azure AD Premium P2 trial</h3><br>
I. Click on the settings icon on the menu bar in on the portal.<br>
<p align="center">
<img src="https://i.imgur.com/IDEP82c.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

II. Identify the newly created directory and click 'Switch' <br>
<p align="center">
<img src="https://i.imgur.com/OR4dcMx.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

III. Now in the new directory, click on 'View' under 'Manage Active Directory' <br>
<p align="center">
<img src="https://i.imgur.com/472wQDC.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
IV. On the left pane, click on 'Licenses' under 'Manage'<br>
<p align="center">
<img src="https://i.imgur.com/79D9Aq9.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
V. Click on 'All products', '+Try/Buy', 'Free Trial' and 'Activate'<br>
<p align="center">
<img src="https://i.imgur.com/oJz1rID.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
<h3>4. Creating Users</h3><br>
I. In the new directory, under 'Manage' on the left pane, click on 'Users'.<br>
<p align="center">
<img src="https://i.imgur.com/FJYoPfZ.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

II. Click on 'New user', 'Create new user'<br>
<p align="center">
<img src="https://i.imgur.com/Fxkx8H5.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

III. Fill in the details and create user. Create 3 different users using the same method <br>
<p align="center">
<img src="https://i.imgur.com/0PhEa9B.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
<h3>5. Assigning Azure AD Premium to users</h3> <br>
I. Under the new directory, click on 'Licenses'<br>
<p align="center">
<img src="https://i.imgur.com/W7udDtW.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
II. Click on 'All products', 'Azure Active Directory Premium P2', '+ Assign'<br>
<p align="center">
<img src="https://i.imgur.com/IGpPWwy.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
III. Cilck on 'Add users and groups', select users, 'review + assign'<br>
<p align="center">
<img src="https://i.imgur.com/pPYlasE.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

<h3>6. Configuring MFA</h3><br>
I. Still in the new directory, click on'Security' under 'Manage'<br>
<p align="center">
<img src="https://i.imgur.com/ssCQY4p.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
II. Click on 'Multifactor authentication'<br>
<p align="center">
<img src="https://i.imgur.com/9rH3kWK.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
III. Click on link under 'Configure'<br>
<p align="center">
<img src="https://i.imgur.com/rf3A1G2.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
Follow these steps as a new tab opens  <br>
IV. Click on service settings. Ensure all verification options are checked, click save <br>
<p align="center">
<img src="https://i.imgur.com/qPGtei0.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
V. Click on user tab, select users , click on enable, click on 'enable mulifactor auth' <br>
<p align="center">
<img src="https://i.imgur.com/qPGtei0.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
VI. Click on 'Fraud alert', turn all alerts 'on'in the Azure portal <br>
<p align="center">
<img src="https://i.imgur.com/rX5q8tK.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
VII. Open private mode browsing. sign-in with user 1 account.  <br>
  
VIII. Select 'different method of authentification', then choose <br>
<p align="center">
<img src="https://i.imgur.com/ecaGC97.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

<h3>7. Implementing Azure AD Conditional Access Policies </h3><br>
I.Still in the new directory.<br>
  
II. Click on'Security' then 'Conditional Access', 'Polices' '+New Policy'<br>
<p align="center">
<img src="https://i.imgur.com/2TuWg4X.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<img src="https://i.imgur.com/L1hzzZ6.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
  
III. Fill in the details, select specific users included, Select all the needed policies and controls,'enable policy on'  then 'Create <br>
<p align="center">
<img src="https://i.imgur.com/NP8Tp71.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

IV. Test it out by signing in using user 2 credentials<br>

<h3>8. Impementing Azure AD Identity Protection</h3><br>
I. Click on 'Security', 'Identity Protection'. 'User risk policy', Set configurations, 'enable policy' then 'Save'.<br>
<p align="center">
<img src="https://i.imgur.com/Hkp4Kxt.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
II. Configure Sign-in-risk in the same way as User risk policy<br>

III. : Simulate risk events against the Azure AD Identity Protection policies<br>
Switch to the directory where the VM was deployed<br>

IV. Select the VM, click on 'Connect' select 'RDP'<br>
<p align="center">
<img src="https://i.imgur.com/Uaer9wo.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
V. Download RDP<br>
  
VI. Launch RDP and connect with credentials used for creating the VM<br>
VII. Set IEE Security to OFF.<br>
<p align="center">
<img src="https://i.imgur.com/5yifPjt.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
VIII. inPrivate mode sign-in to user 3. it gets blcked because of Sign-in risk policy<br>
<p align="center">
<img src="https://i.imgur.com/sRTVfnI.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
inPrivaate mode sign-in to user 1. it gets suspicious sign-in because of Sign-in risk policy<br>
<p align="center">
<img src="https://i.imgur.com/drGW8XJ.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />
  
IX. Analyse Reports of risks in the new directory that was created<br>
<p align="center">
<img src="https://i.imgur.com/0i56cSx.png" height="80%" width="80%" alt="Create a new tenant in Azure Active Directory"/>
<br />
<br />

Remediate and Respond to findings in all the reports.

  
