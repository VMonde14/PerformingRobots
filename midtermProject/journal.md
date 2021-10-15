## Burn Out - The Robot

# The Concept

In this project my main goal was to create a robot with a certain amount of energy. It would happily complete any task you ask of it as long as its energy was still in stock. Once its energy was completely depleted, it would need to rest, thus refusing to move. 

[Here is the final video!](https://youtu.be/UVROnT5NgNw)

# The Process

This process was both very frustrating and very rewarding. I started with the Neopixel. First, I created what I call the "base shape" of the energy bar. This became a white box surrounding the actual energy bar, which is varying shades of green and orange. This was inspired by a video game, Stardew Valley, which uses an energy bar that starts green and slowly drops and turns yellow and red as energy depletes. 

![011](https://user-images.githubusercontent.com/54527264/137479975-c7a05adf-8ae3-4a7f-b3a7-ab801bee9a70.png)
![de92ave88rv01](https://user-images.githubusercontent.com/54527264/137480019-878a0879-0e9f-4d26-810e-f0bc2ff64930.jpg)

Once I had this sequence done, I moved on to the "sleep" function. This would allow the robot to recharge its energy if the handler pressed a certain button. When I first coded this, it worked really well- it played a similar sequence to the depletion of energy sequence in which the yellow and red would slowly turn green again over time. 

Then, I looked at the radio transmitter and reciever. At this point, I was worried that I would get disorganized and confused really easily, so I took a break from electronics and made notes about how each item was hooked up and connected to the arduino. I actually used my closet door as a white board to organize my thoughts. This would prove to be extremely helpful.

![IMG_6329](https://user-images.githubusercontent.com/54527264/137482841-8d40e0ef-69a1-4da8-bb60-d8066dc553cf.jpg)

With this, I felt like I could proceed to putting the individual pieces together. As of now, I had the majority of the cardboard structure done, the neopixel, and the radios working. With my notes on the board, I put it all together, making sure to pay attention to matching pins and staying organized. Once it was together, I tested it to make sure it still worked, and then moved on to add the wheels. Finally, I had all the pieces set up. Now I just needed to construct them into the robot! I had a box that, coincidentally, was the exact same height as the neopixel, which meant I could slide it in and out without having to fasten it. This made trouble shooting very easy. 

One of the decisions I made was to use the secured breadboard on the tray from Intro to IM, which made it very easy to pull out the electronics if there was a problem. I used blue tack to make sure the individual pieces didn't get too displaced as well. I struggled a bit with where to put the power boost and battery. I needed it to be semi-accessible since it was my on/off switch, so I put it on the top of the cardboard box, which reuined the aesthetic a little but was very convenient. The blue tack didn't work well for this, so I used a thin red tape to secure it better. 

## Issues I ran Into

Once I had all of the different pieces hooked up, the neopixel "sleep" function stopped behaving like I expected it to. I suspect that there were too many things being written to the neopixel because it would flash quickly on and off instead of having a steady light. I simplified the "sleep" function, just turning it green instead ofthe powering up animation I initially had. This made things a little better cosmetically, because the flashing green lights were at least consistent and looked similar to a power up. I went through my code so many times but couldn't find the issue. Eventually, I decided to go to bed and try again in the morning. I woke up a solid two hours before class, so I spent the time trying to look through my code again. I managed to get it a little bit better and then decided it was good enough. 

Ultimately, if I hadn't procrastinated so much I would have been able to get help from Jack or another lab member to try and find the problem. Unfortunately, part of this procrastination was also migraine struggles. I am happy to say, however, that throughout the days when I was building this robot, I did not have a single migraine even with getting frustrated and working with complicated parts!! So, even though the robot didn't turn out exactly how I wanted, it was still a great experience and I'm very proud of it. 

![IMG_6340](https://user-images.githubusercontent.com/54527264/137484528-780ba659-c5fe-4b0f-ad70-fd5fa2d7b099.jpg)

![IMG_6338](https://user-images.githubusercontent.com/54527264/137484531-92d4f208-3316-444b-9a80-36663417e03b.jpg)

![IMG_6339](https://user-images.githubusercontent.com/54527264/137484533-7d986e72-58c4-4e59-b3c7-e0af92ef466c.jpg)
