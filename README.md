<h1>Wireshark Packet Analysis</h1>


<h2>Description</h2>
In this Lab, I will be presenting the different data you can find with an inputted Hash value into Wireshark.
<br />


<h2>Utilities Used</h2>

- <b>Wireshark</b> 

<h2>Environments Used </h2>

- <b>Linux OS/VM</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Open the Wireshark application and simply select the desired or investigated packet: <br/>
<br />
<img src="Screenshot 2025-05-27 223112.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You can view the packet file details by clicking the statistics tab and then clicking on Capture File Properties (this shows the file details, time frame of packets, the capture, Interfaces used, and the capture file comments).  <br/>
<br />
<img src="Screenshot 2025-05-27 163918.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate to the packet number and click on the packet time frame, payload size and other info: <br/>
<br />
<img src="Screenshot 2025-05-27 165425.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Export and save the file to look up the hash in the terminal via- md5sum (filename)  <br/>
<br />
<img src="Screenshot 2025-05-27 173259.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The error button will show the highest information level with the number of errors and warning that were tiggered:  <br/>
<br />
<img src="Screenshot 2025-05-27 174828.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>
