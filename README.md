<h4>Targeting Packet Sniffing📡🔍</h4>
<p>involves focusing your packet capture on specific network traffic or devices. Whether it is: </p>

<p>Filter by Network: Capture packets from a particular SSID (Wi-Fi network) or BSSID (network device).</p>
<p>Filter by Device: Capture packets from a particular MAC address.</p>
 <br />
_________________________________________________________________________________________________________________________________________
<br />

<img src="https://github.com/user-attachments/assets/ba35bcce-ffdc-48bf-bf42-2b87e0d3d1d6" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/c69fc0d4-14cd-433b-a186-2d8706509d57" height="80%" width="80%" />
  <p> airodump-ng --bssid 6C:B0:CE:E2:58:90 --channel 3 --write testmore wlan0 captures and shows packets from a specific Wi-Fi network with the BSSID number on a specific channel to test on my adapter to sniff network.
 



</p>
  


<br />
_________________________________________________________________________________________________________________________________________

 <img src="https://github.com/user-attachments/assets/45b4b60a-6d52-482e-9074-19e16eb19455" height="80%" width="80%" />
    <img src="https://github.com/user-attachments/assets/f634e186-ddc2-4e95-90df-8e95249bb0d5" height="80%" width="80%" />
    
  <p>using ls to see the list of files in the root directory, and seeing the new file we created so we can open it on wireshark.</p>
  



<br />
__________________________________________________________________________________________________________________________
<br />

<img src="https://github.com/user-attachments/assets/7963bbd4-7978-463b-b17a-e7d0a4cad239" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/a70d3574-f587-45de-b13a-56df86783755" height="80%" width="80%" />
  <p>Opening the new file we creaated using airodump-ng in terminator unto wireshark.</p>
  <p>the same BSSID we scanned in terminator, we can see the manufacturer is NETGEAR in wireshark.</p>
  
