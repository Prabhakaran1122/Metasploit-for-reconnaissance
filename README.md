# Metasploit-for-reconnaissance

# Metasploit

Metasploit for reconnaissance in pentesting

## AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system

### OUTPUT:

# Metasploit-for-reconnaissance

# Metasploit

Metasploit for reconnaissance in pentesting

## AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system

### OUTPUT:

<img width="624" height="465" alt="image" src="https://github.com/user-attachments/assets/51bbde22-4a82-4ed3-9a01-f7491ddc85b0" />


## Invoke msfconsole

### OUTPUT:

<img width="624" height="451" alt="image" src="https://github.com/user-attachments/assets/a0488283-ac7d-42de-b905-07a7314c09eb" />


Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

<img width="828" height="895" alt="image" src="https://github.com/user-attachments/assets/64d412a7-58d4-4ab8-9da1-a9c7f9a0ebca" />


## Port scanning:

### msf > nmap -sT 192.168.103.220-p1-1000

<img width="569" height="80" alt="image" src="https://github.com/user-attachments/assets/d507cbc3-9b31-4c7d-8d17-a845eb1d017a" />



### msf > db_nmap 192.168.103.220
<img width="550" height="129" alt="image" src="https://github.com/user-attachments/assets/7d2a09b3-79d4-4549-a9bb-bee05d00e434" />


### kali > ls-l

<img width="516" height="89" alt="image" src="https://github.com/user-attachments/assets/199c5add-5d60-4748-ae17-52075a6c70e3" />

### search 
<img width="932" height="900" alt="image" src="https://github.com/user-attachments/assets/f580e46a-7e00-4375-8681-51032e267285" />



### info

<img width="826" height="766" alt="image" src="https://github.com/user-attachments/assets/b7f74d3b-adf5-4fb5-a9e3-3bce5796fe3e" />

## MYSQL ENUMERATION

### db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

<img width="510" height="122" alt="image" src="https://github.com/user-attachments/assets/b1154f0b-3621-495d-b55c-130bab8cdb04" />

### search

<img width="646" height="384" alt="image" src="https://github.com/user-attachments/assets/a7b9ddf0-b278-40f4-9e76-2ab0a61332a4" />


###  use 11 Or: use auxiliary/scanner/mysql/mysql_version

<img width="630" height="261" alt="image" src="https://github.com/user-attachments/assets/60cca1bb-9183-4359-a330-2244309185ba" />

### Use the set rhosts command to set the parameter and run the module, as follows:

<img width="607" height="78" alt="image" src="https://github.com/user-attachments/assets/b6c09141-dc53-4eee-8a59-f21bd6675666" />

### After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

<img width="947" height="544" alt="image" src="https://github.com/user-attachments/assets/f650d956-a73f-4c43-ae10-5216574f5f55" />

### /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 


<img width="820" height="230" alt="image" src="https://github.com/user-attachments/assets/217fbd68-9d4b-4bdb-b693-8c812d2f16db" />

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully

