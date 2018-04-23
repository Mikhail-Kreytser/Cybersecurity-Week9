# Cybersecurity-Week9
Time spent: 2.5 hours to setup

## Which Honeypot(s) you deployed: 
Dionaea over HTTP
Cowrie
Wordpot

## Any issues you encountered
After installing the mhn-admin I could not access it through my web browser via the ip address. The instructions for GCP Users did not mention that I needed to open port 80. After opening port 80 everything worked fine for a day. The next day I had no access to the mhn-admin website via web browser and ssh. I had to delete the vm and redo everything. From then on, I only opened port 80 when I wanted access to it. I also set up Cowrie and Wordpot. I left them running for a few days but, the mhn-admin portal said there were no attacks on them.

## A summary of the data collected: 
Number of attacks: 12543
TOP 5 Attacker IPs:
 * 69.118.33.48 : (1,076 attacks)
 * 5.62.63.222 : (649 attacks)
 * 77.72.82.101 : (237 attacks)
 * 61.128.149.63 : (99 attacks)
 * 123.249.79.250 : (86 attacks)
  
TOP 5 Attacked ports (Dionaea):
* 5060 (678 times)
* 23 (337 times)
* 3306 (155 times)
* 445 (146 times)
* 80 (78 times)

## Any unresolved questions raised by the data collected
None

## GIF
<img src ="https://i.imgur.com/mpHSLqx.gif">
