**IoT Angular Reporting Reference Application**
==================
The example IoT Angular Reporting Reference application implements a simple IoT Reporting application that can be used to display the posted data from the [IoT Device Raspberry Pi Sense HAT](https://github.com/markreha/cloudpi/blob/master/README.md) application. The IoT Angular Reporting Reference application consumes a REST API published by the [IoT Services Reference](https://github.com/markreha/cloudservices/blob/master/README.md) application. These applications in combination  demonstrate a simple, scalable, Cloud based IoT application. Get the [Cloud Workshop SDK!](https://github.com/markreha/cloudworkshop/blob/master/README.md).

Architecture & Technologies
--------
The IoT Angular Reporting Reference application is designed and implemented in JavaScript using the Angular Framework. The application uses Material UI to assist in supporting a responsive design. The Angular application imports the Ng2 library, for charting, and the Axios library, for an HTTP Client used for making the REST API calls.
 
Basic Application Functionality
--------
The IoT Angular Reporting Reference application, as show in the screen shots below, primary functionality includes implementing a simple reporting parameter screen, allowing the user to specify the Report Type, Report Start Date, and Report End Date, and a report display screen, displaying the IoT data either as a Tabular Report or a Line Chart Report. The main application is displayed by the App Component to display a common application App and NavBar. The application supports a responsive design and can be accessed from desktop, mobile, and tablet browsers.

![IoT Angular Reporting Screen Shots](https://github.com/markreha/cloudworkshop/raw/master/sdk/docs/architecture/images/iotreportingangularss2.png)
