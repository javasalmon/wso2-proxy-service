# wso2-proxy-service
wso2 proxy service to external soap based web service deployed on windows env

Installed following for development envionment
  * wso2ei-6.1.1
  * Eclipse with WSO2 Developer Studio (Setup WSO2 EI Server from eclipse, fixed Waiting for required Module: rampart-core issue)
  * SOAP-UI

Developed
  * Proxy Service
    - Created Pass Through Service that calls External SOAP based webservice deployed on .NET envionment
    - Logs Info Message when calling external service
    - Added header to set Action for operation
  * Composite Application Project
  * Deployed CAR on server
  * SOAP UI project to test Proxy service

Enclosed
  * Snapshot of SOAP-UI
  * Snapshot of Enterprise Integrator Dashboard
  * Snapshot of Server logs
  * SOAP UI project
  * Proxy Service project
  * CAR project

Test Instructions
  * Import Proxy Service and CAR project in eclipse
  * Deploy them on EI server
  * Run SOAP UI and import SOAP UI project
  * Run GetUKLocationByTown request
