# Excel to PowerPoint Robot
This robot creates graphics in Microsoft Excel, copies them into PowerPoint and saves the new PowerPoint in the exact same location as the Excel document.
This robot demonstrates important Desktop Automation features
* Never using timing guards
* How to ensure an application has focus
* how to deal with unexpected popups
* How to use application aliases
* How to use **Freeze Tree** group steps to speed up execution
## Configuration
* Install Kofax RPA 11.0 or later
* Install Microsoft 365 Excel and Powerpoint on your Desktop System.
* Create TaskBar icons for Both (these are used for starting the application and regaining focusing)  
![image](https://user-images.githubusercontent.com/47416964/79317853-82d8d080-7f06-11ea-8bd9-10fadf14b798.png)
* Configure your Desktop Automation Service with the token **Office365**
* Download both robots
* Pass the Excel document (**input.xlsx**)'s Full Path to the robot as input parameter
