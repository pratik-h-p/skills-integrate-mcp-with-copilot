# Add Authentication and Roles (admin, organizer, student)

Description
-----------
Add user accounts, login (session or token-based), and role-based access control. Students should register/login to sign up for activities. Admins/organizers get elevated access for management tasks.

Acceptance criteria
-------------------
- Users can register and authenticate.
- Roles (student, organizer, admin) are enforced on protected endpoints.
- Protected endpoints return proper 401/403 responses when unauthorized.

Labels: backend, enhancement
