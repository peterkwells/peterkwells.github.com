---
title: Improving UK voter registration
description: Voter registration is a problem in the UK.
date: '2016-03-06T23:34:38.009Z'
categories: []
keywords: []
slug: /@peterkwells/improving-uk-voter-registration-d73ae805a7d5
---

Voter registration is a problem in the UK.

If we [opened up aggregated data](http://theodi.org/what-is-open-data) and registration APIs then we could build a network of services to help get people registered. As a result we would get more people registered and, hopefully, more people voting in our elections.

#### Millions of people are not registered to vote

In January 2016 there were [reports that 800,000 people dropped off the electoral register](http://www.theguardian.com/politics/2016/jan/31/electoral-register-loses-estimated-800000-people-since-changes-to-system) last year. That 800,000 is on top of [the Electoral Commission report in July 2014 which found that around 7.5 million of people who are eligible to vote weren’t on the register](http://www.electoralcommission.org.uk/__data/assets/pdf_file/0005/169889/Completeness-and-accuracy-of-the-2014-electoral-registers-in-Great-Britain.pdf).

That’s a lot of people. If we can get them registered (and engaged enough to turnout and vote) then it could help increase [the turnout in UK elections](http://www.ukpolitical.info/Turnout45.htm).

Wouldn’t that be nice.

#### Voter registration data is available but only shared with some people

Voter registration data is managed and held locally by [electoral registration officers](https://en.wikipedia.org/wiki/Electoral_Registration_Officer) (EROs). They share it with some people.

There are [2 versions of the electoral register — the ‘open register’ and the full version](https://www.gov.uk/electoral-register/opt-out-of-the-open-register). You choose whether to go on the open one when you apply to register. The ‘open register’ is [available for inspection at council offices](http://www.southwark.gov.uk/info/200033/voting_and_elections/1310/4_the_electoral_register) or to purchase. People [build websites with it](http://www.searchelectoralroll.co.uk/Electoral_Roll_Search.asp) and [use it for marketing](http://www.dma.org.uk/article/can-marketers-live-without-the-edited-electoral-register).

Many people do not want their name and address available for lots of people to see so they keep their details off the ‘open register’. The full version of the electoral register can be accessed by fewer people. Some of the [people who are allowed to use it](http://www.royalgreenwich.gov.uk/info/364/elections_-_electoral_register/301/registering_to_vote/2) include the election staff who post out our voting details and political parties who get occasional releases and use it to knock on our doors and ask us to vote for them.

When election results are announced we get all to see an aggregated summary of the voter registration data. The Electoral Commission uses the total number [in election results and to calculate the turnout in the election](http://www.electoralcommission.org.uk/our-work/our-research/electoral-data).

Other than that we rarely get to see the data. The [Office of National Statistics](https://data.gov.uk/dataset/electoral_statistics_for_uk) publish a yearly update and the [Electoral Commission](http://www.electoralcommission.org.uk/our-work/our-research/electoral-data) publish historic data but nowhere shows a total count of the current number of people registered to vote (\*).

#### Many organisations are improving voter registration

Government launched a new [easy to use website](https://www.gov.uk/register-to-vote) in 2014 and runs [voter registration campaigns](http://www.independent.co.uk/news/uk/politics/generalelection/national-voter-registration-day-2015-how-to-register-your-vote-for-the-general-election-in-may-10025360.html) whilst political parties also use the occasional release of voter registration data that they are given to target unregistered voters. Meanwhile lots of other good organisations (such as [Bite The Ballot,](http://bitetheballot.co.uk) [Operation Black Vote](http://www.obv.org.uk) and [Hope Note Hate](http://www.hopenothate.org.uk/vrdrive/)) are also working to get more people registered.

Releasing regular aggregated data (“X people are registered to vote in [area Y](https://en.wikipedia.org/wiki/ONS_coding_system)”) to these organisations will help them target their time and money. These groups do **not** need access to the full register and they should not get it. I doubt these groups even need the ‘open register’. I suspect simple regular releases of aggregated data for particular areas will make a big difference to their efforts.

If the government can release [national totals](https://www.gov.uk/performance/register-to-vote/registrations-breakdown) for voter registration every day then aggregated voter registration data for local areas can also be released every day. It would create more informed debate about the challenges of voter registration and help target efforts to increase registration.

#### Better voter registration services

We will continue to need paper forms for people to register (never forget that [12 million people, 20% of UK adults, are not on the internet](https://medium.com/@peterkwells/12-million-people-can-t-read-this-blog-54e82e8b19d3#.bp274wol2)) but we can also build better online services. As well as using aggregated registration data to campaign we could also use [APIs](https://www.gov.uk/service-manual/making-software/apis.html).

Rather than relying on one [website](https://www.gov.uk/register-to-vote) we could use APIs to build a network:

1.  A citizen could inform their local authority that they have moved address and allow them to update the electoral register at the same time.
2.  A voter registration organisation could [translate the current website into one of the many other languages spoken by UK citizens](https://www.ons.gov.uk/peoplepopulationandcommunity/culturalidentity/language).
3.  A political party could register its members.
4.  A student could allow their university to update the electoral register.
5.  A tenant could allow a housing association to update the electoral register.

Many better ideas will exist. Open APIs allow innovation to flourish.

A voter registration API could follow exactly the same rules and regulations as the current website. Ideally the API would also allow individuals to check if they are registered. This would reduce the inevitable duplicated requests that must cost councils time and money. The [Government Digital Service](https://gds.blog.gov.uk) could monitor use of the API and get action taken against people who misuse it.

To be clear this is not about [opening up](https://www.whatdotheyknow.com/request/individual_electoral_registratio#comment-64291) [the code](https://gdstechnology.blog.gov.uk/2016/01/26/working-out-how-to-open-up-the-register-to-vote-code/) for the API. It is about allowing people to use a voter registration API in the same way that [HMRC plans to allow people to use its APIs](https://www.gov.uk/government/news/hmrc-launches-ambitious-api-strategy). Once the voter registration API is open then any local council, university, [civic technology](https://democracyclub.org.uk) organisation, housing association or voter registration campaign can pick it up and build it into their services.

#### Opening up voter registration will make things better

Voter registration is clearly a problem in the UK. The simple new website helps but voter registration is not a problem that a single website will solve.

Government could choose to go further than I’ve outlined in this blog and redesign voter registration. Such a redesign would hopefully consider better open data and open APIs but also consider bigger questions such as whether people could be automatically registered under some circumstances or whether the data could be managed within [a central platform](https://governmentasaplatform.blog.gov.uk) rather than the distributed network of systems managed by Electoral Registration Officers. It is not clear if government has the appetite for such a redesign or how long it would take so I’ve focussed my thoughts on pragmatic things that could help tackle the known problem of under-registration (\*\*).

It is every government’s responsibility to ensure voter registration works. By opening up aggregated data and building open APIs, government can improve how it works with the existing network of voter registration campaigns, [civic technology](https://democracyclub.org.uk) organisations and local authorities and make things better.

— — — — — — — — — — — — — — —

(\*) Sentence updated after publication to be [more precise](https://twitter.com/owenboswarva/status/706764954729390080).

(\*\*) Paragraph added after publication to be [clear on pragmatism v redesign](https://twitter.com/psd/status/706769770591461376).