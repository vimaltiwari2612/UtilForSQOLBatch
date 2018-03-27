# UtilForSQOLBatch

Utiltiy to fetch all the SOQL's in your code base. It takes all the Apex Classes from your code base and Extract Soql document which you can save in any form.

#HowToUseIt

1.Run below command in anonymous Window
    Database.executeBatch(new UtilForSOQLBatch(),chunkSize); // chunkSize can be any figure ,for example : 20 ,40 , 100  etc ...
![screenshot](https://github.com/vimaltiwari2612/UtilForSQOLBatch/blob/master/1.PNG)

2. track you batch completion under Apex jobs
    Setup -> apex jobs -> UtilForSOQLBatch
    
3. after completion of Job , download the extract from Documents tab
![screenshot](https://github.com/vimaltiwari2612/UtilForSQOLBatch/blob/master/2.PNG)



HAVE FUN!!

    
