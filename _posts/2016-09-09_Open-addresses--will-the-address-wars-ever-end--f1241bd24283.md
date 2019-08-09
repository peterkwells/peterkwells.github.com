---
title: Open addresses: will the address wars ever end?
categories:
- General
feature_image: "https://www.nasa.gov/sites/default/files/images/562317main_PIA14033_full.jpg"
---

This is the (rough) text of a talk I gave at the [British Computer Society (BCS) Location Information Specialist Group’s 3rd annual addressing update seminar](http://www.bcs.org/content/conEvent/10494) in August 2016. There were more jokes in person. And some Pikachu. The [slides for my talk are also online](http://www.slideshare.net/peterkwells/bcs-address-seminar-open-addresses) _as are_ [those for Ant Beck’s talk](https://github.com/AntArch/Presentations_Github/tree/master/201609_UtilityAddresses_Presentation).

<!-- more -->

Hi, I’m Peter. I do some stuff at the [Open Data Institute](http://theodi.org) (ODI). The ODI was founded three years ago. It’s mission is to connect, equip and inspire people around the world to innovate with data. Its headquarters are in the UK but it works around the [world](http://theodi.org/our-network).

I’m here to talk about open addresses in the UK. To understand the tale it’s useful to start off with a (shortened) bit of history.

### Ancient history…

Addresses and other types of geospatial data were early targets for [open data](https://hackernoon.com/tagged/open-data) releases. They are vital datasets that make it possible to build many, many services and products. Way back in 2006 [Charles Arthur and Michael Cross wrote in the Guardian](https://www.theguardian.com/technology/2006/mar/09/education.epublic) to ask the UK government to “give us back our crown jewels”. They pointed out the complex arrangements for [maintaining](https://hackernoon.com/tagged/maintaining) address data and how the data was sold to fund those complex arrangements. They even pointed out the issues it generated for the 2001 census.

In [2009 the UK government announced that Tim Berners-Lee, one of the ODI’s founders, was going to help it open up data](https://www.theguardian.com/technology/2009/jun/10/berners-lee-downing-street-web-open) and in 2010 government said that [postcodes and address data were going to be early releases](http://news.bbc.co.uk/1/hi/technology/8402327.stm). Victory!

![Some of the tales from 2013](https://cdn-images-1.medium.com/max/600/1*q7vJGuS3iBgGF-2PpqBpZQ.png)
Some of the tales from 2013

But it was a pyrrhic victory. Whilst [government](https://hackernoon.com/tagged/government) released many thousands of datasets the promised address data was not one of them. In 2013 the Royal Mail was privatised along with its rights to help create and sell that address data. The complex arrangements that were pointed out in 2006 just got more complex. And, in the meantime, [another census happened with the inevitable, and costly, need to build another new address list](http://www.ons.gov.uk/ons/guide-method/census/2011/how-our-census-works/how-did-we-do-in-2011-/evaluation---address-register.pdf).

The [open data community was rightly sad](http://www.telegraph.co.uk/news/uknews/royal-mail/9994741/Everyones-postcodes-to-be-privatised-in-Royal-Mail-flotation-despite-objections-from-Sir-Tim-Berners-Lee.html), and probably got a bit angry. [They knew how important that data was](http://theodi.org/news/paf-decision-flies-face-government-commitments-odi). They kept working to make things better. They didn’t just tweet, they organised.

### More recent history…

In 2014 the [Cabinet Office’s release of data fund](https://data.blog.gov.uk/2014/06/26/funding-agreed-for-important-new-open-data-projects/) provided some money to the ODI to [explore whether it was possible to rebuild the UK’s address list and publish it as open data](http://theodi.org/blog/open-addresses-discovery-phase). The ODI pulled together [lots of people who work with addresses to share and debate ideas](https://theodi.org/blog/the-open-addresses-symposium).

![The homepage of [Open Addresses](https://alpha.openaddressesuk.org)](https://cdn-images-1.medium.com/max/600/1*rQbTFAvSU6fbjCED1N-CZQ.png)
The homepage of [Open Addresses](https://alpha.openaddressesuk.org)

This led to the [launch](https://theodi.org/news/free-and-open-address-list-launches-today-open-addresses-uk-calls-for-individuals-and-organisations-to-get-involved) of [Open Addresses UK](https://alpha.openaddressesuk.org/). I was one of the team working for Open Addresses. We worked as openly as possible with regular [blogs](https://alpha.openaddressesuk.org/blog) and [open source code](https://github.com/openaddressesuk).

We explored the benefits of better address data for the UK. We found that we could help fix problems such as the [months it can take before new addresses are added to computer systems across the country](https://alpha.openaddressesuk.org/blog/2015/02/09/living-breathing-problem). Months during which someone might not be able to order a pizza, get home insurance or register to vote. We looked at the economic evidence from case studies of other countries, such as Denmark, that have released address data as open data. If [the success of Denmark scaled in proportion to the population of the country then the UK could expect to see an extra £110 million a year of social and economic value](https://alpha.openaddressesuk.org/mission/benefits). Value that we don’t get at the moment because [paid data creates less economic value than open data](http://theodi.org/research-economic-value-open-paid-data).

We looked at funding models. We started off with [£383k of funding from the Cabinet Office](http://theodi.org/news/383k-government-grant-released-to-create-uk-open-address-list). We got some [extra funding from BCS](https://alpha.openaddressesuk.org/news/2015/04/20/bcs-press-release) (thank you). We knew that we would need to be able to show people what our services would look like before we could start bringing in funding from the users of address services.

From talking with potential users of those services we learnt about the challenges of address entry on many websites. [User research supported our theory](https://alpha.openaddressesuk.org/blog/2015/05/13/free-format-user-research) that moving to free-format address entry would both make life easier for many people and lead to better quality address data going into organisations. We built a [working demo of that service](https://alpha.openaddressesuk.org/blog/2015/01/23/give-our-sorting-office-a-try).

We knew we needed to gather address data. Following on from the discovery phase we built [a model that would allow any organisation or individual](https://alpha.openaddressesuk.org/developers/addingdata) to contribute their own address data; that would allow anyone to add large sets of open data containing addresses if they followed guidelines and confirmed that they were legally allowed to publish that address data as open data; and put in place a takedown policy to investigate and remove any infringing data. For the legally minded, [we were set up to host the data](http://www.out-law.com/page-431). This was important. In the past [people had been threatened with legal action by the Royal Mail over address data](http://blog.okfn.org/2009/10/05/ernest-marples-uk-postcode-site-has-been-taken-down/) and the hosting model provided a defence.

Unfortunately we hit a snag.

![Digital cholera makes me sad.](https://cdn-images-1.medium.com/max/600/1*0DW5zWTeia3wVquvvF0qhQ.png)
Digital cholera makes me sad.

We learned that one of the largest open data sets held by government was tainted by what we called ‘digital cholera’. It [contained third party rights that government was not authorised to licence as open data](http://mapgubbins.tumblr.com/post/107499166390/it-was-all-a-dream-land-registrys-price-paid). This was no good. We wanted to [publish address data that was safe to use](https://alpha.openaddressesuk.org/blog/2015/01/26/making-address-data-safe).

We didn’t want to spend the limited grant funding on more and more legal advice or court battles (sorry lawyers…). So we concentrated on other approaches.

We used clean open data sets and statistical techniques to [multiply the address data](https://alpha.openaddressesuk.org/blog/2015/02/12/inference) we already had. For example, “if house number 1 exists and house number 5 exists then house number 3 probably exists”.

We started developing [a collaborative maintenance model](https://alpha.openaddressesuk.org/about/collaborative-maintenance). People could use our address services to both improve their own services and improve the address data that everyone was using. The model would enable us to learn and publish new address information (such as [alternative addresses — like Rose Cottage rather than 8 Acacia Avenue](https://alpha.openaddressesuk.org/blog/2015/04/28/better-addresses-3) and new addresses) as people started to use them. This would increase the speed of publishing new information and improve data quality. By crowdsourcing data through APIs the data would get better as more people used it.

The team recognised that these new ways of collecting address data would impact on confidence. So, we started developing [a model that would allow the platform to declare a level of confidence in each address](https://alpha.openaddressesuk.org/blog/2015/02/20/confidence%20%20). The model allowed for different levels of trust based on how frequently we’d seen an address, who reported it, and how long ago they’d reported it. Data users could use the [APIs to determine confidence and choose whether to trust an address](https://alpha.openaddressesuk.org/blog/2015/02/20/confidence) for their particular use case.

But all this time the clock was ticking. There was limited funding. From the beginning we knew that we were testing two hypotheses.

![Two hypotheses. Both are true.](https://cdn-images-1.medium.com/max/600/1*ubKJfci8SRvyPgzN9wxBWQ.png)
Two hypotheses. Both are true.

Unfortunately we discovered that both hypotheses were true. We could build much better address services using modern approaches, but the intellectual property issues would keep hindering us.

A report was published: to [share the lessons of what worked, and what didn’t](http://theodi.org/case-studies/open-addresses-the-story-to-date). As you’ll see in the report even with all of our mitigations against intellectual property violations in place, Open Addresses was only able to find one insurer who would provide it with cover for defence against Intellectual Property infringement claims. The insurers were too concerned that the Royal Mail would take legal action to protect their revenues from address data.

A blog was published about [the shades of grey in open data](http://theodi.org/blog/shades-of-grey-in-open-data). And then Open Addresses [went to sleep](https://alpha.openaddressesuk.org/blog/2015/07/27/a-time-for-going-to-bed).

Someone else would have to take up the challenge of opening up address data and making things better for everyone.

### Meanwhile…

While Open Addresses was happening so were other things. Lots of things. I’m obviously interested in the data ones.

The ODI was thinking about [who owned our data infrastructure](http://theodi.org/who-owns-our-data-infrastructure%20). Data is infrastructure to a modern society. Just like roads. Roads help us navigate to a location. Data helps us make a decision.

![Spot the infrastructure in this excellent picture by [Paul Downey.](https://gds.blog.gov.uk/2015/09/01/registers-authoritative-lists-you-can-trust/)](https://cdn-images-1.medium.com/max/600/1*CtVvof0ePvsnUuSj0yWaqg.png)
Spot the infrastructure in this excellent picture by [Paul Downey.](https://gds.blog.gov.uk/2015/09/01/registers-authoritative-lists-you-can-trust/)

The government was also working on its policy of government-as-a-platform. [Companies House were opening up their data and putting it on the web](https://gds.blog.gov.uk/2015/06/22/congratulations-companies-house/). The Land Registry described itself as [a steel thread](https://gds.blog.gov.uk/2015/07/24/building-on-the-steel-thread/) that we could all build on.

Things started to come together with the description of [registers as authoritative list that we could all trust](https://gds.blog.gov.uk/2015/09/01/registers-authoritative-lists-you-can-trust/). We could all build things on top of government’s open registers.

Registers are data infrastructure. An important part of data infrastructure is geospatial data, like addresses.

### Now

In the 2016 budget it was announced that [government had allocated £5m to explore options to open up address data](https://www.gov.uk/government/speeches/geoplace-conference-matt-hancock-speech).

It is important to understand that this is about _exploring options._ As Open Addresses had learnt UK addresses are pretty complex. We have [centuries of legacy](http://www.huffingtonpost.co.uk/jeni-tennison/a-brief-history-of-open-a_b_6485628.html) to deal with.

Matt Hancock, who was the Minister for the Cabinet Office when the announcement was made, likened it to the ‘[US administration (decision) to allow GPS data to be made freely available for civilian use in the 1980s, which he said had “kick-started a multi-billion dollar proliferation of digital goods and services”](https://www.civilserviceworld.com/articles/news/next-gps-matt-hancock-talks-benefits-opening-address-data)’.

He got the importance of this data being open. Not that surprising when you know that his parents ran a company that built “[software that allows you to type your postcode into the internet and bring up your address](https://www.ft.com/content/027bd85e-0290-11e4-a68d-00144feab7de)”.

![Government is building [a common language about addresses](https://data.blog.gov.uk/2016/08/19/the-language-of-addresses/).](https://cdn-images-1.medium.com/max/600/1*3LMiaH3QV4KZstr222zwIw.png)
Government is building [a common language about addresses](https://data.blog.gov.uk/2016/08/19/the-language-of-addresses/).

Government is exploring the options as openly as possible. They are sharing their research into topics such as the need and complexity of [address matching](https://data.blog.gov.uk/2016/08/09/tackling-address-matching-together/). and the need for [a common language for addresses](https://data.blog.gov.uk/2016/08/19/the-language-of-addresses/). They are trialling technology approaches, [you can see the source code for yourself: it’s open](https://github.com/openregister/addressbase-data). And this all forms part of the bigger picture of building [registers](https://www.gov.uk/government/collections/registers-guidance) as infrastructure for the government-as-a-platform strategy. In fact just this week government announced [an early version of an authoritative register for English local authorities](https://data.blog.gov.uk/2016/09/07/local-authority-england-alpha-register/).

Whilst not all of the work is in the open (remember, the arrangements for UK address data are complex commercially and legally) it is clear that many government organisations — such as the Cabinet Office, Ordnance Survey, BEIS and Treasury — are working together to explore the options and business case for an open register. Good ☺

### Will the address wars ever end?

All of the above is what I said in the talk at the [BCS addressing update seminar](http://www.bcs.org/content/conEvent/10494). At the end the audience debated some of the issues raised. The legal issues seemed to confuse some people — [derived database rights](https://blog.ldodds.com/2015/09/05/what-is-derived-data/) are tricky. Eventually I was asked the most important question: will this new UK government initiative to create an open address register succeed?

The honest answer is “I don’t know” but I do trust the people working on it. They are good and there is clear political will to get this problem sorted. With good people and political support it’s possible to do hard things. I choose to be optimistic. I think they’ll succeed. Good ☺

![The web of data is coming.](https://cdn-images-1.medium.com/max/600/1*wl09Bts5K-FkLIAClWKl7w.png)
The web of data is coming.

It is important for the UK that they do. We need to build for the future [web of data](http://theodi.org/blog/we-need-to-learn-how-to-search-the-web-of-data).

Other countries recognise the value of [data infrastructure that is as open as possible](http://theodi.org/what-is-data-infrastructure). The [USA](http://fedscoop.com/national-address-database), [Australia](https://blog.data.gov.au/news-media/blog/geocoded-national-address-data-be-made-openly-available) and [France](https://www.etalab.gouv.fr/the-first-french-collaborative-national-address-database-is-now-online-and-freely-accessible) have all recently made strong moves to get their address data open.

Data infrastructure is [a competitive advantage in the 21st century](http://theodi.org/blog/an-open-letter-to-the-chair-of-the-new-infrastructure-commission). We need to move on from old licensing and funding models that don’t make the best use of the qualities of the web and data.

Let’s [build better data infrastructure that makes things better for everyone](http://theodi.org/guides/principles-for-strengthening-our-data-infrastructure).

[![](https://cdn-images-1.medium.com/max/400/1*0hqOaABQ7XGPT-OYNgiUBg.png)](http://bit.ly/HackernoonFB)
[![](https://cdn-images-1.medium.com/max/400/1*Vgw1jkA6hgnvwzTsfMlnpg.png)](https://goo.gl/k7XYbx)
[![](https://cdn-images-1.medium.com/max/400/1*gKBpq1ruUi0FVK2UM_I4tQ.png)](https://goo.gl/4ofytp)

> [Hacker Noon](http://bit.ly/Hackernoon) is how hackers start their afternoons. We’re a part of the [@AMI](http://bit.ly/atAMIatAMI) family. We are now [accepting submissions](http://bit.ly/hackernoonsubmission) and happy to [discuss advertising & sponsorship](mailto:partners@amipublications.com) opportunities.

> If you enjoyed this story, we recommend reading our [latest tech stories](http://bit.ly/hackernoonlatestt) and [trending tech stories](https://hackernoon.com/trending). Until next time, don’t take the realities of the world for granted!

[![](https://cdn-images-1.medium.com/max/2560/1*35tCjoPcvq6LbB3I6Wegqw.jpeg)](https://goo.gl/Ahtev1)
