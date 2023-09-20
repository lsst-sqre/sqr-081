:tocdepth: 1

.. sectnum::

.. Metadata such as the title, authors, and description are set in metadata.yaml

.. TODO: Delete the note below before merging new content to the main branch.

.. note::

   **This is not a Rubin Data Management policy document; it is an explanation of practice in one team. It is being published for transparency and in the hope of sparking useful discussions.**

Abstract
========

An editorial on how I hire and why.

On Recruiting
=============

This is an explanation of the interview format I prefer and the reasons for it.
It was developed in order to recruit software engineers / devops engineers into high-performing teams, but it has been adapted successfully in other areas of the project.
It takes into account lessons that have been learned in how to minimize bias and discrimination during this process
For an account of my credentials and earned experience that led to these opinions, please see Appendix A.

I will occasionally contrast this with the “traditional” process that is frequently used in quasi-academic, government and other institutions without a strong technical ethos, as well as the “dotcom” process that describes practices common in Silicon Valley.

If this seems like strange content for a technote: you can't have software without people, and the people you get determine the software you write.

Goal
====

It should be obvious, right? You need someone to do a job.
The purpose of recruiting is to find someone who can and will take the job.

But it’s not that simple.

Finding someone who can and will take the job is a *necessary but not sufficient* outcome of the recruiting process. **A better goal for the recruitment process to** **maximize the job satisfaction** **of the collective unit (team lead, existing team, new hire) with the** **most** **efficient (in time and energy) process that will allow that (collective) unbiased determination.**

Why does this framing matter?

1. It highlights the fact that it takes two to tango: it’s as important to determine whether you are what the candidate wants/needs as much as the reverse.
   You need to spend as much time allowing the candidate to evaluate you as much as you do to evaluate them.
   It is common for us to hire people who take a (sometimes drastic) compensation cut to come here.
   If you still want the best talent, how are you conveying to them that it’s worth it?
   Do you understand how to contrast it with other options they may have?
2. It should make you aware that how you evaluate candidates sends a powerful signal to them, as does the rest of your recruitment process (from the quality of your public presence to the online application form).
   What does it say about you when you ask a lame question of doubtful value that you always ask just because habit?
3. It places the team (typically peers) centrally in a process that often favours managers.
   (Note this is *not the same at all* as the dreaded “interviewing for fit” practice - see later).
4. It acknowledges that the trade-offs that are made during nuanced recruiting that are hard to capture in a standard question + point scoring format.
   For example, the team may respond more positively to a more junior person with a great track record for picking up new things than a more exprienced person with an inflexible attitude.
   Sure, all things being absolutely equal you might want the person with more experience, but things are never absolutely equal.
5. Transparency! Informed consent! You cannot maximize job satisfaction if you hide things from the candidates.
   It’s like using a solver for Wordle.  You’re only cheating yourself (and it misses the point of the exercise.)
6. It’s a process. There’s always new data, for it or against.
   If you feel the work is done when the new employee starts, you are never learning any lessons from it.
   Two years later, how do you feel about your people? What came out (or should have come out) in your process that you needed to know?
7. You are not only trying to determine whether you want to hire a great person.
   You are also trying to determine whether you can hold on to them.

On Bias
=======

This should be obvious too? Don’t be biased, especially not in ways that are against the laws of the land.
Most of us go “that’s okay! I am not sexist/racist/etc so I’m good, and look, I even took that unconscious bias training our HR made us do”.

Again, this is *necessary but not sufficient*.

Here’s a thought experiment: what if I tell you the candidate I just interviewed was well presented, charming, articulate, easy-going and very enthusiastic about the prospect of working here?
Bet you have formed a positive impression - even though I have told you nothing, *literally nothing*, that is predictive of their success in post.

A more holistic way to think about this is that **bias is introduced by any aspect of your process that prevents you from meeting your goal**, which to restate, is to efficiently and effectively determine which candidate choice will maximize the job satisfaction of the (lead, team, candidate) triplet.
And the biggest obstacles (among many) to that effective determination are:

1. Preventing the candidate from being at their best
2. Introducing “noise”, information that dilutes your signal and falls prey into well-known cognitive biases.

To give just one brief example of each here (we will be discussing many biases throughout this document)

1. Panel (group) interviews with unknown (to the candidate) rote questions are very hostile to neurodivergent and introverted candidates.
   They will not be at their best.
   Yet this is a core practice of the “traditional” model.
2. Trick or puzzler questions.
   These do not represent normal working situations and if a candidate does well in them it is *noise* - you can’t help taking that into consideration but it is not information that goes to your goal.
   These are a core practice of “dotcom” interviews where there is a rationalization that the idea is to see “how the candidate thinks”, but in practice on a job, a candidate’s ability to think aloud on a strange unfamiliar and high-stakes topic with a bunch of people staring at them is irrelevant - unless your job is to hire the next White House press secretary.

The biggest unintentional bias in interviewing is *picking people who interview well*.
Not only does this trigger a lot of conscious and unconscious biases (of the \*-ism variety), but the person you are hiring is not going to do job interviews for a living.
People tend to overestimate the correlation between interview performance and job performance, especially under the “traditional” model.

Eliciting information that might give you a false-positive feeling about a candidate is one of the things to guard against, and a reason to reduce information-poor formats.

The Process
===========

With all the preamble out of the way, here is the form our interview process at the time of writing:

1. As much as possible, ahead of time, look into and evaluate the candidate’s existing work output (here, code, but could be papers, writings, project plans etc)
2. The candidate visits and presents on a topic of *their* choice that they judge may be of interest.
   Questions follow.
3. Lunch with the team
4. Candidate has 1:1 sessions with team members.
5. Manager-to-Manager call.

… and that’s it, besides the “go talk to HR about benefits”.
These stages are all designed to provide information-rich interaction with the team, but overall 1, 2 and 5 are the most useful steps for us while 3 and 4 are the most useful for the candidate.

Note that this assumes you already have reached a candidate shortlist.
Discussion of how get to this stage is in Appendix B, but it boils down to (a) market your job (b) read every resume (c) screen your longlist in a highly targeted matter.

Evaluate the candidate’s work
-----------------------------

This can be the most straightforward and most information-rich step.
The candidate is asked to provide a Github username, or a pointer to any other publicly available code.
This is reviewed ahead of time by both panel and team members.

Simply put, the best way to determine whether someone will write good code is… to look at their code.
Imagine recruiting a hair stylist. What is more useful - asking them a bunch of questions or seeing portofolio of their work?
Would you actually consider hiring them without seeing a portofolio?

Even if the code is not in a language or area relating to the job description, you can derive highly actionable information from it such as cleanliness of style, documentation style, architectural hygiene and best practices such lint and test.

If the candidate has code on Github (increasingly common in these “Github is your username” days) this is ideal, as you can also asses peri-code interactions such as whether they are polite to people filing bug reports, or whether their velocity is good.

If the candidate does not have code publicly available that they can point you to, you can ask them to provide you with sample code.
This is somewhat less information-rich than seeing their unedited activity, but is still remarkably useful: in our experience, people who write poor code don’t know they are writing poor code, and hence the code provided is flawed, despite the opportunity given to showcase their best work.

You can find a bias analysis of this approach in Appendix C.
However this is a step that provides information that is so well correlated with success in post that provided one is alert of the pitfalls I highly recommend it.

Candidate technical presentation
--------------------------------

The candidate is invited to give a technical presentation on the topic of their choice.
They receive a briefing email, in good time, with instructions.
The full text of this email can be found in Appendix D. You might find, upon consulting this appendix, that it tells the candidate… everything.
That’s the idea.

Let’s break down the presentation instructions to the candidate and the reasons for them.



      **Topic:** *We are asking you to prepare in advance a 30-60 minute technical talk based on your work and that seems to you to be relevant to the technical space of the position as you understand it. The emphasis is on content, not presentation. You may use slides, give a demo, do a code walkthrough, or just talk, as you prefer. […]*

Note this is not a “job talk”.
Generally asking candidates to give a talk-as-resume is merely advantageous to neurotypical extrovert characters with no cultural or gender reservations against self-promotion and they bias you towards presentation skills - great (maybe) if you’re hiring a marketing person, biasing noise if you’re hiring a devops engineer.

Leaving the choice of topic to the candidate is a critical part of the process:

*  “Tell me about something I might find interesting” probes the candidate’s empathy (or ability to form a theory of mind).
*  It sets the Q&A interaction on the candidate’s home ground.
   This is *critical* as by handing domain expertise to the candidate, you eliminate a very typical information poor exchange from traditional interviews that requires the interviewer to set the frame for a question before they ask it.
   Now if the candidate gives a poor answer you don’t know whether it was because you did a lousy job explaining the context (trust me, I’ve seen it and I’ve done it), and it also burns time that could be used listening to the candidate instead of your fellow interviewers. When the candidate choses the frame, you can reasonably expect them to answer questions authoritatively without risk of misunderstanding.
*  It probes a quality that is very important to me, personally, as a manager: I expect my engineers to have *better* narrow domain expertise than me, and I need them to be able to *explain* things to me effectively in a way that allows me to make good decisions.
   It is a *feature* to allow a candidate to talk about something that is not immediately related to our position: we are evaluating their effectiveness at technical communication.
*  As the only group format in the process, it gives a candidate a way to get a handle on any anxiety.
   Even folks that don’t like being in the spotlight warm up when they are talking from a position for expertise.
*  It goes to the ability to follow instructions; it has happened that a candidate who received a brief like this ended up giving a resume talk anyway.
   Doesn’t matter how good it was.
*  It’s applicable at all levels of experience. An experienced engineer can talk about a cutting edge project; a student can talk about programming for their robotics team; someone who is under NDA can talk about a personal project; etc.
   This is important because there are circumstances in which the right junior person is a better choice than a more exprienced person.

Note the guidance on time. In earlier iterations of this process I would say “take as long as you want” (and meant it) but I discovered some candidates found the lack of specificity stressful.


       **Audience:** *The team manager will invite a small group (some local, some perhaps coming in via teleconferencing) that are sufficiently versed in the technical area that you do not need to worry about skirting around details or providing large amounts of background. The team manager will e-mail you the expected attendance list and their roles by the prior evening.*

Some notes:

*  The invited audience format includes the team and stakeholders as well as formal members of the recruitment panel.
   Not only does your team get a good look, you get a better pool of questions.
*  Note the guidance to not avoid technical details.
   We reinforce this verbally in other interactions with the candidate - “no detail too detailed” - we want to get to a substantive technical level (that we can probe) not remain on superficial presentation (which introduces bias noise).
*  It’s a good use of time for our people.
   We have gotten some very interesting talks even from candidates we did not proceed with, and we had useful discussions with them. Otherwise we get (collectively) nothing from all the time we spent on candidates we did not hire.
*  The conventions of the talk format is that everyone is oriented towards the candidate.
   This reduces herd-mentality biases by making it less likely that recruitment committee members are monitoring each other’s reactions (which is a big problem in roundtable, and even worse on zoom)

Note that the audience is invitation-only.
In earlier iterations I did an open talk, but I found this gave less air-time during Q&A to people with more involved interest and the ability to ask better questions.
It also allows for the candidate to be given a participation list ahead of time; the “let’s go round the room and introduce ourselves” is utterly useless to certain candidates (including myself!) who have trouble catching names, understanding role and organisation titles, etc under stressful conditions (or at all).
This way they only need to put names to faces.


      **Format:** *You should expect an informal atmosphere with frequent interruptions for questions and ad-hoc discussions on the material that lead sometimes to considerable tangents. You are free to pursue questions of your own as these topics come up. Typically this adds another hour to what would have been the normal duration of the talk.*


The talk Q&A is where the magic happens.

*  This is a far, *far* more realistic simulation of a real work interaction that the “traditional” or “dotcom” interview formats provide for.
   This is literally what we do in the team week in and week out - have constructive technical arguments - and I greatly value someone’s ability to navigate them effectively (not combative or defensive but also not conflict averse).
   Interruptions are realistic and they allow questions to arise that need context (questions with high contextual value allow for greater specificity in answers).
*  At this point even anxious and/or neurodivergent candidates get into the swing of things - being asked a vague question of uncertain context is stressful, being asked “oh I see you used module X here - did you like it, cause I tried it and thought it kinda sucked” is a question that makes any candidate light up.
   It meets them where they are, and introduces an honest, gentle, productive conflict (to be clear, only say things like that if they are true, don’t create fake drama, omg).
*  Yeah it takes time. It takes a lot of time.
   And the better the candidate is, the more time it can take.
   That’s fine - overall, it’s great investment, and since we make time savings in other areas of the process, it’s not more overall than other methods.

If you look at the candidate letter in Appendix D you will see that it includes other guidance, from whether we have wifi to what to wear.
The intent is to address, pro-actively, anything that an anxious candidate might be stressing about.
Again, the goal is to help the candidate be at their best.

Lunch with the team
-------------------

The idea is not just to feed people. For god’s sake don’t order in take-out.

This step is for the candidate’s benefit.

*  After what could have been two hours of being cooped up in a room with strangers being grilled (no matter how nice we are about it, it can still feel that way) everybody needs to get out and get some air and a walk.
   Lunch break should be generous enough to allow people to leave the building and go somewhere.
*  This is a good time to show a bit of Tucson a bit to candidates for whom relocation might be on the cards (we usually take the streetcar to somewhere chill).
*  The candidate gets to watch the team’s interaction and ask us questions.
   In our experience great engineers are less interested in what one might naively assume (benefits, boss, mission) and more interested in who they are going to work with and what toolchain is in use. A+ people want to work with A+ people doing A+ type work. You need to show them you have A+ people.
*  My experience is that after the candidate has taken the lead with their talk, the team wants to show off to the candidate a bit.
   This is great.
   Often my people will end up talking about what their prior career was and what they like about working here and it’s all unforced and authentic and sets up the 1:1 phase nicely.
*  Okay so everybody also gets fed.

You will note this assumes an on-site format.
I am a big fan of doing on-site for shortlisted candidates.
It makes you think more carefully about your short-listing, they meet more people, and people do better in person than over zoom.
Also, zoom issues grossly disadvantage certain candidates, particularly ones where English is not their first language, or with poor Internet access.

Please note that teams are assumed to be responsible adults and can follow a brief like “lunchtime is still part of a recruitment process, no you don’t get to ask them if they have kids or get into politics”.

1:1 time
--------

Panel members, team members, and anyone who wishes to compete for whatever slots remain after that get 30 minutes each for 1:1 time with the candidate. Each pair gets to decide how to spend that time.
I generally spend it describing how rewarding I find the job (if I am hiring) or offering to ask any questions (if I am a team member).
If I detect the candidate is frazzled, I might even just offer them coffee and a break.
You can see the guidance we offer to the candidate in Appendix D.
At these point everybody has seen the talk and many have had informal lunch time with the candidate, so questions from the candidate get to be very relevant and useful for them.
This is also a time to show our transparency by acknowledging challenges in our organization.

While I consider these sessions to be primarily for the candidate, they are also of benefit to us.
By breaking up 1:1 we have a defense against herd mentality effects.
It is not uncommon, on debrief, to get interesting perspectives that were not apparent when we were in group.

Manager-to-Manager call.
------------------------

This is a critical part of the process that I perform for candidates that remain in consideration after the interview day.
The candidate is asked to provide contact for a previous manager or (preferably) two (it doesn’t have to be their current one for obvious reasons) who would be willing to talk to us.
I contact this person and ask for a voice call; if they decline (only has happened once!), I offer them to answer my questions over email.
I take notes during voice calls, summarize their tone for the recruitment committee and forward them unedited to HR for the record.

You can see a list of the questions for this call in Appendix E.
Generally questions 7-9 provide the most useful unanticipated input, while questions 1-6 fulfill the more typical reference check requirements.

Elsewhere reference checks are often pro-forma (in some cases occurring after a candidate has been selected or even been offer a job).
In fact they are so valuable that I no longer trust any process that does not take the output of this stage into account for selection. There are two reasons for this:

*  They are **your best defense against your biases**.
   This is where a candidate that you unconsciously felt less than positive about (because of language barrier, because of neuro-atypical behavior, because they were too goddamn nervous despite your best efforts to put them at ease) gets the benefit of an account of them in the absence of those biases.
   It also allows you to fact-check your impressions - for example, a candidate who appeared perhaps a bit too combative in their interview got a reference that identified that their intensity and sense of ownership sometimes comes across as combative.
   This was great input and resulted in that candidate being offered the position - and they have done great in post.
*  Reference letters are useless.
   Come on, you know it, you have written a reference letter that did not contain a full account of someone’s flaws, right?
   (Even in cases where you are allowed to write a reference letter at all).
   Tone of voice does not lie and people are more direct in a 1:1 call.
   Let’s take the following (real) answer given to the open-ended question 9 (“is there anything else you want to tell me?”): “if you can get them you are so stinking lucky”.
   People don’t write “stinking lucky” in reference letters.
   But the signal to noise in just that one word is exceptionally high (more when you add tone).
   The candidate was hired and the assessment was correct.

Manager-to-manager calls are not a cover-your-ass step - they are a treasure trove of useful actionable information.

There are two objections that usually come up here: one, that people won’t or can’t talk to you about previous employees.
This has never been a problem for me, though as mentioned people are happier to talk in a voice call.

The second one is one if the manager is biased against the employee?
This has happened to me on rare occasions - I would do a call where I would feel the feedback that I got was at significantly at odds with what we had perceived.
This is why ideally you should do two calls for each candidate.
And then sure, use your judgement, but I put it to you that at this point your judgement has more data available to it than asking “describe a time you had a conflict with a coworker” at a so-called “fit” interview.

Compliance / HR
===============

One of the reasons people are scared to experiment with their recruiting process is that they feel that their existing process is there for legal reasons.
I have generally found my HR professionals to be very open to nuanced discussions about what the law requires (whether in letter or in spirit) and how to experiment within those confines.
It is important to understand that HR’s hands are to some extend tied once you have written the job description. See Appendix F on some tips on job descriptions.
You are required (and should be!) to be able to demonstrate that you did not discriminate against a candidate you rejected.
While the process described here is geared towards reaching the *best* outcome for everybody concerned, I have full confidence it is also fair both ethically and in the manner required by law.

Here are the auditable records that come out of this process (and remember this comes at the end of the screening process described in Appendix B which has its own outputs)

*  A written assessment from the recruitment panel on the basis of the talk-and-q&a.
   This can stand for the output of the “traditional” panel interview format in that it assesses against the job description.
   I personally prefer more narrative categories (“below bar, marginal, above bar, way above bar”) than numbers but if your HR people absolutely need numbers throw them a bone here.
*  A written summary of any comments I received about the candidate from talk attendees not on the recruitment panel.
*  A written narrative assessment compiled by me after the 1:1 session debriefs, focusing on any red flags (if any were raised)
*  A compete set of notes from every manager-to-manager call I made.
*  A typically verbal assessment from me about what the candidate has indicated it will take to close the deal.

In my experience these are acceptable as satisfying any legal compliance requirement.

The biggest barrier to introducing this in your workplace is that there a reflexive administrative desire to have everyone follow the same process.
The challenge is to communicate the fact that different types of job may require a somewhat different process.
In addition, the insanely competitive market for talented developers places an additional role here.

But what about [thing “we always do”]?
======================================

Here are some features of “traditional” and “dotcom” interviews I have rejected as giving poor results and/or introducing biasing noise:

*  The panel interview.
   Reasons largely covered above, this is generally a process that disadvantages certain candidates, introduces biasing noise favoring “good talkers”, creates herd mentality among panel members and gives a false sense of confidence to the panel about the reliability of any opinions they have formed.
   They are also terrible cases of “fighting the last war” (asking questions inspired by thinking of former colleague who did something wrong) and do nothing to help us give a good account of our organization.
*  The “culture fit” interview: There are alarming research findings that this is a minefield for unconscious biases to be expressed, and that it results in people to be hired who are most like the interviewers (or who the interviewers think they are).
   The questions typically asked in these interviews have highly coachable answers, disadvantage many classes of minority or non-traditional candidates, give a false sense of confidence (believe me, you cannot establish how a candidate handles conflict by asking them how they handle conflict) and as a group activity, are prey to herd mentality.
   You are literally telling your brain “here, bias away”.
*  The puzzle or indeterminate answer questions (how to print maximum number of As using 4 keys, what’s the area of all the sliced pepperoni in the US, etc).
   If I wanted dog tricks I’d get a dog from a circus.
   This kind of process could be useful if your entire purpose is to pare down your candidate pool and you believe it is an adequate proxy for smarts; it’s actually a fairly useless proxy for the skills that make somebody successful in my teams.
*  The “do actual work” interview.
   If it is useful work this is illegal in the US and immoral everywhere.
   In any case, get over yourself: It is not reasonable to ask for a major investment of time from a candidate
   You’re not special, and if they are any good they are looking at a lot of options at the same time.
*  There is a “dotcom” practice where managers are not involved in their engineer’s hire.
   The thinking is that as the manager you are desperate to fill a post, and this desperation causes you to accept below standard candidates today, that dilute your technical pool and become someone else’s problem tomorrow.
   I think this is a totally terrible solution to a very real problem.
   In our own context, I think it is sufficient to be aware of management desperation as source of bias and to ensure any candidate you offer a job to is well above bar.
   Don’t be scared to draw a blank and re-advertise; having the wrong person in post is worse than having a vacancy.

If you feel defensive along the lines of “hey I can tell loads from these formats” I invite you to look at all your coworkers that have been in post for 5-7 years.
Are they all awesome?
But they all probably got hired under this format, even that person who you keep hoping will quit one day.
Well, that’s the question that got me started down this route.
No process is perfect, but one can and should do better than “nothing’s ever perfect”.

Future research
===============

I have had great success with this process, but of course I am always thinking of how to do better.

*  I am considering going further away from the “job talk” and specifically asking for a code walkthrough format.
   I haven’t figured out how to do this in the light of the concerns in Appendix C.
*  I take up the slop of the lunch break by finding the candidate a room so they can some quiet time before 1:1s.
   I really want to explicitly build those in the schedule.
   Introverts are in a meltdown at that point and maybe they will feel better knowing a break is coming.
*  Along the same lines, considering explicitly building in bathroom breaks to the schedule.
   Feels wrong when the candidate has to ask.
*  I find unconscious bias training is useful (even though its impact has been questioned scientifically) but it does focus on race discrimination.
   I am interested in finding good training material for my panels that address neurodiversity and cultural and gender socialization issues too.
*  I feel maybe I should blind the code review step, though I am also aware of the risks of blinding (which prevents you from actively supporting an equivalent minority candidate) so it’s not obvious.
   I am monitoring the research on this.
*  Still very concerned about non-neurotypical candidates and misunderstandings that can result (see interrupting someone, which can be for any reason from neurotypical disrespect to neurodivergent sign of engagement).
   This is the area I am most actively trying to educate myself about.
*  My desire to help the candidate deal with the new faces onslaught by sending them pictures of the invited audience is at odds with my distaste for making people volunteer their pictures.

At the end of the day, we are a scientific and engineering organization.
We should bring our curiosity and critical faculties to all aspects of our work and seek to improve where we can.
This document encapsulates what I have learned by engaging with a process that is critical to our mission success. Please contact me if you have any input that will help me improve it further.

Appendix A: learn from my mistakes (I sure try to)
==================================================

So here’s what happened.
Three-ish decades ago when I ended up (alarmingly fast) in a team lead position I went into hiring with a traditional academic-influenced mindset.
I thought I could tell things by being in a panel interview.
I thought I had great judgement.
It didn’t take long to realise that (a) so thought everyone else (b) we were all wrong.

One of the problems with hiring is that you are not often confronted with the consequences of your mistakes.
You can tell yourself you did hire the best candidate - hey it’s not your fault the pool wasn’t that great, it’s not your fault they ended up being lazy, etc.
However I had some rare opportunities to learn from my mistakes. Soon after I made a bad hiring call that left me with a “there must be better ways of doing this” feeling, I had a great lesson fall in my lap: I confidently ranked two candidates and offered the job to the first one.
That candidate failed to acquire the necessary work visa so I went, dubiously, to the second candidate, despite the fact that they had frankly bombed the interview.
This turned out to be an exceptional engineer and loyal team member and I am still kicking myself that I didn’t spot that at the time (now I would have recognized the candidate as neurodivergent and intensely introverted, and I would hope my format would have made it easier for them to stand out).

When I came to Rubin and had to ramp a team from zero, I got a lot more practice - and thanks to a very supportive and engaged AURA HR professional - I got started on the road of improving what works and getting rid of what doesn’t.
At some point my success in this area was noticed and I now serve on many recruitment panels inside Rubin (despite my sometimes needing to explain it’s not me, it’s the process that delivers the results, and that it needs to be adjusted for the kind of job being hired).
This is great as it has given me more data to work with, but I do not fool myself that this is a substitute for keeping up with professional research in this area - which I try to do, though not as I much as I should.
I do keep track of every candidate I was in favor of, and how they end up doing in post.
As a result I am getting better at recognizing my own biases (i.e. the things I tend to be swayed by in a candidate that end up being unrelated to their performance in post).

I am at this point totally convinced that one should be transparent when dealing with candidates.
I still see panels try to “spin” challenges the incumbent will face.
If you include (which you should!) retention in your metrics of a successful recruitment outcome, it rapidly becomes obvious that as always, transparency is the best choice - even if it costs you candidates at the time.

Appendix B: getting to the shortlist
====================================

As mentioned above, it all starts with the job description.
More on that on Appendix F, but let’s assume you wrote a great job description that you don’t have to fight with (or cause HR issues) during this process.
What next?

**Shaking the trees**

Your recruiter will helpfully ask you where you want the ad posted.
You will name some places, they will suggest some more, and then you’re going to lie back and wait for the fish to bite.
Hahahahaha no.

It’s important to understand the job market of the job you are opening.
Currently in tech, there are more great jobs that great people, so it is highly unusual for anyone to be trawling job sites (there are some exceptions, like people geographically trapped by two-body problems, but that’s an exception not the rule).
It is much more likely for people to be attracted to a job either through certain niche social media sites or even more likely, through their own personal network.
If your people bring you people, that’s ideal as they have already done your marketing for you.
If you are going to hit online forums and social media, for the love of god sell your job in the vernacular of those forums.
Our job ads are written with a lot of boilerplate and compliance issues in mind - they are useful in the process but they are *not* marketing documents.
Be aware that people you induce to apply are going to encounter a process that seems slow, bureaucratic and deal with less than impressive application software. Warn them that this does not reflect the team culture.

If you bring someone you already know on the table (such as a former coworker), you obviously have to keep an open mind to alternative candidates and be even more diligent about monitoring your biases and doing your paperwork
Nevertheless, having a known quantity willing to apply is a great predictor of success and I try to time job openings to allow for this.

I greatly dislike non-public hires.
I don’t dislike hiring internal people, but one should compete a job fairly and not just post in in the basement with the burnt out lightbulb.
It’s better for everyone in the long run.
There are many reasons for doing this, but the most compelling one is that if we hire uncompetitively from sister institutions, we are perpetuating the appallingly bad diversity mix of our institutions without even trying to see if we can do better.

**The weed-out**

I read every resume. Every single one, even the one from the fast food cooks.
This is because mistakes can be made when you ask HR to screen your candidates - I have had fabulous luck with non-traditional candidates that failed a keyword match - or even an experienced panel’s shortlisting!
It really doesn’t take long at all to eliminate the unfortunate folks reduced by their circumstances to spamming job sites. I don’t need to bother my panel with this stage obviously.

After that it’s a numbers game.
If I have a large number of viable or at least not obviously non-viable candidates I start building a longlist with my panel.
This is a permissive process - even if one person on the panel is excited about (or just wants to have a better look at the candidate) they get on the longlist - your fellow panelist might have seen something you missed.

Phone or zoom, much as they are problematic, are the only way to narrow down a longlist to a shortlist.
However in respect for everybody’s time this is not a full interview.
It’s most useful in a “we are checking to see if your application materials represent you” stage, as it is easy to disadvantage applicants who are not that good at writing a resume or cover letter.
The main line of questioning is to establish whether you have correctly assessed the breadth and relevance of their previous experience.
This is often the most challenging step HR-wise: our good folks minded for compliance would ideally want a score based on keyword or job ad match output from this phase but it can be challenging to do this fairly unless you were prescient in writing your job description.
I prefer to give narrative rather than numerical records for this reason, but that can be an issue within certain orgs.

Hopefully after this stage the panel can agree on a 4-or-less shortlist (and at this point you do in fact have a lot of things you can say in defense of your choices for compliance purposes).

I try to have at least 2 people come out to interview, though if only one is over the bar (or others have pulled out in the meanwhile) so be it.
My panels do occasionally offer “courtesy” interview days to folks that would not have necessarily been shortlisted; typically these are extended to internal candidates (on the basis that the process will be good practice for them and to demonstrate transparency if they are not selected) and to local early career candidates that will benefit from the networking.
There is a school of thought that says this wastes people’s time, and your HR may have objections.
Generally I have had good feedback from doing this, but use your judgement.

Appendix C: show me the code
============================

As mentioned, looking at actual work output (code if you’re hiring a developer) is the most reliable and direct proxy towards whether some can, you know, actually code.
It is also beautifully easy to “blind” this process even without particularly intending to, as if you ask your team to check out the code under a Github profile they frequently only have access to a moniker that does not reveal a candidate’s gender, ethnicity, etc.
Code review also is priceless in being able to tell the difference between somebody being able to do something versus them being able to do something *well*, especially in an area that affects the team (their code’s readability and maintainability).
It also allows people without professional programming experience on their resume (eg grad students) to compete favorably on the basis of their side projects.

There are two sources of bias in this process (that I am aware of at least):

*  It disadvantages candidates that cannot show any code.
   It’s rarely the case as it involves someone who has worked in a classified/NDA environment *and* does no recreational coding, but it does happen.
*  The open source bias: We are an actively pro open-source culture as an organization and as a team.
   We value a lot of the soft factors that lead to open source development such as ability to work with others, pro-social impulses, a genuine liking for coding, and so on.
   It is also a treasure trove of non-coached coding for review.
   However it can also (indirectly) be a proxy for having free time which in itself is (indirectly) a proxy for having certain levels of privilege.
   Even without considering these factors, purely statistically, if I reach my hand in a jar of open source developers I am likely to draw a white male.

My own feeling is one has to just take these potential sources of bias on the chin - accept they are there but continue to ask for code and list open-source as desirable experience anyway.
It’s just too good a predictor for success in post and it doesn’t disadvantage a candidate *overall* in their general job search: this is a full employment field and the majority of employers will not have a problem with such candidates.
Just be mindful of the consequences.

Appendix D: the letter
======================

Here is the complete letter the candidate receives from us about the process.

**Interviewing at Rubin with SQuaRE**

Here are a few notes about SQuaRE’s on-site visit format we hope you find useful.

During your visit you will:

-  Give a talk followed by extensive Q&A
-  Lunch!
-  Have 1:1 meetings with -members of the search committee - members of the SQuaRE team - any other LSST staff who express interest
-  Meet with our HR generalist

**Talk**

**Topic:** We are asking you to prepare in advance a 30-60 minute technical talk based on your work and that seems to you to be relevant to the technical space of the position as you understand it. **The emphasis is on content, not presentation**. You may use slides, give a demo, do a code walkthrough, or just talk, as you prefer. We have the typical A/V equipment to plug your laptop into and visitor WiFi.

**Audience:** The team manager will invite a small group (some local, some perhaps coming in via teleconferencing) that are sufficiently versed in the technical area that you do not need to worry about skirting around details or providing large amounts of background. The team manager will e-mail you the expected attendance list and their roles by the prior evening.

**Format:** You should expect an informal atmosphere with frequent interruptions for questions and ad-hoc discussions on the material that lead sometimes to considerable tangents. You are free to pursue questions of your own as these topics come up. Typically this adds another hour to what would have been the normal duration of the talk.

Note: We do not engage in trick questions, coding tests, or anything that you would not expect when presenting your work to your team during the normal course of work.

**Lunch**

The team will take you out for lunch afterwards, there are options for most dietary requirements but feel free to advise the team manager of any preferences ahead of time.

**1:1 sessions**

Members of the search committee, team members and other interested parties can request 15-minute 1:1 sessions with you.

Search committee members have different approaches to using their 1:1 time. We typically select staff who will interact with the position in some way to serve on the search committee, and we encourage you to ask questions about their role in the project.

Team member 1:1s will give you a chance to ask any questions you may still have in a private setting (“Is the team manager a deranged despot?” is always a good one), ask team members about their work, and go more deeply into topics of common technical interest. Again, these sessions do not involve any traps or any kind of questioning that you would not expect during a normal work technical interaction.

**HR**

You will also spend some 1:1 time with our HR generalist, who can give you an overview about the employment conditions, benefits and answer any questions you might have in that area. She will advise you on the likely timeline for filling the position and notifying the candidates of the outcome.

**Finally**

The whole process will take most of the working day, so when you make your travel arrangements, please allow a full day for the visit, eg. by arriving the day before and leaving late (or the day after) if flying in.

LSST is a quasi-academic / casual dress environment. With SQuaRE you are not expected to suit up, but neither will you be frowned upon for doing so — do whatever makes you comfortable. Most people in the room will be in “engineer chic” — something like polos/khakis.

Please email SQuaRE’s manager at [] if you have any questions (or would like advice on selecting a talk topic), and we look forward to seeing you soon.

Appendix E: The reference call
==============================

Here is the current version of the questions I ask in this step

1. When, where and in what capacity did you work with [candidate]?

2. How would you describe their core technical competence (such as their ability to write clean, well documented code in good time, [other relevant topipcs] etc)

3. [for non-junior candidates] How would you describe their senior skills (such as software and system design, ability to work effectively in a self-directed manner, capacity to lead in the development of policy and system improvement)

4. How would describe their ability to interact effectively with their coworkers, especially in non face-to-face interactions [this is where I will mention if the candidate plans to join us remotely)

5. Are there any areas in which you wished for some improvement on their part?

6. As far as you know did [candidate] leave your organization on good terms?

7. Would you work with them again given the chance?

8. Is there a question I should have asked you that would have told me something I needed to know?

9. Is there anything else you would like to tell me and ask me?

Appendix F: The job description
===============================

Get this wrong, and you may have ruined your whole process before you even got started.

It’s not that the job description is usually a uninspiring marketing document - you can do better than that (see Appendix B) but that everything you write down is risky. It risks causing great candidates to self-eliminate, it risks putting the job on rails in ways that become evidently wrong once you start interviewing, and it can make your situation very difficult once you discover this halfway through the process.

I find it extremely useful to visualize who I would know that I would be happy to hire (even if they are not on the job market). It’s often a lot easier to paint a picture of the kind of person you are looking for than to generate something coherent out of a list of JIRA tickets that are not being attended to.

Here are some points and pitfalls:

-  Laundry list of requirements: it is well established that minority candidates self-censor when presented with a list of highly specific requirements (for example male-socialised candidates will go “cool I have 6 out of 10 requirements”, whereas female-socialized candidates will go “drat I am missing 2 things that they want, nm”).
-  Some of there requirements don’t make sense. “10 years experience in Python” tells me nothing - as the saying goes, some people have 10 years experience, some people have 1 year experience ten times over.
-  Do you really care about that education requirement you stuck in there? I have hired a talented engineer that had no more than a HS diploma - people find their way to software in sometimes very non-traditional way. “Oh but we said ‘or equivalent experience’” - yeah but you led with the Comp Sci degree and also failed to adequately define equivalent experience. See previous point.
-  On the other hand, we are often under pressure to provide those kind of constraints because they fulfil some administrative criterion for determining “level” or “seniority”, I know, I know.
-  In general resist a tendency academic institutions have of conflating seniority (and salary level) with management duties. It is entirely reasonable that somebody with an absurdly high degree of competence in sought-after skill gets paid more that me, their manager. Their market rate is genuinely higher.
-  Again there is a tendency to fight the last war. Just because you are replacing someone who was a ninja python programmer and also baked killer pain au chocolats is no reason to put both python ninja and pastry chef in the description. A real team (as opposed to a collection of people working individually) is fluid and if you take out one person you should be able to add a person back in that has a somewhat different “shape” and the team will adjust around them. They just need to be *good*.
-  Also don’t fight next week’s war. You may have a hole now, perhaps because you took more scope or someone left, but what do you have planned for that person 2 years from now? 4? 6? Thinking ahead encourages you to value potential more that current knowledge.
-  Don’t be afraid to list seemingly hard-to-score qualititative skills. “Writes lucid documentation” is a skill most of us would kill to have onboard. So why not list it.
-  Re the language issue: a great programmer can code in any language. The question is, are you able to *tell* they are a great programmer in the language they are currently coding in. There’s nothing wrong with asking for python if you are a python shop (obviously), but don’t box yourself in too much.
-  Re the background issue: Ideally a team should have a mix of backgrounds, but I at least have found it far easier to teach astronomy to my software engineers than to teach software engineering to my astronomers. Ask for an astronomical background only when absolutely necessary.
-  Under “Required” only list things you are absolutely unwilling to live without. Most of your content should be under “Desirable” to give yourself more flexibility.
-  Finally, always have your job descriptions proofread by someone outside your immediate organization. It is amazing how often you can be unconsciously telegraphing negative messages, especially if you are in the habit of recycling them or frankesteining text previous openings.

Good luck!
