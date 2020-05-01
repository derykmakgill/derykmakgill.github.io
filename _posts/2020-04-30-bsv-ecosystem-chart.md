---
layout: post
title: Investigating the BSV Ecosystem Chart
permalink: bsv-ecosystem-chart
---

The BSV Ecosystem Chart as of April 30, 2020 records 414 total projects developed at a rate of .8 projects per day.

I've seen this chart shared regularly for months as evidence of all the innovation and development happening in BSV, but I've never seriously taken a look at the projects it lists. This article reviews all the projects and attempts to assess the accuracy of the report.

### 1. BSV Kanban

It took me a long time to find BSV Kanban. Search queries on Twitter for ['BSV Kanban'](https://twitter.com/search?q=bsv%20kanban&src=typed_query&f=live) and ['Bitcoin SV Kanban'](https://twitter.com/search?q=bitcoin%20sv%20kanban&src=typed_query&f=live) don't return anything useful.

I tracked it down on [Github](https://github.com/armedi/bsv-kanban). It hasn't been updated in 4-months and the README says "I made this app to learn how to store data to bsv using moneybutton."

#### Conclusion

I can't find anything else about this project and can't draw any other conclusions than that it is an inactive learning project. 

### 2. Fullcycle

Several Twitter queries don't show anything. A [dead forum link](http://forum.maars.com/viewtopic.php?t=15) I find on Google gives me some clue that it's related to mining, from Google meta data.

I find it on [Github](https://github.com/dfoderick/fullcycle) as well.

>Full Cycle Mining Controller - a workflow message bus microservice architecture for bitcoin mining

The README says it is a monitoring and management system for Bitcoin mining that tracks or does things like "temperature and hash rate of ASIC miners,' 'automatically configure miners with your pool worker accounts,' 'discover new miners on the network,' etc.

![Fullcycle](https://github.com/dfoderick/fullcycle/raw/master/images/FullCycleReact.png?raw=true)

#### Conclusion

It's been 2 years since the last Github commit, which is not necessarily a relevant metric, but I can't find any other information about who is using this project or whether or not it is active.

### 3. Wikisv

~~This is easy because I was at CoinGeek London [thanks to the generosity of Calvin and the help of Ed, and team] when this was announced. ~~

I was wrong as the chart lists BitcoinWiki as well, which is the project I was thinking of. We will cover that later.

One user on [Twitter writes:](https://twitter.com/veganbeefcake/status/1204742328021331969?s=20) "I would happily donate a substantial amount of BSV towards a WikiSV as you described." 

#### Conclusion

I cannot find any useful information on Wikisv. That doesn't mean it doesn't exist, but I don't know where else to look.

### 4. Tocial Chat

Tocial is a Chinese app described as the ['Most Popular Blockchain AGC Photo Social Platform.'](https://tocial.io/) There is not much info on the website and the app links take me to the Apple TestFlight service for beta testers.

It surprises me a service that is in beta would describe itself as 'the most popular' of anything, even if it's in its own category entirely.

I really don't want to download. Is it malware? Will it screw up my phone? Probably not since Apple vets it first, right? Still, I'm worried but I need to be thorough...And at least their [Twitter account is active.](https://twitter.com/tocial_chat)

#### Testing Tocial

I downloaded the app and was prompted to create an account and add some basic personal information. Doing that was easy enough.

When I log in, I see most of the posts made are in Chinese, which isn't surpising. I see @vegard, who is someone I recognize from BSV Twitter has posted a photo of himself. I also see Eli Afram, whom I recognize as well.

The 'Timeline' feature shows a rolling feed of posts that seem to be similar to Instagram's "Discover" feed. There's at least usually a post every day, but seldom many in one day. I don't know if this displays ALL possible posts or just a selection.

Most of the content ranges from, to be blunt, very sexy Asian women to gross BSDM type stuff. There's also a post that says Craig is Satoshi.

#### What I like

Tocial has a neat feature that allows users to upload several photos in a series like Instagram but selectively paywall them with BSV. Users can pay a micropayment, or whatever price set by the owner, to access them instantly.

The paywall seems to mostly be used now for more explicit imagery, but I can imagine something like this being really neat in the future for all types of content creators, not just attractive Asian women.

The app works pretty well. Things load a bit slow as is expected with new apps but the interface is easy enough to follow and I didn't notice anything breaking.

#### What I don't like

It will have a long way to go to gain traction. Sometimes I think it would make more sense to get an existing service to integrate Bitcoin than to replicate one with Bitcoin functionality. The network effects of entrenched social platforms are hard to overcome.

The content is also subpar at best. The women are attractive but I can't imagine spending my days scrolling through the feed for that, and there's really nothing else that's even remotely worth viewing right now.

#### Conclusion

It's a real project. It has a lot of work to do but there's actually some potential here.

### 5. 9k nodes

Once again, it took me a while to find information on this project. According to a video on [The Bitcoin Assocation YouTube channel](https://youtu.be/3Orxl1rKx8Y?t=250), it's a 2d block explorer that shows information in a graph format.

The project looks like it was developed as part of a Hackathon.

The YouTube video links to the [website.](https://9knodes.com/1)

#### Testing it out

It works! And it's actually cool. I can see something like this being more useful than regular block explorers. The way it shows relationships between different data is much more user friendly.

#### What I don't like

I can't find any information on whether or not this is still being developed or any info on the founders. It's also a bit slow and clunky when you open too many data points at once, which is frustrating.

#### Conclusion

It's a neat proof-of-concept. I wish I could find more information. 

### 6. Zakat Network

Zakat is an annual obligatory charitable payment for Muslims, as I understand it. Is this some kind of way to allow Muslims to pay this with Bitcoin SV?

#### Conclusion

I wouldn't know because I can't find ANY information.

### 7. BitcastSV

I already know about BitcastSV because their Twitter account has liked some things I've posted recently. According to their Twitter description:

> The BitCastSV podcast is dedicated to the one and only Bitcoin as described in the Satoshi whitepaper. 

They launched three months ago and have recorded [two episodes on their YouTube channel.](https://www.youtube.com/channel/UCiwOHm0LnbNO1WdU6wxbPVA)

I guess I've got to listen to an [episode...](https://youtu.be/fTVKj1Y2HR0)

#### Conclusion

They have Daniel Krawisz on so the episode is solid. **More people should listen to Daniel.** Daniel rightfully points out that 'speculation' doesn't deserve a bad name. He says a lot of other intelligent things too. And the editing is good!

>The people in BTC thinks that they will succeed by doing what the experts tell them...but that doesn't make sense because if anyone knew what to do to make a lot of money, he wouldn't tell you.

All that said...it's a podcast. I don't really see this as evidence of innovation in BSV. It's more like an add-on and if I were making a chart of the Bitcoin SV Ecosystem, I wouldn't list it, especially one that has only done two episodes in three months.

### 8. ImmortalSV

[ImmortalSV is a web archiving tool](https://immortalsv.com/)that is supposed to take screenshots of websites and archive them on the BSV chain. The idea is to be more immutable than Archive.Today and the Internet Archive.

I have mixed feelings about archive services... on the one hand, they prevent a lot of important information and work from disappearing. On the other hand, I've personally experienced stalkers abusing the archive service with false information. Adding immutability to that might empower them more.

But I'm open to being convinced, and this evaluation is agnostic on the question.

#### Testing it out

I got several error messages and Cloudflare 504 timeouts. It's a neat interface and I know people who have used it successfully, but I tried several browsers and couldn't get it to work.

>Error while fetching website, please try again or contact synfonaut

#### Conclusion

It's a legitimate proof-of-concept project that needs some reliability work.

### 9. Sporstack

[Sporstack](https://sporestack.com/) offers accountless, API-driven VPS hosting for Bitcoin, Bitcoin Cash, Bitcoin SV, and Monero.

This is awesome. I'm sorry to say I'd never heard of it before. There's a lot you can do with it like spinning up servers for a day and running servers for projects that are...against the terms of service.

Here's what they say on their about page.

>Let's say you run a dark web ebook market. The ebooks are full of illegal wrongthink. You're on the run from the Feds and want this market to stay online no matter what. You design it to be self-healing and ephemeral, where your servers buy new ones when they detect their peers have been taken down. They get purchased from funds in the Monero wallet that customers pay into. The servers themselves are torified and don't know where they are. You can do that with SporeStack. You probably won't know how to and maybe only a thousand people in the country could pull it off, but it's doable.
>
>Or maybe you start a masternode hosting service and you configure the masternodes, but you want customers to pay for the servers themselves. You don't want to pay out of your own wallet. You can use SporeStack.
>
>Or maybe you want to spin up servers to run tests as part of your continuous integration. Or even, when you deploy code you get new servers to phase out the old ones. No upgrading, only replacement.
>
>Maybe you just want a server for a day, a month, whatever, and you don't mind that it's not the cheapest option. You feel happier knowing that a potato eating man was paid in the process of you renting a VPS.

#### Testing it out

I don't feel the need to try this one. It's legit.

#### Conclusion

I'm glad to see this project accepting BSV as one of several different currencies. It's not a BSV-specific project however and in fact BSV was one of the last currencies they added. To me, it'd be like saying Coinbase is part of the BSV ecosystem if they add BSV support.

In a broad way, they are, but the chart definitely gives the impression that it is presenting projects that are unique to BSV, or at least primarily in support of BSV, and Sporestack isn't it.

I also find it a little funny that given all the talk about legal compliance in BSV the chart lists a service that very clearly is trying to help at least some people skirt the law.

### 10. My movies

There's a Reddit post about My movies that says ["MyMovies - Signing a Hollywood actress with MoneyButton."](https://www.reddit.com/r/bitcoincashSV/comments/c7m8m4/mymovies_signing_a_hollywood_actress_with/) It links to a YouTube video but the account is [terminated.](https://www.youtube.com/watch?v=jjiiFkYSOXY)

Another Reddit post says ["The Future of Streaming Media is on the BSV Bitcoin Blockchain"](https://www.reddit.com/r/bitcoincashSV/comments/c5zfs1/mymovies_the_future_of_streaming_media_is_on_the/) but it links to a deleted video as well.

So far, nothing.

I finally find an [article on Coingeek](https://coingeek.com/when-craig-wright-met-the-aliens/) about it that describes it as a fan-owned movie studio that helps you distribute your films on the blockchain?

>Mymovies.us – a “decentralized development, finance, production and distribution movie studio ecosystem” or in short, “a fan-owned movie studio”.
>
>Mymovies invites people to fund, secure their rights as creators and distribute their films on the blockchain. Speaking from his home in Silicon Valley, Ted said the idea is to improve on the suggested movies which Netflix presents to its viewers by creating a strip of titles that you’d like to watch if they were made.

#### Testing it out

[MyMovies.us](https://www.mymovies.us/) is the domain! The website looks like an eartly Geocities site or something and says that it is under construction. It also gives a little more info about their backstory.

>THIS SITE IS UNDER CONSTRUCTION:
MYMOVIES.US IS THE BITCOIN ASSOCIATION HACKATHON #1 SEMIFINALIST.
WE ARE CURRENTLY DEVELOPING THE WORLD’S FIRST INTERACTIVE STREAMING MEDIA PLATFORM.
THE FUTURE OF STREAMING MEDIA IS ON THE BSV BLOCKCHAIN.

There are several movies listed as 'in-production' or 'in-development.'

- Lord Timmy and the Mystery of the Last Master

- The Image of the Beast and It Gave Life To

- The Noob: It's Fun and Games Until Someone Gets Hurt

- Night of the Chupacabbra II

- In the Arena: The Joe Kapp Story

There are more but you get the idea.

There is one film that is listed as "streaming now." It's called Mon Blanc a Vendre.

I click and it takes me to a page with a Money Button that says it is 10 cents to unlock. 

It works! A play button appears after I swipe and I can play the movie. 

#### Conclusion

I have no desire whatsoever to watch this movie. It doesn't appear to be "streaming on the blockchain" as was advertised. It's just a paywall to a play button for a movie, which is fine, but that's much less than I expected.

The website is scammy and outdated but there is indeed a movie for sale. I really don't know what to think about this? 

It is actively being worked on? What value does this add to BSV?

I don't know. I don't understand why this was listed.

### 11. BlareSV

This was an easy project to find. It appears to be by the same guy behind The BitcoinSV Channel (RIP YouTube). Here is how it is described on it's [website.](https://www.blaresv.com/)

>BLARE is an innovative, maker-centric social platform for artists and content creators to upload, publish, distribute, price, and sell their exclusive digital content (music, videos, etc.) and physical merch (CD’s, vinyl, clothing, posters, sheet music, books, etc.) at any price to their fans, being paid instantly and fairly in Bitcoin or fiat.

#### Testing it out

I can't. It releases its beta version in June 2020 according to the site.

#### Conclusion

It looks like a neat idea.

### 12. Gemscape

The recently bearded Ryan X.Charles, who I've always respected, introduced me to this when he posted the other day on [Twitter.](https://twitter.com/ryanxcharles/status/1254815371091050503?s=20)

>How can we make Money Button better? We rely on your feedback to guide our priorities. I am paying $5.00 per answer.

Gemscape describes itself like this: 

>Incentivizing feedback. Get thoughtful opinions on what matters to you.
(Or earn BitCoin instantly)

That's cool! I used to be a Quora power-user and this looks a lot better, at least in the basic idea.

#### Testing it out

I tried to use it the day I heard about it to answer Ryan's question, but it wouldn't work for me! I tried again today and was able to answer a question, which was really a survey with a series of questions.

It paid me 13 cents for my answers at the end. Easy enough.

#### Conclusion

It's real and it's a neat proof-of-concept. I didn't notice any major problems. There's some real potential if they run it well and can get good content on it. As I always say with these kinds of sites, network effects are important and a lot of early content is really bad and off-putting. 

I would probably NOT want to be in a business like this personally, but best of luck to the creators. They've definitely made something that could be useful.

### 13. Memorygame

I can't find anything on this project using Google or [Twitter queries.](https://twitter.com/search?q=memorygame%20bitcoin&src=typed_query&f=live)

I try [BSVDevs.com](https://bsvdevs.com/) and can't find it there either.

I really think it would be better to have a PDF report with LINKS to projects instead of a static image with a general name like 'Memorygame.' How am I supposed to find that?

#### Conclusion

I see no evidence this exists or ever existed.

### 14. KwabaSV

I found this easily! It's a simple web wallet. They're active on Twitter and the site is [live.](https://bico.media/b52572081e88233e6ab2ccfa5b8a44d1d969f18e10f25c3631ee4dd37703d41a#)

You can also use the service to upload files (e,g mp3, mp4, pdf's) to the METANET.

#### Conclusion

It's real and it works. It's nothing revolutionary now but it's a nice proof-of-concept.

### 15. BitcoinPong

[I already knew about this!](https://bico.media/1598502b35891e9bb6a66d115f05104b254270085740ebdd02ca36a634ef72d8) BitcoinPong, if I'm thinking of the right one, is a rudimentary pong game hosted on the BSV blockchain. That's pretty cool!

#### Testing it out

It's pong. It's self explanatory. There are five levels and I beat them easily.

#### Conclusion

It's a working proof-of-concept. I don't really know why you'd need this on a blockchain but then again I think you should be able to use the blockchain however you want.

The bigger issue is that this can hardly be considered part of the 'ecosystem' in any important way. Turn it into a real popular game with payouts for winning and other stuff and I'll reconsider.

For now, like I said, it's a proof-of-concept but hardly evidence of Bitcoin SV's progress.

### 16. Trends.Cash

[Trends.Cash](https://trends.cash/) is a tool to visualize application data like popularity on Bitcoin SV. 

#### Testing it out

I typed 'Twetch' into the search bar and it just loaded forever. I don't know if I'm doing something wrong or not, or what the purpose of the search function even is.

#### Conclusion

This is a short review because there isn't much to say. It's simple and it works except for the search function which could be my fault?

There's some interesting data on it and I can see it being more useful if BSV grows.

As with many of the projects I've reviewed so far, it feels like a proof-of-concept.

### 17. MemoSV

Memo.SV is the SV version of Memo.Cash. It's blockchain-based social media for Bitcoin Cash and Bitcoin SV. 

#### Testing it out

I've already used it before way back in the day and it's easy enough to make Twitter-like posts. The design is subpar and the content is mostly a bit spammy. The Bitcoin Cash version is generally of higher quality people and content than the BSV one. 

In fact, among the BSV 'most active profiles,' very few have posted at all in 2020.

#### Conclusion

Censorship-resistant content is important and if blockchain is the best way to do it, let's do it!

I really liked [this bit](https://jasonc.me/blog/what-is-memo) from the creator's website.

>Memo's current functionality is just the tip of the iceberg. Soon you can have your own website forever by paying a one-time fee. No need for registering a domain, paying for servers, or keeping software up to date.

But this isn't currently a unique app to BSV and I can't see much evidence at all that many people are using it or that it has any positive impact whatsoever on the BSV ecosystem.

I don't really know why this is listed.

### 18. MetaNet TV

This is honestly getting exhausting.

MetaNet TV says in its description box: "The MetaNet is currently under construction."

What is MetaNet TV? It appears to be a YouTube/Streamanity (more on that later) channel that talks about Bitcoin SV stuff.

#### Conclusion

The last video was published 5-months ago and there doesn't appear to be much recent activity. I don't know why this was listed because it's basically just a YouTube channel that isn't very active.

### 19. FairBSV

I can't find any information that this exists or what it is supposed to be about other than the WhoIS info which says the url fairbsv.com was registered in October 2019.

### 20. Matterpool

### 21. BSV Camp

I looked up BSV Camp on Google. Their [Twitter account is dead as of this post.](https://twitter.com/bsvcamp)

Their website is also [dead.](https://www.bsvcamp.com/)

The description in the meta data says...

>Workice CRM is a web based invoicing and project management tool for freelancers and small businesses. Create and send invoices and estimates, track deals,

#### Conclusion

It's a dead project and probably never got off the ground.

### 22. RunRunRun

There's a [Medium blog](https://medium.com/@bsvrun/runrunrun-io-game-rule-2fde6d524137) that says "RUNRUNRUN.IO is the first runner lottery game base on BSV bloackchain."

Looking at their [Twitter feed,](https://twitter.com/bsvrun/status/1210457654767697921?s=20) they appear to have had some kind of working product at one point.

But the [website is not loading for me and looks dead.](runrunrun.io)

#### Conclusion

It's a dead project that had some working product at some point, but I can't really tell what.

### 23. Satoplay

### 24. Todos

I can't find any information on this at all.

### 25. Voxel SV

[3d drawing app on the BSV blockchain.](https://connor.software/bsv-voxels/)

The Github project offers a good [description.](https://github.com/connorgaskell/bsv-voxels)

>Voxel drawing application built on BitCoin SV. The position and colour data for each voxel is stored within a transaction on the BSV blockchain, as is the data for deleting a voxel at a specified position.
>
>If you want to try it out you'll need a small amount of BSV, roughly $0.01 worth will allow you to perform 20 actions. You will need to wait 1 BitCoin block, approximately 10 minutes before you can start placing voxels after funding your account. This is due to the unconfirmed transaction limit being currently set at 25, therefore the application splits your UTXO's after receiving the initial funds, this will allow you to place and remove far more voxels per BitCoin block.

### 26. Moneytrain

This is some kind of multiplayer game, but I can't get it to work. The [website](https://game.moneytrain.io/) is live but I get stuck on the create new character screen, which won't load properly.

#### Conclusion

I don't know whether it's a broken project or not. It looks like it could be a good idea.
