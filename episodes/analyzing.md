---
title: "Analyzing data and reporting results"
teaching: 0
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 
- How do I get insight into the kinds of errors my users make or encounter?
- How do I calculate metrics like error rates?
- What is reverse scoring?
- How do I interpret think-aloud data?
- What should I tell people about my study?
- What is an actionable insight?
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives
- Label qualitative data
- Calculate usability metrics
- Present results so that they highlight actionable insights
- Respond to UX skeptics
::::::::::::::::::::::::::::::::::::::::::::::::

## Start by labeling the qualitative data
To learn from your participants’ behavior and think-alouds, you will need to review and label your raw qualitative data. This is sometimes referred to as coding your data and is [a key step in many qualitative analysis methods](https://www.tandfonline.com/doi/abs/10.1191/1478088706qp063oa). You can use open coding to apply labels inductively, coming up with new ones as you proceed. Or, you can work with a coding scheme, a set of predetermined labels that are relevant to your research question. This is an iterative process—label your data as soon after you’ve collected it as possible and return to and revise those labels after you have collected more data. 

The labels you assign are going to represent your data later, so if you want to be able to talk about what activity people were engaged in while encountering system errors or what people’s emotions seemed to be while completing a task, make sure you code for those things.

Tools like Dovetail, Atlas.ti, or Taguette may be used to support this process, but you can do it without specialized software. The main thing you need is a way to associate labels for things you care about with pieces of data like quotes or mouse and click locations. You want to be able to explore labels assigned to data and, conversely, data assigned to labels. Excel spreadsheets can accomplish this. 

### Example: A coded think-aloud
In this example, the coding scheme includes: task, emotional state, and memory issues.

| PID | Quote | Task | Emotional State | Memory Issue |
| --- | --- | --- | --- | --- |
| P1 | Alright, I'm just entering the command. 'pip install PHANCY' and I hit enter. | pip install | neutral | NA |
| P1 | I'm pretty sure there's a way you can specify the specific version but I can't recall. | pip install | neutral | yes |
| P1 | I'm watching it make progress now. Yeah, look at all that. | pip install | positive | NA |
| P1 | And it's done! It's telling me it was successful so that's it. | pip install | positive | NA |

## Categorizing errors
If you are interested in errors, you may use error categories as part of your coding scheme. Common error types include: 
- Failed attempts: Entering invalid data, such as incorrect login credentials or formatting errors.
- Misnavigation: Navigating to unintended pages or sections.
- Repeated actions: Attempting the same action multiple times unsuccessfully.
- Incomplete tasks: Abandoning a task or failing to achieve the intended goal.
- System errors: Triggering error messages or encountering broken functionality.

You could also assign a severity to errors. A severity scale you could use is: 
- Critical: Prevents users from completing a task (e.g., broken functionality or unclear instructions).
- Moderate: Slows users down or causes frustration but doesn't prevent task completion.
- Minor: Small mistakes with minimal impact on task completion.

### Example: A coded error
What counts as errors are up to you; we recommend adopting a user’s perspective though. If they think there’s a problem, document that somehow. 

Here, a participant thinks there is an error because they haven’t seen any changes. The facilitator running the session might know that the tool is working but because the user thinks there was a problem, the error was labeled with two codes—Error: moderate and Error: no status update. These describe the type and severity.

| PID | Quote | Task | Error |
| --- | --- | --- | --- |
| P2 | I hit enter but nothing is happening. I think it’s broken. | pip install | Moderate; no status update |

::::::::::::::::::::::::::::: challenge
### Exercise 7: Applying labels
The quote below is a fictional participant thinking aloud while trying to reserve some nodes for their analysis work; they’re describing filling out a form.

“I’m just filling in my information in the form. I need two GPUs so I’ll enter that here. Okay, I’m….I’m just reviewing to make sure things are correct. Alright, we’re good. I can hit submit. Oh. Wait. I guess I forgot something. Oh just checking that box. Okay now we’re good.”

Read the quote a couple of times and then, in the Zoom poll, list some labels you might apply to the quote if you were studying how easy it is for users to make those reservations. Labels can be a single word or short phrases. Separate labels with commas (,) or slashes (\).

:::::::::::::::: solution
There aren’t really wrong answers here as you’ll apply the labels that you think represent the data well. You might describe each step they take. You might label the error types or their severity. You can use colons or dashes to create labels with subtypes as well, e.g. “task: reserve nodes.”
:::::::::::::::: 
::::::::::::::::::::::::::::: 

## Memoing
When reporting results, you will need to give your audience explanations—why did participants make these errors? What were they doing when they abandoned a task? Why were people feeling a given emotion? You can rely on your labeled data to answer these kinds of questions. Look at all the quotes associated with labels you deem most important and try to find patterns in them. Write short memos that summarize what you are seeing and which point to strong examples or exceptions. 

## Evaluating metrics
The formulas for calculating many of the common usability metrics are shown below. Generally, you will want to evaluate each task individually because that is how you will gain the most actionable insights.

| Metric | Formula |
| --- | --- |
| *Successes:* Number of participants who successfully complete a task. Also commonly reported as a rate. | *Total, calculated for each task:*
number of success
*Rate, calculated for each task:* 
(number of successful attempts / total task attempts) * 100 |
| *Errors:* Number of mistakes made while attempting a task, possibly broken down by error type. Also commonly reported as a rate. When categorized, proportions may be reported. |  *Total, calculated for each task:* 
number of mistakes identified
*Rate, calculated for each task:* 
(number of mistakes identified / total task attempts) * 100
*Proportion of one error type:*
(number of mistakes of X type / number of errors of all types) * 100 |
| *Clicks:*  Number of clicks participants make when completing a task; a proxy for complexity or efficiency.  | *Total, calculated for each task:* 
number of clicks |
| *Completion time:* Time taken to complete a task. | *Calculated for each task in seconds:* 
time at task completion - time at task start - any time spent on extraneous things |
| *Idle time:* Periods of inactivity during a task, indicating confusion or hesitation. | *Calculated for each task in seconds:* 
time at idle end - time at idle start |
| *Drop-off rate:* Percentage of participants who stop a task before completing it. | *Rate, calculated for each task:* 
(number of people who do not complete a task / total task participants) * 100 |
| *Self-reported ease:* Participants’ rating of how easy or difficult a task was to complete (e.g., using a Likert scale). | *Calculated for each survey item or combined items:* 
sum of ratings / total task participants |
| *Self-reported satisfaction:* Participants’ rating of how satisfied they are with the interface or experience. | *Calculated for each survey item or combined items:* 
sum of ratings / total task participants |
| *Self-reported usefulness:* Participants’ rating of how useful the tool or service is. | *Calculated for each survey item or combined items:* 
sum of ratings / total task participants |

Because your sample sizes will likely be small, you should capture the range for any averages, meaning you will state the lowest and highest scores. And, when reporting rates, you should also include totals.

::::::::::::::::::::::::::::::::::::: callout
Typically, when using self-report measures, a higher rating would indicate a more positive response. For example, when using a scale of 1-5, a score of 5 on a question asking how useful a tool is would indicate a highly useful tool. If you use any self-report measures that are negatively phrased, such that a higher score means something bad, you need to *reverse score* that item. To reverse score, subtract the rating from the highest score possible plus one. Reverse scoring should occur before calculating combined metrics.

### Example: Reverse scoring
A score of 2 on a scale of 1-5 can be reverse scored to 4:
(5+1) - 2 = 4 
A score of 7 on a scale of 1-10 can be reverse scored to 4: 
(10+1) - 7 = 4).
::::::::::::::::::::::::::::::::::::: 

## Reporting results
When presenting results from your study, give your audience context so they can form their own judgements. Tell them what the goal of your research was, what you did, and who you did it with. Make it easy for your audience to understand exactly what the data you are showing them represents.

How you plan on delivering results will affect the depth of context you need to share. Will you be delivering a write-up or report? Will you present your findings in real-time? Will you be sharing your slides with them afterward? You may need to include more details if your audience will be reviewing the results asynchronously, without you being there to explain and answer questions.

::::::::::::::::::::::::::::::::::::: challenge
In the Zoom poll, respond to questions about how easy to interpret each of the following options are.

*Option 1*
Error rate: 87.5%
Minor errors: 71.4%
Average ease: 4
Average confidence: 3.8

*Option 2*
87.5% attempts to install included an error, most (71.4%) of which were minor.

Average ease on a 1-5 scale: 4
Average confidence on a 1-5 scale: 3.8

*Option 3*
87.5% attempts to install included an error, most (71.4%) of which were minor.

Overall, the task was ______ to complete. (1 very easy - 5 very difficult)
average ease: 4
range: 3-5 

How much do you agree with the following statement: I felt very confident using the system. (1 strongly disagree - 5 strongly agree)
average confidence: 3.8 
range: 3-5 

::::::::: solution
Option 3 should be clearest. Formatting might help.
:::::::::
::::::::::::::::::::::::::::::::::::: 

Your audience will want an explanation of the behavior behind the metrics. Help them understand what participants were thinking and doing. You can leverage the memos you have written about emergent patterns and important examples and you may wish to again review the labeled data that’s relevant to your research questions. This way you can report on things like what participants were doing when they encountered critical errors.

In addition to quantitative results and qualitative explanations, you should report some actionable insights based on your findings. This is how your rapid usability test can inform development work. An actionable insight describes what the insight is (e.g. users’ expectation or a common problem) and an achievable step you should take next. 

There may be many possible next steps you can see but you can prioritize them by considering: 

- If the issue negatively impacts your value proposition
- The severity of the issue based on how many people it affects and to what degree
- Whether or not your team is able to address the issue in the near future

When reporting actionable insights, don’t hedge, say exactly what should be done next, e.g. redesign a feature, update documentation, conduct additional interviews. [GitLab’s Handbook on UX research](https://handbook.gitlab.com/handbook/product/ux/ux-research/research-insights/#actionable-insights) has useful suggestions about how to craft actionable insights.

You may encounter a team member who is skeptical about whether or not they should act on the results of your study. Generally, an effective response is to compare to the alternative: you know more now than you did before the study and you can move forward based on more than gut instinct. Acknowledge that your sample size may be small, but this is the norm in UX work and continued engagement with users can help you gauge how representative your results are. And, just like the software code itself, the user experience and your understanding of it is iteratively improved. That’s why we do rapid usability testing—it fits in with agile work cycles. 

::::::::::::::::::::::::::::::::::::: keypoints 
- Apply a coding scheme to label qualitative data like transcripts. Iteratively review the data and labels you have applied so that you represent the data as best you can. You can combine labels together or make new ones that better represent your data. 
- Specialized tools are helpful for labeling and exploring qualitative data but spreadsheets or printed transcripts and post it notes can do the job too. Whatever your system, you want to be able to explore labels assigned to data and, conversely, data assigned to labels.
- Errors can be labeled by severity or type, allowing you to more easily recognize which issues are the highest priority.
- Evaluate and report on tasks individually so that you have finer grained insight into users’ experiences. Multiple metrics can help inform your interpretation of how usable the tool is.
- When reporting results, tell your audience what the goal of your research was, what you did, and who you did it with. 
- When presenting data, ensure the audience can understand exactly what metrics mean and provide information like ranges, medians, and modes to assist with interpretation.
- Leverage the labeled data to help you report trends in what participants were doing, thinking, and feeling throughout their tasks. 
- An actionable insight describes what the insight is (e.g. uses’ expectation or a common problem) and an achievable, concrete step you should take next. These should be included in your reporting.
- Rapid usability testing can be integrated into your development process so that you continuously improve your understanding of your tool’s UX.
::::::::::::::::::::::::::::::::::::::::::::::::

