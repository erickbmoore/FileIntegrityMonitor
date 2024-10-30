<h1>File Integrity Monitor (FIM)</h1>

<h2>Description</h2>

#### Overview
This project involves the creation of a File Integrity Monitoring (FIM) system that enables users to monitor the integrity of specified files. The FIM provides two main options for user interaction:

1. **Collect New Baseline**: 
   - The user can choose to calculate the hash values of target files and store the file hash pairs in `baseline.txt`.

2. **Begin Monitoring Files with Saved Baseline**: 
   - The user can load existing file:hash pairs from `baseline.txt` and continuously monitor the integrity of these files.

#### Functionality

- **Option 1**: 
  - Calculates the hash value from target files and stores the results in `baseline.txt`.

- **Option 2**: 
  - Loads the file:hash pairs from `baseline.txt` and initiates a monitoring loop.
  - In this loop, the system calculates the current hash of each file and compares it to the corresponding hash in `baseline.txt`.
  - If a file is changed or deleted, the system notifies the user, displaying a message in color to indicate compromised integrity.

#### Outcome
This FIM system enhances file security by providing real-time monitoring and alerts for any unauthorized changes, ensuring the integrity of critical files.

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Program walk-through:</h2>

<p align="center">
Powershell Script FIM created:  <br/>
<img src="https://imgur.com/jECWnLH.png" height="80%" width="80%" alt="File Integrity Monitor (FIM)"/>
<br />

  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
