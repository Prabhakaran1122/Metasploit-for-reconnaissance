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

### msf > nmap -sT 192.168.1810/24-p1-1000

<img width="614" height="108" alt="image" src="https://github.com/user-attachments/assets/f4f0e3c4-6392-4bb5-994a-472d72af9848" />


### msf > db_nmap 192.168.181.0/24

<img width="825" height="345" alt="image" src="https://github.com/user-attachments/assets/189142ad-6815-4dc3-8db0-1f093346f637" />

### kali > ls-l

<img width="516" height="89" alt="image" src="https://github.com/user-attachments/assets/199c5add-5d60-4748-ae17-52075a6c70e3" />

### search 


### info

<img width="826" height="766" alt="image" src="https://github.com/user-attachments/assets/b7f74d3b-adf5-4fb5-a9e3-3bce5796fe3e" />

## MYSQL ENUMERATION

### db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

<img width="825" height="345" alt="image" src="https://github.com/user-attachments/assets/a6398b67-257e-40c3-8634-7afbb3cb8a77" />

### search

<img width="824" height="223" alt="image" src="https://github.com/user-attachments/assets/06568ffd-094e-4244-b166-82970e4d17bb" />

###  use 11 Or: use auxiliary/scanner/mysql/mysql_version

<img width="818" height="158" alt="image" src="https://github.com/user-attachments/assets/66b252ea-3514-44f1-a550-7fa89fa31507" />

### Use the set rhosts command to set the parameter and run the module, as follows:

<img width="823" height="111" alt="image" src="https://github.com/user-attachments/assets/eaff8658-4245-4087-9462-f70338bf7e8a" />

### After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

<img width="826" height="309" alt="image" src="https://github.com/user-attachments/assets/34b5c4d4-37d6-43f0-8a9a-70c38a21ff7a" />

### /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 

<img width="826" height="311" alt="image" src="https://github.com/user-attachments/assets/8a5e2345-fb27-40f2-acba-2215a8fd6c3e" />

<img width="820" height="230" alt="image" src="https://github.com/user-attachments/assets/217fbd68-9d4b-4bdb-b693-8c812d2f16db" />

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully

## Invoke msfconsole

### OUTPUT:

<img width="602" height="527" alt="image" src="https://github.com/user-attachments/assets/15e28d9c-25e7-4909-9974-3722fdaaf1ff" />

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

<img width="684" height="867" alt="image" src="https://github.com/user-attachments/assets/36003a67-4191-4ca2-a8b9-4bff5303b79d" />

## Port scanning:

### msf > nmap -sT 192.168.1810/24-p1-1000

<img width="734" height="418" alt="image" src="https://github.com/user-attachments/assets/e871d329-fc68-42c2-825d-5c84f8410e34" />

### msf > db_nmap 192.168.181.0/24

<img width="825" height="345" alt="image" src="https://github.com/user-attachments/assets/189142ad-6815-4dc3-8db0-1f093346f637" />

### kali > ls-l

<img width="516" height="89" alt="image" src="https://github.com/user-attachments/assets/199c5add-5d60-4748-ae17-52075a6c70e3" />

### search 


### info

<img width="826" height="766" alt="image" src="https://github.com/user-attachments/assets/b7f74d3b-adf5-4fb5-a9e3-3bce5796fe3e" />

## MYSQL ENUMERATION

### db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

<img width="825" height="345" alt="image" src="https://github.com/user-attachments/assets/a6398b67-257e-40c3-8634-7afbb3cb8a77" />

### search

<img width="824" height="223" alt="image" src="https://github.com/user-attachments/assets/06568ffd-094e-4244-b166-82970e4d17bb" />

###  use 11 Or: use auxiliary/scanner/mysql/mysql_version

<img width="818" height="158" alt="image" src="https://github.com/user-attachments/assets/66b252ea-3514-44f1-a550-7fa89fa31507" />

### Use the set rhosts command to set the parameter and run the module, as follows:

<img width="823" height="111" alt="image" src="https://github.com/user-attachments/assets/eaff8658-4245-4087-9462-f70338bf7e8a" />

### After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

<img width="826" height="309" alt="image" src="https://github.com/user-attachments/assets/34b5c4d4-37d6-43f0-8a9a-70c38a21ff7a" />

### /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 

<img width="826" height="311" alt="image" src="https://github.com/user-attachments/assets/8a5e2345-fb27-40f2-acba-2215a8fd6c3e" />

<img width="820" height="230" alt="image" src="https://github.com/user-attachments/assets/217fbd68-9d4b-4bdb-b693-8c812d2f16db" />

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
