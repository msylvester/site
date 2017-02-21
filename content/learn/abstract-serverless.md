---
title: AbstractAI +  Brainitch + LaidBackLuke
description: "95% reduction in recuring back-end costs using Serverless Framework"
layout: Default
---

# AbstractAI reduces back-end costs using Serverless Framework


### Background



<a href="http://www.abstract.ai" target="_blank">AbstractAI</a> (Abstract), based in Los Angeles, develops software and services to enable users to get the <b>results</b> they need <b>faster</b>.<br>  Conversational Interfaces (CI)
are among the the types of software that Abstract develops with less emphasis on conversation and more emphasis on CI's inherent light weight and cross platform abilities.

Abstract partnered with <a href="http://brainitch.com/" target="_blank">Brainitch</a>, a Los Angeles-based startup that offers personalized, 1-to-1 marketing to artists on Facebook Messenger and related platforms.

Brainitch’s client in this case was <a href="https://www.facebook.com/OfficialLaidbackluke/" target="_blank">Laidback Luke</a> (LBL), an electronic music artist based in the Netherlands. AbstractAI and Brainitch were collaborating to offer a bot for LBL's birthday bash, which he was throwing in NYC and Amsterdam. LBL wanted to build a bot that would ask recipients trivia questions, and if the user got enough questions right, the user could attend the party.
<br>
<img src="https://scontent-lax3-2.xx.fbcdn.net/v/t1.0-9/15977340_1635678823401086_4005659267908456100_n.jpg?oh=2472c93f9df5c282dc57197bb740ea19&oe=590868FB">
### The Challenge

AbstractAI created <a href="https://www.facebook.com/digitalassetmonitor/" target="_blank">DAM</a> (Digital Asset Monitor) which was among the first 10,000 FB Messenger public bots and was also featured on<a href="https://www.producthunt.com/posts/digital-asset-monitor" target="_blank">  Product Hunt</a>.  DAM's' architecture leveraged Heroku and Heroku's dyno product to add scalability. That same architecture supported other deployments for artists
and events, but these bots had <i>hundreds or thousands of attendees or users</i>.

Laidback Luke has almost <i>2 million fans</i> on Facebook!

Simply changing LBL's profile picture with a QR code linking to the bot caused a huge spike in traffic. Because of the myriad of APIs (a database, NLP, etc.) the bot had to call, it was clear the legacy architecture would not scale.

In response, AbstractAI engineers deployed additional Dynos to maintain an acceptable response time.  All and All, the legacy architecture that supported the LBL bot would cost nearly $100/month to maintain.

<img src="https://scontent-lax3-1.xx.fbcdn.net/v/t1.0-9/15241180_10155018659806564_434315781857504498_n.jpg?oh=52595ac03a4afd91bd3efbee6caa4bf3&oe=5916BC77">
### Why Serverless

In short, Abstract chose the Serverless Framework because it provided access to abstraction via Amazon Lambda and it took the Abstract team one week to develop the skills to do a production level deployment.

Using the Serverless Framework, Abstract <b>reduced the recurring costs associated with Laidback Luke's bank-end services nearly 95%</b>. When there are large spikes in users, the architecture
will provide the needed network resources, but the user will not be charged otherwise.  In short, leveraging Amazon Lambda, Serverless Framework requires payment only when network resources are used.

Unlike some frameworks, developing proficiency with Serverless Framework took only a week.  There are resources available within the Serverless Framework which taught the Abstract team how to create RESTfull API in less than ten minutes.

It solved our problem by providing an infinitely scalable bot, at almost no cost. Instead of having to monitor server metrics constantly, Abstract was able to have peace of mind.
### Results

Feedback from the client was extremely positive. The bot sent and received over 100k messages in the first week and hundreds of people signed up to attend his birthday party in Amsterdam and New York.  

Most importantly, the following table shows the change in monthly cost after implementing the Serverless Framework:

| Cost without Serverless Framework ($/month) | Cost with Serverless Framework ($/month) |
|:-:|---|
| *340* | **17** |

The ability to build a model quickly with the Serverless Framework has had a positive effect on Abstract's product development methodology.  Specifically. abstracting advanced functionality is a huge benefit to the developer community.  For example, as mentioned above, an engineer at Abstract found a tutorial that explained how to build a RESTful API in less than ten minutes using the Serverless Framework.  

Abstract's client are interested in products that leverage both artificial intelligence and machine learning.  
Removing the friction associated with publishing an API, Abstract is able to concentrate on the area where Abstract creates the most value: <i> abstracting </i> resources and functionality so front-end developers can focus on the design and implementation of the UI/UX.

At AbstractAI, the Serverless Framework is the backbone of our proprietary methodology for developing rest API's and chatbots.  In the words of our client

<blockquote>Laidback Luke’s Messenger (bot) experience was a success and Luke’s birthday bash guest lists are filled up with super fans who deserve a free show! <br/><b>Todd T.</b> - <i>CEO of Brainitch, Inc.</i></blockquote>
