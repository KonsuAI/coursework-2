# Business Execution Journal

### Overview

Since submitting our original business plan, we’ve taken significant steps to start turning our concept into a tangible product. We have developed and launched a functional prototype, which is now hosted on a domain that we were able to secure using pooled funds, and created a video to showcase the product. Using our prototype, we have created a questionnaire and started carrying out user studies in order to gather valuable feedback from our first customers, helping us to refine our work. We’ve also begun engaging with potential investors and government grants and have been finalising our company structure and share distribution in preparation for registering Konsu as a limited company. Together, these steps have laid the groundwork for the next stage of Konsu’s development and eventual launch.

### Prototype and Customer Engagement

Our prototype is a progressive web app (PWA) built using SvelteKit, accessible via web browsers and installable on both Android and iOS devices. For this initial version, we focused on building the core user interface with limited functionality, allowing us to begin collecting feedback on the user experience while simultaneously progressing on the development of more complex features behind the scenes. The design was intentionally simple and intuitive, with broad accessibility in mind to ensure it could resonate with a wide and diverse audience.

The main page of our prototype is the ‘Create a Trip’ page, where users can chat with a real LLM agent capable of searching the web, offering destination suggestions, and displaying relevant images. Though we still need to refine interactions with the LLM, it still serves as an early demonstration of how users will interact with the app. Looking ahead, our next major feature will be flight search and booking, for which we plan to integrate Duffel, a digital platform for online travel agencies.

The prototype also includes several additional pages that outline key components of the intended user journey:

- Upcoming Trips: a section where users can view their booked trips, each with a basic daily itinerary navigated by swiping horizontally.
- Drafts: a space for saving in-progress trip plans, allowing users to return and complete them later.
- Past Trips: an archive of previously planned trips.
- Explore: a page where users can browse pre-planned trip templates to customise or use as inspiration, rather than starting from scratch.

While these pages are currently non-functional, they are included to provide a complete structure of the app and to gather feedback on layout and user experience, particularly for elements such as the horizontal layout of the itinerary view, which will help guide improvements.

To bring our prototype to life, we collectively pooled our £10 challenge funds to purchase and host it on our own dedicated domain, [konsu.ai](http://www.konsu.ai/). This step marked our first move towards establishing Konsu as a real, public-facing product. Our frontend is hosted for free on GitHub pages, and our backend runs on Digital Ocean. The backend is built using a Python REST API that integrates the Google Agent Development Kit, Gemini 2.5, and the Google Maps API. To date, we’ve remained within the free usage tiers for all services, meaning we’ve incurred no further costs beyond the purchase of the domain name.

Throughout development, our team adopted agile practices, using GitHub to coordinate and share our work. Sam, our Scrum Master and CTO, played a central role in managing this workflow and ensuring technical consistency.

With the prototype accessible online, we have now begun our first phase of stakeholder engagement, which is still ongoing. The process has included distributing a questionnaire and conducting user studies to gather actionable feedback for future iterations. We also onboarded our first two customers, Bhagy Patil and Neil Langmead, who were the first to receive this questionnaire and who have helped to validate that there is real interest in our concept. Their feedback, along with insights gathered from broader user testing, will inform the next iteration of Konsu, helping us refine the product’s design and functionality to better meet real-world user expectations.

By launching this prototype and actively engaging with early users, we’ve created a feedback loop that will shape Konsu’s future development and guide us toward a more robust MVP.

### Product Video

To showcase Konsu to new potential customers and investors going forwards, we created a simple but effective product video. The video aims to highlight key groups of potential customers, and show how Konsu would positively impact their holiday planning experience. It outlines the stress and indecision many people face when trying to plan a trip, then demonstrates how Konsu responds to these challenges, walking the viewer through realistic use cases of the prototype. Rather than focusing on technical details, the video aims to communicate the core experience and benefits to users, showing Konsu as an intuitive and accessible tool that can simplify and enrich travel planning for a wide audience.

Our hope is that the video helps viewers quickly understand the real-world value of Konsu, both in terms of convenience and personalisation, and sparks interest from early users and supporters. By showcasing the product and framing it around genuine customer needs, we aim to build excitement around Konsu’s potential.

### Investor Outreach

Our funding approach balances fiscal discipline with strategic growth. At this early stage, we’re prioritising product development and validation over large-scale investment. By keeping overheads low and maintaining a lean structure, we’re building a sustainable foundation to test, iterate, and refine Konsu’s core offering before scaling.

To accelerate development, we’re combining internal resources with targeted angel investment. These funds will cover critical costs, such as infrastructure, prototyping, and user acquisition. This will enable the team to build Konsu full-time while remaining capital-efficient.

In parallel, we’re pursuing non-dilutive funding via UK government programs such as the Flexible AI Upskilling Fund, Innovate UK, and youth enterprise grants. These sources support team development and AI infrastructure without diluting equity or control. We’ve also applied to Y-Combinator, hoping to gain access to a global network of mentors, technical founders, and early-stage investors. 

Once our MVP launches and we demonstrate traction, we’ll pursue our first formal funding round. At that point, we’ll seek strategic investors, particularly those with expertise in AI, travel tech, or consumer platforms who align with our long-term vision and can guide Konsu from product-market fit to global scale.

### Company Formation

Recognising the long-term potential of Konsu, we have begun exploring the process of registering a Limited Company in the UK. We will name the company ‘Konsu Travel’ Ltd, since when searching ‘Konsu’ in the [gov.uk](http://gov.uk) company name availability checker, it was found to be too similar to an existing company ‘Konsus’. We are still in the final stages of internal discussions on board structure and share allocation, however these are the currently agreed details: we will all be listed as directors with equal amounts of shares and voting rights, and we intend to adopt the model articles for private companies limited by shared for our article of association, as provided by the UK government. Additionally, we believe the most fitting SIC code for our company will be 79110, for travel agency activities.

Though there is more research to be done before reaching that stage, we are excited for the future of Konsu, and proud of what we’ve been able to achieve so far.