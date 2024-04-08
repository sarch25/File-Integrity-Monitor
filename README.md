# File-Integrity-Monitor

## Objective
[Brief Objective - Remove this afterwards]

A File Integrity Monitor (FIM) is a security tool that constantly checks files and directories for unauthorized changes. It compares the current state of files to a known baseline, alerting users if any discrepancies are detected. FIMs are essential for maintaining data integrity and detecting potential security breaches in real-time.

The File Integrity Monitor (FIM) offers users two primary functionalities: collecting a new baseline or initiating file monitoring with a saved baseline.

For collecting a new baseline, the program calculates hash values from target files and stores the file|hash pairs in a baseline.txt file.

When beginning file monitoring with a saved baseline, the program loads the file:hash pairs from the baseline.txt file. It then continuously monitors file integrity by looping through each target file, calculating the hash, and comparing it to the baseline. If a file's actual hash differs from what is recorded in the baseline, indicating a change or deletion, the user is promptly notified. This feature serves as a crucial safeguard against integrity compromises, alerting users to any unauthorized alterations to their files.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc


![Screenshot 2024-03-31 095645](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/11b7a674-95a6-4924-bb14-56a7123f86c3)

![Screenshot 2024-03-31 095423](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/420fb315-4cbf-453c-960a-582fcf14ac9c)

![Screenshot 2024-03-31 095250](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/c087d2c7-a4ef-4a32-8ad6-4423ee8fa6e2)

![Screenshot 2024-03-31 095201](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/b80f85ff-b12d-4071-8b98-61be2efa28e4)

![Screenshot 2024-03-31 094941](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/a3d57443-6b22-44de-bb3e-3dadcbe581eb)

![Screenshot 2024-03-31 094650](https://github.com/sarch25/File-Integrity-Monitor/assets/130470960/9d237119-70d6-4f99-9f74-df2c1b81a89e)





