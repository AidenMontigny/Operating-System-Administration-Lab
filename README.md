<h1> Operating System Administration Lab </h1>

<h2>Description</h2>
This project demonstrates foundational and advanced principles of Windows Server administration, focusing on user account management, security groups, authentication policies, and system updates in a Windows domain environment. It begins with ensuring the system is up to date through the installation and verification of Windows Updates. Users were then added to different departments such as Research and Development, Human Resources, and IT, with group policies implemented to define logon hours, enforce disconnection after hours, and update policies across the network. Role-based access control (RBAC) was also configured, allowing HR to read and write user object attributes and IT to reset passwords and enforce password changes. Departmental access was tested, and role-specific permissions were validated. Additionally, the project explored the critical importance of operating system updates, authentication group policies, and the balance between security and usability in enterprise environments, reinforcing key concepts in system security, patch management, and user access control.
<br />

<h2>Languages and Utilities Used</h2>

- <b> Windows Server Update Services </b>
- <b> Group Policy Management Console </b>
- <b> Active Directory </b>
- <b> Powershell </b> 

<h2>Environments Used </h2>

- <b> Windows Server 2019 </b>

<h2>Project walk-through:</h2>
<p align="left">
Initiation of the Windows Update process to ensure the operating system is current with the <br/> latest security patches and improvements. <br/><br/>
  <img src="Screenshot 2025-04-19 204016.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Confirmation of the successful completion of the Windows Update process, indicating that the <br/> system has been updated with the latest patches and enhancements. <br/><br/>
  <img src="Screenshot 2025-04-19 204025.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Verification that the system is fully updated and running the latest available updates. <br/><br/>
  <img src="Screenshot 2025-04-19 204032.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Confirmation of a user successfully added to the appropriate Active Directory group for <br/> role-based access control. <br/><br/>
  <img src="Screenshot 2025-04-19 204039.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Three users were successfully added to the Research and Development Department's Active <br/> Directory group to align with organizational role assignments. <br/><br/>
  <img src="Screenshot 2025-04-19 204048.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Three users were added to the Human Resources Department group in Active Directory to reflect <br/> departmental user organization and access control. <br/><br/>
  <img src="Screenshot 2025-04-19 204055.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Four users were successfully added to the IT Department group within Active Directory to <br/> establish appropriate access permissions and departmental alignment. <br/><br/>
  <img src="Screenshot 2025-04-19 204103.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The Research and Development Department group was configured with logon hours restricted to <br/> 9:00 AM through 8:00 PM, Monday through Friday, to enforce secure access during standard business hours. <br/><br/>
  <img src="Screenshot 2025-04-19 204109.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The "Disconnect clients when logon hours expire" option was enabled to ensure that user <br/> sessions are automatically terminated outside of designated access times, enhancing system security and compliance. <br/><br/>
  <img src="Screenshot 2025-04-19 204115.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The policy update was forcibly applied to ensure that all system configurations, including <br/> group policies and user access controls, are synchronized and implemented across the network. <br/><br/>
  <img src="Screenshot 2025-04-19 204121.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The configuration process for delegation controls within the HR Department was initiated, <br/> allowing <br/> for the assignment of specific administrative permissions to designated users within the department. <br/><br/>
  <img src="Screenshot 2025-04-19 204128.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The "User Objects" option was selected, with permissions configured to allow only <br/> "Read and Write" access, ensuring controlled access to sensitive user data within the HR Department. <br/><br/>
  <img src="Screenshot 2025-04-19 204135.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The delegation controls for the IT Department were initiated, allowing for the configuration <br/> of specific permissions and roles tailored to the department's requirements.The delegation controls for the IT Department were initiated, allowing for the configuration of specific permissions and roles tailored to the department's requirements.
 <br/><br/>
  <img src="Screenshot 2025-04-19 204149.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The configuration illustrates the selection of the "Reset user passwords and force password <br/> change at next logon" option, which is set to enforce a mandatory password reset for users upon their next login. <br/><br/>
  <img src="Screenshot 2025-04-19 204155.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The configuration demonstrates the forced update of the policy, ensuring that all changes <br/> to the system settings are applied immediately across the relevant user accounts and groups. <br/><br/>
  <img src="Screenshot 2025-04-19 204201.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The HR and IT departments were successfully added to the local login page, enabling <br/> authorized users from these departments to access the system directly.
 <br/><br/>
  <img src="Screenshot 2025-04-19 204210.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The user ‘Tyler Childers’ from the HR department successfully logged into the system, <br/> confirming proper account creation and authentication configuration. <br/><br/>
  <img src="Screenshot 2025-04-19 204220.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The HR Department was granted the necessary permissions to modify user name attributes, <br/> confirming  appropriate delegation of authority. <br/><br/>
  <img src="Screenshot 2025-04-19 204227.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
Bob Smith from the IT Department successfully executed a password reset for a user in the <br/> Research and Development Department, demonstrating proper delegation of user account management privileges.
<br/><br/>
  <img src="Screenshot 2025-04-19 204233.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>

            
<h2>Write Up</h2>

<p><u> The Importance of Patches and Updates </u></p>
<p>Patches and updates are crucial for maintaining a secure operating system. Updates and patches typically address newly found vulnerabilities and bugs, and improve the system as a whole. Regularly installing these patches will help prevent attacks or breaches and ensure that the system remains stable and secure. As well, patches aid with securing different aspects of a system and can add layers of security against malicious parties. Overall, installing updates and patches is important as it will aid organizations to be up to date with all vulnerabilities and issues that are occurring in cyberspace. </p>

<p><u> The Importance of Authentication Group Policies in System Management </u></p>
<p>Configuring appropriate authentication group policies is a critical part of managing a system, as different users require varying levels of security. By implementing multiple group policies, an administrator can ensure that users have access to only what is necessary for their role in the company-creating a system. These policies not only protect against unauthorized access but also prevent productivity slowdowns (Tang, 2021). Additionally, implementing different policies enables testing of new authentication methods, such as multi-factor authentication, before deploying them organization-wide. This flexibility allows for enhanced protection without causing unnecessary steps for users. </p>

<p><u> Security vs. System Usability </u></p>
<p> The interaction between security and system usability is a complex topic. The balance between having user protection without disrupting the user experience has become more complex as more security measures have been taken against malicious parties. For example, traditional methods such as CAPTCHA have become easier for malicious attackers to bypass, while simultaneously making it harder for users to access their accounts (Reyes, 2021). While more authentication does increase security, it also has harmed employees, creating more workarounds to access their workloads, making them less productive and engaged. Overall, finding a balance between security and usability is crucial, as making it too complicated to access a work account may cause employees to not be as focused on their tasks at hand. </p>

<p><u> References </u></p>
<p>Reyes, A. (2021, August 2). Google Cloud BrandVoice: Security versus usability: A new approach. Forbes. https://www.forbes.com/sites/googlecloud/2021/08/02/security-versus-usability-a-new-approach/#:~:text=Secure%20the%20user,%20with%20usability%20in </p>
<p>Tang, S. (2021, March 24). Benefits of multiple authentication policies. Work Life by Atlassian. https://www.atlassian.com/blog/access/benefits-of-multiple-authentication-policies#:~:text=An%20authentication%20policy%20dictates%20which%20authentication </p>
