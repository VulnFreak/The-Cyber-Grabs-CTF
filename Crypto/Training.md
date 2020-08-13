# Challenge: Training

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/taining.JPG)

### Solution
If we look at the string it will look like Hex encoding so we use site [HEX to text](http://www.unit-conversion.info/texttools/hexadecimal/) and enter the string inside it 
we got the our flag :)

## Flag ->
flag{YOU_GOT_ME}

# Challenge: binary_binary

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/binary_binary.JPG)

### Solution 
first we try to convert the binary to text format for this we use site [Binary to text](https://www.rapidtables.com/convert/number/binary-to-ascii.html) 
and enter our binary code here and we got this message 

**IF YOU WANT TO GET FLAG DECODE THIS 666c61677b434f4e47524154537d**

this is look like a hex string again we use [Hex to text](http://www.unit-conversion.info/texttools/hexadecimal/) and we got our binary flag :)

## Flag ->
flag{CONGRATS}

# Challenge: Mr. Robot

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/mr_robot.JPG)

### Solution 

Again if we look for the Challenge it is binary so we use [Binary to text](https://www.rapidtables.com/convert/number/binary-to-ascii.html)
after decoding binary we get a message 

**MZWGCZ33NVZHE33CN52H2===**

This is our Base32 encoding we use site [Base32 Decoder](https://emn178.github.io/online-tools/base32_decode.html) and we got our Mr. Robot Flag :)

## Flag ->
flag{mrrobot}

# Challenge: Based

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/bas3d.JPG)

### Solution
After downloading the Bas3d.txt file i find some base64 encoding i try online tools to decode base64 and i saw a flag.txt file in string so
i try to store the base64 output in a zip file by using this command 

**echo "base64 string"  | base64 -d > flag.zip**

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/base01.jpeg)


and we got a text file in zip but the zip is password protected so i try the Zipcracker tool to crack the zip file and i got the password 

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/base02.jpeg)

and after entering the password i got the Base flag :)

## Flag ->
cyb3rg4abs{Ev3ry_B4s364_is_not_3ncrypt3d}

# Challenge: Ancient_one

![alt text](
