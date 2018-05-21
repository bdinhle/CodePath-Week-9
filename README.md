# CodePath-Week-9
Time spent: 2.5 hours to setup, 5 hours for lab assignments

## Which Honeypot(s) you deployed: 
  * Dionaea over HTTP
  * Cowrie
  * Wordpot

## Any issues you encountered
I had trouble setting up GCP, in particular, using port 80. The instructions for GCP Users did not mention that I needed to open port 80. After opening port 80 everything worked fine for a day. The next day I had no access to the mhn-admin website via web browser and ssh. I had to delete the vm and redo everything. From then on, I only opened port 80 when I wanted access to it. 

I also set up Cowrie and Wordpot. I left them running for a few days but, the mhn-admin portal said there were no attacks on them.
<img src ="https://github.com/bdinhle/CodePath-Week-9/blob/master/Sensors.png">

After a few days running it, I could not open the mhn-admin website. I kept getting a 504 Gateway Time-out.
<img src ="https://github.com/bdinhle/CodePath-Week-9/blob/master/504%20Gateway%20Time-out.png">

## A summary of the data collected: 
Number of attacks: 12543
TOP 5 Attacker IPs:
 * 69.118.33.48 : (1,076 attacks)
 * 5.62.63.222 : (649 attacks)
 * 77.72.82.101 : (237 attacks)
 * 61.128.149.63 : (99 attacks)
 * 123.249.79.250 : (86 attacks)
  
TOP 5 Attacked ports (Dionaea):
* 5060 (718 times)
* 23 (288 times)
* 3306 (115 times)
* 445 (196 times)
* 80 (79 times)

## Any unresolved questions raised by the data collected
None

## GIF
<img src ="https://github.com/bdinhle/CodePath-Week-9/blob/master/Demo.gif">
