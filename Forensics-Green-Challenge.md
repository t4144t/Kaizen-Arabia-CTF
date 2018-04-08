#Forensics-Green-Challenge

Hello All,

This challenge worths 200 point is Kaizen Arabia 2018 CTF made in 7/4/2018

Download the image from this link : [Green.zip](https://github.com/tal3at7/Kaizen-Arabia-CTF/files/1887643/Green.zip)

Once we open the challenge we find a very simple green image like this:

![green](https://user-images.githubusercontent.com/16243263/38468658-fd4fd05c-3b51-11e8-8630-4569037f6eed.png)

Well ?? Nothing here, so let's try some color planes to see if there are any changes in the colors of the image.

Using 'Stev Solve Tool and by changing the color planes we find:

![image](https://user-images.githubusercontent.com/16243263/38468859-676fb40a-3b54-11e8-92b1-49f095aa4941.png)

The sentence saying : L!ghtUpTh3D@rkn3ss (Yes there is a type here :D)

Submiting this as a flag but it didn't submit so this is not the flag

let's try to find something else..

By analysing if there is any file hidden in the image using binwalk using command (binwalk Green.png)

we find that there is a zip file inside the image. 

Now we have 2 solutions, to extract it with binwalk using command (binwalk -e Green.png) then we will find  a zip file by extracting it we find it needs a password (Guess what password? :P)

The other one is the simplest, just by adding (.zip) after the file name to change the extension of the file to zip

Then just right click and extract and enter the password we found earlier L!ghtUpTh3D@rkn3ss

and here we found the flag: 

![image](https://user-images.githubusercontent.com/16243263/38469057-540f8f9a-3b57-11e8-9d22-e9b14f90ff42.png)

GoodBye ;)
