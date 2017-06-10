=========================YOUTUBE PLAYLIST DOWNLOADER=============================== 

YouTube_playlist_downloader.py is a Python program which can download HD(720p) 
videos of playlist from youtube.
	Prerequisites:
            ## Python 3x
            ## Following modules
               1.requests
               2.urllib
               3.BeautifulSoup
 
This program can download videos with there name prefix with serial number in order.
***NOTE:: This program can download 720p and 480p videos only.
          You might get error while trying lower quality videos. 


Playlist can be downloaded in three different modes
Mode 1 : To download playlist form url (Complete)
Mode 2 : To resume your download.
Mode 3 : For custom download

Mode 1 :will allow you to download complete playlist. You just need to enter the 	
	url of any video of that playlist.

	URL should be in this form:
	https://www.youtube.com/watch?v=xyz&list=abcd

	In this mode three text file will be created 
	1.links.txt
	2.vid_titles.txt
	3.keepvid.txt
	
	***NOTE:: In case your download get interrupted use mode to to resume your 			
		download.

Mode 2:This mode only works if you have above three .txt files.If you don’t have 	
	the .txt file in the same folder or you have deleted these files then you 	
	can’t resume download. In that case use mode 3 to download rest of the 	videos. 

	You need to provide the video number from which you want to resume the 	download. 
  
	***NOTE::If you use mode 3 then you cannot resume using mode 2.

Mode 3: This mode is for downloading a part of playlist.
	Just enter URL of any video of that playlist and specify the starting video 	
	number and ending video number.	

	***NOTE::1. You can’t resume using mode 2.
		   2. Only consecutive videos will be downloaded 




*************************************NOTE****************************************
You might get errors and warnings. Please report issue.
Program may be unstable and cause unwanted interruptions , 
may be due to internet connectivity problems or poor speed.


*************************************END*****************************************

  
