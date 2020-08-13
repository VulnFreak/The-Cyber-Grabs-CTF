# via_la_france 

<p align="center">
  <img  alt="via_la_france" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/via_la_france.JPG">
</p>

This challenge is check to check basic knowledge of cipher encoding.

we are given encoded string and original string and have to find the key.

```
Encode: ivpfciyjdfehvkqtwscijpwvtrpcighxxhlnunarsypy
Original: theflagforthecypherisheredecryptitandfindkey
```

## Fact To Remember : 
**`When encrypting, the key is added to the plain text to get encrypted text. So, from the encrypted text, subtract the plain text to get the key.`**

So by this fact we can simply get our key. We only have to use original string as key to decode the encoded string and as a result of it we get our needed key.

<p align="center">
  <img  alt="key" src="https://github.com/VulnFreak/The-Cyber-Grabs-CTF/blob/master/Images/key.png">
</p>

## Flag :
`flag{polarise}`
