---
title: A data perspective on the IP bill
categories:
- General
feature_image: "https://www.nasa.gov/sites/default/files/images/562317main_PIA14033_full.jpg"
---

Recently the UK Government issued a draft of legislation that would alter its powers to investigate illegal activity on the internet: the [Investigatory Powers (IP) bill](https://www.gov.uk/government/publications/draft-investigatory-powers-bill). The draft is being debated in committee, in public and will be debated in Parliament before a decision is made on the final text.

I have chosen to consider the IP Bill through the prism of data. The bill is lengthy and hard to unpick but it moves large datasets from closed to shared on the data spectrum. Sometimes with unclear ownership and governance.

<!-- more -->

As a whole the bill creates risks to our economy and privacy with the aim of increasing our security. We risk causing significant damage as a result.

Perhaps we should go back to first principles and consider other ways to use data to improve our security.

#### Bulk communications data for telephone calls

To understand the implications we need to look in detail at the data impact of the draft bill.

First, a dataset containing bulk communications data for telephone calls. The telecoms industry calls these Call Detail Records (CDRs).

CDRs contain information for each telephone call made to or from a UK number. It was confirmed on release of the IP bill that CDRs have been [collected since 2001](http://www.techweekeurope.co.uk/e-regulation/mi5-gchq-collected-phone-data-180038). This was confirmed by an oblique reference to the [1984 Telecommunications Act](https://en.wikipedia.org/wiki/Telecommunications_Act_1984) in the IP Bill debate. This was the first time that government had confirmed that CDRs were being collected by the intelligence agencies. Alongside the draft bill more detail was released of how CDRs will be [acquired and used](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/473780/Handling_arrangements_for_Bulk_Communications_Data.pdf).

The dataset contains what is known as telephony [metadata](https://en.wikipedia.org/wiki/Metadata): the calling number, called number, date, time and duration for each call. It does not contain the content, i.e. what was said, or the identity of the person at either end of the call but under some conditions that could be inferred to a high level of confidence. For example, with access to other data CDRs could be linked to the identity of the bill payer at either side. That might disclose the name of a person, a business, a charity, a government department. If you knew that I called a letting agent and removal firm on a given day you might be able to guess my purpose.

As well as through the CDR dataset disclosed in the IP bill, the police, the security services and multiple other public sector organisations can also gain access to CDRs, and the identity of the person who pays the bill, under the [Regulation of Investigatory Powers (RIPA) Act](http://www.legislation.gov.uk/ukpga/2000/23/contents) but with a different access method.

RIPA states that communication companies must store this data within their own organisation. Authorised bodies make requests under [certain conditions](https://www.gov.uk/guidance/surveillance-and-counter-terrorism) to search the data. The communications company provides data that matches the request. For example a communications company might receive a request for details of “all calls from phone number X within time period Y to Z” and the requesting body might have made the request to support a criminal investigation.

There have been [many](http://www.theguardian.com/media/2014/nov/04/police-ripa-powers-spy-journalists-sources) [cases](https://www.bigbrotherwatch.org.uk/TheGrimRIPA.pdf) where people have used RIPA to access data in dubious circumstances such as investigating the sources of journalists or checking whether parents live in a catchment area for a school.

![Image by [Jeremy Segrott](https://www.flickr.com/photos/126337928@N05/). CC-BY-2.0](https://cdn-images-1.medium.com/max/800/1*7hzitrmQgYgc-HohI3ElhA.jpeg)
Image by [Jeremy Segrott](https://www.flickr.com/photos/126337928@N05/). CC-BY-2.0

The [Interception of Communication Commissioner’s Office (IOCCO)](http://www.iocco-uk.info/) has regulatory responsibility for RIPA and can take action against bodies that use RIPA incorrectly. From IOCCO’s reports it appears that they were [asked to take responsibility for regulating the newly disclosed bulk CDR dataset and, in return, requested it to be put on a clearer legislative footing early in 2015](http://www.iocco-uk.info/docs/2015%20Half-yearly%20report%20%28web%20version%29.pdf).

This is a complex tale. It is tricky to even spot this dataset being disclosed in the debate in Parliament let alone unpick its history and understand the impact.

A simpler way to consider the data is using the Open Data Institute’s [data spectrum](http://theodi.org/data-spectrum).

![Data spectrum image by the [Open Data Institute](http://theodi.org/data-spectrum). The circles represent datasets.](https://cdn-images-1.medium.com/max/800/1*lEWJVt5j6D4DxmTnLHy-KQ.png)
Data spectrum image by the [Open Data Institute](http://theodi.org/data-spectrum). The circles represent datasets.

Communications companies need CDRs to provide services and bill customers. The CDRs used for billing would be in the internal access part of the spectrum: it is only accessible by the communications company (1). The [Information Commissioner’s Office](https://ico.org.uk/) regulates that the data is kept securely. Customers understand that the dataset exists and receive a derived version in the form of their personal telephone bill (2).

The data that is retained by communications companies to meet their requirements under RIPA and the dataset that is gathered and retained by the intelligence services under the newly disclosed powers are different datasets. They are also derivatives of the internal access dataset that is used to provide services and bill customers.

The RIPA dataset sits within the named access part of the data spectrum (3): it is maintained by the communications company who provide access to authorised public sector organisations. IOCCO’s function as regulator is to verify and report that all parties are are complying with the rules under which Named Access is permitted.

It is unclear whether the dataset newly disclosed by the IP bill is gathered directly by intelligence agencies or provided to them by communications companies. It could be internal access or named access on the data spectrum (4).

Coupled with a historic lack of visibility and independent scrutiny it is difficult for people commenting on the draft of the IP bill to understand some key questions about this dataset. Does the bill provide an appropriate level of regulatory scrutiny? Has the data proved operationally useful to the intelligence services since it was first collected in 2001? Has it, like that accessed under RIPA, been misused?

#### Internet Connection Records

The second dataset we will consider is Internet Connection Records (ICRs). The intelligence services have informed government that they need access to this new dataset to protect our security. The IP Bill requires communication companies to gather ICRs, retain them and provide access on request.

In the draft bill the ICR definition is loose and no example is given of precisely what it might look like and contain. It is clear that ICRs will contain a level of metadata for internet usage: i.e. which websites are accessed and when.

![Data spectrum image by the [Open Data Institute](http://theodi.org/data-spectrum). The circles represent datasets.](https://cdn-images-1.medium.com/max/800/0*rD8KwW9i_QElz-lb.)
Data spectrum image by the [Open Data Institute](http://theodi.org/data-spectrum). The circles represent datasets.

Communications companies need to temporarily use this data to connect customers to websites (5). They may retain an aggregated form of the data to understand the behaviour of their customers and help with marketing and network management. They are unlikely to retain detailed data due to the cost of gathering and securely retaining, the risk that would be identified by a privacy impact assessment and the low value to their business.

Under the IP bill communications providers are asked to derive and retain ICRs for all of their customers (6). Like the RIPA datasets this would be held by the communications company but provided to police and intelligence services on request. This is a dataset in the named access part of the data spectrum.

Attempts to recreate ICRs show that they are likely to contain [personal data which when linked together and analysed would be extremely revealing about individuals](https://paulbernal.wordpress.com/2015/11/05/a-few-words-on-internet-connection-records/). The data is far more revealing than the bulk communications dataset for telephone records.

This is concerning.

By moving data from closed to shared we increase the risk of malicious actors gaining access. Every point of data storage, transfer or access is open to attack. The data that malicious actors could gain access to contains personal data about all UK citizens who use telephones or use the internet.

To give a simple example of the potential damage, details continue to emerge of the [personal impact of the hack to a single website, the Ashley Madison dating site in America](http://fusion.net/story/242502/ashley-madison-hack-aftermath/). A leak of an ICR dataset from either the intelligence services or a major communications company would show not just who used that one website but **_every_** website that had been browsed and when. An increasing number of services are delivered and used online. Anyone using the data would be able to paint a realistic picture of each of our lives.

The data should be kept securely but it is difficult to guarantee protection against malicious attacks. The UK ISP TalkTalk recently suffered from a [hack](http://www.bbc.co.uk/news/business-34743185) whilst one of the many things that the [Edward Snowden](https://en.wikipedia.org/wiki/Edward_Snowden) leaks showed us is that even if there are safeguards in place to protect against such hacks, there are still ways for human beings to circumvent the safeguards.

To provide confidence that this data is being kept securely will require significant organisational transparency from both the intelligence services and communications companies. It would require disclosure of how the data is used, how it is shared, who it is shared with, why it is shared, how it is secured, whether it has been breached, who audits it, and who regulates the access. It would also require us to trust the answer to each of these questions and that the auditor and regulator are performing their functions to our satisfaction.

#### Bulk Personal Datasets

The final dataset to consider is bulk personal datasets (BPDs). BPDs contain personal data relating to a large number of individuals. The majority of the individuals in a BPD are not of interest to them, but the intelligence agencies still deem the whole dataset to be useful

It became clear in [March 2015 that the intelligence services had been gathering, retaining and using BPDs for some time](https://rusi.org/sites/default/files/201511_bp_investigatory_powers_bill.pdf). Privacy International started [legal action against the UK intelligence agencies in June 2015](https://www.privacyinternational.org/node/594). The IP Bill creates a regulatory framework for how BPDs are gathered and retained.

![Data spectrum image by the [Open Data Institute](http://theodi.org/data-spectrum). The circles represent datasets.](https://cdn-images-1.medium.com/max/800/1*Nb8SpzKHVNWn_lS4dc0lhw.png)
Data spectrum image by the [Open Data Institute](http://theodi.org/data-spectrum). The circles represent datasets.

It is good that BPDs (7) are being defined and regulated in the draft bill but it is not yet clear how many and which BPDs are being gathered and retained, how they are being used or who they are being shared with. They could be Internal Access or Named Access.

The definition in the draft bill is broad. BPDs could be telephone directories, property records and electoral registers. BPDs could also be medical records, travel records, financial records, records for membership or sports clubs or political parties. They could be biometric records such as the planned [NHS genomics dataset](https://www.england.nhs.uk/2014/12/22/genomics-project/).

The [Intelligence and Security Committee (ISC)of the UK Parliament](http://isc.independent.gov.uk/home) has reported that “[_each Agency reported that they had disciplined — or in some cases dismissed — staff for inappropriately accessing personal information held in these (bulk personal) datasets in recent years._](https://b1cba9b3-a-5e6631fd-s-sites.googlegroups.com/a/independent.gov.uk/isc/files/20150312_ISC_P%2BS%2BRpt%28web%29.pdf?attachauth=ANoY7cr6tE8y6CdHYdjLaZSR-pz_33VTGCOtsG5sf4GEhzrygDxsI6q7BW0ofCLt27wMtgCszEzzvpYM6rjCU8xgBpHKLwTFJdu4EKc-cow1uEveMO-bGCqwxF-O6sdCsT34GP2RdjARYjV8OZEQArRhNtrDdN9YorsrTjwynk3LZNZ3eg1eR5u7m-9N7iGa8hZqyCS-dwBgu828rJ4Pjt27KV6uT1Eu6yjp2KJq8EmatRA75nVwETGFflzvEhN7d0OJy4vCyzR0&attredirects=0)”.

Without additional clarity, openness and ongoing transparency it is unclear whether BPDs create a larger or smaller risk to privacy than the new ICR dataset. Due to the disciplinary action reported by the ISC it is clear that some damage has already been done.

#### Increasing the risks to people’s privacy will damage the digital economy

There are other changes to communications data in the bill. For example the power to interfere, including in bulk, with consumer equipment such as smartphones, communications company network equipment or the potential requirement for online services to provide ways to [bypass](http://www.theguardian.com/technology/2015/nov/23/apple-google-microsoft-weakening-encryption-back-doors) [encryption](http://blog.cryptographyengineering.com/2015/12/on-juniper-backdoor.html).

![Image by Juniper Networks of a [Netscreen firewall](http://www.juniper.net/us/en/products-services/security/netscreen/). It was [recently disclosed that the software on these firewalls had been interfered with](http://www.wired.com/2015/12/juniper-networks-hidden-backdoors-show-the-risk-of-government-backdoors/). It is not known who or even [how many](http://blog.cryptographyengineering.com/2015/12/on-juniper-backdoor.html) individuals or organisations performed this act.](https://cdn-images-1.medium.com/max/800/1*b0ER2P2fUTA295XDOWcDgQ.png)
Image by Juniper Networks of a [Netscreen firewall](http://www.juniper.net/us/en/products-services/security/netscreen/). It was [recently disclosed that the software on these firewalls had been interfered with](http://www.wired.com/2015/12/juniper-networks-hidden-backdoors-show-the-risk-of-government-backdoors/). It is not known who or even [how many](http://blog.cryptographyengineering.com/2015/12/on-juniper-backdoor.html) individuals or organisations performed this act.

But the overall message is consistent.

By increasing the number of people who can access communications data and bulk personal datasets we are moving data from the closed to the shared area of the data spectrum. Whenever we move data in this way it increases the number of people who can use the data. This increases the risk of invading privacy. We need to protect data against these risks.

If protection fails then malicious actors could use their access to discriminate against us, to steal our identity or steal our possessions. They could even choose to openly publish data that was always meant to be kept private. If such breaches occur then it will cause personal and economic damage. Lives will be damaged.

We will ask for compensation from the services that we think failed us and we will stop using services — from the public and private sectors — that we don’t trust.

To protect against the risk of personal damage some individuals can be expected to use personal cryptography to protect their data.

To protect against the risk of economic damage that will threaten their businesses it can be expected that internet companies will respond by continuing to deploy end-end cryptography and hence reducing the value of the data that is collected under the powers in the bill. The battle between internet companies and governments will be played out behind closed doors and [in the media](http://www.theguardian.com/technology/2015/nov/09/tech-firms-snoopers-charter-end-strong-encryption-britain-ip-bill). Perhaps the internet companies will escalate their response and [mobilise their users](http://www.nytimes.com/2015/11/05/technology/airbnb-and-uber-mobilize-vast-user-base-to-sway-policy.html?_r=0) to lobby governments and sway policy.

With a continuing battle, occasional data hacks and the corresponding loss of trust we risk individuals choosing the [locked down future for their data](https://theodi.org/blog/locked-down-data-future-infrastructure). This is a future where all data is as closed as possible. That would reduce the value we can gain from data and increase the damage to our economies.

We need to tread carefully when changing the way we store and use data on such a large scale. We need a more informed and open debate. We may find that in an attempt to reduce the immediate danger to our security we are risking irreversible damage to trust between the state and citizens, to our economy and to our privacy.

We want to be world leaders in the digital economy but are risking both the digital economy and our privacy as the intelligence services believe that mass surveillance and ‘big data’ is the best way to use data to protect the security of citizens. Perhaps we should go back to first principles and [reconsider whether that is the case](http://www.washingtonexaminer.com/targeted-surveillance-could-be-the-new-weapon-against-terrorism/article/2577939)?

\[Note2: this isn’t an authoritative assessment of the IP Bill. The bill’simpacts are complex. An internet search will find you many more assessments. [This is a useful legal review](http://infolawcentre.blogs.sas.ac.uk/investigatory-powers-bill/investigatory-powers-bill-research-group-resources/).\]

\[Note: this blogpost was updated on 23 December to include a section on bulk personal datasets and clarify some detailed points in the last section\]
