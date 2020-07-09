# neo2cf

This mta supports the creation of an html5 application that calls a Java backend via destination forwarding an OIDC token (IAS flow).
Managed HTML5 Runtime (saas approuter) is used to run the solution. This saas approuter should support IAS login flow
Pre-requisites:
1. Zone enabled subaccount
2. Redirect/Logout URL configuration IAS administration console

IAS Administration Console
https://aybzbjlhs.accounts400.ondemand.com/admin/


Test appplication in current subaccount (saas-approuter-consumer3):
https://saas-approuter-consumer3-saas-approuter.cfapps.sap.hana.ondemand.com/neo2cf.myapp/index.html