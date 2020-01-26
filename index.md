---
layout: default
title: "Saving the World From Fascism"
slug: home
---

# Saving the World From Fascism by Bringing Widespread Mental Health to the Techscape

**How?** I'm not quite sure yet. Read on.

Back in the day I used to be a successful online entrepreneur. Depending on your definition of success, of course. I was netting $40k per year from a site that required one hour per week of my time. And another $100k per year from a day job. To me, that counted as successful.

And then, out of nowhere, I started to battle with depression and existential crises. And like any good Brené Brown disciple, I didn't shy away from them. I leaned in.

In 2016 I started going full Tylder Durden on my life. I burnt it all down. Quit the cushy day job. Sold the cushy side hustle (I was just going to shut it down, but [this guy](https://wanderingaimfully.com/) convinced me to sell it for $75k instead). Moved across the country. Hired a life coach. Hired a therapist. And then willingly broke my own heart when I divorced my childhood best friend.

I don’t regret any of those things. But damn. You honestly wouldn’t believe me if I told you how many times I cried myself to sleep. How many times I took a shower just so I could cry without my hostel-mates hearing me. The time I went on 58 dates in 35 days solely because I couldn’t exist alone without my thoughts spiraling into darkness. How much I drank so I could just feel nothing.

Following that, I hard-quit the internet. I just needed a break from it all. It wasn’t logical, and I knew that. But sometimes the bigger picture is more important. I *needed* a break.

So I shut down a few SaaS projects, deleted my entire email list, and deleted all of my social media accounts.

Many tough decisions and more than a year of travel later, I’m starting from scratch with zero contacts. Zero community. Zero people to care about what I'm doing. That’s my penalty for my dramatic exit from the internet... a penalty I’m happy to pay. Because along with that penalty comes an incredibly clear **big picture** of what I want to be doing.

A big picture from the immense capabilities I saw during my stint as a Machine Learning Engineer. It’s scary stuff, folks. And the future, if it remains in the hands of powerful people with chips on their shoulders who feel like they have things to prove and trophies to earn... the future is very, very scary. I firmly believe that - and this is not me being hyperbolic - the most important thing that humanity needs to do right now is increase empathy and equity in tech. I’d love to indirectly help the equity piece by donating all profits of whatever we build together to places like [Black Girls Code](http://www.blackgirlscode.com/), [Girls Who Code](https://girlswhocode.com/), and others (would have to do further research). And I want to *directly* touch the empathy piece by trying to connect people in tech with their inner heart strings. I know what it’s like to be a priviliged white guy who feels slighted despite having every advantage. And I know the path out of that.

So, I know the big picture. This site will document my attempt at figuring out the finer details.

<p>&nbsp;</p>

{% for f in site.fascism %}
  <p><strong>{{ f.date | date_to_long_string }}</strong> <a href="{{ f.url }}">{{ f.title }}</a></p>
{% endfor %}