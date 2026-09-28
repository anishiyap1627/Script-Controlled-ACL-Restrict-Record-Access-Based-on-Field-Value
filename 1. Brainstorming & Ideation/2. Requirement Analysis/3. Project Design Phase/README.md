3. Project Design Phase

System Design:

The project uses ServiceNow Access Control Lists (ACLs) and server-side scripting to control access to records based on user roles and field values.

Architecture:

User -> ServiceNow Login -> User Role Verification -> ACL Evaluation -> Branch Field Validation -> Allow / Restrict Record Access

Main Components:

- User and Role Management
- Institution Details Table
- Access Control Lists
- Server-side Script
- Branch Field
- Role-based Access Control

ACL Operations:

- Read
- Create
- Write
- Delete

Access Logic:

If the user has the required role and the Branch field satisfies the defined condition, access is allowed. Otherwise, access is restricted. Administrators retain full access.
