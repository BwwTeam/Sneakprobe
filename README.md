<h1>Sneakprobe scanner introduction</h1>
<h3>0x01 Sneakprobe scanner URL：</h3>
<h5>Sneakprobe's Scan official website https://scan.bwwteam.com/#/</h5>
<h3>0x02 Sneakprobe Scanner Introduction:</h3>
<h5>Sneakprobe adopts the form of B/C architecture. The client can easily access the scanner through a WEB browser and transmit the data directly to the Web server. In addition, Sneakprobe can also realize cross-platform and cross-device scanning and management, and users can access the scan results through the web anytime and anywhere.

Sneakprobe uses front-end and back-end technologies for development, and uses redis for data caching to reduce the performance and response speed of the web service system. Front-end and back-end technologies can achieve better user experience and interaction and meet user needs for functions.</h5>
<h3>0x03 Sneakprobe scanner features:</h3>
<h5>The entire site adopts dark style and the language is English

With memcache, smb, wmi, vnc, telnet, rdp service blasting function

Database blasting, including MSSQL, ftp, orcale, postgresql

Number of plug-ins, currently there are 5000+ plug-ins

Add scan targets in batches

Custom scan content

Custom scan poc

Intranet scan</h5>
<h3>0x04 Sneakprobe manual</h3>
<h5>
  If you do not have an account, please click " Register " to register as a user. Registration is currently open and there is no invitation code, email or mobile phone verification.
  <h4>1、Home</h4>
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image1.png>
  After logging in, there is a menu bar on the left, including Home , Target , Target group , Progress , Loophole , and User Set . On the right is the approximate number of vulnerability data, etc., which can be clearly seen visually.
  <h4>2、Target</h4>
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image2.png>
  The right side of the target column is mainly used to add targets, start scanning, etc. Easy to operate
  <h4>3、Target group</h4>
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image3.png>
  In the target group, you can classify your targets and then scan this category.
  <h4>4、Progress</h4>
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image4.png>
  On the right side of the progress, you can see some progress in vulnerability scanning of the target, so you can know whether you are still in the scanning stage. When you click on the report icon or details, you can see some details of the vulnerability.
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image5.png>
  Click on the corresponding vulnerability to view the request packet and response packet.
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image6.png>
  <h4>5、Loophole</h4>
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image7.png>
  Here is a rough classification of vulnerabilities, the level and quantity of vulnerabilities.
  <h4>6、User Set</h4>
  <img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image8.png>
  User settings are mainly the selection of these scans. For example, if you only want to select port scan, then select port scan. The port range is also chosen by you. The scanning time is mainly used for some network problems. When the scanning time of a target exceeds the set default 60 minutes, the scanning of this target will be ended directly, reducing the need for the client to Some consumption of the machine, etc.

Below is the user's password reset
There is a client at the top, currently only compiled for Linux and Windows. On the right are some service keys of the web side that the client connects to.

Next is a demonstration. After downloading the client, you can directly unzip it and see the two clients for win and linux.
<img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image9.png>
Use -h to use help
<img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image10.png>
Users can specify a poc. When scanning a specified poc, other pocs will not be scanned:
<img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image11.png>
Copy your unique key from the web
<img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image12.png>
When the connection is returned successfully, it means that vulnerability scanning and detection can be performed. Be careful not to close the client! Once closed, all targets that are being scanned, or targets that are queued to be scanned, are deemed to have ended or failed!
After entering the key once, a conf.ini will be generated. You will not need to enter the key value when you start the client later.
<img src=https://github.com/BwwTeam/Sneakprobe/blob/main/img/image13.png>
</h5>
<h3>0x05 contact us</h3>
<h5>Telegram Chat group: https://t.me/ctCCdrBrB_0wZjQy</h5>
<h5>Technology sharing channel: https://t.me/bwwtechnology</h5>

<h3>0x06 pay tribute</h3>
<h5>The intranet scanning system information function is based on fscan: https://github.com/shadow1ng/fscan</h5>
