Firefox History Viewer 2025
===========================


Simple history viewer for Mozilla Firefox in Python. 

Requires:
- Linux
- Python 3+
- sqlite3
- jinja2
- Mozilla Firefox

Usage: 

	firefoxHistoryViewer.py [OPTIONS]
	Options:
		-h,  --help :  print this usage
		-p,  --path :  path to places.sqlite file
		               default is the one from current user 
		-o,  --out  :  generated report file
		               default is "output.html" in current folder
