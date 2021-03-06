------------------------------------------------------------------------------------------------------------
Course Name : Computer Networks
Course Code : CSE5231
Instructor  : Dr. Marco Carvalho
Team 		: Lavanya, Nanditha, Sridhar, Hari
------------------------------------------------------------------------------------------------------------	   
Description : 
This class assignment creates an emulation of two files transfer process in an network environment
of multiple nodes. For the transmission the capabilities of four OSI layers 
i.e. Physical, Datalink, Network and Transport layers are implemented.
------------------------------------------------------------------------------------------------------------
Execution Steps:

1. Navigate to the root path of the project folder
2. Run the following command with input argument as path to the config file
	~<project-root>$ sh run.sh <config-file-path>

Example command to execute using config file placed in <project-root/ext/testfiles
	~<project-root>$ sh run.sh ext/testfiles/FP_configfile_1.txt
	
------------------------------------------------------------------------------------------------------------
More Info :

File Category								Location			Examples
-------------								--------			--------
Config files								ext/testfiles		FP_configfile_1.txt
Input files(referred in config file)		ext/testfiles		FP_inputfile_1.txt
Log files 									ext/logfiles		A2-LOG_2015.10.18.17.56.37.log
Output files								ext/outputfiles		A2-OP_2015.10.18.17.59.28.txt
Java doc 									doc/index.html

------------------------------------------------------------------------------------------------------------ 
Example

Input Config File:
Time	Source	Destination	File
0	ND1	ND2	ext/testfiles/A2_inputfile_1.txt 2
1000	ND1	ND4	5000 1 ext/testfiles/A2_inputfile_2.txt 4


Output Description:	

The two files,FP_inputfile_1.txt and FP_inputfile_2.txt, mentioned in config files reach the destination
nodes 2 and 4 respectively. The reached files are written as output files in the folder ext/outputfiles.

Details of various events involved from source to destination are written to a log file in the folder ext/logfiles
------------------------------------------------------------------------------------------------------------ 
    	
    	
