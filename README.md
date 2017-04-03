# NDS_Assignment2_.jmx_files    

Scripts are dependant on three files exisitng in your /bin directory where your Jmeter executable is:    

curr_time.csv   
num_threads.csv   
survey_ids.csv   

If you create the above files in your /bin directory the .jmx scripts will read and write to these files.   

Important condition:    

You must run scripts in the below order:     
(TestCase 1 and 2 can be run whenever....)    

1. TestCase3 - creates the surveys   
2. TestCase4 - takes the surveys   
3. Clear Data - deletes the surveys    

(reason: if you ran 4 before 3, there would be no surveys to take!)     
  
