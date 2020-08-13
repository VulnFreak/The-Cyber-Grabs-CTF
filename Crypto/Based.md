# Challenge: Based

<p align="center">
<img alter ="base" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/bas3d.JPG">
</p>

### Solution
After downloading the [Bas3d.txt](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Challenge_docs/B4s3d.txt) file i find some base64 encoding i try online tools to decode base64 and i saw a flag.txt file in string so
i try to store the base64 output in a zip file by using this command 

**echo "base64 string"  | base64 -d > flag.zip**

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/base01.jpeg)


and we got a text file in zip but the zip is password protected so i try the Zipcracker tool to crack the zip file and i got the password 

![alt text](https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/base02.jpeg)

and after entering the password i got the Base flag :)

## Flag ->
cyb3rg4abs{Ev3ry_B4s364_is_not_3ncrypt3d}
