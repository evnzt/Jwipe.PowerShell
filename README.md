<p align="center">
<img width="340" height="220" alt="428757709-0d87934c-ecbf-4062-8e22-dd29b5c00add" src="https://github.com/user-attachments/assets/6f9f55e7-2bd5-481b-a19c-5eccf86a1a2e" alt="Microsoft PowerShell Logo" />
</p>

<h1>JWipe - Disk Sanitization</h1>

<h2>Description</h2>
A PowerShell utility that safely zeros out (wipes) any drives connected to the system. Select the target disk and the number of overwrite passes to run. The script then generates a matching DiskPart script from your choices and then runs DiskPart to do the actual sanitizing.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used</h2>

- <b>Windows 10</b> (21H2)

<h2>Highlights</h2>

- Interactive disk selection
- Configurable number of passes
- Auto-builds a DiskPart script from your choices
- Launches DiskPart to execute the wipe

<h2>Prerequisites</h2>

- Download the script file
- Run PowerShell as administrator from script directory

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<br />
<img src="https://github.com/user-attachments/assets/dea89e9c-f46d-4516-b8de-4b706b3d19e8" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
   ```cmd
   Powershell .\JWipe.ps1
   ```

---

<p align="center">
Select the disk:  <br/>
<br />
<img src="https://github.com/user-attachments/assets/0bb6dced-5dcd-4a7d-8bf6-b36815ecfa10" height="80%" width="80%" alt="Disk Sanitization Steps"/>

---

<p align="center">
Enter the number of passes (recommended 10): <br/>
<br />
<img src="https://github.com/user-attachments/assets/b4d4ad1f-7d7f-4eb9-8183-32f7a2541b33" height="80%" width="80%" alt="Disk Sanitization Steps"/>

---

<p align="center">
Confirm your selection:  <br/>
<br />
<img src="https://github.com/user-attachments/assets/e0ff5177-cd6b-4005-8120-b707e62cd26d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
   ```cmd
   confirm
   ```

---

<p align="center">
Wait for process to complete (may take some time):  <br/>
<br />
<img src="https://github.com/user-attachments/assets/f07d35fc-388f-415b-af47-8131aefc218a" height="80%" width="80%" alt="Disk Sanitization Steps"/>

---

<p align="center">
Sanitization complete:  <br/>
<br />
<img src="https://github.com/user-attachments/assets/6d66e41c-8011-4269-bf48-4e48d23d91aa" height="80%" width="80%" alt="Disk Sanitization Steps"/>

---

<p align="center">
Congratulations! Hopefully, the Sanitization has been completed without any errors.

---

<p align="center">
Observe the wiped disk:  <br/>
<br />
<img src="https://github.com/user-attachments/assets/7bc91918-b6e7-4320-a5bf-a31653270ddc" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
