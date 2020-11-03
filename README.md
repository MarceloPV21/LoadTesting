How to run tests 

jmeter -n -t Login.jmx -l csv/testreport -e -o html/testreport

Non GUI commands with explanation:
# Jmeter -n : This command tells the command prompt I want to run my Jmeter script in Non GUI mode.
#Jmeter -t : This will pick the Jmeter .jmx file and execute it. Here we give the path of jmx file which is under bin folder by default or could be in other folder.
# Jmeter -l : Here we give the path where we want to save the executed results into .csv format. We give the path of bin/example folder along with the same name of csv file. Better to create a folder named “csv” in bin/example folder to keep separate your csv and html files.
# Jmeter -e : This command is used to convert the .csv results into HTML format at the end of the test.
# Jmeter -g : [path to CSV file] generate report dashboard only.
# Jmeter -o : This command saves the html results into given output folder. Better to create a folder named “html” in bin/example folder to keep separate your csv and html files.

