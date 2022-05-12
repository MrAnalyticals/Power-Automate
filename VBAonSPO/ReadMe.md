VBA can run against Excel files resident on SharePoint online. 
In the following YouTube video I demo how this can be done using Power Automate Cloud and Desktop. 

![image](https://user-images.githubusercontent.com/47678539/167988532-3c21623a-ca50-46c1-a57a-ca69fd891793.png)

The YouTube video: https://youtu.be/7k4lD7IY68U

The process is to run the VBA is to have the VBA triggered on the Workbook open event. Create a Desktop Flow that opens Excel xlsm workbook then closes the workbook after an interval of time. 
Use Power Automate Cloud to run that Desktop Flow in unattended mode. 
You must, of course, be logged out of your Windows machine for the Flows to work! 
