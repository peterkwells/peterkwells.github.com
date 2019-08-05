---
title: Open your effing data
description: 'Warning: this post contains content that will be offensive to some people.'
date: '2017-07-02T18:50:49.383Z'
categories: []
keywords: []
slug: /@peterkwells/open-your-effing-data-de5b6e57f63e
---

_Warning: this post contains content that will be offensive to some people._

_The post is a version of talk I gave at the_ [_ODIFridays series of lectures_](https://theodi.org/events) _at the HQ of the_ [_Open Data Institute_](https://theodi.org) _in London. The slides and a video of the talk are at the end of the post. Like most of my talks I adlibbed a bit. The post has links to most of the material I adlibbed from, others are at the end of the slides. It includes some thoughts on swearwords, Roger Mellie, democracy, censorship, Blackpool FC, artificial intelligence, context and an apology to my mum._

One of the UK’s regulators, Ofcom, commissioned research on offensive language last year. The research got lots of headlines. It was a nice opportunity for papers and websites to make cheap gags about swear words.

![A [report from the Metro on the publication of the report](http://metro.co.uk/2016/10/02/swearing-ranked-from-mild-to-strongest-6165629/).](https://cdn-images-1.medium.com/max/600/1*J8sOGA2XjX_NRQ5eydugxw.png)
A [report from the Metro on the publication of the report](http://metro.co.uk/2016/10/02/swearing-ranked-from-mild-to-strongest-6165629/).

But it also gave me an opportunity to open up some swear word data and to use that example to talk with people and think about things like democracy, censorship, context and artificial intelligence. I made some cheap gags about swear words too.

#### Data needs context

Ofcom published the research in [an openly licensed 126-page document](https://www.ofcom.org.uk/__data/assets/pdf_file/0022/91624/OfcomOffensiveLanguage.pdf) and [a 15-page quick reference guide](https://www.ofcom.org.uk/__data/assets/pdf_file/0023/91625/OfcomQRG-AOC.pdf).

![from the [report](https://www.ofcom.org.uk/__data/assets/pdf_file/0022/91624/OfcomOffensiveLanguage.pdf) that Ipsos Mori did for Ofcom](https://cdn-images-1.medium.com/max/600/1*lTeAMydUZDf8siXU-cdb7Q.png)
from the [report](https://www.ofcom.org.uk/__data/assets/pdf_file/0022/91624/OfcomOffensiveLanguage.pdf) that Ipsos Mori did for Ofcom

The newspapers extracted the data from the PDF to write their stories. I extracted the data too. (btw [some work that our friends at ODI Leeds and Adobe are doing might make my cut and pasting easier in the future](http://odileeds.org/blog/2017-04-19-Open-Data-and-PDFs)…)

Unfortunately at first I missed the all important context for the data. I discovered the mistake by checking my data with the helpful team at Ofcom.

![[Take a look at the data](https://peterkwells.github.io/uk-attitudes-to-offensive-language-and-gestures-data/data/list-of-swearwords-and-offensive-gestures/) or if you want to use it in a project or service there’s a [CSV in github](https://github.com/peterkwells/uk-attitudes-to-offensive-language-and-gestures-data).](https://cdn-images-1.medium.com/max/600/1*1r4Zx_UbrHyb8_ymyKwScg.png)
[Take a look at the data](https://peterkwells.github.io/uk-attitudes-to-offensive-language-and-gestures-data/data/list-of-swearwords-and-offensive-gestures/) or if you want to use it in a project or service there’s a [CSV in github](https://github.com/peterkwells/uk-attitudes-to-offensive-language-and-gestures-data).

After some discussion within the ODI and with Ofcom’s research team we ended up with [this](https://peterkwells.github.io/uk-attitudes-to-offensive-language-and-gestures-data/data/list-of-swearwords-and-offensive-gestures/). The same data as the PDF but in a format that is both human and machine readable.

Now, a big part of our job at the [Open Data Institute](https://theodi.org) is “getting data to people who need it”. Normally I start with problems but this time I had started with data. My bad. Now to find out who needed it and how they would use it.

#### Some of the things people use this swear word data for

As I put the data out on twitter there was a background mantra of “arse…balls….knob…bastard…” from around the office. One person then wrote [a little script that people could use to get their computers to say the list of words](https://gist.github.com/pikesley/d2eaa794703c529be4f1b377f64004df). Soon I could hear both human and machine voices swearing away. The swearing mantra was charming, if a little unsettling, but I had my serious face on. Why do people swear?

Well a bit of research showed an [academic saying](https://www.mcla.edu/Assets/MCLA-Files/Academics/Undergraduate/Psychology/Pragmaticsofswearing.pdf):

> The main purpose of swearing is to express emotions, especially anger and frustration.

Seems fair. I suspect that a lot of people get frustrated at not being able to get data they need to do something. That explained the background mantra from the Open Data Institute office, but what about other uses of the data?

![[Roger Mellie](https://en.wikipedia.org/wiki/Roger_Mellie), copyright Viz. Note that the swear word data might allow people to block his language, but not his gestures.](https://cdn-images-1.medium.com/max/600/1*R1Ij7ShOAtzfSn8dr9cOAw.png)
[Roger Mellie](https://en.wikipedia.org/wiki/Roger_Mellie), copyright Viz. Note that the swear word data might allow people to block his language, but not his gestures.

The content of the report told us about some other users. It would help TV broadcasters and presenters understand how people would react to things that they said on air and so help the presenters decide what they could say.

For example the word “bollocks” was seen as somewhat vulgar if it referred to testicles but less problematic if it was being used to call something ‘nonsense’.

This might mean that people did or did not say words in certain contexts. It might lead to some content only being accessible if a PIN was entered to unlock it.

#### This data was created because of democracy

![Democratic processes can need data to be created. Image [Nick Youngson](http://nyphotographic.com/), CC-BY-SA-3.0 via [http://thebluediamondgallery.com/d/democracy.html](http://thebluediamondgallery.com/d/democracy.html)](https://cdn-images-1.medium.com/max/600/1*n7YNR6kaZaccmJ99jrnG_w.png)
Democratic processes can need data to be created. Image [Nick Youngson](http://nyphotographic.com/), CC-BY-SA-3.0 via [http://thebluediamondgallery.com/d/democracy.html](http://thebluediamondgallery.com/d/democracy.html)

But the biggest user of the report is [Ofcom](https://hackernoon.com/tagged/ofcom) themselves. Ofcom commissioned the research because through our democratic processes we have decided that there are limits to free speech on TV & radio and made it Ofcom’s [job](https://www.ofcom.org.uk/about-ofcom/what-is-ofcom) to regulate those limits. They needed the data to help with this job so Ofcom commissioned [Ipsos MORI](https://www.ipsos.com/ipsos-mori/en-uk/) to produce the data by performing user research through [focus groups, interviews and follow-ups based on a long list of potentially offensive words and phrases](https://www.ofcom.org.uk/__data/assets/pdf_file/0022/91624/OfcomOffensiveLanguage.pdf).

We have given Ofcom the power to [fine organisations and people that breach their codes](https://duckduckgo.com/?q=ofcom+fine+offensive+language&bext=msl&atb=v58-4&ia=web). By publishing the report openly, they were helping broadcasters understand how they might use those powers and therefore discouraging breaches. This probably makes the system cheaper and more effective.

Broadcasters are likely to have their own guidance to help them meet the expectations of their target audiences. They could merge Ofcom’s list with their own list to help them meet both society’s needs and their own user’s needs.

#### Similar data is maintained in contexts outside of TV and radio

![In Britain [Mary Whitehouse](https://en.wikipedia.org/wiki/Mary_Whitehouse) was a famous campaigner from the 1960s to the 1980s against things that she found offensive. I can imagine Mary being keen on data-driven censorship. Image fair use via Wikipedia.](https://cdn-images-1.medium.com/max/600/1*iewNktNz0j3kBSC722nnkQ.png)
In Britain [Mary Whitehouse](https://en.wikipedia.org/wiki/Mary_Whitehouse) was a famous campaigner from the 1960s to the 1980s against things that she found offensive. I can imagine Mary being keen on data-driven censorship. Image fair use via Wikipedia.

The data includes the word ginger saying it is ‘mild language, generally of little concern’, but the word ginger can also be used to describe a [very tasty type of biscuit](https://en.wikipedia.org/wiki/Ginger_snap). A filter that used the swear word data to block offensive words might ban ginger nuts. That would be bad. This is a common problem with simple data-driven solutions. They ignore context.

I couldn’t find a list of offensive biscuit names but there are other sets that are similar to the swear word data used in contexts other than TV and radio.

#### The UK has a list of suppressed car registration plates

It is the job of part of the UK government, the [DVLA](https://www.gov.uk/government/organisations/driver-and-vehicle-licensing-agency), to maintain a list of combinations of letters and numbers that you cannot put on a car. Unfortunately, and curiously, the list is not published openly, but sometimes it is made available after freedom of information requests.

![An extract from the suppressed car registration plate list via [Whatdotheyknow](https://www.whatdotheyknow.com/request/numberplate_blacklist#incoming-548093)](https://cdn-images-1.medium.com/max/600/1*HPvOycl98JKFGZs4bslZeQ.png)
An extract from the suppressed car registration plate list via [Whatdotheyknow](https://www.whatdotheyknow.com/request/numberplate_blacklist#incoming-548093)

The list of suppressed car registration plates helps prevent confusion over typographically similar symbols, like o (zero) and 0 (oh). It blocks language that is likely to be considered offensive, for example “\*B\*\* UMS” and “\*R\*\*APE\*\*”.

The list also explicitly contains the [names of terrorist groups](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/612076/20170503_Proscription.pdf) such as the UVF, UDA and UFF. Another terrorist organisation, the IRA, are already banned, like any other organisation beginning with I, because of the potential for confusion between 1 (one) and I (aye).

More controversially the acronym for the far-right [British National Party](https://en.wikipedia.org/wiki/British_National_Party), BNP, is also on the list. The BNP are allowed to stand in the UK’s democratic election process. How was that decision made? Unfortunately just as the list isn’t publicly available neither is the methodology.

#### Context affects what words are offensive

The UK’s democratic processes produce others lists of offensive words.

The speaker in the UK’s parliament can request that politicians withdraw words when debating with their opponents, so called unparliamentary language. The way in which words are deemed to be unparliamentary or not are unclear. In 2015 the opposition leader Ed Milliband was [allowed to call the then Prime Minister David Cameron “dodgy”](https://www.theyworkforyou.com/debates/?id=2015-02-11d.769.0), yet in 2016 an opposition backbencher [Dennis Skinner was asked to leave a debate because he called David Cameron “dodgy Dave”](https://www.buzzfeed.com/emilyashton/dodgy-dave?utm_term=.rrzo4plZL#.vqY5Pz9xB). The word “dodgy” isn’t on Ofcom’s list, it’s offensive to call an MP “dodgy” in a parliamentary debate but not to call them it on television.

The [list of unparliamentary langauge is currently unpublished](https://hansard.parliament.uk/Commons/2012-10-17/debates/12101767000001/ParliamentaryLanguage). To help UK politicians make better decisions about being unparliamentary or not I [compiled some examples into a list](https://peterkwells.github.io/unparliamentary-language/). Parliaments in other countries, and [other UK nations](https://en.wikipedia.org/wiki/List_of_counties_of_the_United_Kingdom), have similar lists. They show the importance of geographic context.

The [Australian parliamentary records](https://github.com/wragge/hansard-language) show offense was taken against the term “[suck-holing](http://www.thefreedictionary.com/suckholing)”, a word that in 1977 was decided to be offensive in the Australian parliament but that will be meaningless to most British people and has [never been used in the British parliament](https://hansard.parliament.uk/search?searchTerm=suck-holing). I wonder if a British MP would get away with using it.

![The word “Oyston” is offensive to me and my community of fans of Blackpool football club. The offensiveness is not only because of this cringeworthy picture but because of how the Oyston family treats fans.](https://cdn-images-1.medium.com/max/600/1*0lKT4hlk1X6i8Q0uPjUDZQ.png)
The word “Oyston” is offensive to me and my community of fans of Blackpool football club. The offensiveness is not only because of this cringeworthy picture but because of how the Oyston family treats fans.

Another example of offensive language in a particular context is the word “Oyston”.

The Oyston family own the football club that I support, Blackpool FC. Because of their [actions against fans](https://medium.com/@peterkwells/they-dont-get-it-f8624b6bde06) being called an Oyston fan on one of the [website](http://fansonline.net/blackpool/mb/index.php)s [used](http://www.backhenrystreet.co.uk) by Blackpool fans would be offensive. How would anyone outside of the community of Blackpool fans discover this?

There are related examples that may help us understand how we could do this.

#### Collaborative maintenance of data

[Hatebase](https://www.hatebase.org/about) maintains a list of hate speech from around the world. The data is maintained by automated processes and manual interaction to cater for how hate speech changes over time and in different places. Hate speech can be used to encourage violence against people and communities. The collaborative maintenance process allows people to debate which words are hate speech or not.

![“popular” types of hate speech from [Hatebase](https://www.hatebase.org/popular).](https://cdn-images-1.medium.com/max/600/1*0A-_5_WDVsYZLqs0G43Ttg.png)
“popular” types of hate speech from [Hatebase](https://www.hatebase.org/popular).

An interesting experiment would be to see if the hatebase dataset could have helped predict violent events through rises of hate speech in parliaments, newspaper and social media. [Do get in touch with them if you have money to fund that research](https://www.hatebase.org/contact).

Other people could learn from the example of Hatebase. If British politicians wanted, and could get to grips with github, then they could [collaboratively maintain my initial list of unparliamentary language](https://github.com/peterkwells/unparliamentary-language/blob/gh-pages/data/a-list-of-unparliamentary-language-used-in-parliaments.csv) and create something that would help them understand the boundaries of offensiveness.

#### Offensiveness is affected by time, place and communities

![[Rebecca Roache in Aeon magazine](https://aeon.co/essays/where-does-swearing-get-its-power-and-how-should-we-use-it).](https://cdn-images-1.medium.com/max/600/1*co5tcKFC0IHilM8sO1--yQ.png)
[Rebecca Roache in Aeon magazine](https://aeon.co/essays/where-does-swearing-get-its-power-and-how-should-we-use-it).

By this point in my own research I was clear that the context of offensiveness is affected by time, place and communities.

When I checked I found that [swearing philosophers were, of course, already aware of this](https://aeon.co/essays/where-does-swearing-get-its-power-and-how-should-we-use-it). As often happens I was a technologist rediscovering ground that others had already covered. But technology can also affect how and which words become offensive.

#### People create new offensive words

Oyston is an example of a word that became offensive to a small group of people before becoming offensive to a larger group. Blackpool fans have effectively used social media and the press — oh, and talks & blogposts like this ;) — as part of a campaign to get the Oyston family out of our football club. An effect of this has been to spread the understanding of the offensiveness of the Oystons from the seaside to wider parts of the footballing community. A more famous example is the case of Rick Santorum who found his surname [defined as an offensive word in a campaign led by Dan Savage](https://en.wikipedia.org/wiki/Campaign_for_the_neologism_%22santorum%22).

This is a challenge to any list of swear words and a risk for people who use them. People create new offensive words for their own purposes. They game systems.

![A t-shirt with the [universally unique identifier for beef curtains](https://github.com/peterkwells/uk-attitudes-to-offensive-language-and-gestures-data/blob/gh-pages/data/list-of-swearwords-and-offensive-gestures.csv).](https://cdn-images-1.medium.com/max/600/1*fklPGSghf_zvRpoDJPAQaQ.png)
A t-shirt with the [universally unique identifier for beef curtains](https://github.com/peterkwells/uk-attitudes-to-offensive-language-and-gestures-data/blob/gh-pages/data/list-of-swearwords-and-offensive-gestures.csv).

Would people game the swear word data I created from Ofcom’s list? Yes, of course they would.

An example quickly came to mind. When I published the Ofcom offensive word list as open data then in line with good practice I gave every entry a [universally unique identifier](https://en.wikipedia.org/wiki/Universally_unique_identifier) (UUID). UUIDs make it easier for machines to use the data.

If this data was to get widely used then how long would it be before people started to circumvent the system by being interviewed on telly wearing t-shirts with the UUID of a swear word? Perhaps over time the UUIDs, or parts of them, would become offensive? “That fella’s a right 81cb.“, they’d say. Maybe the UUIDs would need to be added to the list as they became offensive?

People adapt and change. That is one of the best things about people and one of the biggest challenges we face when maintaining and using data. We need to build in mechanisms to change datasets over time as needs and uses change.

#### Swear words-as-a-service is hard

It is clear that swear word data was easy to build and also clear that it would be more difficult to maintain and make it useful in multiple contexts.

I knew that many companies were already maintaining similar lists as, like many other people, I had seen, laughed and evaded filters on websites that had turned the British town of Scunthorpe into the apparently inoffensive “S\*\*\*horpe” due to simplistic and bad data-driven algorithms. I do wonder how useful those filters and services are.

Many of the website filters I had seen are simple and flawed because of the lack of context and their inability to adapt to people’s changing behaviour but thinking ahead I wondered if people would start to apply machine learning / artificial intelligence (ML/AI) and create services that could automatically learn new swear words? Perhaps this could be used on a massive scale to reduce the damage caused by offensive language on the web?

![A couple of snippets from [this patent](https://www.google.ch/patents/US20150309987)](https://cdn-images-1.medium.com/max/600/1*9Z9fL2KqHYfu56rFD1fqXQ.png)
A couple of snippets from [this patent](https://www.google.ch/patents/US20150309987)

I knew that I wouldn’t be the first person to think of this idea. While 2016 had been the year when every problem could be fixed with a blockchain, 2017 is the year of ML/AI.

A quick search of patent libraries showed that in 2015 Google had registered [a patent to classify offensive words using machine learning](https://www.google.ch/patents/US20150309987). Unfortunately it looks rubbish. The training mechanism worked on a large set of text samples, it failed to recognise the context in which the text was being used. The resulting service might be slightly better than current filters but would still be data-driven rather than informed by data.

Maybe, like Hatebase, it would help if users were to train the machines that provided the service. After all Google, like most other large internet companies, use [thousands of people](https://arstechnica.co.uk/features/2017/04/the-secret-lives-of-google-raters/) — including you — to help train their services. I started to consider what I had learn about offensive language and think of the tasks that Google would need to give to swear word raters to train their machine:

> **Task**: go to a football ground in Gdansk, Poland. Play this video to people near you. Observe their attitude to you, and each other, over the following seven days and then categorise the offensiveness of the video. Repeat this exercise every 3 months.

Hmm… I quickly realised that this might be a [Quixotic](https://www.gutenberg.org/ebooks/2000) mission and that AI/ML might provide a better service but still only a partial one. There would be no perfect service. People decide what is offensive, not machines. If the service only considered some contexts then the people who controlled the machines and trained them on those contexts would be the ones who decided where it was useful. Swear word data isn’t like the location of bus stops or the list of transactions in a bank account. The context is even more important.

This is one of the challenges of the web and providing data and services for it. The web is pervasive. It interacts with the physical world in many places. It appears in multiple contexts. I use the web to watch broadcast news, like that regulated by Ofcom. I use it keep up to date on politics, where the unparliamentary rules are useful. I talk about football, and the Oystons, on message boards. I keep up to date on current affairs, and feel helpless at the levels of hate speech deployed at people in the UK and abroad. I chat to friends, both publicly on sites like Twitter and Facebook and also privately in messaging applications.

Datasets and services that reduce offensive content on the web will need to cater for all of these different contexts, and more. Even if they do, some people will still work around them. Data and technology may be able to help the problem but it will only ever be part of a solution to something that is fundamentally a more human problem. Our need to express our emotions in language.

#### Sorry mum

It was clear from my investigations that we could usefully create data about swear words, i.e. words that are offensive. That the need for this data came from people who swear, people who didn’t want to swear and societies & communities trying to decide the boundaries between what was offensive or not. That it would be useful if the research and rules for deciding on what was offensive were open. And that if people could collaborate to decide on what was offensive that the data would be more useful because it would cater for more contexts. But it was also clear that while technology creates new possibilities to reduce offensiveness that people will still adapt to achieve the goal they want. [So it goes](https://en.wikiquote.org/wiki/Slaughterhouse-Five).

The other thing that was clear from the talk was mine and my audience’s squeamishness with some of the words. In my case it was certainly because of one of my most important contexts: my upbringing and my family. I’d like to end this post the same way I ended the talk by apologising to my mum. Sorry mum.

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — -

#### The questions from the audience showed the importance of context

At the end of the talk at the ODI the audience raised several points about offensive language that had not been covered in the talk, such as the use of racial and religious slurs. I was already covering a wide topic. Racial and religious offensiveness cover even more ground. I couldn’t cover everything.

![Image from [The Wanderers](https://en.wikipedia.org/wiki/The_Wanderers_%281979_film%29), based on a book by [Richard Price](https://en.wikipedia.org/wiki/Richard_Price_%28writer%29). The film includes [a fantastic scene](https://www.liveleak.com/view?i=29a_1427692583) in a 1960s New York school where people of different religions and ethnicity try, and fail, to remember all of the offensive names they have for each other.](https://cdn-images-1.medium.com/max/600/1*Syy9FwjutVudd1P-0epgKQ.png)
Image from [The Wanderers](https://en.wikipedia.org/wiki/The_Wanderers_%281979_film%29), based on a book by [Richard Price](https://en.wikipedia.org/wiki/Richard_Price_%28writer%29). The film includes [a fantastic scene](https://www.liveleak.com/view?i=29a_1427692583) in a 1960s New York school where people of different religions and ethnicity try, and fail, to remember all of the offensive names they have for each other.

I did find it interesting that the audience in the room hadn’t heard of some of the words in the list. Particularly [choc ice](http://www.urbandictionary.com/define.php?term=choc+ice), [blood claat](http://www.urbandictionary.com/define.php?term=bloodclaat) and [bum claat](http://www.urbandictionary.com/define.php?term=bum%20clat), words that in my — white, middle class, mostly Northern England and South London experience — are used against black people or in black communities. In the case of the latter two more specifically within Jamaican communities.

That people hadn’t heard of these words says something about the context of the audience. A context where those words may not have been seen as offensive. Perhaps next time I talk on this topic I should try and sneak in some offensive language from different contexts to see what happens.

#### Watch the original talk or read the slides

If you want you can watch a recording of the talk (which includes some swear-a-long fun):

You can also see the presentation on [slideshare](https://www.slideshare.net/peterkwells/open-your-effing-data-presentation-2017) or [google slides](https://docs.google.com/presentation/d/1R-Od3xvxTPgILY1dpbyHfHiG2ujTuP-Qc5C18xkAbBQ/edit#slide=id.g1f4b8421a4_0_0), whichever your prefer.

[![](https://cdn-images-1.medium.com/max/400/1*0hqOaABQ7XGPT-OYNgiUBg.png)](http://bit.ly/HackernoonFB)
[![](https://cdn-images-1.medium.com/max/400/1*Vgw1jkA6hgnvwzTsfMlnpg.png)](https://goo.gl/k7XYbx)
[![](https://cdn-images-1.medium.com/max/400/1*gKBpq1ruUi0FVK2UM_I4tQ.png)](https://goo.gl/4ofytp)

> [Hacker Noon](http://bit.ly/Hackernoon) is how hackers start their afternoons. We’re a part of the [@AMI](http://bit.ly/atAMIatAMI) family. We are now [accepting submissions](http://bit.ly/hackernoonsubmission) and happy to [discuss advertising & sponsorship](mailto:partners@amipublications.com) opportunities.

> If you enjoyed this story, we recommend reading our [latest tech stories](http://bit.ly/hackernoonlatestt) and [trending tech stories](https://hackernoon.com/trending). Until next time, don’t take the realities of the world for granted!

![](https://cdn-images-1.medium.com/max/2560/1*35tCjoPcvq6LbB3I6Wegqw.jpeg)