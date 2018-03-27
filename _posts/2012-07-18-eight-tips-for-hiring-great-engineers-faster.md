---
layout: post
title: "Eight Tips for Hiring Great Engineers, Faster"
date: 2012-07-18 16:27:31
---
It's a Monday morning at 9:30 AM, and I'm standing in a prominent Portland startup's office, getting the cold shoulder from another engineer wearing a MailChimp shirt. Recruiting engineers is tricky. 

The day had started innocuously enough; I'd gotten a text from my CEO asking me to meet him at a local hackathon, sponsored by a few technology companies. No big deal. He's been on the hunt for engineers, and wanted me to help him work the room. Per his request, I showed up a few minutes later, and performed the ritual with a few jumpy-looking coders huddled around a table. 

We've all done it: gone to a hackathon or other technology event with the hope that we might meet an engineer willing to let us refocus their horsepower on our problem. The conversation typically goes something like this:

bq. You: Oh hey, so, what are you working on today?
Engineer: Uh, I'm hand-crafting some artisnal Java bytecode. 
_(witty banter)_
You: Yeah, so I'm working on a <span id="this-text">Adult Friend Finder</span> for <span id="that-text">Pets</span>[1]. You should totally work with us because _&laquo;insert reason here&raquo;_.
Engineer: Oh okay, yeah, that's cool -- I'm kind of tied up right now, I've been super busy working on this project for _client x_.

At this point in your journey, flight avionics will begin screaming "PULL UP! PULL UP!" and you'll know that you've just lost any chance you had at landing this engineer. 

Here's the secret: hiring engineers is a user-experience problem.

## 1. Use warm introductions; connect organically.

Unless you're a well-known entrepreneur or engineer, chances are good that an average engineer has no idea who you are, or what you've done. When someone walks up to me with a business proposition, and I have no idea who they are, I immediately doubt the legitimacy of their proposition. 

It's in your best interest to know who you want, and why you want them, and ask a mutual FoaF (Friend of a Friend) in your network to facilitate an introduction organically, rather than trying to cold-call or shoulder-tap MailChimp guy.

## 2. Communicate with engineers on their level, using their tools.

One might think that the hiring process for engineers has been well-engineered. It hasn't.

In Elaine Wherry's post, "_The Recruiter Honeypot_":http://www.ewherry.com/2012/06/the-recruiter-honeypot/, she creates a fictional JavaScript engineer, and is able to glean some pretty interesting statistics surrounding recruiting channels. Her conclusion is that recruiters rely almost exclusively on LinkedIn. This is the first mistake. When you start a conversation with an engineer from a business-y, network-y site like LinkedIn, or even via e-mail, their BS meter tends to spike, and they're already preparing to be sold something.

Use IRC, hit them up on GitHub, Tweet at them, implement "IETF RFC#6214 (IP over Avian Carriers":http://en.wikipedia.org/wiki/IP_over_Avian_Carriers) -- whatever it takes to talk to them in an environment which they're comfortable with. It boosts your credibility tremendously.

## 3. Turn down the pressure.

Not everything has to be a negotiation. Sometimes, people just want to talk about what they're working on, and get some relevant feedback. In turn, they'll most likely ask you what you're working on, which will be your chance to explain your project. 

Don't worry about closing the deal. First, build the relationship.

## 4. Lead with your problem.

True engineers are typically people that are passionate about solving problems. The most dedicated engineering purists I know don't particularly care about money -- they care about having interesting problems to work on. This can work in your favor.

By presenting your problem first, and framing your conversation in its terms, you can pique the interest of the engineer and get them thinking about how they'd tackle it. My favorite anecdote is one of a JS engineer whom we'd wanted to hire. We'd talked to him at our co-working space the day before, and he'd turned us down -- only to walk in the next day with a big grin on his face saying, "you tricked me!" He'd started playing around with an issue we were having, and had gotten so wrapped up in it that he ended up coming up with a solution overnight. Even though we still haven't managed to hire him (and believe me, we're still working on it), he did provide us with a perpetual license to the code, and we're using it in production today.

## 5. Sponsor events, share knowledge.

One of my favorite engineers and all-around good guys, Joe Stump, gave me a very good hiring tip early on: sponsor events in exchange for the ability to give a 10 minute presentation on how you solved a cool problem. He's had great success with the technique, and we'll be trying it out soon ourselves.

## 6. It's not all about you.

The allure of being in a startup is just as much about what the engineer will get from you, as what you'll get from them -- it's a valuable chance to make good connections, learn new technologies, and meet some of the brightest minds in the world. Make sure you ask what *they're* looking to get out of it. Pay attention to it, and make it happen.

## 7. Pay open source committers to do something they already love.

We haven't released much code yet at Superbly, but my experience at RedHat showed me that open-source projects can be a great recruiting avenue. If you release something useful, and other people start submitting patches, keep track of those people -- find the most committed ones, and offer them jobs. It's not hard to convince somebody that they should be receiving compensation for something they enjoy anyway.

## 8. Be consistent, every step of the way.

Your biggest challenge is to make sure that your culture is reflected in every step of the hiring process. From initial outreach, to interviews, to team introductions, you should make sure that you represent the culture you have, and the culture you're trying to create.

I have a CTO voice that I use when I talk to engineers, and it's based heavily on "Alex Payne's":http://al3x.net/ voice. The thing about Alex is that he has an incredible knack for hiring genuine, talented people. Although he recently left "Simple":http://simple.com/, you can walk into their office and immediately feel his influence; every person you meet is the nicest and smartest person you've ever met. That's what I'm trying to create at Superbly.

At the same time, we're a young company; we do harmonies of theme songs from _Super Mario Brothers_ as we're leaving the office, and flip for which type of alcohol we're going to drink at our 10-4 meetings[2] -- we need to represent that culture and be true to it, as well, or we won't have a good cultural fit. I do my best to tell both stories in our conversations with engineers.

fn1. Reload for a new product idea; these come from "It's This for That":http://itsthisforthat.com/. I take *no* responsibility for the combinations.

fn2. We hold a meeting at 10:04PM every night, during which we take exactly six minutes to talk about all of the awesome things we accomplished during that day. Being in a startup can be really hard -- you get a lot of negative feedback, and you have to remind yourself that you're doing alright. Every other day, there's a company drink involved, and we flip for the type of alcohol (between bourbon and tequila) that we'll all be drinking.

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<script type="text/javascript">
  $(document).ready(function(){
    $.getJSON('http://itsthisforthat.com/api.php?call=?', function(data){
      $('#this-text').text(data['this']);
      $('#that-text').text(data['that']);
    });
  });
</script>