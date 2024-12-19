# File Integrity Monitor

## Summary


One essential security tool for preserving data integrity and spotting possible security breaches is a File Integrity Monitor (FIM). It compares the current state of files and folders with a specified baseline, continuously scanning them for illegal changes. With this real-time monitoring feature, users may quickly spot any inconsistencies and take the necessary steps to reduce security threats.

The two primary features of the PowerShell Script-created File Integrity Monitor (FIM) are gathering a fresh baseline and starting file monitoring using a saved baseline. The tool computes hash values from target files and saves them in a baseline.txt file in order to gather a fresh baseline. The application loads the file:hash pairs from the baseline.txt file and starts file monitoring with a saved baseline, continuously checking the integrity of the file. Users are alerted right away in the event that any differences are found, such as deletions or modifications, offering a vital safeguard against integrity breaches.

![Screenshot 2024-03-31 094650](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/9d237119-70d6-4f99-9f74-df2c1b81a89e)

### Skills Learned


- The importance of continuous file monitoring in maintaining data integrity and detecting security breaches
- How to establish a baseline for file integrity monitoring and compare it against current file states
- The significance of prompt notifications in responding to unauthorized file changes and preserving data integrity.

### Tools Used


- File Integrity Monitor (FIM) software
- Baseline.txt file for storing hash values
- Hash calculation algorithm for file comparison
- PowerShell scripting for FIM implementation

## Images

#### PowerShell script that provides the prompts and responses for the File Integrity Monitor, along with implementing the hashing algorithm.
![Screenshot 2024-03-14 111439](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/c4b81f2c-6c27-43ec-8704-d4ec706dd74e)

#
#### The program initiates with a prompt, asking users, 'What would you like to do?' with 2 options as they begin their interaction.
![Screenshot 2024-03-31 094650](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/9d237119-70d6-4f99-9f74-df2c1b81a89e)

#
#### If 'A' is selected, the program will create a hash to be used as a baseline for the file.
![Screenshot 2024-03-31 094941](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/a3d57443-6b22-44de-bb3e-3dadcbe581eb)
![Screenshot 2024-03-31 095645](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/11b7a674-95a6-4924-bb14-56a7123f86c3)

#












#### If 'B' is selected, the program will begin monitoring files and notify the user of any changes, such as file creation, deletion, or modification.
![Screenshot 2024-03-31 095201](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/b80f85ff-b12d-4071-8b98-61be2efa28e4) 
#### Powershell script for the above response.![Screenshot 2024-03-14 172250](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/2949376c-1472-44dc-beb6-dc26b3888a83)
#
#### A file has been changed!
![Screenshot 2024-03-31 095250](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/c087d2c7-a4ef-4a32-8ad6-4423ee8fa6e2) ![Screenshot 2024-03-31 095423](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/420fb315-4cbf-453c-960a-582fcf14ac9c)






#### Powershell script for changed file.![Screenshot 2024-03-14 175227](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/0d5a445b-7946-42af-a124-186bf9a065e7)
#





