### Python & Robot Framework Windows 7###

 *	Download Python 2.7.x Windows installer from: https://www.python.org/
 *	Install Python and edit PATH in Environment Variables
	 *	Environment Variables are located in Start > Computer > Properties > Advanced System Settings >
		Environment Variables
	 *	Select PATH from System Variables and Edit... and add ;&lt;InstallationDir&gt;;&lt;ScriptsDir&gt;  
		(e.g. ;C:\Python27;C:\Python27\Scripts) in the variable value field
 *	Install easy_install
	 *	Download ez_setup.py from: https://bootstrap.pypa.io/ez_setup.py
	 *	Move ez_setup.py to Python27 folder (e.g. C:\Python27) and run it
 *	Install robotframework and selenium2library.
	 *	Open cmd and run to:  
			easy_install robotframework-selenium2library  
		 	easy_install robotframework  
		 	easy_install selenium  
		 	easy_install decorator  
		 	easy_install docutils
 *	Verify Installation
	 *	Start python (C:\> python)
	 *	Type in to the Python prompt "import Selenium2Library"
		 *	If the Python command line interpretor doesn't give error, installation was succesfull
		 
### Run Robot Framework Tests ###

 *	Open cmd and execute your tests:  
		python -m robot.run &lt;filename&gt;  
		or  
		pybot &lt;filename&gt;
   


References:

Robot framework:
http://robotframework.org/  
http://robotframework-seleniumlibrary.googlecode.com/hg/doc/SeleniumLibrary.html?r=2.4  
http://eficode.fi/en/blog/maintainable-automatic-tests-for-your-web-application/  

Installation:  
https://github.com/robotframework/robotframework/blob/master/INSTALL.rst  
https://github.com/rtomac/robotframework-selenium2library/blob/master/INSTALL.rst  

User Story:  
http://www.mountaingoatsoftware.com/blog/non-functional-requirements-as-user-stories  
