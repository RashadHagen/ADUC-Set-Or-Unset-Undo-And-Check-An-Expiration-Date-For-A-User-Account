<h1>Active Directory Users and Computers (ADUC) - et Or Unset (Undo) And Check An Expiration Date For A User Account</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to set an expiration date for a user account using Active Directory Users and Computers. Setting an expiration date for a user account in Active Directory Users and Computers automatically disables the account at the specified date and time. This means the user will be unable to log in or access resources using that account after the expiration date. This is a useful feature for managing temporary accounts, 
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Active Directory Users And Computers</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Active Directory Users and Computers.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/FS09IXw.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/WBa58Zn.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Use: Find (OR) Go: To the location of the user.  <a href="https://github.com/RashadHagen/ADUC-Find-Computer-User-Contact-Group-Printer-Shared-Folder-Organizational-Unit-Common-Que" style="font-family: Arial, sans-serif; font-size: 16px; font-weight: bold;">How To Find A User In Active Directory Users and Computers</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/ejilua8.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/FZr7yCG.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: The user’s name.  Click; Properties (bottom).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/cEGSj7i.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Account tab.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/evZ9IAj.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/p0w67GT.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/5dzk0aX.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Look: Account expires (bottom). Click: End Of.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/eMXFCEE.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/43skPoG.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Apply. Then, Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Nb7ohGj.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>To UNDO an EXPIRED user account: Change the expiration date  (OR)  Instead of Clicking: End of. Click: Never. Click: Apply.  Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/L9BAZh8.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/L9BAZh8.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/4Bthzdl.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>NOTE: To check if the account does not expire / when it expires now: Open: Command Prompt.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/iNQXYQR.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/ApQ1MGC.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: net user (username) /domain. NOTE: Because this user’s account was created using Active Directory Users and Computers and not on the local computer, you need to add /domain at the end. Look: Towards the top.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/uWpQ0xK.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/m7UTz5C.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
