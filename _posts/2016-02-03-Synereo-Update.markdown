---
layout: post
status: publish
published: true
title: Synereo Weekly Update
date: '2016-02-17 08:00:00 +0200'
---

![image](https://avatars.slack-edge.com/2016-01-13/18348683472_4472479791c39eaf2392_512.png)<br>

## Contents in Brief <BR>


### [Watch the full Hangout](https://www.youtube.com/watch?v=tTMDtmkxID4)

 <BR>
[01:40 - Eric explains flow](https://www.youtube.com/watch?v=tTMDtmkxID4&t=1m40s)<br>
[07:10 - Bootstrapping nodes](https://www.youtube.com/watch?v=tTMDtmkxID4&t=7m05s)<br>
[10:15 - Diaspora model](https://www.youtube.com/watch?v=tTMDtmkxID4&t=10m15s)<br>
[11:00 - Built your segment of the network](https://www.youtube.com/watch?v=tTMDtmkxID4&t=11m10s)<br>
[15:00 - Login, different persona’s](https://www.youtube.com/watch?v=tTMDtmkxID4&t=15m00s)<br>
[20:38 - MLM approach???](https://www.youtube.com/watch?v=tTMDtmkxID4&t=20m38s)<br>
[23:58 - Synereo UX sprint](https://www.youtube.com/watch?v=tTMDtmkxID4&t=23m58s)<br>
[25:03 - Mission](https://www.youtube.com/watch?v=tTMDtmkxID4&t=25m03s)<br>
[28:43 - Modes of web use](https://www.youtube.com/watch?v=tTMDtmkxID4&t=28m43s)<br>
[36:00 - Ultimate experiences](https://www.youtube.com/watch?v=tTMDtmkxID4&t=36m00s)<br>
[37:56 - Building blocks](https://www.youtube.com/watch?v=tTMDtmkxID4&t=37m56s)<br>
[42:20 - Design candy](https://www.youtube.com/watch?v=tTMDtmkxID4&t=42m20s)
<br>
[45:20 - Feedback on icon](https://www.youtube.com/watch?v=tTMDtmkxID4&t=45m20s)<br>


## Detailed Notes <BR>

### [01:40 - Eric explains flow](https://www.youtube.com/watch?v=tTMDtmkxID4&t=1m40s)

![overview](http://i.imgur.com/15H5nXd.jpg)

Dina, Eric, Noy and Greg had long email conversations about design (why this channel?). Eric gives an overview of how they understand the system. For example what does it look like to login. The setup of a node itself, which is also an essential part of Synereo, is not covered yet.

1. Normal web page. Introduction of Synereo + invite to login page
2. Is a marketing video that directs you also to the login page 
3. Is a logon page for people that don't have their own node setup. A kind of central place to start. Dina will later show some designs of the login page.
4. When you're logged in then you will see the feed that you've selected.
5. If you don't have a login, you get an invite to create an account.
Just going through this it opens up a bunch of questions of the central-decentral problem. If we all have individual islands with content and people. We want our node. We want to be able to connect. Is there a centralised login and what's the difference when you login to your own node.

### [07:10 - Bootstrapping nodes](https://www.youtube.com/watch?v=tTMDtmkxID4&t=7m05s)

Greg's feeling in 2014 with the Splicious crowd sale was that they wanted to bootstrap as many nodes as possible. And then make it easy to connect and disconnect nodes through node-management. This was important for creating a mindshift with the people from centralised to decentralised. The real value is in the fact that Synereo is decentralised. This is very different from the FB experience. In the early stages we can never measure up against to the features of FB, but we can make a difference by creating a new world, decentralised and distributed and there's not one trusted party. So the network creation experience is the most important. It should be very simple. The most questions of new people were at that time not "How do I login", but "How do I setup a node".
Ed proposes to put on the login page two options. The first is just login to the node and the second is create your own node.


### [10:15 - Diaspora model](https://www.youtube.com/watch?v=tTMDtmkxID4&t=10m15s)

Greg says it is like the [Diaspora](https://diasporafoundation.org/about#host) model. There you can login to a Diaspora pod or you can stand up one on [yourself](https://diasporafoundation.org/about#host).
<br>
![login](http://i.imgur.com/veAYGxZ.jpg)
<br>
![pods](http://i.imgur.com/C3ihPbh.jpg)



### [11:00 - Built your segment of the network](https://www.youtube.com/watch?v=tTMDtmkxID4&t=11m10s)

Eric thinks that Synereo can provide the building blocks to for example Joe to set up a node with an own interface and own login page and his own people live on that island. And he can do a distributive marketing push to get more people on his node to create his own segment of the network through his own channels. So he wouldn't use the default login page at all. It would be another flavor that is built with the tools that Synereo provides to him like: post content or do the social network feed interaction.<br>
So there's two fundamental user sets that happen to overlap: users that want to stand up a node and users that want to connect with other people. I want to connect with my node to your node so that we can share information. But how do you connect to other people that are on other nodes than you are.
Greg says that if two nodes are connected then it doesn't matter one which you node you login. Eric wants to be sure that he understands the transportability of user profile and content. Is there for example a single identifier over the whole network or does an identity sit only on a single node and could collide with other identities when he goes off the node into the network.
Dina thinks of the Wordpress model.You can login with your own credentials but you can set out a kind of avatar. So in that way your actual login name doesn't matter as much.


### [15:00 - Login and different persona’s](https://www.youtube.com/watch?v=tTMDtmkxID4&t=15m00s)

Greg says that indeed the username and login is a separate issue. There is an agent identity that can be portable amongst nodes. It's not the same as an identity, but it's a channel by which you can reliably communicate. The agent who has the credentials to access that channel, can reliably get to profile information and the AMP wallet. Agents that create a connection between their channels, can reliably get to information that's been shared over that connection. But a user can create multiple channels with each an AMP balances. In short you can not treat an agent as a single universal identity and once you have created a login on one node, you can later logon to any node you want. If you're not recognized on the first node then that node will ask other nodes until your credentials are found. So the login page is exactly the same on each node.
Dina makes it clear like this: If there were some sandbox nodes, set up by Synereo. And new users login and then no matter where they are later logging into another node on the network, they'll at least be able to access what they set up on that node.
Greg says that if a login anywhere can happen, then it goes against decentralisation. In fact we want people to login on the initial node and when the network is robust enough and we know better how the whole system behaves then we can allow people to login on any node they want.

Ed says that one way to incentivise node creation is that when you set up a node, then Synereo will reward you with AMPs. If you log on to that node it cost you nothing, but if you use a shared one, then it will cost you AMPs. If that happens to be your node, then you will also be rewarded by the users that use your node to login to.


### [20:38 - MLM approach???](https://www.youtube.com/watch?v=tTMDtmkxID4&t=20m38s)

Dina understands it! If a user signs up at your node, you get a portion of their AMPs. And if they sign other users up, then you get also a portion of their AMPs. So the Multi Level Marketing approach is clear. LOL

After all it's important to know what product you are creating. Is it the platform on which third-parties can develop an application and create a node or is it simply connecting to users and consume and create content.
Christian argues that usually it's only 1% of the community is active and 99% are just like: Yeah this is cool, stopping in, checking in, consuming. 


 
![sprint](http://i.imgur.com/1OZSfkE.jpg)


### [23:58 - What is our "Minimum lovable product"?](https://www.youtube.com/watch?v=tTMDtmkxID4&t=23m58s)

What will users actually love to use?
And this hangs of course in a long term strategy.

![LT](http://i.imgur.com/i5yb9tH.jpg) 

With the considerations of decentralised and distributed applications, own your own data, etc. And this has to be set out in a time frame.



### [25:03 - Mission](https://www.youtube.com/watch?v=tTMDtmkxID4&t=25m03s)<br>
![mission](http://i.imgur.com/ntiJxzr.jpg)

This mission is a big mouth full but Greg likes the sentiment. It's not only for the front page of the web site or for attracting investors. For the designers it's really important for having a criterium to allow for this feature and not for that feature. It helps to give focus on the design. The mission can of course be expressed in other words. Greg refers to Joseph Gorden-Levitt, [Hitrecord](https://www.hitrecord.org). (red. mission: We're a new kind of online community
working together as a production company), with a small change. JGL has the final responsibility of what content is released and monetised. And he hopes that Synereo becomes this amazing place where people come together to create amazing things, but that it is the crowd that has the collective insight of what's good content. That is the same intention that Dor has with the Attention Economy Model. Current social networks are mostly passive: surfing, browsing and less about active focused creative attention.
 


### [28:43 - Modes of web use](https://www.youtube.com/watch?v=tTMDtmkxID4&t=28m43s)

Below are the modes of web use. And have a look at [Jerry's Brain](http://jerrysbrain.com)

![web use](http://i.imgur.com/Kd1vdOB.jpg)
<br>
[reactive media](http://i.imgur.com/tkQcdHq.jpg)


### [36:00 - Ultimate experiences](https://www.youtube.com/watch?v=tTMDtmkxID4&t=36m00s)

![ultimate experience](http://i.imgur.com/GhgnWhV.jpg)


### [37:56 - Building blocks](https://www.youtube.com/watch?v=tTMDtmkxID4&t=37m56s)<br>
![bb1](http://i.imgur.com/twZGnb0.jpg)<br>

How are we going to design this thing?
So we start with the login. Then how are we going to present the different content types. How much do we care about people, creating really really immersive content.
The content life: So what action can be done to content? How does it work with AMPs and REO? Does the content that is displayed really make sense? How do I see the history of what I put up?

![bb2](http://i.imgur.com/G0g4qlr.jpg)<br>
![bb3](http://i.imgur.com/KBhIhvG.jpg)<br>
![bb4](http://i.imgur.com/fqTaQ5a.jpg)<br>


### [42:20 - Design candy](https://www.youtube.com/watch?v=tTMDtmkxID4&t=42m20s)

The original sketch for showing how we work. We want to know how the icon feels.<br>
![sketch](http://i.imgur.com/RBNFIIV.jpg)<br>
This resulted in in the really cool smoky background with kind of the nodes coming out. And the idea was that you were to be coming here and you were going to step into this node and that will kind of unfold the rest of the network for you.

![icon](http://i.imgur.com/fuJL9wx.jpg)<br>

For the icon we are working on the "Google-Icognito-mode" and "Carmen San Diego" and "Red Hat".

![redhat](http://i.imgur.com/VMDv2bo.jpg)<br>
![creepy](http://i.imgur.com/8lER4It.jpg)<br>
So we're creating something that reflects: privacy, hackery. Maybe a bit too sinister. We want to get your reaction. A second version is with a looping video in the background with kind of robot guys.


### [45:20 - Feedback on icon](https://www.youtube.com/watch?v=tTMDtmkxID4&t=45m20s)

It gives a kind of censorship and Greg doesn't want to go in that direction. He's also not so much on the robots. He would prefer to go a little bit more organic. Because that world is full of decentralised metaphors. Dina just took the available video, but Greg didn't like so much the metaphors being used. The mechanistic world is kind of the opposite he wants to point to. <br>
Also what's missing is "launch a node" it's only "login".<br>This has to be figured out.<br>

Eric says that the initial focus is on the bitcoin, hacker minded people to get this network up and running, that want to keep their privacy. A character doesn't replace the logo of Synereo. You have these kind of general characters.<br>
![general characters](http://i.imgur.com/4pTP4s7.jpg)<br>
The ideas for this character came out of initial target market and the social self determination, trust and social components. 


### Some examples from the community:

![organic](http://i.imgur.com/eM3lNYk.jpg)<br>
![flowey](http://pre03.deviantart.net/c47d/th/pre/f/2015/322/5/4/flowy_ref_by_nightwisper40-d9h3i19.png)<br>
![image](http://www.cliparthut.com/clip-arts/1469/mushroom-clipart-face-cartoon-clip-art-540pxpng-1469393.png)<br>

Christian likes the ideas of mushrooms with a reference to organic gardening. You start with mushrooms because they built the network out there.<br> It maybe also a good idea that this character is evolving with the network. The evolving character is a brilliant idea. <br>
You could consider a turtle. come out of your shell when you feel safe. Also, the turtle could be shown in different states depending on login state, chatting state, etc.


Dina stresses that we have to get really fast to a kind of demo product. And we can not stick to just the login screen. If there's too much churn on a specific kind of side thing like a character,  then we never get some UI made and we want Synereo to get running. Too much churn is not workable. How much iterations do we allow for? Or do we just use the Synereo logo and leave the icon for the moment. And keep moving.


Greg says that timeboxing is ok, but we also want to create a culture of ownership and empowerment. We are in this together. And what we have to learn is governance. How much crowd attention can we allow on which problems. That's kind of learning as we go.

### So Dina asks:

1. Is the spy kind of icon not wanted for Synereo?
2. Is it ok to bring up an icon, early on in this process, that is a bit more human, organic?
3. And how much importance do we attached to such an icon?

The general feeling is that we could stick to the current Synereo logo and do polishing later. Getting Synereo up and running is more important.


### Let's work out the twelve points mentioned and use tools like:
* [Taiga](https://tree.taiga.io/project/synereo-synpm/)
* [Ventrilo](http://www.ventrilo.com)
* [Slack](https://synereonet.slack.com/messages/design/team/dina/)
* [Github](https://github.com/synereo)
* [Maybe Jitsi](https://jitsi.org)


### Links from the chatbox
* [collaboration platform](http://www.sitegrinderblue.com/)  This is a photoshop plugin that allows for awesome web design. I can see how this could be used for designers to build customized interfaces which users could choose from.
* How about a page that shows available nodes and their uptime, like  [pump.io](https://pumpiostatus.website/dashboard/events)<br>
* [Hitrecord](https://www.hitrecord.org/)<br>
* [Wordpress](https://randompandaman.files.wordpress.com/2012/03/alex-grey.jpg?w=300&h=420)

<br>
That's all for this week!

If you like what we’re creating, send some bitcoin to 18c1en55Cs2jBgBT2LTAiK9M81vMUmXmxw

![18c1en55Cs2jBgBT2LTAiK9M81vMUmXmxw](http://i.imgur.com/jlHprSv.jpg)


