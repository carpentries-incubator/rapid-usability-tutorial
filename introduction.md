---
title: "What is Rapid Usability Testing?"
teaching: 0
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is usability?
- What is user experience research (UXR)?
- How can UXR help solve usability problems in scientific software?
- What is rapid usability testing?
- Under what circumstances should you conduct a rapid usability test?
  
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Define user experience research
- Recognize key characteristics of rapid usability testing
- Identify scenarios and tasks appropriate for rapid usability testing


::::::::::::::::::::::::::::::::::::::::::::::::

## What is usability?
User experience research (UXR) is the investigation of how people interact with, make sense of, and respond to technology and services. Often, your goal with UXR will be to improve the usability of your product, making it easier to adopt and use. 

Usability is made up of other attributes that determine how easy to use a technology or service is. [Nielsen Norman Group](https://www.nngroup.com/articles/usability-101-introduction-to-usability/), a respected authority on usability and user research, identifies several characteristics of usability (lightly adapted here):

- *Learnability*: How easy is it for users to accomplish basic tasks the first time they encounter the design?
- *Efficiency*: Once users have learned the design, how quickly can they perform tasks?
- *Memorability*: When users return to the design after a period of not using it, how easily can they reestablish proficiency?
- *Errors*: How many errors do users make, how severe are these errors, and how easily can they recover from the errors?
- *User satisfaction*: How pleasant is it to use the design? How positive or negative are users’ feelings about the tool?
- *Utility*: Does it do what users need? Does it enable users to accomplish their goals?

:::::::::::::::::::::::::::::::::::::: challenge
### Exercise 1: One form of UXR-Rapid Usability Testing 
In the skit you’ll watch, a study facilitator guides a participant through a rapid usability test. For the purposes of this tutorial, you have the view a participant would. This means you can see the participant’s screen when the facilitator would (as they complete a task) and times when the facilitator would not be able to see their screen (as they reply to a survey).

After the skit is over, we’ll discuss the skit as a group: What was interesting to you? What was confusing? What aspects of usability do you think this study could address?
::::::::::::::::::::::::::::::::::::::

::::::::::::::: instructor
Below is the script for the skit, two people are needed. The **participant** should begin sharing their screen with students from the start and can pretend to begin/end that at the appropriate points in the script. Discuss reactions with students—what suprised them, confused them, was interetesting? What aspects of usability do they think could be addressed by this study? Note that the survey question the facilitator sends the participant suggests that the research is focused on user satisfaction.

Facilitator: Thanks for joining me today. I’m Hannah and I’ll be guiding you through the study session. We’re here to try and find ways we can improve the US-RSE website. Just to assure you, this is not a test of your abilities—we’re here to evaluate the website, not you. During this session, I will assign you a task to complete on the US-RSE website and then I’ll have a survey question for you.

**Participant**: Okay

*Facilitator:* I sent you the informed consent information over email. Did you have any questions about that?

**Participant**: I saw that. No questions.

*Facilitator:*  Great. Do I have permission to record this session then? You might want to minimize any open applications.

**Participant**: Sure. Nothing’s open right now.

*Facilitator:* Okay. The recording has started. To set up for the task I’ll assign you, can you start sharing your screen so I can observe what you do on the website? 

**Participant**: Yeah. Let me do that. Done.

*Facilitator:* I’m going to send you a link to the US-RSE website. I’ll chat it to you in one second. Your task is to submit a poster to the US-RSE 2025 conference, so follow the link and begin your poster submission. I’ll stop you before you have to actually upload any files. While you’re working, please narrate your thoughts and actions so that I can hear what you’re thinking. Any questions?

**Participant**: Nope

*Facilitator:* Okay, here’s the link: https://us-rse.org/ And as you’re trying to submit your poster, don’t forget to think aloud.

**Participant**: Okay. So I guess this is the US-RSE website and I’m submitting to the conference…Get Involved seems like maybe where they’d put conference info. [click dropdown] But no…oh and okay, there’s a conference link here. [Click it and fall silent for 5ish seconds while moving around then hovering over “Submission window closed”]

*Facilitator:* What are you thinking right now?

**Participant**: Oh I was just wondering if maybe I can’t submit? It says the window is closed. But I guess it says “except posters” [click on “Submit your work”]

**Participant**: Okay, “Call for submissions…..” Oh and there’s just one link on this page here and that’s to submit your poster so I’ll click. Oh, I don’t have an account.

*Facilitator:* I’ll stop you there. That’s as far as you need to go in the task for now. You can stop sharing your screen now. [BUT DON’T STOP SHARING] Here’s a link to a survey question I have for you about that task. The survey will ask you for a participant ID—yours is P4. Just let me know when you’re done with that. https://docs.google.com/forms/this_is_a_fake_link_4demos

**Participant**: Okay. [Fill out survey] All set.

*Facilitator:* Great. That’s all I have for today. Do you have any questions for me?

**Participant**: Nope.

*Facilitator:* Alright, well thank you for participating. I hope you enjoy the rest of your day.
:::::::::::::::

![](ep1_infographic.png){alt='An infographic on User Experience Research and Rapid Usability testing'}

There are many methods to study user experiences. You could do interviews, observation, participatory design, A/B testing, surveys, contextual inquiry, card sorting, or one of many more options. 

Rapid usability testing is a kind of user research experience that focuses on how a small number of users interact with a specific software, technology, or service—it evaluates the experience. Rapid usability testing is meant to help you make decisions about how to design your tool and user experience. It’s not academic level rigor, it’s meant to be quick and good enough to make informed decisions. 

In a testing session a researcher will ask a participant to perform a series of tasks or respond to a set of prepared prompts related to the tool being tested. Tasks should be well scoped; this makes them quick to accomplish and results easier to interpret. The researcher will observe the participant's behavior, may ask them to 'think aloud' as they perform the task, and will ask follow-up questions when necessary. Only 3-10 participants are needed, fewer if you include any interview questions as a follow up to your tasks. Five is a norm for sample size in usability testing.

You may wish to use rapid usability testing in order to compare user populations or design options. For example, “Do people prefer X or Y design?” You might find sometimes that neither design option is good but, especially if you have follow-up interview questions, you can learn why and can still integrate some improvement into the code quickly.

Because usability tests are used to assess some interface and offer insights, this means that you must have something for users to work with during the test. That could be a tool or service already available for use. Alternatively, you can create an interactive prototype using tools designed for this purpose, such as Balsamiq or Figma. Or, maybe you have a paper prototype people interact with. Whatever you have does not have to be final or perfect, but you need something for users to interact with. 


:::::::::::::::::::::::::::::::::::::: challenge
### Exercise 2: When should rapid usability testing be used?
For each of the scenarios below, consider if the person in each scenario should start rapid usability testing next. Indicate your decision using the Zoom poll and jot down some notes on why you chose your answer.

**Scenarios:**

- Rae is going to develop a gold standard dataset of journal article submissions, tagged with their venues, peer review outcomes, and reasons for acceptance or rejection. Rae will develop a tool that assesses draft articles for their probability of successful publication.
- Chung previously made their software package PHANCY accessible via downloads on their personal website; users could install the downloaded files. Chung recently made PHANCY installable with the pip package management system. He’s gotten a bunch of emails from users having trouble with pip though.
- Sam wrote a script that helps their two labmates automate some common tasks. Sam was thinking the script might be more useful if it also logged in a shared spreadsheet when it was executed and by whom.

:::::::: solution
This is a bit subjective but it comes down to whether or not you have something for people to work with, people to talk to, and something you want to learn about. Rae is probably too early in development given they don’t seem to have any kind of tool for users to work with. Chung seems like they would benefit from usability testing. Sam might have too few people for any kind of quantitative evaluation but talking to the labmates would likely be useful.
::::::::
:::::::::::::::::::::::::::::::::::::: 

::::::::::::::::::::::::::::::::::::: callout
Rapid Usability Testing is one of many approaches in UXR. There are a variety of methods which may be better suited for different scenarios, circumstances, and/or phases in the product lifecycle. For example, user discovery sessions may be a good fit for when a general concept is known but an associated tool or service does not yet exist (more on the discovery phase [here](https://www.nngroup.com/articles/discovery-study-guide/); and [affinity diagramming](https://www.nngroup.com/articles/affinity-diagram/) is an approach that is particularly well-suited for the qualitative analysis of user feedback with smaller sample sizes. [This guide from 18F](https://web.archive.org/web/20250222140849/https://guides.18f.gov/methods/), the former GSA digital services team, helps lay out the many options available to you. 
::::::::::::::::::::::::::::::::::::: 






::::::::::::::::::::::::::::::::::::: keypoints 

- Usability refers to how easy it is to use a technology or service. 
- User experience research is the investigation of how people interact with, make sense of, and respond to technology and services. 
- UXR improves scientific software products by revealing differences between software developers’ and users’ perspectives and assumptions. UXR can also surface insights that can simplify tool use and adoption and help determine user needs amid a rapidly changing technological landscape.
- UXR can measure a product’s learnability, efficiency, memorability, errors, or utility and user’s satisfaction. 
- Rapid usability tests are tools for observing how users interact with a tool or service. Tests should involve narrowly scoped tasks and measurable outcomes. Results from these tests are used to guide development work.
- Rapid usability tests are most effective for teams that already have an interactive prototype, a minimum viable product, or more mature tool or service
::::::::::::::::::::::::::::::::::::::::::::::::
