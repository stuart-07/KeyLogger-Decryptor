To decrypt a log file there are 5 steps:

*Step1: Go to DiskC > Users> (your user)> appdata> Roaming> Microsoft> CLR> (All the log fils will be there)

*Step2: Copy all the log files (as many u want) in a folder then copy the decrypt.exe in that same folder
where log files you pasted before #Make sure the log files and decrypt.exe in same folder.

*Step3: Open Windows Powershell

*Step4: type cd .\(Your folder directory where the log files and decrypt.exe is in)
             (Example: cd .\Desktop\Folder)

*Step5: Once you have write the line and ur directoy like the exmaple givne below press Enter,
then type "ls" hit enter. If you write "ls" and hit enter it will shwo all the files in that folder if u se them,
then you are in the right track!

*Step6:Then type .\Decrypt.exe '.\(The logfile  numbers you will see in the UI after typing "ls") 'decrypt.log'

Example: .\Decrypt.exe '.\08.09.2023 13_57_53.log' 'decrypt.log'

Note: Copy any log files number "But don't copy it's lenght too" 
___________________________________________________________________

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          9/8/2023   1:55 PM            246 08.09.2023 13_55_12.log
-a----          9/8/2023   1:55 PM            502 08.09.2023 13_55_33.log
-a----          9/8/2023   1:55 PM           3146 08.09.2023 13_55_51.log
-a----          9/8/2023   1:56 PM           4206 08.09.2023 13_56_28.log
-a----          9/8/2023   1:56 PM            886 08.09.2023 13_56_58.log
-a----          9/8/2023   1:56 PM           4206 08.09.2023 13_56__9.log
-a----          9/8/2023   1:57 PM           1998 08.09.2023 13_57_16.log
-a----          9/8/2023   1:57 PM           2426 08.09.2023 13_57_34.log
-a----          9/8/2023   1:57 PM           2426 08.09.2023 13_57_53.log
-a----          9/8/2023   1:58 PM           2426 08.09.2023 13_58_11.log
-a----          9/8/2023   4:28 PM        1115604 Decrypt.exe



###NOTE: You will see this things if uyiu have correctly do the previous teps simply copy any number, 
but don't copy the length number!! Only Copy from Name and onwards example : 08.09.2023 13_57_16.log 

But don't copy "2426 08.09.2023 13_57_34.log" this avoid the first 4 letters!


Then once you have something like this : .\Decrypt.exe '.\08.09.2023 13_57_53.log' 'decrypt.log'

Press enter.

*Step7: Type "ls" again this ime u will see this :


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          9/8/2023   1:55 PM            246 08.09.2023 13_55_12.log
-a----          9/8/2023   1:55 PM            502 08.09.2023 13_55_33.log
-a----          9/8/2023   1:55 PM           3146 08.09.2023 13_55_51.log
-a----          9/8/2023   1:56 PM           4206 08.09.2023 13_56_28.log
-a----          9/8/2023   1:56 PM            886 08.09.2023 13_56_58.log
-a----          9/8/2023   1:56 PM           4206 08.09.2023 13_56__9.log
-a----          9/8/2023   1:57 PM           1998 08.09.2023 13_57_16.log
-a----          9/8/2023   1:57 PM           2426 08.09.2023 13_57_34.log
-a----          9/8/2023   1:57 PM           2426 08.09.2023 13_57_53.log
-a----          9/8/2023   1:58 PM           2426 08.09.2023 13_58_11.log
-a----          9/8/2023   4:28 PM        1115604 Decrypt.exe
-a----          9/8/2023   5:41 PM            975 decrypt.log  <--------------------(New file)





### A new file was created named "decrypt.log" if u see this then you are just moments before the strong!

*Step8:  type :  cat .\decrypt.log

then you will see the full decryption of that logfile in detail. 


*Step9: To decrypt more log files do the same thing again from step6;
*Step10: Enjoy

