# Elliptic-Curve-Cryptography

## Overall Program
Random Key generation using Elliptic curve cryptography

Requirements for ECC
* Using non-singular elliptic
* Interaction with the keys and files
* Discrete log 

This project is a key generation program  that creates a private key and public key using elliptic curve cryptography. The key size is unknown but likely to be low.  It will be able to print the keys onto a text file for transport. After generation there will an encryption option in the menu which also prints to a text file

## Stages
* Research elliptic curves over finite fields
* Start creation of first functions
* Key Generation
* Saving Key pair’s into text files

### The program's main menu will have  
An option to generate a new key pair
An option to save key pair into a text file
An option to encrypt ascii using a key pair
An option to decrypt ascii using a key pair

First Week
Start the function that generates key pairs
Second Week 
Finish the functions that generates key pairs
Third Week
Finish function that saves key pairs into .txt
Start Encrypt ascii using a key pair function
Fourth Week 
Finish encrypt ascii using a key pair function
Start decrypt ascii function using a key pair
Fifth Week
Finish decrypt function and do graphic work with 
Console graphic work for menu

## Testing
The Majority of the testing in my program
was testing the return value’s of the important functions such as those who
calculated the point of the parent elliptic group which is the first step to
generate a keypair.

This consisted of using various reference
websites to verify my programs results. The one that I used the most was an
interactive graph created by Andrea Corbellini

https://cdn.rawgit.com/andreacorbellini/ecc/920b29a/interactive/modk-mul.html

This graph calculated the order of the
elliptical group, the subgroup of a given point, scalar multiplication of a
point and point addition. This tool helped me to realize when  my values were correct. The problem arose
when the values continued to get higher. The website is unable to deal with
primes over 10000 and crashed when attempted. This created a problem as I was
no longer able to verify my answer when is that of a
high degree.

An example an output from my program I was
able to check the parent group order by visiting the website

ECC ENCRYPTION KEY GENERATION
(1) Key Generation
(2) Remnants of Schoof
(3) Print Keys to File (only if ran
keygen)
(4) Quit

1
Prime p = 13
a = 2
b = 3

Parent group order N = 18
Random subgroup order n = 3
Cofactor N / n = 6
Random point on curve: X = 3 Y = 6
Private is d in which H = dG

Private Key = 2

Public Key is point H
X = 3
Y = 7
