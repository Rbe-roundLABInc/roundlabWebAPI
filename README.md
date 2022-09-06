# roundlabWebAPI
roundLAB Web API


This application is to provide as a sample guideline in adding a hypertext communication protocol, or HTTP, to your application for sending to and receiving data from the roundLAB Web Application Programming Interface or roundLAB Web API.

1 COMMUNICATION PROTOCOLS

roundLAB’s trusted partner can use the standard hypertext communication protocol, or HTTP, to send data to roundLAB Web API.  The handshaking protocol must meet the following security and settings:

1.	All communication requires the secured HTTPS protocol when communicating with the roundLAB Web API.

2.	All post and get requests must include the job API Key in the header as Bearer Token.  This API Key can be found on the http://EddiLAB.com job details page. 
 
NB:  The API Key is unique for each job and is changed from job to job.

2 HOW TO USE ROUNDLAB CLASS LIBRARY

To use this class library:

•	Add the roundLABWebAPI.c# class library file to your project.

•	Install “Newtonsoft.Json” from NuGet.  (or using the Microsoft .NET JSON)

3 SAMPLE DESKTOP APPLICATION

To test the library, we have created this WinForm project for the test drive.  

•	Just download the project and install the "Newtonsoft.Json" from NuGet.

•	Compile and run.
