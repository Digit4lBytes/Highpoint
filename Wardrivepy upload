
import subprocess
#Add Cloud upload location
from dbupload import upload_file 
#Use Datetime as filename
from datetime import datetime 
#Int File number count 

count = 0 
while True:
    count = count + 1
    
    fileName = str(datetime.now().day) + "-" + str(datetime.now().month) + "-" + str(datetime.now().year) + " AT " + str(datetime.now().hour) + "-" + str(datetime.now().minute)
    #Set TCPDump
    tcpDumpProcess = subprocess.Popen(["tcpdump", "-Z", "root", "-w", fileName, "-i", "bridge0", "-G", "60", "-W", "1"]) 
    
    #Run TCPDump
    tcpDumpProcess.communicate() 
    print "Obataining file number " + str(count) + "."
    
    #Upload to Cloud account 
    upload_file(fileName,"/",fileName, "YOUREMAIL","YOURPASSWORD") 
    print "File uploaded"
