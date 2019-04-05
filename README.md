# robocopy_edm
Robocopy Example for Imaging Server

 
#robocopy from server to new mappeddrive, every variable can be replaced to fit needs ex. E is a Drive on server copying to
#also logs..

robocopy \\SERVER\DRIVE$\FOLDER\ E:\FOLDERorDRIVE\ /LOG:E:\RoboCopyLog\RoboLog.txt /NS /NC /NDL /NFL /S /E /COPYALL /ZB /NP /MT:128 /R:1000000 /W:1
