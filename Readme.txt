This project is in ASP.net and provides the facility to embed the Metabase in iframe using windows authentication and display the dashboard contents as per user privileges.

Instructions:
1)	 In Metabase project make the field as non-editable which you want to handle through this project
2)	In Database, crate a user table with privileges where you can control users access level for the dashboard


Web.config changes.
1) Change the database configuration (ConnectionStringName)
2) Change the metabase base url (MetaBaseURL)
3) Change the metabase secret key(MetaSecretKey)
4) Change the metabase dashboardId(dashBoardID)


.CS Changes
1) Change the SQL Query as per your needs

Reference:
JWT for .NET Written by John Sheehan(http://john-sheehan.com)

