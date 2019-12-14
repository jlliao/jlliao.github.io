---
title: "Behind The Scenes: Designing Yale-NUS Bazaar"
excerpt: "How to design an application from idea to UI?"
header:
  overlay_image: /assets/images/ui-design.jpg
  overlay_filter: 0.5
categories:
  - Works
  - User Experience
tags:
  - design
---

I have designed and implemented YNC Bazaar, a mobile application, to improve the interaction between Yale-NUS members and “For Sale or Free at YNC” Facebook marketplace website. The application aims to address the problem that many of users, who have requested items on [For Sale or Free](https://www.facebook.com/groups/823773567681380/), are not able to receive a timely attention of sellers, and sellers are not able to sell their second-hand products efficiently to the desired buyers.

The journey began even before my pen touched the paper…

# Let Me Hear My Customers

In my college, we use “For Sale or Free at YNC” is a Facebook marketplace page to sell and trade items. The target audience of “For Sale or Free at YNC” is Yale-NUS students, especially people who trade and sell items frequently. Since Yale-NUS College is a very diversified college, there are many international students on campus who might have different shopping experiences and habits. I decided to visit the college library to find potential candidates through observing their usage on the Yale-NUS’s marketplace – “For Sale or Free” Facebook page.

Participant 1 is a female international freshman from China. She has only been a member of “For Sale or Free” page for almost a year. She requests daily supplies and stationary intermittently. Checking upon sales and request items occasionally have been the main reasons for her to visit the marketplace page.

Participant 2 is a male sophomore at Yale-NUS College, majoring in Life Science. Even though he visits the page frequently, he is still not satisfied with the application due to the experience of failed transactions and ineffectiveness of on-demand requesting.

Participant 3 is a junior undergraduate student who is avid about marketing and business. She is a frequent seller on the Facebook page. She has been using the app since two years ago. Although she has done many transactions on the “For Sale or Free”, she expressed that she does encounter situations that sales and request do not effectively match, which results in unsuccessful, undone transactions.

## Procedure

Before starting the actual usability test, I first gave the participants an introduction of my project and the purpose of my observations. Once the candidates agreed to serve as my user testing subjects, an iPhone is given to them to navigate the “For Sale or Free” page. I proceeded by asking each participant to accomplish three tasks. I asked them to use the “think-aloud” method while interacting with the Facebook “For Sale or Free at YNC” page. If they were confused or did not know what to do for a particular task, I asked them to tell me  their expectations and predictions.

Finally, I concluded each session by thanking the participant for his/her time and efforts.

## Observation Measures

The primary goal of the observation was to receive feedback on the Facebook Marketplace’s interface. During observation, I placed a big emphasis on user-friendliness and program intuitiveness. Whenever the user became confused or hesitant to do a task, I asked them questions such as “What do you think you should do next?”, “What do you think will happen if you press X?”, etc. By asking such questions, I hoped to learn more about the “natural” way that users follow to accomplish a goal. I carefully documented breakdowns each user had while interacting with “For Sale or Free at YNC”. Furthermore, I asked general questions regarding their transactions and suggestions that they could think of to improve the design.

<figure>
	<a href="/assets/images/ui-process.png"><img src="/assets/images/ui-process.png"></a>
	<figcaption>Breaking down each process of the observation. Looking for pain points and suggesting potential solutions</figcaption>
</figure>

# Build Low-fidelity Prototype

The Paper Prototype I used for my Low Fidelity Prototype is actually designed on the computer (using Balsamiq), as it allows for more flexibility when it costs less time to update and make changes. The mockup allows interaction, letting me conduct more user-testings.

<figure>
	<a href="/assets/images/mock-up-ync.png"><img src="/assets/images/mock-up-ync.png"></a>
	<figcaption>The Overall Mockups for YNC Bazaar</figcaption>
</figure>

One of my major priorities for Yale-NUS Bazaar is to maintain a clear connection to Facebook’s familiar existing features in which Yale-NUS students are accustomed to. My goal is to design a feature that is both valuable to our students and are easy to adopt and intuitive for anyone.

<figure>
	<a href="/assets/images/iterations-ync.png"><img src="/assets/images/iterations-ync.png"></a>
	<figcaption>Multiple iterations were created for user testings to get feedbacks</figcaption>
</figure>

# Setting Milestones

Many functions were developed concurrently so that each element/section would fit well within the overall context. Most of times, fine-tuning and adjustments take much longer than expected.

I have created a table of milestones, including what I have done until the current version and what I plan to do for the full implementation. I need to reflect a bit and plan ahead before the changes become too complicated.

<figure>
	<a href="/assets/images/milestones-ync.png"><img src="/assets/images/milestones-ync.png"></a>
	<figcaption>Milestones allowed me to reflect and plan</figcaption>
</figure>

# Moving to High-fidelity 

There are a number of big and small changes from the previous low-fidelity prototype to the current high-fidelity prototypes, including the segmented functional parts in the home page, categorization of the items, trading history, requesting/sale page, and messenger interface designed specifically for the marketplace application. Another important change is that I removed the time control for lending/borrowing.

For the high-fidelity prototype, I segmented the homepage, simplified the category page, and made interactions more intuitive. If previously I focused more on adding features, this step is more about subtraction: take a lean methodology, cut all the wastes and only leave the essential parts.

<figure>
	<a href="/assets/images/low-high-fidelity.png"><img src="/assets/images/low-high-fidelity.png"></a>
	<figcaption>Comparison between low and high fidelity of the category page in YNC Bazaar</figcaption>
</figure>

The new iteration also integrates search function into the “posting” section workflow. Before sending sales or request posts, the application will match relevant listed requests or sales post to the one users are creating. This was a separate functionality in the first iteration. You can contact the seller directly if there are already matching sales. This function is currently only a demo function because the matching sales to request and vice versa is a complicated function if hard coded. This way, the user creating a post can contact the relevant seller or requestor prior to their post creation. However, if they believe that the suggested requestors or sellers are not whom they are looking for, users can continue to post their items.

<figure>
	<a href="/assets/images/high-fidelity-matching.png"><img src="/assets/images/high-fidelity-matching.png"></a>
	<figcaption>High-fidelity prototype with the matching function</figcaption>
</figure>

The most important issue is the grouping of different functionalities. For a computer screen, different functionalities can be placed concurrently without much issue; however, for a small smartphone five-inch screen, different functionalities have to be grouped to make sure the interaction is smooth and intuitive.

<figure>
	<a href="/assets/images/site-map-ync.png"><img src="/assets/images/site-map-ync.png"></a>
	<figcaption>Grouping of different functionalities is essential to a mobile app</figcaption>
</figure>

# Future: Evaluate, Prototype, Develop

I have done individual interviews with participants. Although I have also done interviews for my low fidelity prototype, the high fidelity’s interview is more informative because my prototype has the core functions that I had envisioned. In total, I have conducted 15 interviews, 7 male, and 8 female students. Although the sample size might small, but to ensure the diversity of the sample, I have interviewed students across different year groups. When testing my prototypes, each interviewee has given me their honest feedback, with many comments that I had initially not expected.

To summarize, the feedbacks were constructive and many interviewees looked forward to the actual implementation of the application because they have been frustrated by the “For Sale and For Free” function on Facebook. The majority of users could interact with the application without any guidance.

However, the main source of confusion for my application seems to be that users found it difficult to differentiate which posts were sales and which post were requests because both types of posts looked almost exactly the same. Therefore, in future iterations, I will have to consider whether I should color-code the different posts so that users better differentiate each post’s function.

As I work on transforming these design decisions into reality, my iterative process continues. I poke, play and test the live code so I can continue to fine-tune and improve the user experience before putting it back in front of my customers to beta test.

As the designer and developer on this project, this challenge and process has been rich, exciting and inspiring. I’m excited to continue to collaborate with my target consumers, Yale-NUS students, as I build YNC Bazaar and look forward to sharing it with the rest of you!

Check out [my project](https://spaces.proto.io/project/D54F39DD-F87F-BB60-FCED-78A26C60321E/YNC-Bazaar/) here.