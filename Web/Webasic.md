# Webasic 

<p align="center">
  <img  alt="web" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/webbaisc.png">
</p>

In the challenge description we are given a link which redirect as to a website. There we get lot of button when we click on it it takes to the another page which says `cyb3rg4abs{Fake_flag}`.

<p align="center">
  <img  alt="home" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/home_page.png">
</p>

<p align="center">
  <img  alt="try" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/try.png">
</p>

But one thing here is that when we check url it is something like `http://blog.nihalcybersecurity.com/1.html`. One thing here is when we like any button ony the numeric value get change.
So I decide to write a script to send the request ot all pages and get response.

Script: 

```
import os
for i in range(1,1001):
        os.system(f'curl http://blog.nihalcybersecurity.com/{i}.html')
```

<p align="center">
  <img  alt="terminal" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/termianl_req.png">
</p>

After sometime I see a response which have one comment in it `A cake is waiting for you at grabmeflag.html`.

<p align="center">
  <img  alt="result" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/result.png">
</p>

So. I visit the page and there I check for source code there is javascript which sets our flag to the cookie.

<p align="center">
  <img  alt="cookie" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/web_basic_source.png">
</p>

After it you can simply check cookies and get the flag.

#### WAY-1
Copy the javascript statement and beautify it using [Beautifier](https://beautifier.io) and easily get the flag.
<p align="center">
  <img  alt="basic" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/basic_01.png">
</p>

### WAY-2
Go the cookies and get your flag
<p align="center">
  <img  alt="basic" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/basic_02.png">
</p>


## Flag :
`cyb3r4grabs{U_g0T_S0M3_sk1LlS_1_4m_1mpr3ss3d}`
