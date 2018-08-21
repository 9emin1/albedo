# rorymercury
Yo dawg I heard you love End-to-End Encryption.

## description
End-to-End Encrypted webshell for lulz and annoyance.

Implementated with Cryptopost class from the following reference package:  
https://www.phpclasses.org/package/9912-PHP-Encrypt-and-decrypt-forms-with-AES-and-RSA.html  
Full description is available above.

Simple PHP webshell that uses the system function to execute command, taken from:   
webshells/php/simple-backdoor.php in Kali.

## misc
Inspired from projects that has E2EE implementation for financial instituitions that have to abide to some regulations (Singapore MAS).

## usage
1. Find a vulnerable server that has an exploitable file upload feature
2. Upload rorymercury.php
3. Enjoy your encrypted POST request webshell

## to-do list
1. Add pictures to h2ck3r-m1ze it
2. Add authentication to the backdoor
3. Add obfuscation on the PHP code
4. Clean up unnecessary JavaScript code
5. openssl.cnf file to be in a PHP variable instead of writing to /tmp folder
6. Add jsp support

## demo
<figure class="video_container">
    <video controls="true" allowfullscreen="true">
        <source src="rorymercury-demo.mov" type="video/mp4">
    </video>
</figure>
