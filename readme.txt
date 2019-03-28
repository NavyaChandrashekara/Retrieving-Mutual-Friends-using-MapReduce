input for q1:

hadoop jar <jarname> <classname> <path to soc-LiveJournal1Adj.txt > <outputPath>

input for q2:

hadoop jar <jarname> <classname> <path to soc-LiveJournal1Adj.txt > <outputPath>

input for q3:

-conf.get() was throwing exception "Cannot create path from null string"
- Have hardcoded the path to userdata file and soc-LiveJournal1Adj.txt 
-Have entered the friend pairs into a text file(friendslist.txt) and uploaded it to hadoop.
-Have uploaded soc-LiveJournal1Adj.txt and userdata.txt to hadoop

hadoop jar <jarname> <classname> <path to friends pair file ie friendlist.txt> <path to soc-LiveJournal1Adj.txt > <path to userdata.txt> <outputPath>

Note: Even though the paths given in command line for soc-LiveJournal1Adj.txt and userdata.txt are not used(as its hard coded), it must be provided to run this.

input for q4:

-conf.get("USERDATA") was throwing exception "Cannot create path from null string"
- Have hardcoded the path to userdata file

hadoop jar <jarname> <classname> <path to soc-LiveJournal1Adj.txt > <path to userdata file> <temporary path for job1 output> <final output path>

Note: Even though the paths given in command line for userdata.txt is not used(as its hard coded), it must be provided to run this.