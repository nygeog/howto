#How to get some stuff to work

##Get Python to Run with Sublime Text 2

###Windows - Python to run with Sublime Text 2
* 1) [Allow to view Hidden Folders in Windows like this] (http://www.blogtechnika.com/what-is-application-data-folder-in-windows-7/)

* 2) Go to Here:
C:\Users\.......<USERID>......\AppData\Roaming\Sublime Text 2\Packages\Python

* 3) The <strong> Python.sublime-build </strong> file should be modified (in Windows) to look like this:
  
	 {
		"cmd": ["C:\\Python27\\ArcGIS10.1\\python.exe", "-u", "$file"],
		"file_regex": "^[ ]*File \"(...*?)\", line ([0-9]*)",
		"selector": "source.python"
	}
