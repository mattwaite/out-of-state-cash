# Out of state cash

A look at where donations are coming from in Nebraska political campaigns. 


**REQUIREMENTS**

csvkit
agate
jupyter notebooks

**SETUP**

1. Download the bulk data from the Nebraska Accountability and Disclosure Commission. It will unload more than 60 files. We are interested in formb1ab.txt, which contains info about donations. 
2. Using csvkit, convert the pipe delimited text file to csv. `csvformat -d "|" formb1ab.txt > formb1ab.csv`
3. Open OutofStateCash.ipynb and run the commands.

