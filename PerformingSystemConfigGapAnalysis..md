> ## Performing System Configuration Gap Analysis
>
 Gap analysis is widely used in business strategy, project management, and process improvement to prioritize actions and allocate resources effectively.
 It identifies gaps or discrepancies between "what is" (current performance) and "what should be" (target performance), helping to outline the necessary steps to bridge the difference.


Determine the build number for windows server in this example am using Windows server 2019.

 - **Step 1**: *Select Search magnifing icon from the taskbar*
		  Type : ***winver***

     ![cmd_winver](https://github.com/user-attachments/assets/7d1ff376-e382-4098-a689-2bf3db79a2d3)

	
   Results : version 1809 , OS Build Number 17763.

 -**Step 2** :  *Copied my Lab Files from D - C dirve*
   
   			Run Powershell as Administrator : cmd : copy D :\*c: \LABFILES
                	Navigate to c -drive : cmd : cd c:\LABFILES
   	        	To view the list of files in the Lab file folder : cmd : ls

   ![copied_mylabfiles_tocdrive](https://github.com/user-attachments/assets/0c94e807-4038-4d51-9e64-1bc26babc908)


- **Step 3** : *unzip the two folder to be used in this lab*
  
	  	cmds : Expand-Archive - Path PolicyAnalyzer.zip
	               Expand-Archive -Path Windows 10 Version 1809 and Windows Server 2019 Security Baseline.zip


    ![unzipping_files](https://github.com/user-attachments/assets/99172f91-75e3-4e99-95b9-a4671fa5c088)


  Open the Policy Analayer application with this command.
  
  		c: \LABFILES\PolicyAnalyzer\PolicyAnalyzer_40\PolicyAnalyzer.exe
  

    ![policyanalyzer](https://github.com/user-attachments/assets/59426097-87ff-454b-86ca-367bc4925f45)

  At the bottom of the Policy Analyzer window, *select the Policy Rule sets in* field.


  Select Documentation fold found inside the Windows 10 Version 1809 and Windows Server 2019 Security Baseline folder.
  Perform a View / Compare of *MSFT-Win10-v1809-RS5-WS2019-Final* , mark the checkbox , then select *View / Compare*

   ![policyviewer](https://github.com/user-attachments/assets/b80de68b-b506-422d-93cc-b00b256259d0)

 Perform a compare to Effective State using the Policy Analyzer by selecting the *Compare to Effective State*

  ![policyviewer2](https://github.com/user-attachments/assets/ca965916-8b88-4fdf-83a3-38ff600b8e1a)

 Here one can compare the baseline requirements verses the currently set configured policies

  ![compareandview](https://github.com/user-attachments/assets/297aaa43-8bb2-4cdc-a657-7aad742cb619)

  






  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI0MzMxMjQ0MSwtMTU3NjU4ODc0Nl19
-->