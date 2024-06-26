# Sanity Check

Hello!

This is Team ```Banannanna's``` writeup (we are all sec 3's with this being our first ctf/writeup)

---

The challenge 

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-ivgj.png?raw=true)

---

A breakdown

The Challenge consists of a weird link with the prefix discord.gg

Our best guesses led us to believe that it would be either a file stored on the Discord INC servers or it would be a link to a server.

Well since our best teammate ETHAN DALGADO (he got 0 solves) realised that a file stored on discord servers would have the prefix of media.discordapp.net as visible in this link 

``` https://media.discordapp.net/attachments/1211314841533550613/1233423005506338876/8d3c8178-6910-4b8d-8745-d43bc94fc326.jpg?ex=662d0a30&is=662bb8b0&hm=090c14c4562171c00fbfa7081f388960dad686fce2d33b08a1af30427dc939c3&=&format=webp&width=1058&height=700](https://media.discordapp.net/attachments/958620955465363456/1239574055955464274/image.png?ex=6644bc4d&is=66436acd&hm=23c76ac669b1302d156d2a9e54a05f1f00d04ddecd0e91923493592f03d95640&=&format=webp&quality=lossless&width=1160&height=1148 ```

discord has a terrible skill issue with media so here's the image if you're really curious

https://disboxapp.github.io/web/file?name=12-121001_download-zip-archive-penguins-of-madagascar-model-hd.png&size=23909#eJwVyDsOwjAMANC7dOjYJHZix0gVB0EI5eOoHfoRzcDxge3pPYal9_O6GVPqPtX1Kse7pvOcyrGZ1Hsqy6Z7v4yzLIzgkT1GIWQKxgGKoCAGts5bR94aZEvxZe_6mYm8z9p0XK~_kSrruGwzoI8uN2j6K7A1~0YulJoAI4VcmZRKQxarUlMpGTgFSRECZI2K4_D8AkvtM_E-

(dont load up the image)

Well since it's a Discord link we have no other choice but to join the Discord server.

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/maxresdefault.jpg?raw=true)

---
How to solve it?

Well despite our best instincts we just had to click on the link. With that, we are faced with this screen

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-ixwn.png?raw=true)

So we comply with its instructions

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-ixyw.png?raw=true)

After that, we are asked to pick out which house we would like to swim in 

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iyas.png?raw=true)

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iydb.png?raw=true)

After solving that difficult challenge we are faced with this screen

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iyff.png?raw=true)

We were all immensely sceptical of this "DISCORD INC" website as the whole time it caused my GPU to spike its usage to 100%

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iypk.png?raw=true)

Hence, we used the one way we knew how to use the website

# LOGGING IN

So we went back to the main website link and clicked the very subtle "I have an account" button

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iyve.png?raw=true)

And enter our very secure credentials

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iyyj.png?raw=true)

After that, we are asked to pick out a waterpark again

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-izdl.png?raw=true)

However, even the waterpark was not enough to get past its defences

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-izkd.png?raw=true)

To our horror, we realised that they had been pulling a DDoS attack on us the entire time

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-iznl.png?raw=true)

Despite our private details being leaked to a weird mascot who only goes womp-womp we persevere and make it to the Discord main page
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jdus.png?raw=true)

since the messages failed to load we realised this CTF was going to be MUCH MUCH harder 

so we looked through all the channels

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jhpf.png?raw=true)

and one dm

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jhqh.png?raw=true)

we clicked on the link and were distraught that we didn't have sufficient access

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jhsv.png?raw=true)

this discord website was truly a scam. So we went back to see the server

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jhwx.png?raw=true)
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jhxw.png?raw=true)
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jhzc.png?raw=true)
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jias.png?raw=true)
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jibo.png?raw=true)

just then, we realised there was a link in #announcements

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jiea.png?raw=true)

this was definitely a clue to solving the challenge

so we logged into this website called "x" (kinda sus) and were greeted by this on the main page

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jith.jpeg?raw=true)

we then searched for NusGreyhats

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jive.jpeg?raw=true)

dropped a follow
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jixh.png?raw=true)

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jjas.png?raw=true)

then we watched this video which was an advertising video of sorts for this CTF
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jjcw.png?raw=true)


It did not contain the flag

so we were back to the Discord server

in a desperate attempt to solve it, we simply used the search function to search up the word "grey" as we had insider information that the flag would have the word grey in it

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jlnm.png?raw=true)

the first search result was a dud. However, the second result showed this

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jlpd.png?raw=true)

a mysterious black censor bar?
my speciality

so we clicked on it. and lo and behold as bright as day there was the flag

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240427-jlpy.png?raw=true)

So in conclusion,

* We are pro flag hunters 😎😎😎

* the flag was ```grey{w3lc0m3_to_gctf2024_enjoy_your_stay!} ```


* saumil is the goat of finding flags

* daivik failed physics

* zenneth had some plot development 
