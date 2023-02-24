# idekCTF-2022-Osint-Crime-Confusion-1-W-as-in-Where

Category : OSINT

Description : 

Someone has died unexpectedly. The police is on it, but between you and me, I cannot wait for the police. I am a private investigator and I need your help. Unfortunately, we might be tracked so I cannot give you the information directly. Start in a major social network. Certainly not a problem for the best hacker I know right...? Alright here goes a beautiful poem:

Some people in weird ways were connected
Some were a triangle, some were less directed
For one night they all met
At doctor's Jonathan Abigdail the third they wept 
Things were said, threats in the air
A few days later someone is dead
Who is that someone? That is for you to find,
Also who is the killer, if you really don't mind.

Note for the all the challenges: The challenge is divided into three challenges: Where, Weapon, and Who. Where is the first one the others will come later. In each one you can find the flag somwhere online. You might find the information in any order, however the expected order is: Where, Weapon and Who. Example: If the answer is knife then when you would discover that somewhere: like "the killer used a idek{knife_V5478G}" or instructions on how to get the flag: like idek{weaponUsed_V5478G}. The flag would then be idek{knife_V5478G}.


Solution : 

At first, I manually searched on social media for Jonathan Abigdail, and after searching, I found a profile on Instagram with the name of Dr. Jonathan Abigdale III

![Screenshot (220)](https://user-images.githubusercontent.com/80649768/221230296-a58fba85-dd22-4897-8c90-4a3ee75946de.png)

![Screenshot (219)](https://user-images.githubusercontent.com/80649768/221231935-95710fb0-9903-4dc2-88eb-6e165f898aaa.png)




I already found a post with a hashtag

![Screenshot (218)](https://user-images.githubusercontent.com/80649768/221231962-9f4d5f61-f092-4570-8829-8f745ca6c330.png)


Clicking the hashtag brings us to another image. The image is another eye but neither the image itself nor the description contains anything of interest. However, we see that the image is posted by a different user with the username

![Screenshot (221)](https://user-images.githubusercontent.com/80649768/221232776-48609fb1-8128-4fa7-90ba-dfc60d03e427.png)


After into the account of the other user, we see that there is a post that contains important details

![Screenshot (229)](https://user-images.githubusercontent.com/80649768/221233560-57e6b853-49db-4a84-b91e-d3f6a3478e93.png)

Checking out the image, we find a number of clues from the description, namely the great_paintball_portugal competition, and something being listed for sale on eBay.

I initially thought that the great_paintball_portugal competition was a real location or event, and tried to google keywords related to this, to no success. Next I tried to see if great_paintball_portugal could be a username on eBay

To that effect, eBay’s user profiles are accessible at https://www.ebay.com/usr/"username". Replacing "username" with great_paintball_portugal brings us to the user’s profile.

As we can see in the can see in the description, there is a link to a Wix website.

![Screenshot (223)](https://user-images.githubusercontent.com/80649768/221235170-819ca4f0-062c-4f4b-b4e9-2de6fb1ca343.png)

Navigating to the website, we see only see a home page with no sign of the blog post as mentioned in the eBay description.

![Screenshot (226)](https://user-images.githubusercontent.com/80649768/221236779-9a054ced-ad4c-4dc3-955a-68e2973b3baf.png)

After a while, I tried append /blog to the URL, and it worked! We can see a single post on the website.

![Screenshot (227)](https://user-images.githubusercontent.com/80649768/221236819-79494734-6ab2-464b-97be-36d1d387e5e8.png)

wow , the flag is here


![Screenshot (228)](https://user-images.githubusercontent.com/80649768/221237291-8c8bd6ca-b613-49de-8aa1-812b0086e0a6.png)




