A01:2021 – Broken Access Control
A description of the vulnerability.
this is a process that they can modified the url or different keys to bypass the security feture of a site.
How to prevent it.
one way to prevent it is to create ways how to identifed user before they gain access 
An example of an attack.Scenario #1: The application uses unverified data in a SQL call that is accessing account information:

 pstmt.setString(1, request.getParameter("acct"));
 ResultSet results = pstmt.executeQuery( );
