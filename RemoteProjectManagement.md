# Remote Project Management
Los Angeles FTC Kickoff 2020-09-06

Hello everybody!  My name's Fletcher Porter.  I'm a mechanical engineer, though lately I've been working on writing software with [Tetra Bio Distributed](https://tetra.bio/) to drive an open-hardware ventilator splitter that will help combat COVID-19.

This is my 10th year with FTC.  I spent 4 years in high school on the Suit Bots, and since then I've been mentoring teams at Monrovia High School and judging at tournaments (I actually tied for most tournaments judged last year!).

A common question that I've been hearing since people started to realize that this season would be remote is *how are we going to build a robot?*  How do you design and build a thing when you can't be in the same room as the other people designing and building it?

Broadly, it comes down to three things: communication, documentation, and compassion.

Before the quarantine, communication was relatively easy.  You would show up to your team meetings and talk about what needs to be done on the robot.  The only work you needed to do for communication was to set a time and place for the meeting.  Given the Safer at Home order, this isn't possible.  A team member a mile away may as well be 1,000 miles away.  Most of you have probably found ways to communicate with others in the last 6 months, so you might be able to find a time and place to meet, but conveying information over a call is much harder than face-to-face.  You can't read body language as well, people's mics cut in and out, and showing things to your teammates like parts that you have made is awkward and frustrating.  So to develop a communication strategy that acknowledges and attempts to overcome those difficulties is incredibly important.

To document your design as it's created becomes super important when doing remote work.  Veteran teams will be familiar with the *Engineering Notebook* that FIRST required of teams in previous years, a big book you write documenting every bit of design work you put into your robot.  Although it's not required this year, I'd actually recommend that you keep one anyway.  When you're working in-person, if you need a bit of information, you can just walk up to the person that would know and ask.  But separated by distance and coronavirus, it's not so straightforward.  The person you need help from may not be online when you need them, they may be busy doing homework, they may not be in the mood to do robotics stuff at the moment.  However, if they fully documented their work (and I'll suggest some ways to do that in a moment), then you'll have much less need to ask questions.

The last of these points, compassion, is the least obvious and is kind of nebulous, but it's really important.  Life these days is nuts; there's a big wildfire blazing only a couple miles from where I sit, a deadly disease is killing near a million people, and of course we're struggling to figure out how to do a FIRST season without being with our friends.  So making a part of that plan to be to have a healthy dose of patience and understanding for each other will make life quite a lot easier.

So let's get into the meat of the presentation.  What tools can you actually use to design a robot in a distributed manner?

## Kanban Board

For managing the tasks you need to complete, a **kanban board** is an incredibly useful tool for communicating who's working on what and what state each task is in.  They were originally developed by an industrial engineer at Toyota in the 1950s in order to increase productivity of their production line.  They work by allowing you to visualize progress in a project and in individual components of a project in the form of cards, which represent project components, moving between various columns, which mark how far a component has progressed.

[Here's one](https://github.com/tetrabiodistributed/project-tetra-display/projects/1) that I'm using for the ventilator splitter I'm working on.  When I'm planning out what work I need to do, I'll create these cards in the *Backlog* column.  Then when I'd like to get some work done, I'll move one of the cards into the *WIP* (work in progress) column.  I've got this *Blocked* column here for when I can't proceed with work on a card that I've already started because I'm waiting on work from someone else.  But when those sorts of conflicts are resolved and I finish work on a card, I move it to the *Review* column.  Then I'll ask one of my team members to take a look at my work to make sure it looks good.  This reviewer role is actually a super useful thing to have mentors do.  Their experience means that they'll be able to share with you best practices for how to do what your doing and tell you when there's an easier way to do what you're trying to do.  Finally, work goes into the *Closed* column.  It's super important to have this column rather than just deleting the cards because you can look at how much work you've finished over the course of the season.

You can see each card has some information on it.  A title, some labels, maybe a milestone marker, and in the corner here it's got the profile pic of a person assigned to work on that card.

There are a couple of websites that offer kanban boards like this for you to use.  I've been showing you one in [GitHub](https://github.com) (which is free), where if you create a repository, you can go to the *Projects* tab and create a *Project Board* and use the *Simple Kanban* template to get something similar to what I showed you.

Another site that offers this with a free tier is [Trello](https://trello.com), which I think is a little simpler to use.  Here's a board that I'm working through to apply to grad school.  It's largely similar to what's on GitHub, but the notable difference that I've found is that you can attach due dates to cards in Trello, which is really nice.

## General Communication Channel

It's super important to have a general communication channel for the team.  There needs to be a place to ask questions about what's happening on the team and to discuss what direction the team should move forward in.  There are many options that I'm sure many of you are familiar with, but I'll go over them anyway.

[Discord](https://discord.com/), which if you're watching this live then you're definitely aware of, is my personal favorite.  You can have a bunch of text channels, you can have voice channels where you can do team meetings, and all of this is totally free (you can pay to get higher-quality video).  

There's also [Slack](https://slack.com/), which is very similar to Discord except it doesn't have integrated voice calling and will only keep the most recent 10,000 messages in the free tier.  It does have a message threading feature that some people like though.

[Zoom](https://zoom.us/) is another tool that you might possibly be familiar with.  It has voice calling features and limited text chat.  But in the free tier you only get 45 minute calls, though some of you may have a premium Zoom link through school or a parent's work.

There's also the various instant messaging apps, all of which are good, though I've found that people tend to get annoyed by notifications they don't care about and end up muting the chat and missing important messages.

For persistant communication, that is communication that you want to be easily accessible for a long time, like design, software, or outreach plans, meeting agendas and minutes, and changes in plans, [Google Docs](https://drive.google.com) is an invaluable and free tool.  You can make documents, spreadsheets, slideshows, or even flow charts.  Just make sure all your work is in a shared folder that everyone on the team can access.

## Scheduling Meetings

As lame as it is, it really helps everyone to stay on the same page to have regular meetings.  There's a few kinds of meetings I'd recommend to have.

- **Planning**--Decide on what you're going to accomplish in the next two weeks (perhaps note cards on the kanban board) and assign individuals to complete those tasks.  Have this once every 2 weeks.  Might be good for Mondays or Tuesdays.
- **Retrospective**--Go over what you've gotten done since the last planning meeting.  How are people feeling, is stuff coming along?  Have these the weeks you don't have planning meetings.  Might be good for Thursdays or Fridays.
- **Tag Up**--Everyone takes a turn answering three questions: what have you been doing since the last tagup, what will you be doing until the next one, and what are you blocking on.  Keep these short and focused; they're not a time for discussion.  You can chat with people that block your work or are blocking on you after.  Have these once or twice a week.
- **Social Hour**--Talk about anything other than robotics; games, movies, TV, people, whatever.  The point is to get to know the people on your team so you can be more understanding of them when you're working.  Have this as many times per week as you want to; they're fun.

One important thing with meetings is to be understanding if anyone on your team can't make every meeting.  None of you are being paid to do this, y'all have way too much homework, god help you if you want to have a life, so if someone has to miss a meeting, just have some compassion for them.  A helpful thing is to decide on which meetings are critical.  I'd suggest that Planning is most important, then Retrospective, then Tag Up, and finally Social Hour.

## Build Days

A concern that I've heard from a lot of teams is "How are you supposed to have build days with quarantine?"  Well fortunately I've been getting build day experience with the ventilator splitter I'm working, so I can offer some practical advice.  However, I'll say that it's a lot more difficult than build days under normal conditions, and ultimately you do need to have people meet in the same place to build, something that not everyone will be comfortable with.

### Planning

The fact that people need to meet up to build means that there needs to be quite a bit of planning going into it.  Weekly builds to just "figure it out" isn't a viable strategy when you need to minimize exposure to each other.  So I would say that drawing your robot out using a CAD program before you turn a single nut is more important than ever.

Fortunately as students you have free access to nearly every professional-grade CAD program.

- [OnShape](https://www.onshape.com/) is an online-based CAD program that I've heard some people call "the Google Drive of CAD".  For free you get all the modeling functionality of the pro version.  If you need help learning, you can visit the [OnShape forums](https://forum.onshape.com/).  It also runs on fairly low-end computers (though it can have some slowdowns).  *Linux/macOS/Windows*
- [SolidWorks](https://www.solidworks.com/) is the most common CAD package that I've seen in my work.  There normally isn't a free tier, but they offer a free version to FIRST students if you apply at [this link](https://app.smartsheet.com/b/form/6762f6652a04487ca9786fcb06b84cb5), which will get you a software package that would normally cost $96,000.  If you're stuck on something with it, you can visit the [SolidWorks subreddit](https://www.reddit.com/r/SolidWorks/)  It'll chug on less powerful computers though.  *Windows*
- [Fusion360](https://www.autodesk.com/products/fusion-360/overview) is the CAD program that I've been using for the ventilator splitter, and it's very fully featured.  The student version is free and gets you 100% of the functionality of the program.  It also runs decently well on low-power computers.  *macOS/Windows*
- [PTC Creo](https://www.ptc.com/en/academic-program/academic-products/free-software/creo-college-download) is used at a couple places, like the Blue Origin rocket company.  *Windows*

There are others too, but these are what I have experience with.  If I had to pick one for a FIRST team, I'd probably suggest OnShape on account of how easy collaboration is.

Prior to going to a build, you need a list of everything you're going to make at that build and you'll also need all the parts to put what you're building together.  All of these CAD packages have functionality to make BOMs (bill of materials), which will tell you how many of which parts you'll need, and build instructions just like what you'd find in a LEGO kit, so I would *highly* recommend putting together build instructions before build days.  It makes them go incredibly seamlessly.

A note on getting parts together, I'd highly recommend using standard kits of parts like what's offered by goBuilda, REV, Actobotics, or Tetrix in order to reduce hassle in getting parts together.

Then there's the logistics of the build.  Where can you hold these things?  Ideally, you can meet at your school.  Assuming your school isn't in-person presently, you'd have to get permission from the school administration for you to go on campus.  It's not guaranteed, but if you show them a schedule of what exactly you're planning on building *in detail* and promise that you'll wear masks and maintain six feet social distancing, you might have a chance.

Alternately, you could hold builds in a teammate's well-ventilated garage.  Failing that, you could set up card tables in a teammate's backyard (which is actually what I did for builds when I was in high school).  However, do be concious of the weather.  If it's smokey out like it is today, then a team member with asthma may have a hard time working.  If it's raining, then it's hard to work generally if there's not some sort of roof over you, especially if you're working on electronics.

### Execution

When it comes to the build itself, the #1 thing is to wear a mask and maintain social distancing.  Building a robot isn't worth you getting COVID, nor the people you live with getting COVID, nor your teammates getting COVID.

You should also consider where people can go to the bathroom at a particular location.  And when people arrive, they should probably wash their hands.  And then if the build goes over lunchtime, where will people eat in a distanced manner?  Writing this all down into a persistent document could be a very valuable excersize.

Even with masks and social distancing and planning, you or some of your teammates may not be comfortable with an in-person meeting.  They or someone they live with may have an immune deficiency that makes their risk tolerance for COVID lower, or they just really don't like the idea of meeting in person during a pandemic.  Don't make showing to builds a matter dedication to the team, especially during a pandemic.

But given a space, parts, tools, instructions for how to build everything, and everyone following proper COVID procedures, the build can be fairly normal.  Make sure to write down everything that goes differently from expected so you can discuss after the build.

### Storage

Between builds, where does the robot go?  Well if you're able to work at your school, the school would be best since it's a communal location.  If not, then I would say a team member should volunteer to store the robot at their house.  This could perhaps be the team member whose house builds are held at.

## Software and Testing

The robot should get built with plenty of time prior to your first competition so that the software can get run and tested to where everything works.  The setup I can imagine would be to have a programmer take the robot home and keep it there while they work.  Other programmers can contribute to the codebase using [git](https://git-scm.com/).
