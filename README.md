# WarGamesNE
Network engineering Wargames

# Y. K. Rajapakshe  - IT10004746

# Wargames Assignment

### Bandit 0 - 1
```sh
bandit0@melinda:~$ ls
readme
bandit0@melinda:~$ cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1


```
### Bandit 1 - 2


```sh
bandit1@melinda:~$ ls
-
bandit1@melinda:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9 

```

### Bandit 2 - 3

```sh
bandit2@melinda:~$ ls
spaces in this filename
bandit2@melinda:~$ cat spaces\ in\ this\ filename
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

```

### Bandit 3 - 4

```sh
bandit3@melinda:~$ ls
inhere
bandit3@melinda:~$ cd inhere
bandit3@melinda:~/inhere$ ls
bandit3@melinda:~/inhere$ ls -a
.  ..  .hidden
bandit3@melinda:~/inhere$ cat ./hidden
cat: ./hidden: No such file or directory
bandit3@melinda:~/inhere$ cat .hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB

```

### Bandit 4 - 5

```sh
bandit4@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  inhere
bandit4@melinda:~$ cd inhere
bandit4@melinda:~/inhere$ ls -a
-file00  -file02  -file04  -file06  -file08  .
-file01  -file03  -file05  -file07  -file09  ..
bandit4@melinda:~/inhere$ file ./*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@melinda:~/inhere$ cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit4@melinda:~/inhere$

```

### Bandit 5 - 6

```sh
bandit5@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  inhere
bandit5@melinda:~$ cd inhere
bandit5@melinda:~/inhere$ ls -a
.            maybehere02  maybehere06  maybehere10  maybehere14  maybehere18
..           maybehere03  maybehere07  maybehere11  maybehere15  maybehere19
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16
maybehere01  maybehere05  maybehere09  maybehere13  maybehere17
bandit5@melinda:~/inhere$ find ./ -size 1033c
./maybehere07/.file2
bandit5@melinda:~/inhere$ cat ./maybehere07/.file2
DXjZPULLxYr17uwoI01bNLQbtFemEgo7

```

### Bandit 6 - 7

```sh
bandit6@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile
bandit6@melinda:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@melinda:~$ ^C
bandit6@melinda:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

```

### Bandit 7 - 8

```sh
bandit7@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  data.txt
bandit7@melinda:~$ cat data.txt | grep millionth
millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```

### Bandit 8 - 9

```sh
bandit8@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  data.txt
bandit8@melinda:~$ cat data.txt |sort|uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```

### Bandit 9 - 10

```sh
bandit9@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  data.txt
bandit9@melinda:~$ string data.txt | grep '='
-bash: string: command not found
bandit9@melinda:~$ strings data.txt | grep '='
epr~F=K
7?YD=
?M=HqAH
/(Ne=
C=_"
I========== the6
z5Y=
`h(8=`
n\H=;
========== password
========== ism
N$=&
l/a=L)
f=C(
========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
ie)=5e

```

### Bandit 10 - 11

```sh
bandit10@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  data.txt
bandit10@melinda:~$ base64 -d data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

```

### Bandit 11 - 12

```sh
bandit11@melinda:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile  data.txt
bandit11@melinda:~$ cat data.txt | tr a-zA-Z n-za-mN-ZA-M
The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

```

### Bandit 12 - 13

```sh

```
