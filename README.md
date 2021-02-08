# JenkinsALM

This files is Jenkins ALM configuration for Start, Stop and Ping ALM Service on Windows Machine

## Installation

Copy below files to your ALM host directory:
	- shutdown.bat
	- startrun.bat
Above files needed to be run as local/service Administrator, hence need to be run in elevated mode
Copy file ElevatedRun.bat nad doubleclick it to Run in your ALM host machine. Follow the guideline.
1. Create a fileName as shortcut, example on this repository: shutdownALM and startALM
2. Locate the full path of the bat file that you copy from above step: example C:\Users\<username>\<directory>\shutdown.bat
3. ElevateRun.bat create 1 file per run, if you need to create for startALM.lnk you have to configure again for startrun.bat
4. File shortcut will displayed in your desktop, move shortcut file to your desired location, you can place in same location as other files

 [pip](https://pip.pypa.io/en/stable/) to install foobar.

Create Jenkins pipeline configuration for each activity, change the configuration for emails, message, and node.
In this case I create separated jenkinsfile for stop, start, and ping

## End