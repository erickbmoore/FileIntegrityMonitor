<h1>File Integrity Monitor (FIM)</h1>

Test. Update in progress...

<h2>Description</h2>
FIM creation. The FIM will Ask the user what they want to do. Two Options: 1) Collect new Baseline or 2) Begin monitoring files with saved Baseline. Option 1 will calculate HASH value from target files and store the file hash pairs in baseline.txt. Option 2 will load file:hash pairs from baseline.txt. Continuously monitor file integrity by looping through each file, calculate the hash, and compare the file|hash to what is baseline.txt. It will notify user if a file is changed or deleted by comparing the actual hash to what is recorded in the baseline and print to the screen with color if a file has been changed or deleted (Integrity compromised).
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
