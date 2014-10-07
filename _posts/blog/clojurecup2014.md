---
title: Clojure Cup 2014
layout: post
categories: blog
---

#A lesson in failing fast
A few weekends ago, Mark and I competed in [Clojure Cup](https://clojurecup.com/). The web app was written in ClojureScript, and the language's JavaScript interop capabilites allowed us to use [jaws.js](http://jawsjs.com/) a JavaScript library for making HTML5/Canvas games. Our entry was an interactive experience called [robot\_dance\_party.gif](http://robotdanceparty.clojurecup.com/). Create a robot dance party in your browser. Export to .gif (we never got around doing that part).

Although we received only a few votes from the public and mediocre ratings from the judges, that is besides the point of this blog post. Why this was so important to me was that we made this thing in two days. Our previous game took two years! I've learned a lot from these two projects of contrasting time scales.

##Super Wizard Potion: the neverending project 

Our previous project was also our first video game, an in-browser puzzle game called [Super Wizard Potion](http://superwizardpotion.pythonanywhere.com/). On the day of the beta release Mark posted a post-mortem of sorts on Facebook:

<blockquote>I am so burned out of this game. We're going to let the game sit for a while as we gather feedback, and come back to it after we pursue some smaller projects. In the near future, we plan on focusing on making quick prototypes for games, not spending over a month on a particular idea. That way, we can let our ideas flow and focus on our favorite ones and build on them. By recent months, I started to get tired of SWP, so I want to make sure we focus on projects we feel enthusiastic about.
  
  
<p>I'm not saying I don't like SWP, it's just that I had so many ideas for it that we had to unfortunately cut out just to get it finished. But hey, this is only our first game! The lessons I've learned and the experience I've acquired are a great personal investment. My horrible coding was sloppy and huge (first time with a big project in Javascript), but I can learn from the mistakes I've made if I decide to make another game in Javascript. I learned a lot about pixel art, and I've never seen Kris churn out music so fast before. So even if I'm not super-proud of the game itself, at least we came out with pretty cool art and music.
  
  
</blockquote>


##robot\_dance\_party.gif: a quick and dirty version 1

In the tech startup world much advice is given to release early and fail fast. In his essay ["The Hardest Lessons for Startups to Learn"](http://paulgraham.com/startuplessons.html), co-founder of startup incubator Y Combinator Paul Graham writes:

<blockquote>The thing I probably repeat most is this recipe for a startup: get a version 1 out fast, then improve it based on users' reactions.
<p>By "release early" I don't mean you should release something full of bugs, but that you should release something minimal. Users hate bugs, but they don't seem to mind a minimal version 1, if there's more coming soon.</blockquote>

Although playtesting became an integral part of the development of Super Wizard Potion, it took us a very long time to get it in the hands of players. By the time of the first round of playtesting, we were already so deep into the development process. We were so caught up in what WE thought the game should be that we were blinded to what first-time players would think of the game or if they could even get into the game at all. After that first round, we began to make drastic changes to the game. We would have saved so much time and energy if we had people play a much earlier iteration of the game.

Contrast this with the end result of the Clojure Cup coding competition. With robot\_dance\_party.gif we had a working product in two days. We submitted our entry and soon the [feedback](https://clojurecup.com/?#/apps/robotdanceparty) came rolling in. It didn't really matter to me that we didn't receive anything more than 3 out of 5 stars from the judges on any of the criteria. The important thing was that the judges were able to use a minimal yet working application so they can give us feedback.

##Failing Faster

Learning from these two drastically different approaches in development, we have since changed focus as a team. Still being beginners in game development, we realize that we shouldn't be taking on ambitious, long-term projects but smaller projects that would take no more than a month before a prototype is sent off to testers.

Beyond just relieving the pressure of wasting so much effort into a project that would probably fail, focusing on non-ambitious games would free us to take more risks and explore the possibility space of game design before we plunge deep into an idea that we think would be worthwhile investing more time and energy on. To quote Paul Graham once again (from ["Before the Startup"](http://paulgraham.com/before.html)):
<blockquote>Starting a startup is like a brutally fast depth-first search. Most people should still be searching breadth-first at 20.</blockquote>

You can expect some strange little interactive experiences from Plunger Games released more frequently in the near future. Although we do not yet have a website that acts as a portal for our games, you can [follow me on Twitter](https://twitter.com/zangderak) and [Mark on Tumblr](http://skid-marq.tumblr.com/).

I will leave you with this motivational piece from Extra Credits:

<iframe width="560" height="315" src="//www.youtube.com/embed/rDjrOaoHz9s" frameborder="0" allowfullscreen> </iframe>
