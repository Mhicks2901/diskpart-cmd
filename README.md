<h1>Diskpart- Command Prompt Disk Cleaning</h1>

<h2>Description</h2>
Project consists of a simple command prompt line that shows the user through erasing/cleaning any drives that are connected to the system.


<h2>Languages and Utilities Used</h2>

- <b>Command Prompt</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>
<p align="center">
Launch command prompt as an admin
  Type Diskpart and press Enter:
  <img src="https://i.imgur.com/1bUR1fo.png"/>
  <br /> 
  <br />
  Type list disk and press Enter:
  <img src="https://i.imgur.com/2BqyRe8.png"/> 
  <br />
  <br />
 Type select disk and the number:
  <img src="https://i.imgur.com/HjNI56d.png"/>
  <br />
  <br />
  Select your desired Disk:
  <img src="https://i.imgur.com/Txa0Dug.png"/>
  <br />
  <br />
  After disk has been selected type Clean
  <br />
  Warning: Once you type clean and hit enter the drive will be erased. No warning will be provided.
  <img src="https://i.imgur.com/RW3QNHu.png"/>
  <br />
  Command Prompt window will display "DiskPart succeeded in cleaning the disk"
  <br />
  Now the drive can be partitioned and formatted
