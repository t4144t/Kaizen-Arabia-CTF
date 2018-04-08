Hello 


This challenge is all about this sound. You can download it from here : [sound.zip](https://github.com/tal3at7/Kaizen-Arabia-CTF/files/1887623/sound.zip)

when you open it , from the hearing we know it's a kind of voice encoding , by searching for an online tool for decoding the voice hidden secret messages we find amazing tool: 
https://morsecode.scphillips.com/labs/decoder/

upload the sound on it and choose moorse then it will start the decoding process 

when it finishes you will find the message : 

```
The message is: 7 3 7 4 6 5 6 7 6 8 6 9 6 4 6 5 2 0 7 4 6 8 6 5 2 0 7 0 6 1 7 3 7 3 7 7 6 F 7 2 6 4 2 0 6 9 7 3 2 0 7 0 6 5 6 1 6 3 6 8 6 5 7 3
```
But it's not the flag? so what is this? 

hmmmm maybe a kind of hashing? let's use a tool to check hash type

https://md5hashing.net/hash_type_checker

It's telling us that this is a Hex hashing

By converting the hex to Text we got : 
```
steghide the password is peaches ```

BINGO, GoodBye


