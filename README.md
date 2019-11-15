# Qlik Nprinting Scheduler Log Checker
- The app to read Qlik Nprinting Scheduler Log (Scheduler, Scheduler Dev)
- It may assist you to analysis Npritning Scheduler related incidents

# Requirement
- The app works on QlikView Desktop
- License verseion of QlikView Desktop is necessary to use this app.
- More logs volumn, more machine resource consumed. If resource shortage occurs, please either reduce the logs volumn or increase machine resource. 

# Instruction
1. Download "NP_SchedulerLog_Checker-v1.0.qvw" onto your Windows Machine where installed QlikView Desktop.
2. Collect Qlik Nprinting Scheduler logs from Nprinting Scheduler machine and copy them into a folder where is reachable from Qlikiew Desktop
3. Open "NP_SchedulerLog_Checker-v1.0.qvw" using QlikView Desktop.
4. At "Qlik Nprinting Scheduler Log folder path" section on Configuration Sheet, Enter path where you stored Qlik Nprinting Web Engine logs in No2.
  By default the path is set to "C:\yheTemp\Nprinting", please change it to fit to your environment.
  Note: Please don't include \ into last character of the path.  
5. Click Reload button on Configuration Sheet. Logs will be loaded into the app
6. Go to "Logs" Tab and see the data

# Disclaimer
The application is not supported by Qlik. Please use it on your own risk. 

# License
This project is provided "AS IS", without any warranty, under the MIT License - see the LICENSE file for details
