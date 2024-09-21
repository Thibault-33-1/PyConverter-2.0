You must put the files to convert in the folder PyConverter-2.0

I added a pic in it for you can test.


Install python3 if you don't have it : 
-------------------------------------

sudo apt update

sudo apt-get install python3


Install Tkinter : 
----------------

sudo apt-get install python3-tk

Install pillow : 
---------------

sudo apt install python3-pillow

Install ffpmeg : 
---------------

sudo apt install ffmpeg


Start the application with thoses commands : 
-------------------------------------------

sudo chmod +x PyConverter.py

./PyConverter.py


If you have this error : /usr/bin/env: ‘python3\r’: No such file or directory : 
------------------------------------------------------------------------------

sudo apt install dos2unix

dos2unix PyConverter.py

dos2unix convert.py

then run again ./PyConverter.py


![PyConverter](https://ibb.co/DLMj66d)


