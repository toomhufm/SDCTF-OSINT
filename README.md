# SDCTF-OSINT
# **Chall Name** : mann hunt [HARD] 
## Description : 
We were on the trail of a notorious hacker earlier this week, but they suddenly went dark, taking down all of their internet presence...All we have is a username. We need you to track down their personal email address! It will be in the form ****.sdctf@gmail.com. Once you find it, send them an email to demand the flag!

**Username:**

mann5549

# Solution 

First I used sherlock to find social media accounts with mann5549 username and found this twitter account

[Twitter Account](https://twitter.com/mann5549) 

![Twitter](https://raw.githubusercontent.com/toomhufm/SDCTF-OSINT/main/img/mannweb.png)

Go to his website : https://mann.codes

Inspect elements and found his Github respiratory 

![Respiratory](https://raw.githubusercontent.com/toomhufm/SDCTF-OSINT/main/img/git.png)

I tried to find his email in git commit by adding **.patch** in the commit URL 
[article](https://www.nymeria.io/blog/how-to-manually-find-email-addresses-for-github-users)

Found an email but not what I wanted tho, should be a gmail address instead 

![Img](https://raw.githubusercontent.com/toomhufm/SDCTF-OSINT/main/img/gitmail.png)

So I kept scroll down and found this **author name** 


![Author](https://raw.githubusercontent.com/toomhufm/SDCTF-OSINT/main/img/author.png)

## Emaneul Hunt 

We're getting close! 

I searched his name on Google and found his Linkedin account and found a GoogleDrive 

[Account](https://www.linkedin.com/in/emanuel-hunt-34749a207/)

[Drive](https://drive.google.com/file/d/10No4G_5iv2t5jxbvg2-weXkFouZrnQtg/view?usp=sharing)

## **Final Step** 

I used ghunt to find his info from the drive 

![Img](https://raw.githubusercontent.com/toomhufm/SDCTF-OSINT/main/img/ghunt.png)

__email__ : mann.sdctf@gmail.com

Now send him an email and get the flag 

![Flag](https://raw.githubusercontent.com/toomhufm/SDCTF-OSINT/main/img/flag.png)





