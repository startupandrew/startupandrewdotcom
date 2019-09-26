---
title: "How Firebase Interviewed Software Engineers"
date: 2019-09-26T08:42:36-07:00
---

Today, Firebase has a large team with hundreds of engineers. Before the Google acquisition, however, we had a small team of just 24 exceptional people that I firmly believe was among the strongest of its kind in the world. A big part of that success was the way we interviewed software engineers. I’m sharing our approach below so that other teams can compare methods and learn from what we did in the early days of Firebase.

Please note that **this post is intended to help with vetting of software engineering candidates at early-stage startups with significant technical complexity**. It is specifically not intended for later stage companies, non-software-engineering candidates, or for startups without significant software challenges. It is also not intended to provide guidance regarding broader team composition, sourcing candidates, or closing candidates. Each of those topics could fill a book in their own right.

# The Ideal Candidate

At Firebase, we looked for candidates who were **friendly, smart, and motivated**. Our strategy was to build a small team where every single member was highly talented, hard working, and collaborative. This allowed us to create an atmosphere of trust where employees had high agency over their work and could move quickly. 

In addition, we looked for **generalist, pragmatic problem solvers**. The needs of early stage startups change very rapidly so it’s critical your engineers can learn new things quickly and fill whatever roles the project demands. If you hire a specialist too early you may find that their skills quickly become irrelevant. Note that this generalist requirement extends beyond software engineering &mdash; our early engineers helped with sales, attended hackathons, wrote documentation, handled support emails, helped us move offices, and more.

So, what do friendly, smart, and motivated engineers who are generalist, pragmatic problem solvers look like *on paper*?

Here are some things to look for:

* **Strong communication skills** &mdash; a well written introductory email and resume along with good communication in their online content (videos, blogs, websites, etc)
* A **passion** for your company or your problem space
* A history of working on **challenging projects with real deliverables** (rather than purely research projects or projects that never completed)
* A **broad set of experiences** (even if much of the experience is shallow) demonstrating an ability to learn new things quickly and “wear many hats”
* A high velocity of skills **growth** over time

Note that you can apply this same filter to candidates of all levels of experience. For new grads without a long career history, you can look at internships, class work, and side projects to assess these attributes.

Finally, I want to note that in my experience many companies overweight academic credentials and brand-name employers. Attending a “top school” or working at a FAANG company are positive signals, but they’re not particularly strong ones. You’re better off applying the more general criteria above and some good judgement.

# Our Interview Funnel

An interview process works just like any conversion funnel. Your goal is to maximize the number of qualified candidates that make it all the way through the process while minimizing the amount of time wasted both for you and the candidate. In general, you want to eliminate candidates early if they aren’t a fit, though it’s important to apply some good judgement here to minimize false negatives &mdash; sometimes the outliers are the best candidates.

Building a great team requires considering a very large number of candidates. At Firebase, we had to interview nearly 1000 candidates to build our 24 person team, and we considered a great deal more applicants than that on paper.

This is how our hiring funnel worked.

* Phone screen: ~1000 candidates; ~40% pass rate
* Technical test: ~400 candidates; ~25% pass rate
* On-site interview & reference checks: ~100 candidates;  ~40% pass rate
* Offer: ~40 candidates; ~60% hire rate

As a startup, process speed and transparency are your secret weapons when competing for candidates with large companies. Move quickly to schedule interviews and communicate outcomes. Don’t hide the founders behind recruiters, admins, or arcane processes; give candidates direct access. It’s also a good idea to have a dedicated person on your team (perhaps your office manager) checking in regularly with them to help with scheduling and logistics. 

Remember that every interaction you have with a candidate is an opportunity to sell your company to them. It’s important to get them excited, so that when you do make them an offer, they accept.

# The Phone Screen

We began our 30 minute phone screens by explaining our interview process, answering any questions they had, and trying to get them excited about us. Then we interviewed them about their interests, soft skills, logistical issues, and culture fit. We avoided technical questions, as it is hard to assess technical skills on a short phone call.

Specifically, we would try to assess if the candidate:

* ...is excited about our company.
* ...is a good verbal communicator.
* ...is prepared to leave their current employer.
* ...is willing and able to relocate (if needed) or commute to our office.
* ...is a match for our culture. At Firebase, we had a list of nine clearly defined ‘Cultural Values’ that we shared with the candidate and discussed (note: I’ve included our list of values at the end of this post).

Sometimes, if a candidate was local and we were particularly excited about them, we would conduct the initial screen in person at a coffee shop. While this is more time consuming, it helped us close candidates later on by demonstrating a level of interest and openness that bigger companies couldn’t match.

After the call (or coffee), the interviewer would make the decision of whether or not to move forward with the candidate. About 40% of candidates passed our phone screen and advanced to the next step.

# The Technical Test

Our next step was an at-home technical test where candidates built a real, working solution to a complex algorithmic problem. Our test was called “GoldMine”, and it involved optimizing the route a miner takes through a maze to maximize the amount of “gold” collected. Candidates worked from home, using their own computer and dev environment and with full access to the internet. The whole test was designed to take 6 hours.

Most companies don’t do hands-on tests and instead try to assess programming skills during onsite interviews. I believe, however, that the take-home test is a better approach for a few reasons:

* It’s a lower stress environment where candidates can use the tools they are used to.
* The longer time limit allows for a significantly more complex test question where you can observe the candidate handling complex algorithms rather than basic “reversing a linked list”-type problems.
* It’s a more objective data point versus an experience-based interview. Candidates can’t bluff their way through a real programming challenge.
* It enables consistency across candidates. It’s much easier to provide the same testing experience to everyone who applies using this method.
* It’s less vulnerable to bias.

#### Don’t candidates hate programming tests?

One common objection I’ve heard to take-home tests is that they are too time consuming, and candidates won’t be willing to do them. This was not our experience. In fact, I don’t believe we ever lost a candidate due to them not being willing to take our test. The strongest candidates take their job search seriously and are willing to devote a fair amount of time to landing the right job.

Note that I’m not saying this isn’t a significant use of time or that you shouldn’t appreciate the sacrifice the candidate is making to take your test. It is, and you should!

It’s critical that candidates don’t feel their time is wasted. At Firebase, we made sure of this by putting a great deal of effort ourselves into the take home test process. We checked in with candidates by phone when they began the test and also periodically during the test to answer any questions they might have. Then, after they submitted their answer, we would provide them with a thorough and detailed code review (usually by the legendary [@mikelehen](https://twitter.com/mikelehen)). 

We treated this code review like a real production code review, and we did it whether or not we planned to move forward with the candidate. This review was very important for two reasons. First, it showed the candidate that we took them seriously and that we were investing a significant amount of our own time in the interview process. Second, it gave the candidate an idea of what working at Firebase might be like; “If they do code reviews this well for their coding challenges, I can’t wait to work with this team on real production code!”

Most candidates found our technical test to be a positive experience, and we received a lot of feedback during on-site interviews along the lines of “I wasn’t expecting that to be so much fun, but I really enjoyed it.” The test process also had positive effects on team morale. New employees had a shared experience with their coworkers from day one. More importantly, the high, objective bar we set with the test gave people confidence in the skills of their teammates and helped them build trust with each other.

{{< figure src="/images/interviewing/goldmine-scoreboard.jpg" caption="James and I in front of the GoldMine technical test scoreboard." >}}

Some of our employees enjoyed the test so much, in fact, that they continued working on their solutions after they were hired. GoldMine took on a life of its own inside the company as a healthy rivalry developed between teammates. All of the top solutions ended up being built by employees on their 3rd or 4th tries at internal hackathons. Our UI team built a nice visualization that showed miners traversing the maze. We even built a giant scoreboard for the office so everyone could see who had the highest scoring solutions. Even today there are ex-Firebase engineers working on better GoldMine solutions “just for fun”, despite the fact that we haven’t administered this test to any candidates since 2014! 

#### Our Test: GoldMine

Our GoldMine test was an open-ended optimization problem designed to be easy to understand and easy to generate a valid solution for, but extremely hard (potentially impossible) to generate an optimal solution for. This allowed us to learn a great deal more about our candidates than a test that was merely pass/fail. Some candidates failed to produce valid output at all, some built valid but basic solutions, and some built sophisticated algorithms that produced highly optimized solutions.  

To ensure we were seeing each candidate’s best work, we allowed them to build solutions in any programming language, and boy did we see a range! We saw dozens of languages from Erlang, to Scheme, to Lua, to C. Input and output was done through text files to keep things simple and compatible with whatever language they chose.  

#### Designing Your Own Programming Challenge

For your startup, I recommend designing your own programming challenge. A wide range of problems can work well for this, but you’ll want to keep the following in mind:
Keep it generic. You’re looking for general problem solving capabilities here, not specific experience, so you want something that doesn’t rely on knowledge of a particular language, library, or problem space.
Make it objectively scorable. GoldMine solutions could be easily assessed and given a numeric score, and your test should do this too.
Choose an open-ended problem. You want to be able to differentiate candidates across a wide skill spectrum. Ideally it will be easy to create an OK solution, hard to create a good solution, and impossible to create an optimal solution.

After you’ve designed your test, you’ll need to calibrate it to learn what a “good” solution looks like. At Firebase, James and I asked several friends who we knew to be exceptional programmers and used their solutions as a baseline. If you already have a team, you could try giving this test to them. Remember not to use your own score as a baseline &mdash; you designed the test, so you have an unfair advantage!

#### Administering the Test

We gave candidates a link to the test and let them take it on their own schedule. When they clicked “Start” we gave them instructions and simultaneously logged their start time (we used the amount of time they took as one data point in assessing their performance).

In addition to instructions, we gave them sample input and output files, a tool they could use to verify and score their solutions, and a (compiled) reference solution they could run on their own machines so they could understand by example what a correct solution should do. Providing candidates with lots of examples and tools to make the process smooth for them is important as it keeps them from getting stuck on issues that have nothing to do with their programming skills. I recommend automating as much of this process as possible. This is partly to save yourself time, but also to ensure you’re providing a consistent test to each candidate.

The test was designed to take six hours, though we would let candidates take up to twelve. We required candidates to do the entire test in one sitting so we could use elapsed time as a data point in our decision. *In retrospect, I think our test was a bit longer and more difficult than ideal. If I were to do this over again, I would design the test to take about 4 hours. However, I would keep the requirement that they do the test in one sitting, as the amount of time a candidate took turned out to be a pretty strong signal.*

When the candidate completed the test, they had to email us their solution, including all code and instructions on how to run it.

To evaluate the candidate’s performance we would run their solution against a secret master test file. We used the same set of randomly generated input mazes for every candidate to ensure a fair comparison. We also performed a thorough code review, which we shared with the candidate as I mentioned above.

Our decision to move forward with a candidate was based on (1) their objective score, (2) the quality of their code, and (3) their communication throughout the process including the instructions they provided to run their solution and conversations during our check-in phone calls. About 25% of candidates passed our technical test and advanced to the next step.

# The On-site Interview

While our technical test gave us a strong signal about a candidate’s general programming skills, we still needed on-site interviews to round out our picture of them. In addition, the on-site interview was a chance for the candidate to meet the team and learn more about our company.

One critical lesson we learned at Firebase was to make sure the candidate’s physical needs are taken care of so that you’re seeing them at their best. Consider any special needs they may have. Give them restroom breaks and offer them drinks and snacks throughout the day. If the candidate is traveling for the interview, your company should pay for all travel expenses and make sure they have a reasonable schedule and are able to get a full night’s sleep the night before. And finally, make sure you don’t overwhelm the candidate with the length of interviews or the number of people they have to meet.

I remember one particularly bad example of this last point at Firebase. We had a candidate wake up at 5 AM to fly in for an interview the same day. I took him out for breakfast as soon as he arrived and then brought him to the office for a full day of interviews, including a lunch with the team. Afterwards the whole team took him out for drinks and dinner. At the decision meeting, half of the interviewers were strongly in favor, and the other half thought he was “low energy” and were less impressed. We eventually figured out that he was just too tired! Everyone in favor had interviewed him during the morning, and everyone against had interviewed him late in the day. The candidate later told me he was so tired at dinner he could barely keep his eyes open. Don’t do this!

#### Our Interview Schedule

Our interview day generally consisted of:

* Four 45-minute interviews with individual team members
* One 1-hour review of their GoldMine solution
* Lunch with the team

The four individual interviewers generally consisted of at least one of the founders (me or [James](https://twitter.com/JamesTamplin)) and at least one person they would be working with directly if they joined. The other two we would choose based on interview experience and availability. I would strongly recommend keeping at least one founder engaged directly in your interview process as long as possible. Founders will likely be the most effective at vetting candidates for culture fit and in getting them excited about your company. This is so important, that had we stayed independent, either James or I would likely have interviewed every single candidate until we had a team size in the hundreds.

In the morning before you start the interviews, It’s a good idea to have the interviewers meet to discuss which questions each person will ask to ensure the best use of time by everyone.

#### Individual Interviews

During the individual interviews we would focus on engineering design problems, communication skills, past experience, and assessing culture fit. We would not have candidates write code or do white board problems, as we used GoldMine to assess coding skills instead.

As a general rule, we tried to keep our interview questions open-ended so that we could assess the full range of a candidate’s skills and knowledge. Asking a question with a single correct result gives you one bit of data, but asking a question that can be answered with infinite detail can tell you a lot more.

One of my favorite interview questions (created by [Vikrum](https://twitter.com/vikrum5000)) was: 
“What happens after you type ‘https://www.google.com’ into a browser and hit enter?” 

It’s a beautiful question because there’s such a range of possible responses, from very shallow to incredibly detailed. An average response might describe how the browser fetches HTML from a server, renders it, and executes JavaScript. A better response could include some details about resolving DNS, setting up a TLS connection, and loading images, CSS, and other resources in the HTML page.

We had one candidate though that really blew us away. Her response started with, “Well, most laptops have mechanical butterfly mechanism in their keyboards...” and continued with a detailed explanation of USB, OS interrupt handlers, and kernel scheduling. After we told her she could skip ahead to the part where the browser starts making network requests, she jumped into detailed explanations of BGP, TCP, TLS, and certificate authorities. By the time she was halfway through Diffie-Hellman key exchange we were pretty confident she knew a thing or two about how the internet works.

It can be very helpful to ask consistent questions across candidates. This allows you to more easily compare candidates with one another. While this runs the risk of your interview questions leaking and giving future candidates an advantage, this is unlikely at an early stage company.

If you want some example interview questions to consider, there’s [a long list](https://firstround.com/review/40-favorite-interview-questions-from-some-of-the-sharpest-folks-we-know/) on the First Round blog.

#### The GoldMine Review

The most important interview of the day was our review of the candidate’s GoldMine solution. This was our primary means of technically vetting the candidate during the onsite interview. We reserved an hour and had in attendance four or five engineers, including some of the individual interviewers as well additional members from the team the candidate would be joining.

While we already had a pretty good signal on coding skills by looking at the solution they wrote, the in-person discussion allowed us to go deeper with technical design questions because we knew the candidate had already spent a good deal of time thinking about this specific problem. It also allowed us to learn about their technical communication skills. Finally, it allowed us to catch cheaters &mdash; if someone had not written the solution to their at-home test themselves they would not have been able to pass this review (we never had anyone cheat, which I am thankful for).

We would usually ask the following questions:

* Please walk us through your solution and explain how it works.
* What other approaches did you consider while designing this solution?
* If you had more time, what would you improve about your solution?
* We see your code does X. Why did you choose that approach instead of Y?
* How would you improve your solution if it was to become part of a real production service?
* If we changed the requirements in ways A, B, and C, how would you need to modify your solution?

We tried to make this review mirror what it might be like to review a real engineering design with the team as a Firebase employee. We wanted it to be engaging and challenging but also fun, and we hoped the candidate left excited about our team and their potential for personal growth as a part of it.

#### Lunch with the Team

One of the critical parts of our on-site interview was giving the candidate a chance to meet the teammates they would be working with. Allowing the candidate to build rapport with their new team and build some trust in us helped us maintain a high conversion rate from offer to hire. In addition, it helped the existing team build confidence in our hiring process by making sure they were involved in the process for each of their coworkers. We’d always check with the lunch group before making our hiring decisions and ask for any feedback they had on the candidate.

#### Checking References

When we invited candidates for the on-site interview we also asked them to provide one or two references. We called these references in parallel with organizing the on-site interview so we could use this information in our decision process.

The most important aspect of a reference is who they are and how they relate to the candidate. Strong candidates will have many people they worked closely with who are happy to say nice things about them: close coworkers, former managers, professors, classmates, advisors, and so on. If the candidate has trouble finding references that they’ve worked closely with recently, that’s a bad sign.

In addition to contacting the references they provided, we also tried to source our own references if our professional networks overlapped. This won’t always be possible, but it can provide a more neutral perspective.

# Making Your Decision

We made our hiring decisions as quickly as possible after interviewing a candidate &mdash; usually the same day. This ensured that the interviews and reference checks were fresh in our minds and let us get offers out to candidates quickly, which was a huge competitive advantage when competing against Google, Facebook, etc. for talent.

Immediately following the last interview, we would have non-interviewing teammates take the candidate out for a happy hour (or boba or coffee, depending on the candidate’s preference). Meanwhile, the interviewers would gather for the “decision meeting”. After we made our decision we would go join the rest of the group and socialize with the candidate. If the group had decided to say “yes” to the candidate, we would present a written offer to them the same day before they went home.

Our “decision meeting” had a very clear process. First, before any discussion had occurred, we would count to three and simultaneously vote with our thumbs to “hire” or “not hire”. For interviewers who were unsure, they could put their thumbs sideways or slightly up or slightly down (float values for votes were allowed at this stage). Next, we would go around the table and each interviewer would share their high level notes from their time with the candidate, and the person who had conducted the reference checks would share their notes as well. This was followed by some discussion led by those with strong opinions.

Finally, we would all vote again, and this time, a “hire” decision needed to be unanimous to move forward. Requiring unanimous agreement definitely led to some contentious meetings, and it meant that we likely said “no” to a number of candidates we should have said “yes” to. However, we believed that the cost of a mis-hire was higher than the cost of saying no to a great candidate, so we erred on the side of caution.

*Note: this unanimous support requirement is probably the most contentious part of this blog post. Some companies require a supermajority, some require one “champion” and no one strongly opposed, and others leave the decision up to the hiring manager. One common argument is that mis-hires can be handled quickly if you have good managers that can spot problems early, so it’s ok to take the risk.*

On average we gave offers to about 40% of the candidates we brought on-site.

# Following Up

Regardless of what you decide, it’s critical to follow up promptly with candidates after their interview. For candidates you decide to make offers to, it’s important to get them a formal offer letter quickly, to answer their questions, and to try to sell them on the exciting potential of your company. For candidates you decide not to hire, it’s equally important to get back to them promptly with a clear decision and to say “thank you” for their time.

You want every candidate to feel that they were respected and that their time was well-spent, whether or not you decide to make them an offer. If you’re doing a good job here, you’ll find that even many candidates you reject continue to refer their friends to your job openings.

# Conclusion

We found that this process worked very well for Firebase. In addition to ensuring we selected a high quality team, it also was a positive enough experience that most candidates (about 2/3rds) accepted our offers. I hope my notes here are able to help you improve your own team’s interviewing process.

**I’m hosting a live video Q&A today (9/26/2019), so stop on by [my Twitter](https://twitter.com/startupandrew) at 1 PM Pacific time if you’d like to learn more about interviewing and hiring.**

<br/>

*Thanks to [James](https://twitter.com/jamestamplin), [Rob](https://twitter.com/robdimarco), [Ben](https://twitter.com/benadida), [Jacob](https://twitter.com/_jwngr), and [Hannah](https://twitter.com/hannapotamus) for reviewing drafts of this post.*

<br/>

-------------------------------------------
<br/>

*Footnote: The nine Firebase cultural values were:*

1. *Be Yourself. Accept Others.*
1. *Continually Improve with Honest Feedback*
1. *Give 110%, 33% of the Time*
1. *Speak Up, We’ll Listen.*
1. *Be Curious, Explore Different Solutions.*
1. *This is Your Happy Place.*
1. *Be Humble*
1. *Honesty and Integrity*
1. *We are all Entrepreneurs*
