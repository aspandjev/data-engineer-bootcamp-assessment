#My experience and further notes

Put here general information about the steps you took, what you liked, disliked, why did you do X instead of Y and so on.

## HDP Sandbox

I started by downloading the virtual machine. Since my laptop doesn’t have that much memory, I decide to use Azure. I set up my account for a free trial and created the virtual machine there. 
The information for my VM is the following: 
Size
Standard A5 (2 vcpus, 14 GB memory)
Public IP address
52.166.237.196

After some time, I am able to deploy the machine and to connect via Putty. I put all the ports (as specified in the tutorial). However, there are some problems with Ambari on port 8080. When opening the port, it says 404 – Not found, Cannot locate document. Ports 8888 and 4200 work fine. So, I start a new connection, but the issue stays and I’m not able to explore the machine. This was frustrating since it looked like everything else was working except port 8080). I spent time looking for hints and tips on how to solve this, even restarted the connection again (carefully inspecting all the ports), but nothing helped. In the end, according to the tutorial only the ls part was left undone, inspecting Ambari. I decided to look at a tutorial for this.


## HDFS & Hive on Spark

I did X because of Y...
<br>I had issues with Z...
<br>I liked doing T...

## HBase

I did A because of B...
<br>I had issues with C...
<br>I liked doing D...

