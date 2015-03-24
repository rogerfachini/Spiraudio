# Spiraudio
Captures sound waves and converts them into a cool spiral pattern, and sends the output to a CNCserver-enabled drawing bot. 

Requirements:
 - Python 2.7 (https://www.python.org/download/releases/2.7.8/)
    - Requests (python-requests.org)
    - PyAudio (http://people.csail.mit.edu/hubert/pyaudio/)
    - NumPy (http://www.numpy.org/)
    - PyGame (http://pygame.org/)
    - (OPTIONAL) Svgwrite (https://pypi.python.org/pypi/svgwrite/)
  
 - CNCServer (http://github.com/techninja/cncserver)
    - Only needed for connection to a drawing robot. The program will run file without it.

Installation instrutions:

0) Install python and its required modules

1) Clone this repo into a new folder

2) To run it, enter the command **python Spiraudio.py**

3) (optional) To have Spiraudio launch its own version of CNCserver for robot printing, install CNCServer into a new folder called 'cncserver' inside the folder Spiraudio is in. 


