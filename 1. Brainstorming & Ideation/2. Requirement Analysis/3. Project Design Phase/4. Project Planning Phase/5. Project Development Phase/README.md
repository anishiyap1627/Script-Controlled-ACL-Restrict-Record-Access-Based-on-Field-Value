5. Project Development Phase

Implementation:

The project was implemented using ServiceNow ACLs and server-side scripting.

Development Steps:

1. Created the required users and custom roles.
2. Created the `u_institution_details` table.
3. Added the required fields and sample records.
4. Created the Read ACL to control record visibility.
5. Created the Create ACL for authorized users.
6. Created the Write ACL to control record modification.
7. Created the Delete ACL to control record deletion.
8. Applied role-based and field-based access conditions.
9. Tested the ACL configuration using different users.

Access Control Logic:

The ACL checks the user's role and the value of the Branch field before allowing access to a record.

Users who satisfy the required conditions can access the permitted records, while unauthorized users are restricted.

Administrators retain full access to the records.

Technologies Used:

- ServiceNow
- Access Control List (ACL)
- Server-side JavaScript
- Custom Roles
- Custom Table

Implementation Result:

The ACL configuration successfully controls access to the institution records according to the defined roles and Branch field conditions.
