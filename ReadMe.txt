TextFinder version 1.4 
tested on windows 64 bit and ubuntu 
python version 3.10

::Description::
This program will search for the lookup string provided in the variable lookuptext. It will search that string by automatically
picking up the text file in the txtfiles folder and then search each file line by line for possible string match. if the string match
occurs then it will extract that line and store in the Results.txt file.

::usage::
1. provide the string to search in lookuptext variable
2. all text files (having extension .txt) should be placed in the txtfolder which should reside at same path where script is placed.
3. open command prompt and navigate to folder where script is placed.
4. type following on commandprompt
   >python TextFinder.python
5. extracted results will be stored in Results.txt