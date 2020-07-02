Software required:
INSTALLATION DOCUMENT
 1. Visual Studio Code (version 1.45.1+)
2. IntelliJ (version 2020.1.1 community edition or above)
3. MySQL Workbench (version 8.0.20 or above)
Tools Required:
1. Maven (version 3.5.0 or above)
2. Java JDK (1.8 or above)
3. Node.js (v 12.16.3 or above)
4. Angular (v 8.3.21 or above)
Files required:
We have attached two folders, one for the back end and the other for UI.
Backend:
Approach 1 – From CLI:
Run the following command from the folder where Alumni Website Backend.zip is extracted.
Cmd:
mvn spring-boot:run -Drun.jvmArguments="-Djava.security.egd=file:/dev/./urandom - Ddatabase.username=sdonthis -Ddatabase.password=Hanumanthu_2"
Approach 2 – Using IntelliJ:
The backend code is in the folder Alumni Website Backend.zip. Extract the content and open it in IntelliJ. Run AlumniApplication.java with VM arguments:
-Djava.security.egd=file:/dev/./urandom -Ddatabase.username=sdonthis -Ddatabase.password=Hanumanthu_2
Frontend:
For the UI, extract ‘Alumni Website User Interface.zip’ file and open the folder in Visual Studio Code. Open the terminal and run the following commands :
npm install – to install all dependencies in package.json
npm run start – to run start the server in local system on port 4200.
MySQL Setup:
The DB is setup in AWS and can be viewed through MySQL Workbench.
