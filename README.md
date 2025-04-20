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
TEXT <br/><br/>
  <img src="Screenshot 2025-04-19 144313.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
