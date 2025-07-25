---
title: "Recruiting and tracking participants"
teaching: 0
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- Who should I be recruiting?
- How many people should I recruit?
- How do I find users that I don't have a connection with already?
- What is snowball sampling?
- What ethical considerations should I have when doing user experience research and how does that work with my scientific research?
- How can I keep track of (potential) participants and their data?
  
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Define a value proposition for the tool to be studied
- Define a target study population for user experience research
- Craft a recruitment email
- Identify ethical considerations that must be accounted for when conducting human subjects research
- Leverage snowball sampling and broader advertising to increase recruitment
- Recruit participants who have never used your tool
- Track participation in a protected spreadsheet
- Establish a participant list for future testing
  
::::::::::::::::::::::::::::::::::::::::::::::::

## Who to recruit
When deciding who to recruit for your study, consider who your tool is meant to support, in what settings, and how. Sometimes this is called a [value proposition](https://online.hbs.edu/blog/post/creating-a-value-proposition)—it’s a statement of benefits. By considering what benefits you offer and to whom, you can identify the general type of person you should be recruiting for your study because this is also your target user audience. 

Your research question can also be helpful when determining who to recruit as it may include some prerequisite requirements. 

### Example: Defining a target population 
Based on your research question and value proposition, you can identify the general type of person and specific requirements for your target population.

| Research Question | Value Prop | Target Study Population | 
| --- | --- | --- | 
|When Slack users return to the design *after a period of not using it,* how quickly can they add a channel?|Via synced phone, browser, and desktop applications, Slack revolutionizes team communication by enabling seamless collaboration and enhanced productivity in a dynamic *work environment.*|**Requirements:**  <br> - Slack users who have not opened the app in XX days  <br> **General type of person:**  <br> - Use Slack for work with a team | 

## How many to recruit
Once you know what type of person you want to talk to, you’ll next need to decide how many users you’d like to have in your study. There are no wrong answers here; what is important is that you feel comfortable with the data you’ve gathered and can use that data to make informed design decisions. If you are seeking statistical significance, you will need to recruit many more participants than you would otherwise. However, because rapid usability testing is easily applied in an iterative development process and because [you don’t need very many participants to gain insights](https://www.nngroup.com/articles/how-many-test-users/), we recommend testing with up to 10 people.

While usability studies outside of scientific software usually offer an incentive for participation, such as a gift card, this is often not needed for scientific software. Scientists and researchers often genuinely want to see improvements in the tools they rely on for their work and to help their fellow researchers; a sense of community and shared interest is generally a sufficient motivator. Additionally, they often appreciate helping to shape the software's future direction. Thus, while an incentive like a gift card is nice, it is not necessary. 

When recruiting, most strangers you reach out to will say no. If you are recruiting from people you are regularly in contact with, you can expect higher and more positive response rates. 

## How to recruit
Unless your study is time bound in some way, recruitment can happen in phases. 

We recommend direct, individualized emails to recruit participants for your study if possible. This approach means that you have a record of when and who you reached out to and personalized requests can be more effective than broad canvassing with flyers or posts to forums. If you have or can find contact information for your users or eligible participants, leverage it to send these emails.

A common risk participants in user studies face is a breach of confidentiality, meaning their opinions or data get shared with unexpected people in a way that compromises their anonymity. With rapid usability testing, most of the study will involve participants engaging with your tool in routine ways, so no unusual risk should be added. However, you might be asking some interview questions or participants might volunteer information they wish to keep private. Be sure to state how you will handle participants’ data: Will you anonymize it? Who will have access to the data? Will you keep any identifiable information? Will you ever publish the data? Providing this information is important for ensuring participants can make informed decisions about participation. 

::::::::::::::::::::::::::::::::::::: challenge
### Exercise 4: Evaluating an Example Recruitment Email 

Recruitment emails should:

- Address an individual
- Introduce the sender and research team
- Summarize the goal of your study
- Explain what you want from the participant and why them
- State the time commitment (based on a pilot study or a best guess)
- Explain any eligibility requirements; Ask or link to necessary screener questions
- State any risks participants might be subject to and how you will mitigate them
- Explain how you will handle their data
- Make clear that participation is voluntary
- State any incentive you have to offer
- Clearly ask for their participation

Review the example recruitment email below and check off the recommended content you see using the Zoom poll. 

Hi _______,

I am a researcher working with PHANCY and am conducting user studies to improve our installation process. I understand you are a PHANCY user and hoped we could learn from your experience. Might you have thirty minutes some time in the next couple of weeks to participate in one of these user studies? 
 
During the study session, I would observe you doing some typical tasks using PHANCY, focusing on how you install updates to the package. I'd record and transcribe the session but only I would have access to those raw files—the broader PHANCY team would only be shown anonymized content so that you can be completely open during the interview. Once I’ve finished anonymization I will delete the raw files completely and retain only anonymous data in our private cloud storage. We’ll only use your data to guide our internal decision making; this isn’t for publication. Participation is completely voluntary.

If you're able to participate, please share a day and time that would work well for you.

Thanks for your consideration!

best wishes,

::::::::: solution
The email could be improved in a number of ways (e.g., be less formal in tone) but only eligibility requirements and incentive info are missing. What you include will depend on who you are emailing and your study design.
:::::::::
::::::::::::::::::::::::::::::::::::: 

::::::::::::::::::::::::::::::::::::: callout
Sometimes recruitment emails can get lengthy and that can be overwhelming, reducing your response rates. You might want to move some details below your email signature or into an [informed consent document](https://www.nngroup.com/articles/informed-consent/) to keep the request simple and clear. Depending on your institution and your goal for your research (i.e. to create generalizable knowledge or to inform only your own decision making), you may have an Institutional Review Board (IRB) that will have additional information and regulations you should heed when planning, executing, and recruiting for your study. If you have intentions to share, present, or publish data, reach out to your IRB for guidance.

When scheduling participants, remember to give yourself some buffer time and end the test promptly at the time limit to respect the participant’s time. Don’t schedule test sessions back to back - give your team a break between sessions.
::::::::::::::::::::::::::::::::::::: 

## Expanding your recruitment efforts
Recruitment is often the most difficult part of any study with human participants. You might find that emails are not effective enough and you need to find more people. You may also be trying to recruit people who have never used your tool and that can be a surprisingly difficult type of person to reach.

Snowball sampling is one approach to increasing your advertising efforts. Snowball sampling is when a potential participant refers the researcher to additional potential participants. This is great for recruitment but can introduce bias and must be done with care to protect participants’ privacy.

::::::::::::::::::::::::::::::::::::: challenge
### Exercise  5: Snow ball sampling
In the Zoom poll, identify which recruitment tactics are examples of snowball sampling:

- Asking someone who did not agree to participate if they know anyone else who might be willing
- Inviting people who have submitted bug reports
- Posting to a community forum
- A participant introduces you to another possible participant
- Adding a link to sign up for your study to your software’s README
- Identifying potential participants by seeing who has cited your software

::::::::: solution
"Asking someone who did not agree to participate if they know anyone else who might be willing" and "A participant introduces you to another possible participant" are snowball sampling. All others are good recruitment mechanisms but not snowball sampling, which requires a referral.
::::::::: 
:::::::::::::::::::::::::::::::::::::

## Tracking participation
You’ll need a central place where you can keep track of who you have recruited and when/if they will be participating. Create a spreadsheet for this.  It can be especially useful to also include when people were contacted and followed up with as well as links to session transcripts or recordings and notes. See the image below or follow [this link](https://docs.google.com/spreadsheets/d/1sNjgCn-u8R545Au8ypEXyH_2Kf5mWtgzP_qRw6aPAwY/edit?gid=0#gid=0) to a template participant tracker that you can make a copy of and use yourself. 

![](ep3_recruit.png){alt='A screenshot of a Google Sheet with columns for Participant ID, Name, Email, Session date and more.'}

In your participant tracker, assign participants anonymous IDs like Participant 1 or P1 so that you can identify them and their data without using their name. The private tracker should be the only location where you link anonymous IDs to identifiable information. If you don’t have to record identifiable information, don’t. You likely don’t need things like age, gender, or race and it is possible you don’t even need participant names or contact information. 

Including links in that tracker to notes and recordings means you are associating private information with identifying information like the participant’s name or email. That makes it very important that this be a confidential, private document accessible only to the people that participants agreed to. Make sure to save it in an appropriate location, preferably somewhere password protected. We recommend keeping a private folder for this tracker and any raw (non-anonymized) data. If you were using cloud storage like Google Drive for your study, you might use a folder structure like this:

![](ep3_folders.png){alt='Two screenshots of different Google Drive folders with annotations indicating which content should be shared and which should be confidential. Raw data and the participant tracker are marked confidential.'}

To make the most of your recruitment efforts and facilitate future studies, you can keep a separate list of people who consent to be contacted about additional user research opportunities. Ask at the end of a study session or via email if it’s okay to reach out again in future. When you do contact those people again, explain that they previously consented to this and ensure they know they can ask to be removed from your list. Keep this list, your participant pool, in a separate location from study data and do not record anything in the list about which research people have engaged in or how they came to be included in the list. It should be private so that only people directly involved in study recruitment have access. You can enable people to join this list by creating and sharing a sign up form.

::::::::::::::::::::::::::::::::::::: keypoints 
- Identify your targeted population for your user study by considering the constraints that your research question implies and your tool’s value proposition. Some constraints might be true prerequisites for participation while others might be nice-to-haves that can be forgone if recruitment is difficult. 
- Recruitment targets can be reached through iteration; about 10 people should be sufficient to gain insights.
- Recruitment should be done conscientiously so that participants understand what they are being asked, what their data is being used for, and how it is being stored. Conducting human subjects research ethically also involves ensuring there are appropriate benefits for participation, that participants are treated with respect, and that you never coerce them. 
- Snowball sampling is when a potential participant refers the researcher to additional potential participants. This is great for recruitment but can introduce bias and must be done with care to protect participants’ privacy. Posting to community forums, leveraging your code repository, and identifying then contacting users based on software citations are other tactics you can use to find participants.
- Recruitment should be tracked in a private location.
- Recruitment efforts for one study can support future studies—ask participants if they are willing to be contacted about future user research opportunities.
::::::::::::::::::::::::::::::::::::::::::::::::
