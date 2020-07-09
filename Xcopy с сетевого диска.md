net use Z: \\serv1\share 
cd /d z:\ 
dir >> testik.txt
xcopy Z:\*.* C:\script\  /e
