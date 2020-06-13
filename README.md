# iRobotTakeHome

System OS: Windows. make sure you are connected to the internet

Steps to run application:
1. Install python if not available.
2. Unzip the folder and extract it to a location.
3. Open CMD inside the unzipped folder(iRobotAssignment) containing src and tst folder and type below command(In this way, there is no need to hardcode the token inside the code and every person who runs the code can provide their own API token):
   pip install -r requirements.txt && set API_TOKEN=ba7b9769d5e94ffd842ffaba0ff223f2
4. Now type the following command "python src\hello.py" to start the application.
5. Enter the ingredients and press enter.

How to run unit tests:
Follow the previous steps from 1 to 3. After that, type the following command "python testService.py"
