# Contribute

In order to change directory run the `cd` command:

	>>> cd C:\Python34\lib\isarchon\pyqt-window
	
In order to convert the `.iu`  markup to a `.py` script run the command below:

	>>> pyuic4 MainWindow.ui -o MainWindowUi.py
	>>> pyuic4 Widget.ui -o DialogUi.py
	
In order to create an `.exe` file run the command below:

	>>> cd c:\python34\lib\isarchon\pyqt-window
	>>> python setup.py py2exe
