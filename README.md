
## Ciphers Project


### Quick start

- in order to run the program you have to install `emu8086`
- Clone the repo: https://github.com/Ola-Mohamed/Ciphers

____________________________________________________________________________________
 Security communication become more important today as a result increasing use of the electronic communication for many daily activities such as internet banking, online shopping.

To establish secure communication, Transmitted data must be encrypted to prevent attacking it using cipher algorithms.
![1](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/1.jpg)


In our project transmitted data, be encrypted and decrypted using two of the most efficient and fastest software encryption algorithms ever (Mono Numeric MonoAlphabetic Cipher)
____________________________________________________________________________________

## Project Description:
This simple encryption program is made for the 8086 microprocessor.
there are two-way to encryption :
1- In the mono-numeric substitution encryption, each alphabetic letter is substituted by a number according to the following table:
|Plain text  | a | b | c | d | e | f | g | h | i | j | k | l | m | n | o | p | q | r | s | t | u | v | w | x | y | z |
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|  Cipher text| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12| 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 |

2- In the monoalphabetic substitution encryption, each alphabetic letter is substituted by another letter according to the following table:
|Plain text  | a | b | c | d | e | f | g | h | i | j | k | l | m | n | o | p | q | r | s | t | u | v | w | x | y | z |
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|  Cipher text| q | w | e | r | t | y | u | i | o | p | a | s | d | f | g | h | j | k | l | z | x | c | v | b | n | m |

## Solution
1. Constructing the table and storing it in the memory.
2. Writing a program to encrypt the input message
3. Decrypting the cipher text to obtain the original text message.

____________________________________________________________________________________
## Project Phases
![image](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/Picture4.jpg)

____________________________________________________________________________________
## Implementation in Assembly
We include `'emu8086.inc'` and CAll some Macros to reduce the code implemantation
such as : `DEFINE_GET_STRING `  and   `DEFINE_PRINT_NUM_UNS ` ,also implemented a procuder Called `parse` 
![image](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/parse%20fun.png)


####  The Program Flow Works As Follows, At Startup The Main Menu Will Be Displayed For The user Like That
![1](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/Picture3.png)

Now if user choose `1` this will appear on screen  after encryption & decryption finished:
![image](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/Picture2.png)



 if user choose` 2` this will appear on screen  after encryption & decryption finished:
![image](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/Picture1.png)

 

| Bug Description | status |
| --- | --- |
| 1- bug in take input from user | Solved |
| 2-bug in storing tables of mononumeric cipher   |  Solved |
| 3-bug of infinite loop        |  Solved |


____________________________________________________________________________________
## Team Members & Work Timeline
 1. [Ola Mohamed](https://github.com/Ola-Mohamed)
 2. [Rana Osama](https://github.com/RanaUsama20)
 3. [Yasmin Atyia](https://github.com/yasmin-attia)
 4. [Doha Khaled](https://github.com/dohakhaled33)
 5. [Mariam Fathi](https://github.com/Mariam-Fathi)
 
and here is a screenshot of the workflow using GitKraken software ...
![2](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/gitkraken1.png)
![3](https://github.com/Ola-Mohamed/Ciphers/blob/main/resource/git2.png)
















  








