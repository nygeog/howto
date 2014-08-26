#How to get some stuff to work


##GDAL/OGR

###File Geodatabase

Get detailed info for FileGDB:
	
	ogrinfo -al "\Users\danielmsheehan\Desktop\tripData2013\taxi_201301.gdb"
or is it?

	ogrinfo -al /Users/danielmsheehan/Desktop/tripData2013/taxi_201301.gdb





##Get Python to Run with Sublime Text 2

###Windows - Python to run with Sublime Text 2
* 1) [Allow to view Hidden Folders in Windows like this] (http://www.blogtechnika.com/what-is-application-data-folder-in-windows-7/)

* 2) Go to Here:
C:\Users\.......<USERID>......\AppData\Roaming\Sublime Text 2\Packages\Python

* 3) The <strong> Python.sublime-build </strong> file should be modified (in Windows) to look like this;
	
	
		{
		"cmd": ["C:\\Python27\\ArcGIS10.1\\python.exe", "-u", "$file"],
		"file_regex": "^[ ]*File \"(...*?)\", line ([0-9]*)",
		"selector": "source.python"
		}

Full documentation at [StackOverflow - How do I run Python code from Sublime Text 2?](http://stackoverflow.com/questions/8551735/how-do-i-run-python-code-from-sublime-text-2)

###Mac - Python to run with Sublime Text 2
fill in next time installing Sublime Text 2 on Mac OS. 