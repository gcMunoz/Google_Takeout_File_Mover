# Google Takeout FileMover
You can follow this project and other project changes via: https://github.com/gesuskryst

Demo Video:
https://youtu.be/dMkTymbZfw4


Description:

With minor adjustments done to two existing packages of Google Photos Takeout, I'm somewhat confident that this program will work at moving all image and video files out of their individually dated folders. A lot of directories store .json files for configuration things I suppose, so I try to isolate those files from my exclusive search. 

To use this project, you will need a few things:
- A Google account with photos uploaded to photos.google.com
- A directory where you want to move your downloaded photos to

1. Start by visiting takeout.google.com
2. Log into your account, then choose the data you would like to export. Since this program is mostly catered towards a specific set of data, your photos, I would advice using this program on one particular set of data as all files moved are simply put into one directory.
3. Click "Next step", and choose your frequency. I would choose "Export once".
4. Click "Create export". Depending on how large your export is, you may get an email instead of an instant download link. 
5. If prompted, click "Download" next to your export. You should now have a zip file with the name "takeout-(exportID)-(exportSegmentNumber).zip"
6. Unzip the file, and now you should have a "Takeout" folder.
7. Run this Python program. You can use it via IDLE, or in a terminal or command line. An example for Windows would be "py takeout_file_mover.py".
8. Choose your "Google Photos" directory. Be sure to always choose the "Google Photos" directory that will be found after unzipping your data.
9. Choose your destination directory.
10. Click "Move Files". All your files will be moved to your destination directory, and duplicates will be renamed so you can identify copied images or similarly named images.


Feel free to contact me about bugs and issues with the program. Thanks.
