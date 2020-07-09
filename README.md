# neo2cf

This mta supports the creation of an html5 application that calls a Java backend via destination.  
The login OIDC token is forwarded to the backend application which validates it against the authentication server.

In this mta the Managed HTML5 Runtime (saas approuter) is used.

Pre-requisites:
1. Zone enabled subaccount
2. Redirect/Logout URL configuration in IAS administration console
   Applications/<applicationName>/OpenID Connect Configuration/ Redirect URIs
   For example: https://saas-approuter-consumer3-saas-approuter.cfapps.sap.hana.ondemand.com/login/callback

IAS Administration Console
https://aybzbjlhs.accounts400.ondemand.com/admin/


Test appplication in current subaccount (saas-approuter-consumer3):
https://saas-approuter-consumer3-saas-approuter.cfapps.sap.hana.ondemand.com/neo2cf.myapp/index.html
