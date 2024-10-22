# Create-A-Role-In-Google-Cloud-IAM

<h2 id="step1">Overview</h2>
<strong>IAM</strong>, or <strong>Identity and Access Management</strong>, is a collection of processes and technologies that help organizations manage digital identities in their environment. With IAM, access control is managed by defining the identity of users and their roles in relation to available resources

In this project, I will be creating a role in Google Cloud IAM for auditors that wants audit Firebase Realtime Database. The auditors will be granted designated roles with restricted access, exclusively for viewing and listing the database contents.
<h2>Objectives</h2>
<ul>
 	<li>I will create a role and assign the required permissions.</li>
 	<li>I will assign the new role I have created to a user.</li>
 	<li>I will verify that the role I created has been granted.</li>
</ul>
&nbsp;
<h3>Creating Role</h3>
<img class="aligncenter wp-image-1776 size-large" src="https://www.businesstoks.com.ng/wp-content/uploads/2024/10/Screenshot-45-1024x505.png" alt="" width="1024" height="505" />

&nbsp;

Each custom role can be given a <strong>role launch stage</strong> which reflects the different phases of a role's development, testing, and deployment.
<ul>
 	<li>I chose General Availability because they are roles that have undergone thorough development, testing, and refinement. They are considered stable, reliable, and suitable for widespread use in production environments.</li>
</ul>
&nbsp;

&nbsp;

<img class="aligncenter wp-image-1778 size-large" src="https://www.businesstoks.com.ng/wp-content/uploads/2024/10/Screenshot-167-1024x667.png" alt="" width="1024" height="667" />

&nbsp;
<ul>
 	<li>I added the permission for the auditors to viewing and listing the Firebase Database contents</li>
 	<li>And created the role</li>
</ul>
&nbsp;

<img class="aligncenter size-full wp-image-1779" src="https://www.businesstoks.com.ng/wp-content/uploads/2024/10/Screenshot-48.png" alt="" width="1600" height="179" />
<h3></h3>
<h3>Assign / Grant Users to Roles that have been created</h3>
&nbsp;
<ul>
 	<li>I granted the roles I created to the auditor's account (student-02-ad12caf6e61e@qwiklabs.net)</li>
</ul>
&nbsp;
<h2><img class="aligncenter wp-image-1780 size-large" src="https://www.businesstoks.com.ng/wp-content/uploads/2024/10/Screenshot-50-1024x811.png" alt="" width="1024" height="811" /></h2>
<h2></h2>
<h3></h3>
<h3>I verified the role I created has been granted with the appropriate permissions.</h3>
<ul>
 	<li>I used Policy Analyzer to verify that the role I created for the auditor's account was granted the correct permissions.</li>
</ul>
&nbsp;

<img class="aligncenter size-large wp-image-1779" src="https://www.businesstoks.com.ng/wp-content/uploads/2024/10/Screenshot-48-1024x115.png" alt="" width="640" height="72" />
<h2></h2>
<ul>
 	<li>After running the query against the auditor's account (student-02-ad12caf6e61e@qwiklabs.net), the result shows that the auditor's account have been granted the <strong>Audit Team Reviewer</strong> role. A role I created for the auditor</li>
</ul>
<h2></h2>
<h2 id="step7">Conclusion</h2>
In this project, I successfully utilized IAM to create a custom role, grant access to a user for that role, and verified the permissions within Google Cloud.

IAM defines who has access to which resources based on their role. It is critical for managing digital identities in an organization's environment.

&nbsp;
