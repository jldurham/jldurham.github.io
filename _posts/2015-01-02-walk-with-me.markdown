---
layout: post
title:  walk with me
subtitle: designer
date:   2015-01-03 18:50:21
image: /images/walkcolor240.jpg
categories: [project] 
---

###A web application to help people, particularly older citizens, find walking buddies in their local community and become more active in their daily lives.

<div class="image-wrapper">
	<img id="first-image" src="/images/walklogo.jpg" />
</div>

## the problem

Countless health practitioners tell patients that they need to be more active in their daily lives. It’s a common problem experienced by the many people living the sedentary lifestyle that accompanies a world full of laptops, Netflix, and 9-5 office shifts. The simple inclusion of 30 minutes of daily walking could dramatically alter a person’s physical and mental health, so a stroll around the neighborhood is an activity that’s importance should not be underestimated.

Walk with Me is a web application that allows people to coordinate a “walking buddy” system between those who live within close proximity of each other. Walk with Me is most closely modeled on the Weight Watchers system that encourages individual improvement in health through local community interaction and support. While Weight Watchers pre-dates the Internet, it has successfully made a cyber transition, one that incorporates it’s dependency on traditional “meet-up”-style social interaction in a physical space with additional support and community features uniquely possible on the Internet. 

Walk with Me is similar to Weight Watchers, but inherently more intimate as people would meet and match up with others in order to walk and, presumably, talk and share their personal thoughts, opinions, and perspectives while doing so. In terms of the physical meeting feature of both systems, Weight Watchers’ locations are usually in strip malls and therefore a reflection of it’s undeniably commercial heart; on the other hand, Walk with Me meetings would be held at the homes of those members who have online counterpart roles similar to a moderator. **By having a dependable buddy system, people will not only have a personal and social incentive to engage in physical fitness, but they will also help their neighbors overcome the challenge of becoming happier and healthier in their daily lives.**

## the solution

As a runner, my original inclination was to design a system influenced by the running apps I have used in the past, but I realized that my familiarity and “expertise” of sorts was blinding me to a more common need for people. There are countless apps, gadgets and gizmos that support running, an activity which is trendier and often perceived as much cooler than walking-for-fitness. **Running applications, while plentiful, tend to fail miserably at fostering community in the inherently solitary sport of running.** For example, the popular Map My Run has a group feature, but the disparity in numbers between user-created running routes in Ann Arbor (30,539) and running groups formed (15) is significant: It goes without saying that social features are secondary to data analysis and visualization. Most applications that exist for walking are, ultimately, adapted forms or add-ons of these running systems.

**Walk with Me allows users to find local meetings by entering a zip code.** While there is an assumption that those living in the same neighborhood have socio-economic similarities that make them compatible, there is a choice available in which meeting to join (organized by age, interests, etc.). The online features of the site are organized by meeting groups, and contain tools for schedule coordination, health measurements and tracking, journaling, and messaging. The nature of the site eliminates the “Craiglist Killer” fear of online intimacy (particularly in live location-sharing), but Walk with Me can also be used to coordinate a walking buddy partnership between old neighborhood friends who often lament the fact that they need to start being more active.

The site can be divided into two sections: the public area and the member area that can only be accessed through log-in. The public area of the site comprises a small portion of user activity on the site. Once a walking group has been found following a search, an application to join is sent to the group’s moderator via the system’s messaging system. If the moderator approves the application, an invitation is sent via email to the new user, who then creates an account and is able to access the member area of Walk with Me.

{% include image.html img="/images/publicwireframe800.jpg" title="public section wireframe" caption="Wireframe of public area homepage." %}

{% include image.html img="/images/memberwireframe800.jpg" title="member section wireframe" caption="Wireframe of member area homepage." %}

**The primary use of the site is to post an “advertisement” for a walking buddy (specifying date, time, and type of environment such as a park or fitness center), and to search for walking buddies who have posted such advertisements.** Because groups are likely fewer than 20 members, there is an option to search an expanded network of groups in the local area. The link to these three primary functions: post a walk, search your group, and search your network, are at the focal center of the home page (Fig. A). Below, making up the rest of the central content area, is a news feed. A sidebar on the right provides access and teasers for the other primary functions: live tracking of other walkers (slides automatically), messaging (most recent), next walk reminder, buddies (most recent), and routes (most recent).

There is a traditional navigation bar at the top of the screen in the header, where the user can access all of the main content areas of the site, as well as the profile and settings control area. The design of the site is intended to be as simple as possible, to accommodate novice users such as the elderly. Elements such as back and submit buttons are clear, and there is little dynamic content that might confuse users who need a simple and conventional layout to best accomplish their tasks.

## the process

**Rapid sketching** was quite helpful early in the design process to generate a variety of ideas and approaches in the development of Walk with Me. If it were not for this work and attention to detail, many of the features and appearance of the system would not be implemented, most significantly the bulletin board for a search. Additionally, writing **personas and scenarios** provided a better sense of the needs of a wide range of users: I realized that if I centered my design too closely on the needs of an elderly woman, I wouldn’t be satisfying the needs of a young woman or middle-aged man who would also benefit from the system. By making **storyboards**, I could see Walk with Me in action, and the problems and needs of the users became much more prominent and apparent. This early sketching prepared me for the phase of architecture, wireframing, and prototyping that gave shape to all of the ideas and approaches that were weighed.

{% include image.html img="/images/sketching800.jpg" title="sketches" caption="Rapid sketches (portion)." %}

{% include image.html img="/images/helenepersona800.jpg" title="persona" caption="Persona of an elderly user, Helene." %}

{% include image.html img="/images/storyboard800.jpg" title="storyboard" caption="Storyboard based upon a scenario written for  Helene (portion)." %}

I used several **models** to weigh design alternatives and build design rationale for individual features. The system's most important and central feature is tool that allows users to search for walking buddies. It is the most essential and frequently used tool, and I used a **QOC (Questions, Options, Criteria) model** to help me answer the question: How does a walking group member find a walking buddy? I generated three answers that I explored as possible approaches for this particular feature.

{% include image.html img="/images/QOC800.jpg" title="QOC model" caption="QOC model to communicate design rationale for search function." %}

**Approach 1**: Advanced search with sortable results. This approach would be the most classic or standard method one could use to find something they’re searching for online. It could have a wide variety of search fields, advanced filters, and sortable results to find a buddy. It is likely that novice and senior users could manage the most simple search, but it is not likely that they can take advantage of the most advanced searches that would provide the best results for them. As the membership that will be searched is fairly small (only a dozen or so people at the most), this sort of search is much more cumbersome than what is truly needed. Additionally, there isn’t a way that those can share their availability can participate in the search function and feel that they are part of a collaborative community in every feature.

{% include image.html img="/images/aproach1-800.jpg" title="approach 1" caption="Approach 1 (from QOC options): Advanced search with sortable results." %}

**Approach 2**: Calendar view with joinable events. This approach is an interactive calendar system similar to Google Calendars. The most used function of the site is a calendar and scheduling system. Through this approach, searching can be incorporated into the feature that the user will next use, after finding a buddy, to schedule the event. When a user posts in the calendar that they are available and looking for a partner on a certain day and time, the searcher can then click on the event and send an offer that the poster can accept or deny. While this feature makes more sense for a small and more intimate population, but it is perhaps too complex for an elderly or novice user.

{% include image.html img="/images/approach2-800.jpg" title="approach2-800" caption="Approach 2 (from QOC options): Calendar view with joinable events." %}

**Approach 3**: Skeuomorphic bulletin board. This approach is the one I’ve chosen. It was an idea I had sketched in an earlier assignment. It is similar to the calendar view approach, but it eliminates the calendar function that may be too overwhelming for elderly or novice users (the calendar can now remain as a separate, simple scheduling device separate from search). This bulletin board, that will include a graphic element that looks like notes being pinned to a corkboard, is simple and converts a beloved icon of civic engagement and community centers to the web. When a walking event is confirmed between both parties, the posted note will be removed from the board. For one of the most repeatedly used features of the site, it is, importantly, fun and visually interesting as well as efficient and easy to use.

{% include image.html img="/images/approach3-800.jpg" title="approach 3" caption="Approach 3 (from QOC options): Skeuomorphic bulletin board." %}

I chose the third approach, despite my hesitance to go the skeuomorphic route as a designer. Ultimately, I had to look beyond my own tastes and accept that for the older users, a skeuomorphic approach is easy to follow and these users heavily rely upon such direct symbolism. My style as a designer would still be present, and emerge as I modified the skeuomorphism to make the bulletin board as abstract and modern as possible. I didn't want the aesthetics to repel younger users, who would likely find this approach (in an unmodified form) pretty dated.

A **paper prototype** was the first time that my design was presented for evaluation, and user tests were conducted on the low fidelity model. At the conclusion of this testing, I collected a number of important issues based upon the feedback:

* There was too much information on the member home page.
* The language was unclear on the front page buttons (which indicates I should design better for people unfamiliar with the system and what it does) .
* The navigation bar repeats a lot of links found elsewhere on the front page.
* There is a lot of space allotted to features that may be used infrequently, such as walk statistic entry, health measurement entry, the journal area, and fitness resources.

<iframe src="https://player.vimeo.com/video/89879882?color=c73320" width="800" height="450" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

Upon these recommendations, I made several significant changes to the organization and layout of the site that were much easier to change at this phase. I used a high-fidelity prototype to work through the most important and unique function of the system: searching. It would have been extremely inefficient to make such drastic changes to Walk with Me after hours and hours spent using Axure, my software choice. As I got closer to the final design, I made some subtle iterations of the system with the **hi-fi prototype**. I found the iterative approach the most important factor in the improvement of the site. With each passage of feedback and critique, in both the low and high fidelity prototyping stages, I was able to see the design with new and fresh eyes.

{% include image.html img="/images/walkscreenshot800.jpg" title="screenshot of prototype" caption="Screenshot of interaction prototype." %}

## links

<div class="links">
<p>
	<a href="http://fg5w8e.axshare.com/public_home.html">explore the interactive prototype (search demo)</a>
</p>
</div>


