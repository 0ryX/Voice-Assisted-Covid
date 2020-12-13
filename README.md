# Voice-Assisted-Covid
###################################################################################################################################

                          Voice Assisted Covid-19 Data Visualization Program in Python
                          
###################################################################################################################################


This is a project in the making, I have scraped data from https://www.worldometers.info/coronavirus/. This website stores live                          updated corona virus data from all around the world. My plan is to have the most up-to-date stats for countries all over the 
world's information output to the user using voice activated commands. 
I would also like to have this data mapped out to show hotspots where showing more cases vs less cases.
    
**Ubuntu/Debian**

Currenly I installed these required packages with Ubuntu 20.04 LTS, and had trouble installing PyAudio. I ended up having to use 
Anaconda's conda install pyaudio for it to run and am still currently debugging pyaudio. 

**Windows**

When trying to install PyAudio on Windows, you will need to first go the:
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio 
and find your current version of python and whether you are using 32bit or 64bit. More then likey you will be running 64bit but to check 
simply start up a python shell session inside your terminal or command prompt run:
python or python3...

**Other Dependencies not inside requirements.txt**

      apt install python3-espeak
      apt install portaudio19-dev python-pyaudio 

"python-pyaudio" may not install, you will need to use ^^ conda install pyaudio then ^^
