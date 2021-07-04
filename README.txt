==================================================================================================================================
				Documentation for Video to text converter program
==================================================================================================================================
- To use this program following requirements should be met : 
	* Python 3.7 and above
	* Installation of following Python Libraries and modules :
		- speech_recognition 
		- os 
		- pydub 
		- moviepy
---------------------------------------------------------------------------------------------------------------------------------
- Filename  : VideoToAudio.ipynb is a jupyter notebook file
- Filename  : src.txt contains the complete source code  in python 
---------------------------------------------------------------------------------------------------------------------------------
- In order to test the codes keep the code file in the same destination as the video file named as "sample_to_convert.mp4"
- For testing purposes, only the "VideoToAudio.ipynb" and "sample_to_convert.mp4" are required rest all files and folders will be auto-created
====================================================================================================================================
************************************************ EXECUTION INSTRUCTIONS ************************************************************

- Using Jupyter Notebook :
	- In Jupyter , open "VideoToAudio.ipynb" 
	- Click inside the code cell to activate it
	- Now Click on Run button from the ribbon or use Ctrl+enter
- Using other Python text editors / IDEs :
	- Open "src.txt"
	- Copy the entire content into a new file	
	- Save this new file as Python file eg :  Desired_Filename.py	
	- Ensure that all the dependencies mentioned above are met before executing
	- Run this file 
--------------------------------------------------------------------------------------------------------------------------------------
=> This code will generate all of the following files : 
	- "transcriptions.txt"
	- audio-chunks/
	- "video_result.wav"
=============================================================================================================================================	