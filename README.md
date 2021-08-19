# RobotBase
This project is the second part of the [robot Arm](https://github.com/MhHaddad/RobotArm_interface)

you will find 5 buttons 
* forward
* backward
* left
* right
* stop 
it will help you to control the base movement of the robot arm.


>  "connectionArm.php" the data will be sent to the database. Where the initial value 0 will be changed to 1 in the column corresponding to the button that was pressed.


>  "display.php" will call the last column that got the number 1 because of pressing the corresponding button in the control panel and showing the symbol or word indicating the direction that was pressed on a special PHP page.
