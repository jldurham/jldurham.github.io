---
layout: post
title:  shinola detroit
subtitle: monogramming system design
date:   2015-02-28 18:50:21
image: /images/puppy.jpg
categories: [project] 
---

### A full-stack design project that turned the monogramming service at Shinola's retail stores into a multi-platform digital experience for e-commerce.

## the problem

A young fashion and luxury goods brand, Shinola has experienced rapid growth in their first two years. During this time, they have been simultaneously growing both their retail business (new stores are popping up across the U.S. and abroad every few months) and their e-commerce business. Shinola are eager to **blend the user experience between their retail and e-commerce customers at every opportunity**, and to capture the unique and "destination shopping" feel of the retail shopping experience online.

Customers who buy handcrafted leather goods at their store locations from Detroit to Tribeca to London almost never turn down the opportunity to have their leather monogrammed with the in-store embossing machine at no charge (about 90%). An otherwise unremarkable check-out experience becomes remarkable as customers watch their bags being stamped by machines that haven't changed much, if any, in the past century. For a brand that strives to infuse every product with not only quality but character, it's an extremely valuable and important service.

The task itself seemed easy enough to hand down to Shinola's user experience designer (that's me): **Make monogramming available for customers online**. I was excited by the prospect of designing a feature from bottom-to-top, but shortly into my work, I discovered that this design task would require the building on an entire organizational system. And then I became even more excited. Before being able to design the interactions and visual surface of the interface, I had to bring together stakeholders from across a nascent and decentralized fashion start-up and make sure that the infrastructure was in place to support the new feature.

## the process

With nothing to start from but scratch, my first move was to gather as much information as possible by **interviewing stakeholders** spread widely across the company. The leather product manager and distribution center had been working together on some basic time trials for staff to emboss a leather product, and to determine which leather goods would be made eligible for the monogramming service online. I spent time at Shinola's flagship store in Detroit and shadowed staff as they embossed products for customers.

The **site requirements** emerged out of my research and I got a sense of the hurdles: formalizing refund policy, estimating demand, placing the embossing machine to the most efficient location, and hiring and training staff to support an interactive system that would be a user experience catastrophe without these pieces in place. With the leather department, distribution center, human resources and customer service, I determined the **scope of the system and its requirements**, and created **maps and models** to communicate and ensure that the goals of the business were in line with the needs of customer.

Stakeholders reviewed my work and when I had revised the contextual design to everybody's satisfaction, I proceeded with the feature's architecture and interaction design. I formed the system's backbone and massaged it into a set of **user flow models, wireframes**, and **site maps** using Axure. The architecture was informed by conversations with the developers about the constraints I had to work within, and my designs had to take into account the heavy backlog of the development team just prior to the holiday season. 

With only a few weeks until a Black Friday deadline, as well as the logistical risks and unknown customer demand, the feature was rolled out in two phases. The test phase lasted two weeks, was limited to only two products, allowed the logistical kinks to be more safely rolled out, and gave the developers more time to work on additional, more elaborate, UI features. I created **annotated mock-ups and documentation** for the developers, which gave them a comparative picture of both the immediate and future needs of their implementation.

Following the heavy conceptual work, I worked through the information and interface design and into the feature's layer of **visual design**. At the center of the system is the personalization modal that would appear next to the Add to Cart button on the eligible product pages. I faced unusually high stakes in terms of communicating refund policy to customers, and needed to ensure the "no refunds under any circumstances" was highly visible, clear, but not intimidating and likely to steer customers away from the checkout funnel. I also needed to contend with the short timeline, busy developers, and difficulty of acquiring assets that would show what the many colors of leather look like when monogrammed.  

The most important element in the personalization modal , and perhaps the entire feature, was the preview area that would allow users to see what the non-refundable leather product would look like with monogramming. My presentation options included: 1) having each product photographed in every color with a generic "ABC" sample, 2) a variation in which only samples of each color are photographed with the "ABC"  which a graphic designer would superimpose on each product 3) photograph every letter on each color swatch and programmatically display the images as blocks based on user input, 4) do the same, but superimpose the letters onto a product image 5) superimpose the individual letter samples onto a square swatch area, 6) do the same, but with text that matches the embossing machine's typeface, or 7) let them users use their imagination and skip the preview altogether. 

My solution took advantage of the limited release test phase, which meant that option two ("ABC" superimposed on a color swatch) could be a feasible option as the graphic designer would only need to work with a small pool of product images (one swatch of each color). This option provided a clean presentation and satisfy the needs of users who want to see essential character of the embossed leather. For the second phase, I chose option six (text superimposed programmatically onto color swatch squares), which still adhered to our constraints, but allowed the user to have more control and information by inputting the letters displayed. To show customers the location of the monogram on each item, I brainstormed another set of options to illustrate placement, as the swatch preview limited customers' ability to get the full sense of their personalized item.

I walked the art director and a lead visual designer through the **interactive prototype**, which I made in Axure, and produced many iterations based upon their feedback and some collaboration. The second release included a landing page for monogrammable items, a front page banner and email campaign designed within the art department based upon my specifications and wireframes. **High-fidelity comps**, which I created in Illustrator, were distributed to stakeholders for review and approval before developers fully dug into implementation. I guided the developers through the tasks at hand and oversaw **testing and review**.

## the result

On the first day of release, the monogramming system **increased sales of both available products 250%**. The test proved successful and the full release saw significant increases in sales for all products. Users were overwhelmingly positive in their feedback and customer service received very few issues. 

Beyond the system's ability to meet business goals and provide customers with a great shopping experience, It was an undoubtedly positive project for Shinola as a young company experiencing the typical growing pains of a start-up was able to pull together productively. 

Most importantly, this system bolstered both the company's values and goals, and those of its customers', by allowing them to transform their leather goods from products into timeless, hand-crafted keepsakes.

## links

[visit shinola and demo the system](http://www.shinola.com/shop/leather/monogram-collection/ipad-mini-envelope.html#color=Natural)

[see the test phase mobile prototype](http://az2trs.axshare.com/monogram_selection_p1_mobile.html)