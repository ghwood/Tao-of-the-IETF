Niels ten Oever and Kathleen Moriarty, Editors

About This Document

This is the upcoming revision of the Tao which can be found at [http://www.ietf.org/tao-possible-revision.html]

The current version of this web page can always be found at [https://www.ietf.org/tao.html]. To contribute to this document or to discuss its content, please join the "tao-discuss" mailing list [https://www.ietf.org/mailman/listinfo/tao-discuss]. A history of the major versions of the Tao can be found here. This particular version was created on 2018-08-20.

This web page is in English. There is a list of translations of the Tao of the IETF.

1. Introduction

Since its early years, attendance at Internet Engineering Task Force (IETF) face-to-face meetings has grown phenomenally and is now averaging between 1100 and 1400 participants [https://datatracker.ietf.org/stats/meeting/overview/]. Many of the attendees are new to the IETF at each meeting, and many of those go on to become regular attendees. When the meetings were smaller, it was relatively easy for a newcomer to adjust. Today, however, a newcomer meets many more new people, some previously known only as the authors of documents or thought-provoking email messages.

This document describes many aspects of the IETF, with the goal of explaining to newcomers how the IETF works. This will enable them to make the meeting and the Working Group discussions more productive for everyone. This document started out fairly short, but expanded over time in response to suggestions from IETF novices about what more they would have wanted to know before attending their first face-to-face meeting or becoming active in their first Working Group.

Of course, it's true that many IETF participants don't go to the face-to-face meetings at all. Instead, they're active on the mailing list of various IETF Working Groups. Since the inner workings of Working Groups can be hard for newcomers to understand, this document provides the mundane bits of information that newcomers will need in order to become active participants.

The IETF is always in a state of change. Although the principles in this document are expected to remain largely the same over time, practical details may well have changed by the time you read it; for example, a web-based tool may have replaced an email address for requesting some sort of action.

Many types of IETF documentation are mentioned in the Tao, from BCPs to RFCs and STDs. The IETF publishes its technical documentation as RFCs, politely known as "Requests for Comments"; and STDs are RFCs identified as "standards". BCPs make recommendations for Best Current Practices in the Internet and are also RFCs; All three types of documents are in the RFC document series; see Section 6 for more information.

This web page is a continuation of the series of the "Tao of the IETF" RFCs. See [RFC6722] for an explanation of how the last RFC in that series became this web page. This web-based version of the Tao is based on [RFC4677], was co-authored with Susan Harris. The original version of this document, published in 1994, was written by Gary Malkin.

So, why "the Tao"? Pronounced "dow", Tao is the basic principle behind the teachings of Lao-tse, a Chinese master. Its familiar symbol is the black-and-white yin-yang circle. Taoism conceives the universe as a single organism, and human beings as interdependent parts of a cosmic whole. Tao is sometimes translated "the way", but according to Taoist philosophy the true meaning of the word cannot be expressed in words.

1.1 Acronyms and Abbreviations Used in the Tao

Some of the acronyms and abbreviations from this document are listed below.

| Term   | Meaning                                             |
|--------|-----------------------------------------------------|
| AD     | Area Director                                       |
| BCP    | Best Current Practice (a type of RFC)               |
| BOF    | Birds of a Feather                                  |
| FAQ    | Frequently Asked Question(s)                        |
| FYI    | For Your Information (a type of RFC)                |
| IAB    | Internet Architecture Board                         |
| IAD    | IETF Administrative Director                        |
| IANA   | Internet Assigned Numbers Authority                 |
| IAOC   | IETF Administrative Oversight Committee             |
| IASA   | IETF Administrative Support Activity                |
| ICANN  | Internet Corporation for Assigned Names and Numbers |
| I-D    | Internet-Draft                                      |
| IESG   | Internet Engineering Steering Group                 |
| IETF   | Internet Engineering Task Force                     |
| IPR    | Intellectual property rights                        |
| IRTF   | Internet Research Task Force                        |
| ISOC   | Internet Society                                    |
| RFC    | Request for Comments                                |
| STD    | Standard (a type of RFC)                            |
| WG     | Working Group                                       |


2. What is the IETF?

The IETF is a loosely self-organized group of people who contribute to the engineering and evolution of Internet technologies. It is the principal body engaged in the development of new Internet standard specifications. The IETF is unusual in that it exists as a collection of happenings, but is not a corporation and has no board of directors, no members, and no dues; see [RFC 3935], "A Mission Statement for the IETF", for more detail.

Its mission includes the following:

    - Identifying and proposing solutions to pressing operational and technical problems in the Internet
    - Specifying the development or usage of protocols and the near-term architecture to solve such technical problems for the Internet
    - Making recommendations to the Internet Engineering Steering Group (IESG) regarding the standardization of protocols and protocol usage in the Internet
    - Facilitating technology transfer from the Internet Research Task Force (IRTF) to the wider Internet community
    - Providing a forum for the exchange of information within the Internet community between vendors, users, researchers, agency contractors, operators, and network managers

The IETF mission further states that the Internet isn't value-neutral, and neither is the IETF.  The IETF wants the Internet to be useful for communities that share our commitment to openness and fairness. The IETF embraces technical concepts such as decentralized control, edge-user empowerment and sharing of resources, because those concepts resonate with the core values of the IETF community.  These concepts have little to do with the technology that's possible, and much to do with the technology that we choose to create.

The IETF meeting is not a conference, although there are technical presentations. The IETF is not a traditional standards organization, although many specifications that are produced become standards. The IETF is made up of volunteers, many of whom meet three times a year to fulfill the IETF mission.

There is no membership in the IETF. Anyone may register for a meeting and then attend. The closest thing there is to being an IETF member is being a participants on the IETF or Working Group mailing lists (see Section 2.3). This is where the best information about current IETF activities and focus can be found.

Of course, no organization can be as successful as the IETF is without having some sort of structure. In the IETF's case, that structure is provided by other organizations, as described in [RFC 2028], "The Organizations Involved in the IETF Standards Process". If you participate in the IETF and read only one BCP, this is the one you should read.

The IETF web site, [fhttps://www.ietf.org], is the best source for information about meetings, Working Groups, Internet-Drafts, RFCs, IETF email addresses, and much more.

In many ways, the IETF runs on the beliefs of its participants. One of the "founding beliefs" is embodied in an early quote about the IETF from David Clark: "We reject kings, presidents and voting. We believe in rough consensus and running code". Another early quote that has become a commonly-held belief in the IETF comes from Jon Postel: "Be conservative in what you send and liberal in what you accept".

The IETF is really about its participants. Because the IETF welcomes all interested individuals, IETF participants come from all over the world and from many different parts of the Internet industry. The IETF conducts its work solely in English. See Section 3.12 for information about the ways that many people fit into the IETF.

One more thing that is important for newcomers: the IETF in no way "runs the Internet", despite what some people mistakenly might say. The IETF makes voluntary standards that are often adopted by Internet users, network operators and equipment vendors, but it does not control, or even patrol, the Internet. If your interest in the IETF is because you want to be part of the overseers, you may be badly disappointed by the IETF.
2.1 Humble Beginnings

The first IETF meeting was held in January 1986 at Linkabit in San Diego, with 21 attendees. The 4th IETF, held at SRI in Menlo Park in October 1986, was the first that vendors attended. The concept of Working Groups was introduced at the 5th IETF meeting at the NASA Ames Research Center in California in February 1987. The 7th IETF, held at MITRE in McLean, Virginia, in July 1987, was the first meeting with more than 100 attendees.

The 14th IETF meeting was held at Stanford University in July 1989. It marked a major change in the structure of the IETF universe. The structure of the IAB (then the Internet Activities Board, now the Internet Architecture Board), which until that time oversaw many "task forces", was changed, leaving it with only two: the IETF and the IRTF. The IRTF is tasked to consider long-term research problems in the Internet. The IETF also changed at that time.

After the Internet Society (ISOC) was formed in January 1992, the IAB proposed to ISOC that the IAB's activities should take place under the auspices of the Internet Society. During INET92 in Kobe, Japan, the ISOC Trustees approved a new charter for the IAB to reflect the proposed relationship.

The IETF met in Amsterdam, The Netherlands, in July 1993. This was the first IETF meeting held in Europe, and the US/non-US attendee split was nearly 50/50. The IETF first met in Asia (in Adelaide, Australia) in 2000.

The IETF currently strives to have a 1-1-1 meeting policy where the goal is to distribute the meetings equally between North America, Europe, and Asia.  These are the locations most of the IETF participants have come from in the recent past.  This meeting rotation is mainly aimed at distributing the travel effort for the existing IETF participants who physically attend meetings and for distributing the timezone difficulty for those who participate remotely. [https://tools.ietf.org/html/draft-ietf-mtgvenue-meeting-policy-07] The IETF has also met in Latin America and Oceanica, but these continents are currently not part of the 1-1-1 rotation schedule. 

2.2 The Hierarchy

2.2.1 ISOC (Internet Society)

The Internet Society is an international, non-profit, membership organization that fosters the expansion of the Internet. One of the ways that ISOC does this is through financial and legal support of the other "I" groups described here, particularly the IETF. ISOC provides insurance coverage for many of the people holding leadership positions in the IETF process and acts as a public relations channel for the times that one of the "I" groups wants to say something to the press.

Starting in spring 2005, the ISOC also became home base for the IETF's directly employed administrative staff. This is described in more detail in [BCP101], "Structure of the IETF Administrative Support Activity (IASA)". The staff initially includes only an Administrative Director (IAD) who works full-time overseeing IETF meeting planning, operational aspects of support services (the secretariat, IANA (the Internet Assigned Numbers Authority), and the RFC Editor, which are described later in this section), and the budget. The IAD leads the IETF Administrative Support Activity (IASA), which takes care of tasks such as collecting meeting fees and paying invoices, and also supports the tools for the work of IETF working groups, the IESG, the IAB, and the IRTF (more about these later in this section).

The IETF Administrative Oversight Committee (IAOC) consists of volunteers, all chosen directly or indirectly by the IETF community, as well as appropriate ex officio members from ISOC and IETF leadership. The IASA and the IAD are directed by the IAOC.

Neither the IAD nor the IAOC have any influence over IETF standards development, which we turn to now.

2.2.2 IESG (Internet Engineering Steering Group)

The IESG is responsible for technical management of IETF activities and the Internet standards process. It administers the process according to the rules and procedures that have been ratified by the ISOC Board of Trustees. However, the IESG doesn't exercise much direct leadership, such as the kind you will find in many other standards organizations. As its name suggests, its role is to set directions rather than to give orders. The IESG ratifies or steers the output from the IETF's Working Groups (WGs), gets WGs started and finished, and makes sure that non-WG drafts that are about to become RFCs are correct.

Check the IESG web pages, [https://www.ietf.org/about/groups/iesg], to find up-to-date information about IESG statements, drafts processed, RFCs published, and documents in Last Call, as well as the monthly IETF status reports.

The IESG consists of the Area Directors (often called "ADs"), who are selected by the Nominations Committee (which is usually called "the NomCom") and are appointed for two years. The process for choosing the members of the IESG is detailed in [BCP10], "IAB and IESG Selection, Confirmation, and Recall Process: Operation of the Nominating and Recall Committees".

The current Areas and abbreviations are shown below (more information can be found here: [https://www.ietf.org/topics/areas/]).

| Area                                   | Description                                                                                                 |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Applications and Real-Time Area (art)  | Protocols seen by user programs, such as email and the web and delay-sensitive interpersonal communications |
| General (gen)                          | IETF process, and catch-all for WGs that don't fit in other Areas (which is very few)                       |
| Internet (int)                         | Different ways of moving IP packets and DNS information                                                     |
| Routing (rtg)                          | Getting packets to their destinations                                                                       |
| Security (sec)                         | Privacy, integrity, authentication, non-repudiation, confidentiality, and access control.                   |
| Transport (tsv)                        | Transport for large volumes of traffic at potentially high bandwidths.                                      |


Because the IESG is reviewing all Internet-Drafts before they become RFCs, Area Directors have quite a bit of influence. Some people therefore shy away from directly engaging with Area Directors, whereas they can be an important resource and help you find the person or the answer that your looking for. At the meeting they might be very busy. Email to schedule a meeting is a great way to get in touch. Emailing with the actual question before or after a meeting is effective as well.

The ADs for a particular Area are expected to know more about the combined work of the WGs in that Area than anyone else.  This is because the ADs actively follow the working groups for which they are responsible and assist working groups and chairs with charter and milestone reviews. The entire IESG reviews each Internet-Draft that is proposed to become an RFC and should be aware of general trends that can be gleaned from the collective work products of the IETF. As part of the document reviews, ADs place ballots that may contain comments on documents.  The AD enters a position that may be YES, NO OBJECTION, DISCUSS, ABSTAIN, or RECUSE as the result of their review.  Any AD may record a "DISCUSS" ballot position against a draft if he or she has serious concerns and would like to discuss these concerns. It is quite common for documents to be approved with one or two "YES" ballots, and the majority of the remaining IESG balloting "NO OBJECTION.".

This is not to say that the IESG never wields power. When the IESG sees a Working Group veering from its charter, or when a WG asks the IESG to make the WG's badly designed protocol a standard, the IESG will act. In fact, because of its high workload, the IESG usually moves in a reactive fashion. It eventually approves most WG requests for Internet-Drafts to become RFCs, and usually only steps in when something has gone very wrong. Another way to think about this is that the ADs are selected to think, not to just run the process. The quality of the IETF standards comes both from the review they get in the Working Groups and the scrutiny that the WG review gets from the ADs.

The IETF is run by rough consensus, and it is the IESG that judges whether a WG has come up with a result that has IETF community consensus. (See Section 4.2 for more information on WG consensus.) Because of this, one of the main reasons that the IESG might block something that was produced in a WG is that the result did not really gain consensus in the IETF as a whole, that is, among all of the Working Groups in all Areas. For instance, the result of one WG might clash with a technology developed in a different Working Group, perhaps from another Area. An important job of the IESG is to watch over the output of all the WGs to help prevent IETF protocols that are at odds with each other. This is why ADs are supposed to review the drafts coming out of Areas other than their own.

2.2.3 IAB (Internet Architecture Board)

The IAB is responsible for keeping an eye on the "big picture" of the Internet, and it focuses on long-range planning and coordination among the various areas of IETF activity. The IAB stays informed about important long-term issues in the Internet, and it brings these topics to the attention of people it thinks should know about them.

IAB members pay special attention to emerging activities in the IETF. When a new IETF Working Group is proposed, the IAB reviews its charter for architectural consistency and integrity. Even before the group is chartered, the IAB members are more than willing to discuss new ideas with the people proposing them.

The IAB also sponsors and organizes the Internet Research Task Force and convenes invitational workshops that provide in-depth reviews of specific Internet architectural issues. Typically, the workshop reports make recommendations to the IETF community and to the IESG. The IAB keeps the community informed through blogposts and by publishing RFCs.

The IAB also:

    - Approves NomCom's IESG nominations
    - Acts as the appeals board for appeals against IESG and IAOC actions
    - Oversees the RFC series through the RFC Series Oversight Committee (RSOC)
    - Approves the appointment of the IANA
    - Acts as an advisory body to ISOC
    - Oversees IETF liaisons with other standards bodies

Like the IESG, the IAB members are selected for two-year positions by the NomCom and are approved by the ISOC Board of Trustees.

2.2.4 IANA (Internet Assigned Numbers Authority)

The core registrar for the IETF's activities is the IANA (see https://www.iana.org). Many Internet protocols require that someone keep track of protocol items that were added after the protocol came out. Typical examples of the kinds of registries needed are for TCP port numbers and MIME types. The IAB has designated the IANA organization to perform these tasks, and the IANA's activities are financially supported by ICANN, the Internet Corporation for Assigned Names and Numbers. The IAB selected ICANN, and the IANA activities are provided for free as specified in [RFC2860]. The IAOC has an Memorandum of Understanding with ICANN about the performance of the protocol parameters functions of IANA as performed by ICANN [https://www.icann.org/iana_imp_docs/59-2016-icann-ietf-mou-supplemental-agreement-v-1-0], which up to now consistently has met its performance targets.

Ten years ago, no one would have expected to see the IANA mentioned on the front page of a newspaper. IANA's role had always been very low key. The fact that IANA was also the keeper of the root of the domain name system forced it to become a much more public entity, one that was badly maligned by a variety of people who never looked at what its role was. Nowadays, the IETF is generally no longer involved in the IANA's domain name and IP address assignment functions, which are overseen by ICANN.

Even though being a registrar may not sound interesting, many IETF participants will testify to how important IANA has been for the Internet. Having a stable, long-term repository run by careful and conservative operators makes it much easier for people to experiment without worrying about messing things up. IANA early maintainers, Jon Postel and Joyce Reynolds, were heavily relied upon to keep things in order while the Internet kept growing by leaps and bounds.

2.2.5 RFC Editor

The RFC Editor edits, formats, and publishes Internet-Drafts as RFCs, working in conjunction with the IESG for IETF RFCs, the IRTF Chair for IRTF RFCs, the IAB for IAB RFCs, and the Independent Submissions Editor for Independent Stream RFCs, and of course working with the authors. An important other role is to provide one definitive repository for all RFCs (see [https://www.rfc-editor.org]). Once an RFC is published, it is never revised. If the specification it describes changes, the standard will be re-published in another RFC that "obsoletes" the first. If a technical or editorial error is found in an RFC, an errata may be filed for review.  If accepted, the errata will be linked to the RFC and may be held for the next document update.

The IAB approves the organization that will act as RFC Editor and the RFC Editor's general policy. The RFC Editor is funded by IASA. Up through the end of 2009, the RFC Editor was a single entity. The function was split by the IAB, in coordination with the IETF community, into many roles that can be performed by different people or organizations, led by the IAB-appointed RFC Series Editor. The RFC Editor model is described in [RFC6635].

Another common misconception is that all RFCs are the work of the IETF. In fact, of the four sources of RFCs listed above (IETF, IAB, IRTF, and Independent Submissions), only those coming direct from the IETF through working groups or sponsored by ADs are capable of having IETF consensus and being described as IETF specifications or standards.

2.2.6 IETF Secretariat

There are, in fact, a few people who are paid to maintain the IETF. The IETF Secretariat provides day-to-day logistical support, which mainly means coordinating face-to-face meetings and running the IETF-specific mailing lists. The Secretariat is also responsible for keeping the official Internet-Drafts directory up to date and orderly, maintaining the IETF web site, and for helping the IESG do its work. It provides various tools for use by the community and the IESG. The IETF Secretariat is under contract to IASA, which in turn is financially supported by the fees collected for attending the face-to-face meetings.

2.2.7 IETF Trust

Near the end of 2005, the IETF Trust was set up to hold and license the intellectual property of the IETF. The reason the IETF Trust was set up is that someone has to hold intellectual property, and that someone should be a stable, legally-identifiable entity. The IETF Trustees are the same people who serve as members of the IAOC at any given point in time. Few IETF participants come into contact with the IETF Trust, which is a good sign that they are quietly doing their job. You can find out more about the IETF trust at their web site, [https://trustee.ietf.org].

2.3 IETF Mailing Lists

Anyone who plans to attend an IETF meeting should join the IETF announcement mailing list (see [https://www.ietf.org/mailman/listinfo/IETF-Announce]). This is where all of the meeting information, RFC announcements, and IESG Protocol Actions and Last Calls are posted. People who would like to "get technical" may also join the IETF general discussion list (see [https://www.ietf.org/mailman/listinfo/ietf]). This is where general discussions are held (Working Groups have their own mailing lists for discussions related to their work). Another mailing list announces each new version of every Internet-Draft as it is published (see [https://www.ietf.org/mailman/listinfo/I-D-Announce]).

Subscriptions to these and other IETF-run mailing lists are handled by a program called "mailman". Mailman can be somewhat finicky about the format of subscription messages, and sometimes interacts poorly with email programs that make all email messages into HTML files. Mailman will treat you well, however, if you format your messages just the way it likes.

The IETF discussion list is unmoderated. This means that all can express their opinions about issues affecting the Internet. However, it is not a place for companies or individuals to solicit or advertise, as noted in [BCP45], "IETF Discussion List Charter". It is a good idea to read the whole RFC (it's short!) before posting to the IETF discussion list. Actually, the list does have two "sergeants at arms" who keep an eye open for inappropriate postings, and there is a process for banning persistent offenders from the list, but fortunately this is extremely rare.

Only the Secretariat and a small number of IETF leaders can approve messages sent to the announcement list, although those messages can come from a variety of people.

Even though the IETF mailing lists "represent" the IETF participants at large, it is important to note that attending an IETF meeting does not mean you'll be automatically added to either mailing list.

3. IETF Meetings

The computer industry is rife with conferences, seminars, expositions, and all manner of other kinds of meetings. IETF face-to-face meetings are not like these. The meetings, held three times a year, are week-long gatherings whose primary goal is to reinvigorate the WGs to get their tasks done, and whose secondary goal is to promote a fair amount of mixing between the WGs and the Areas. 

For many people, IETF meetings are a breath of fresh air when compared to the standard computer industry conferences. There is no exposition hall, few tutorials, and no big-name industry pundits. Instead, there is lots of work, as well as a fair amount of time for socializing for many participants. IETF meetings are of little interest to sales and marketing folks, but of high interest to engineers and developers.

The general flow of an IETF meeting is that it begins with a hackathon on Saturday and Sunday, tutorials and an informal gathering on Sunday, and that there are WG and BoF meetings Monday through Friday. WG meetings last for between 1 and 2.5 hours each, and some WGs have meetings multiple times during the week, depending on how much work they anticipate doing.

There are two plenary sessions, one technical and one administrative, in the evenings during the week (mostly Wednesday). The technical plenary is organized by the IAB and usually has one or two panels of experts on topics of interest across many WGs and Areas. The administrative plenary, organized by the IETF Chair, covers things like progress reports from the RFC Editor and announcements of upcoming meetings. The plenaries are a good time to share with the IESG and IAOC. Praise is welcome, but more often concerns and gripes are raised. In recent meetings, the two plenaries have been combined.

Currently, the IETF meets in North America, Europe, and Asia, approximately once a year in each region. There have been more than 100 IETF meetings so far, and a list of upcoming meetings is available on the IETF web pages, [https://www.ietf.org/how/meetings/upcoming]. You can read more about the meeting selection process and criteria here ([https://datatracker.ietf.org/doc/draft-ietf-mtgvenue-meeting-policy/] [https://datatracker.ietf.org/doc/draft-ietf-mtgvenue-iaoc-venue-selection-process/])

Newcomers to IETF face-to-face meetings often expect them to be like other standards bodies, or like computer conferences. Fortunately, many new attendees get quite animated about how much fun they are having. On the other hand, IETFers can sometimes be surprisingly direct, sometimes verging on rude. To build a climate in which people of many different backgrounds are treated with dignity, decency, and respect IETF has both an anti-harsassment policy, guidelines for conduct [https://tools.ietf.org/html/rfc7154] and an ombudsteam. (see [https://www.ietf.org/contact/ombudsteam/])

3.1 Registration

To attend an IETF meeting, you have to register and pay a registration fee. The meeting site and advance registration are announced at least two months ahead of the meeting — earlier if possible. An announcement goes out via email to the IETF-announce mailing list, and information is posted on the IETF web site, [https://www.ietf.org], that same day.

You can register and pay on the web before the meeting, or in person at the meeting. To get a lower registration fee, you must pay by the early registration deadline (about five weeks before the meeting). The registration fee covers all of the week's meetings, the Sunday evening welcome reception, and afternoon beverage and snack breaks.

Registration is open throughout the week of the meeting. You can find out more about how the IETF handles your personal data here: [https://www.ietf.org/privacy-statement/].

The Sunday is an excellent day to join the meeting (unless you already joined us during the hackathon on Saturday). Sunday is the day for the newcomer's tutorial, as well the Quick Connections session where newcomers get to meet with experienced IETF participants and the Newcomer's Meet and Greet where newcomers can meet Area Directors and Working Group Chairs. After these sessions there is the reception which is a popular event where you can get a small bite to eat and socialize with other attendees.

Before you register, you see a web page titled "Note Well". You should indeed read it carefully because it lays out the rules for IETF intellectual property rights.  The Note Well points to the supporting documentation for IPR, anti-harassment, and other important guiding policies for the IETF. 

If you need to leave messages for other attendees, you can do so at the cork boards that are often near the registration desk. These cork boards will also have last-minute meeting changes and room changes.

You can also turn in lost-and-found items to the registration desk. At the end of the meeting, anything left over from the lost-and-found will usually be turned over to the hotel or brought back to the Secretariat's office.

Incidentally, the IETF registration desk is often a convenient place to arrange to meet people. If someone says "meet me at registration", you should clarify if they mean the IETF registration desk, or the hotel registration desk. This has been a common cause of missed connections.

3.2 Take the Plunge and Stay All Week!

IETF WG meetings are scheduled from Monday morning through Friday afternoon. Associated non-WG meetings often take place on the preceding or following weekends. It is best to plan to be present the whole week, to benefit from cross-fertilization between Working Groups and from corridor discussions. As noted below, the agenda is fluid, and there have been many instances of participants missing important sessions due to last-minute scheduling changes after their travel plans were fixed. Being present the whole week is the only way to avoid this annoyance.

If you cannot find meetings all week to interest you, you can still make the most of the IETF meeting by working between sessions. Most IETF attendees carry laptop computers, and it is common to see many of them in the terminal room or in the hallways working during meeting sessions. There is often good wireless Internet coverage in many places of the meeting venue (restaurants, coffee shops, and so on), so catching up on email when not in meetings is a fairly common task for IETFers.

3.3 Newcomer Training

Newcomers are encouraged to attend the Newcomer's Tutorial on Sunday afternoon, which is especially designed for first-time attendees. The tutorial is organized and conducted by the IETF EDU team and is intended to provide useful introductory information. The session covers what all the dots on name tags mean, the structure of the IETF, and many other essential and enlightening topics for new IETFers. If you are unable to attend this session, recorded ones from previous meetings are available ([https://www.ietf.org/about/participate/tutorials/]).

Later in the afternoon is the Quick Connections session where newcomers have the chance to get to know senior IETF participants, and ask questions. The Quick Connections session is followed by the Newcomer's Meet and Greet, which is only open to newcomers and WG chairs. This is a great place to try to find people knowledgeable in the areas in which you are interested. Feel free to approach any WG chair, not just those in your area, to either learn about their WG or to have them help find you someone in yours.

3.4 Dress Code

At meetings people generally dress informally. Newcomers are sometimes out of place when they show up Monday morning in suits. The general rule is "dress for the weather" (unless you plan to work so hard that you won't go outside, in which case, "dress for comfort" is the rule!).

3.5 WG Meetings

The heart of an IETF meeting is the WG meetings themselves. Different WGs chairs have very different styles, so it is impossible to generalize how a WG meeting will feel. Even though nearly all WGs have agendas for their meetings, some meetings stick tightly to their agenda while others are run more loosely.

There are a few important things that are true for all WG meetings at an IETF meeting. Near the beginning of the meeting, the chair will pass around the "blue sheets", which are paper forms on which everyone writes their name and their email address. These are used for long-term archival purpose to show how many people came to a particular meeting and, in rare cases, exactly who showed up. The normal etiquette is to watch where the blue sheets came from and to pass them along in the same direction.

When speaking in a meeting, you should always go to the microphones in the room. For controversial topics, there will be a line at the mic, but do not hesitate to be the first person at the mic if you have a question or a contribution to the discussion. The WG chair or presenter will indicate when you can speak. Although it would be easier to just raise your hand from where you are sitting, the mics perform a very useful task: they let the people listening remotely and in the room hear your question or comment. It is also expected that you will say your name at the mic so that the person taking minutes will know who is speaking.

3.6 Seeing Spots Before Your Eyes

Some of the people at the IETF will have a little colored dot on their name tag. A few people have more than one. These dots identify people who are silly enough to volunteer to do a lot of extra work. The colors have the meanings shown here.

| Color  | Meaning                     |
|--------|-----------------------------|
| Blue   | Working Group/BOF Chair     |
| Green  | Host group                  |
| Red    | IAB member                  |
| Yellow | IESG member                 |
| Orange | Nominating Committee member |
| Purple | IAOC                        |
| Pink   | IRSG                        |
| Teal 	 | RFC Series Editor           |

(Members of the press wear orange-tinted badges.)

It is important that newcomers to the IETF not be afraid to strike up conversations with people who wear these dots. If the IAB and IESG members and Working Group and BOF chairs didn't want to talk to anybody, they wouldn't be wearing the dots in the first place. Note, however, that IETF meetings are usually intense times for Area Directors. Talking to an AD during an IETF meeting will often lead to a request to send her or him email about two weeks later. Also, when you start a hallway conversation with an Area Director (or even a WG chair, for that matter), it is often good to give them about 30 seconds of context for the discussion.

3.7 Terminal Room

Every meeting the NOC provides unfettered Internet access for the meeting attendees. In general, wireless connectivity is excellent in all the meeting rooms and most common areas, and the wired connectivity is provided in the terminal room. The people and companies that donate their equipment, services, and time are to be heartily congratulated and thanked.

Although preparation far in advance of the meeting is encouraged, there may be some unavoidable "last minute" things that can be accomplished in the terminal room. It may also be useful to people who need to make trip reports or status reports while things are still fresh in their minds.

You need to be wearing your badge in order to get into the terminal room. The terminal room provides lots of power strips, lots of Ethernet ports for laptops, wireless (for the people who don't need Ethernet but want power), and usually a printer for public use. What it doesn't provide are terminals; the name is historical. The help desk in the terminal room is a good place to ask questions about network failures, although they might point you off to different networking staff.

3.8 Meals and Other Delights

Marshall Rose once remarked that the IETF was a place to go for "many fine lunches and dinners". Although it is true that some people eat very well at the IETF, they find the food on their own; lunches and dinners are not included in the registration fee. If sponsorship for it is secure, the Secretariat arranges for appetizers at the Sunday evening welcome reception (not meant to be a replacement for dinner), in some venues, continental breakfast on Monday through Friday mornings, and (best of all) cookies, brownies, fruit, and other yummies during some of the afternoon breaks. These are very often paid for by the meeting host or a meeting sponsor.

If you prefer to get out of the hotel for meals, the local host usually provides a list of places to eat within easy reach of the meeting site.

3.9 Social Event

Another of the most important things organized and managed by the host is the IETF social event. The social event is sometimes high-tech-related event, or it might be in an art museum or a reception hall. Note, however, that not all IETF meetings have social events.

Newcomers to the IETF are encouraged to attend the social event. All are encouraged to wear their name tags and leave their laptops behind. The social event is designed to give people a chance to meet on a social, rather than technical, level.

3.10 Agenda

The agenda for the IETF meetings is a very fluid thing. It is available on the web and through the IETF mobile apps starting a few weeks before the meeting. Small-sized agendas are available for pickup at the registration desk for those with good eyesight who want to keep a copy in their pocket or attached to the back of their badge. Of course, "final" in the IETF doesn't mean the same thing as it does elsewhere in the world. The final agenda is simply the version that went to the printer. The Secretariat will post agenda changes on the bulletin board near the IETF registration desk (not the hotel registration desk). These late changes are not capricious: they are made "just in time" as session chairs and speakers become aware of unanticipated clashes. The IETF is too dynamic for agendas to be tied down weeks in advance.

A map showing the room locations are also shown on the agenda. Room assignments can change as the agenda changes. Some Working Groups meet multiple times during a meeting, and every attempt is made to have a Working Group meet in the same room for each session.

3.11 EDU to the Rescue

If certain aspects of the IETF still mystify you (even after you finish reading the Tao), you'll want to drop in on the on-site training offered by the Education (EDU) team. These informal classes are designed for newcomers and seasoned IETFers alike. In addition to the Newcomer Training, the EDU team offers two in-depth tutorials that are indispensable for both novices and longtime IETF attendees. EDU sessions are generally held on Sunday afternoons and are posted to watch later as well. 

During registration you will also be offered to be linked to a mentor. This is also organized by the EDU team; you will be paired with volunteers who have experience in the IETF and can help you hit the ground running. Ideally you have a call with your mentor before the meeting, a meeting during the beginning of the meeting, and check in some time during the meeting, so they can help you with any questions you might have.

You'll find more about the EDU team at [https://datatracker.ietf.org/group/emodir/about].

3.12 Where Do I Fit In?

The IETF is different things to different people. There are many people who have been very active in the IETF who have never attended an IETF meeting. You should not feel obligated to come to an IETF meeting just to get a feel for the IETF. The following guidelines (based on stereotypes of people in various industries) might help you decide whether you actually want to come and, if so, what might be the best use of your time at your first meeting.

3.12.1 Information Security Managers

As discussed throughout this document, an IETF meeting is nothing like any trade show you have attended. IETF meetings are singularly bad places to go if your intention is to find out what will be hot in the Internet industry next year. You can safely assume that going to Working Group meetings will confuse you more than it will help you understand what is happening, or will be happening, in the industry.

This is not to say that no one from the industry should go to IETF meetings. As an IS manager, you might want to consider sending specific people who are responsible for technologies that are under development in the IETF. As these people read the current Internet-Drafts and the traffic on the relevant Working Group lists, they will get a sense of whether or not their presence would be worthwhile for your company or for the Working Groups.

3.12.2 Network Operators and ISPs

Running a network is hard enough without having to grapple with new protocols or new versions of the protocols with which you are already dealing. If you work for the type of network that is always using the very latest hardware and software, and you are following the relevant Working Groups in your copious free time, you could certainly find participating in the IETF valuable. A fair amount of IETF work also covers many other parts of operations of ISPs and large enterprises, and the input of operators from each of these types of organizations is quite valuable to keep this work vibrant and relevant. Many of the best operations documents from the IETF come from real-world operators, not vendors and academics.

3.12.3 Networking Hardware and Software Vendors


The image of the IETF being mostly network researchers may have been true in the distant past, but the jobs of typical attendees are now in industry. In most areas of the IETF, employees of vendors are the ones writing the protocols and leading the Working Groups, so it's completely appropriate for vendors to attend. If you create Internet hardware or software, and no one from your company has ever attended an IETF meeting, it behooves you to come to a meeting if for no other reason than to tell the others how relevant the meeting was or was not to your business.

This is not to say that companies should close up shop during IETF meeting weeks so everyone can go to the meeting. Marketing folks, even technical marketing folks, are usually safe in staying away from the IETF as long as some of the technical people from the company are at the meeting. Similarly, it isn't required, or likely useful, for everyone from a technical department to go, particularly if they are not all reading the Internet-Drafts and following the Working Group mailing lists. Many companies have just a few designated meeting attendees who are chosen for their ability to do complete and useful trip reports. In addition, many companies have internal coordination efforts and a standards strategy. If a company depends on the Internet for some or all of its business, the strategy should probably cover the IETF.  The attendees participate in the IETF as individuals.

3.12.4 Academics

IETF meetings are often excellent places for computer science folks to find out what is happening in the way of soon-to-be-deployed protocols. Professors and grad students (and sometimes overachieving undergrads) who are doing research in networking or communications can get a wealth of information by following Working Groups in their specific fields of interest. Wandering into different Working Group meetings can have the same effect as going to symposia and seminars in your department. Researchers are also, of course, likely to be interested in IRTF activities.

3.12.5 Computer Trade Press

If you're a member of the press and are considering attending IETF, we've prepared a special section of the Tao just for you — please see Section 8.2.

3.13 Proceedings

IETF proceedings are compiled in the two months following each meeting and are available on the web. Be sure to look through a copy — the proceedings are filled with information about IETF that you're not likely to find anywhere else. For example, you'll find snapshots of most WG charters at the time of the meeting, giving you a better understanding of the evolution of any given effort.

The proceedings sometimes start with an informative (and highly entertaining) message. Each volume contains the final (hindsight) agenda, an IETF overview, Area and Working Group reports, and slides from the protocol and technical presentations. The Working Group reports and presentations are sometimes incomplete, if the materials haven't been turned in to the Secretariat in time for publication.

An attendee list is also included, which contains names and affiliations as provided on the registration form. For information about obtaining copies of the proceedings, see the web listing at https://www.ietf.org/how/meetings/proceedings. IETF proceedings are compiled in the two months following each meeting and are available on the web. Be sure to look through a copy — the proceedings are filled with information about IETF that you're not likely to find anywhere else. For example, you'll find snapshots of most WG charters at the time of the meeting, giving you a better understanding of the evolution of any given effort.

The proceedings sometimes start with an informative (and highly entertaining) message. Each volume contains the final (hindsight) agenda, an IETF overview, Area and Working Group reports, and slides from the protocol and technical presentations. The Working Group reports and presentations are sometimes incomplete, if the materials haven't been turned in to the Secretariat in time for publication.

An attendee list is also included, which contains names and affiliations as provided on the registration form. For information about obtaining copies of the proceedings, see the web listing at http://www.ietf.org/meeting/proceedings.html.

3.14 Other General Things

IETFers in general are very approachable. Never be afraid to approach someone and introduce yourself. Also, don't be afraid to ask questions, especially when it comes to jargon and acronyms.

Hallway conversations are very important. A lot of very good work gets done by people who talk together between meetings and over lunches and dinners. Every minute of the IETF can be considered work time (much to some people's dismay).

A side meeting (historically but often inaccurately called a "bar BOF") is an unofficial get-together between WG meetings or in the late evening, during which a lot of work gets done. These side meetings spring up in many different places around an IETF meeting, such as restaurants, coffee shops, unused hall spaces, and (if we are so lucky) pools.

It's unwise to get between a hungry IETFer (and there isn't any other kind) and coffee break brownies and cookies, no matter how interesting the hallway conversation. Steve Coya, the first IETF Executive Director, often said, "Take your cookie, then step away from the table."

IETFers are fiercely independent. It's safe to question opinions and offer alternatives, but don't expect an IETFer to follow orders.

The IETF meetings, and the plenary session in particular, are not places for vendors to try to sell their wares. People can certainly answer questions about their company and its products, but bear in mind that the IETF is not a trade show. This does not preclude people from recouping costs for IETF-related T-shirts, buttons, and pocket protectors.

There is always a "materials distribution table" near the registration desk. This desk is used to make appropriate information available to the attendees (e.g., copies of something discussed in a Working Group session, descriptions of online IETF-related information). Please check with the Secretariat before placing materials on the desk; the Secretariat has the right to remove material that he or she feels is not appropriate.

If you rely on your laptop during the meeting, it is a good idea to bring an extra battery. It is not always easy to find a spare outlet in some meeting rooms, and using the wireless access can draw down your battery faster than you might expect. If you are sitting near a power-strip in a meeting room, expect to be asked to plug and unplug for others around you. Many people bring an extension cord with spare outlets, which is a good way to make friends with your neighbor in a meeting. If you need an outlet adapter, you should try to buy it in advance because the one you need is usually easier to find in your home country.

3.14 Remote Participation

People have joined IETF meetings remotely for a long time, but the tools for this have changed a lot over the years. Currently all Working Group and Research Group meetings as well as the plenaries are livestreamed and open for remote participation. In order to participate remotely you need to register as a remote participant [https://www.ietf.org/how/meetings/register/], there is no fee for this but registration is required for administrative reasons. You can also make use of audiostreams as well as Jabber (which is explained below). The links for the Meetecho rooms, the audiostreams and the jabber rooms can always be found in the meeting agenda. More information can be found here: [https://www.ietf.org/how/meetings/101/remote/].

4. Working Groups

The vast majority of the IETF's work is done in many Working Groups; at the time of this writing, there are about 115 different WGs. [BCP25], "IETF Working Group Guidelines and Procedures", is an excellent resource for anyone participating in WG discussions.

A WG is really just a mailing list with a bit of supervision and facilitation. You "join" the WG by subscribing to the mailing list; all mailing lists are open to anyone. Anyone can post to a WG mailing list, although most lists require non-subscribers to have their postings moderated. Each Working Group has one or two (or, rarely, three) chairs.

More important, each WG has a charter that the WG is supposed to follow. The charter states the scope of discussion for the Working Group, as well as its goals. The WG's mailing list and face-to-face meetings are supposed to focus on just what is in the charter and not to wander off on other "interesting" topics. Of course, looking a bit outside the scope of the WG is occasionally useful, but the large majority of the discussion should be on the topics listed in the charter. In fact, some WG charters actually specify what the WG will not do, particularly if there were some attractive but nebulous topics brought up during the drafting of the charter. The list of all WG charters makes interesting reading for folks who want to know what the different Working Groups are supposed to be doing.

4.1 Working Group Chairs

The role of the WG chairs is described in both [BCP11] and [BCP25].

As volunteer cat-herders, a chair's first job is to determine the WG consensus goals and milestones, keeping the charter up to date. Next, often with the help of WG secretaries or document editors, the chair must manage WG discussion, both on the list and by scheduling meetings when appropriate. Sometimes discussions get stuck on contentious points and the chair may need to steer people toward productive interaction and then declare when rough consensus has been met and the discussion is over. Sometimes chairs also manage interactions with non-WG participants or the IESG, especially when a WG document approaches publication. Chairs have responsibility for the technical and non-technical quality of WG output. As you can imagine given the mix of secretarial, interpersonal, and technical demands, some Working Group chairs are much better at their jobs than others.

WG chairs are advised to participate in the WG chairs lunch mid-week during the meeting where chair-specific topics are presented and discussed. Slides of the previous versions of this session can be found in the datatracker.

4.2 Getting Things Done in a Working Group

One fact that confuses many novices is that the face-to-face WG meetings are much less important in the IETF than they are in most other organizations. Any decision made at a face-to-face meeting must also gain consensus on the WG mailing list. There are numerous examples of important decisions made in WG meetings that are later overturned on the mailing list, often because someone who couldn't attend the meeting pointed out a serious flaw in the logic used to come to the decision. Finally, WG meetings aren't "drafting sessions", as they are in some other standards bodies: in the IETF, drafting is done elsewhere.

Another aspect of Working Groups that confounds many people is the fact that there is no formal voting. The general rule on disputed topics is that the Working Group has to come to "rough consensus", meaning that a very large majority of those who care must agree. The exact method of determining rough consensus varies from Working Group to Working Group. Sometimes consensus is determined by "humming" — if you agree with a proposal, you hum when prompted by the chair. Most "hum" questions come in two parts: you hum to the first part if you agree with the proposal, or you hum to the second part if you disagree with the proposal. Newcomers find it quite peculiar, but it works. It is up to the chair to decide when the Working Group has reached rough consensus.

The lack of formal voting has caused some very long delays for some proposals, but most IETF participants who have witnessed rough consensus after acrimonious debates feel that the delays often result in better protocols. (And, if you think about it, how could you have "voting" in a group that invites all interested individuals to participate, and when it's impossible to count the participants?) Rough consensus has been defined in many ways; a simple version is that it means that strongly held objections must be debated until most people are satisfied that these objections are wrong.

A related problem is that some people think that their proposals should be discussed in the WG even when the WG Chairs do not. For example, if the proposed work is not really part of the charter, the WG Chairs may constrain the discussion of the proposal in order to keep the WG focused on the chartered work. Individuals who think that a WG should bring up a topic that is considered off-charter by the WG Chairs can bring their concerns to the responsible AD; the AD may agree to adjust the charter to add the topic with the working group, or that it is already covered in the charter, or that the WG Chairs are correct and that the participant should work on the proposal outside the WG.

When a WG document has been fully discussed, it usually goes through Working Group Last Call (often abbreviated as "WGLC"). This is a hopefully-final time fo the WG to iron out issues. Sometimes, WGLC will bring out so many issues that there will be a second WGLC after the revisions have been incorporated. There are no formal rules for how a WGLC happens, or even if a WGLC is needed: it is up to the WG chairs.

Another method that some Working Groups adopt is to have a Working Group "secretary" to handle the juggling of the documents and the changes. The secretary can run the issue tracker if there is one, or can simply be in charge of watching that all of the decisions that are made on the mailing list are reflected in newer versions of the documents.

When a WG has fulfilled its charter, it is supposed to cease operations. (Most WG mailing lists continue on after a WG is closed, still discussing the same topics as the Working Group did.) In the IETF, it is a mark of success that the WG closes up because it fulfilled its charter. This is one of the aspects of the IETF that newcomers who have experience with other standards bodies have a hard time understanding. However, some WG chairs never manage to get their WG to finish, or keep adding new tasks to the charter so that the Working Group drags on for many years (or, in a few cases, decades). The output of these aging WGs is often not nearly as useful as the earlier products, and the messy results are sometimes attributed to what's called "degenerative Working Group syndrome".

4.3 Working Group Documents

There is an official distinction between WG drafts and individual drafts, but in practice, sometimes there is not much procedural difference. For example, many WG mailing lists also discuss individual drafts (at the discretion of the WG chair). The WG chairs get to make the decisions about which drafts will become WG drafts and who the authors or editors of those drafts will be, usually based on consultation with the WG, and sometimes with their Area Director. This process can be tricky in cases where many people want to be a draft author, but can be just as tricky when no one wants to be a draft author but the WG is charted to do some specific work. Procedures for Internet-Drafts are covered in much more detail later in this document.

Some Working Groups have complex documents or a complex set of documents (or even both). Shaking all the bugs out of one or more complex documents is a daunting task. In order to help relieve this problem, some Working Groups use "issue trackers", which are online lists of the open issues with the documents, the status of the issue, proposed fixes, and so on. Using an issue tracker not only helps the WG not to forget to do something important, it helps when someone asks a question later about why something was done in a particular fashion.

For Working Group documents, the document editor serves at the pleasure of the WG Chair. There are often more than one editor for Working Group documents, particularly for complex documents. The document editor is responsible for ensuring that the contents of the document accurately reflects Working Group decisions, particularly when creating a new protocol or extension; when a document editor does not follow the WG consensus, the WG Chairs will either be more forceful about getting changes that match the consensus or replace the document editor with someone more responsive to the WG. As a Working Group document is progressing, participants suggest changes on the Working Group's mail list; the editors are expected to follow the discussion and make changes when there is agreement.

If a participant makes significant contributions, the document editor or chair can invite the participant to become a co-author or co-editor, although such an addition needs to be approved by the WG Chairs. Sometimes a Working Group will consider several alternatives before selecting a particular Internet-Draft as a Working Group document. A Working Group will often take ideas from several of the alternatives to create a single Working Group document; in such a case, the chair determines who will be listed as authors on the title page and who will be acknowledged as contributors in the body of the document.

When a WG document is ready to progress beyond the WG, the WG Chairs will assign a "shepherd" to take over the final process. The role of the document shepherd is described in [RFC4858].

4.4 Preparing for Working Group Meetings

The most important thing that everyone (newcomers and seasoned experts) should do before coming to a face-to-face meeting is to read the Internet-Drafts and RFCs ahead of time. WG meetings are explicitly not for education: they are for developing the group's documents. Even if you do not plan to say anything in the meeting, you should read, or at least skim, the group's documents before attending so you can understand what is being said.

It's up to the WG chairs to set the meeting agenda, usually a few weeks in advance. If you want something discussed at the meeting, be sure to let the chair know about it. The agendas for all the WG meetings are available in advance on the IETF web site, but some WG chairs are lax (if not totally negligent) about turning them in.

The Secretariat only schedules WG meetings a few weeks in advance, and the schedule often changes as little as a week before the first day. If you are only coming for one WG meeting, you may have a hard time booking your flight with such little notice, particularly if the Working Group's meeting changes schedule. Be sure to keep track of the current agenda so you can schedule flights and hotels. But, when it comes down to it, you probably shouldn't be coming for just one WG meeting. It's likely that your knowledge could be valuable in a few WGs, assuming that you've read the drafts and RFCs for those groups. Work in the IETF is often reciprocal, contribute positively to others work and your more likely to receive comments and feedback on your work.

If you are on the agenda at a face-to-face meeting, you should probably come with a few slides prepared. But don't come with a tutorial; people are supposed to read the drafts in advance. Projectors for laptop-based presentations are available in all the meeting rooms.

And here's a tip for your slides in WG or plenary presentations: don't put your company's logo on every one, even though that is a common practice outside the IETF. The IETF frowns on this kind of corporate advertising (except for the meeting sponsor in the plenary presentation), and most presenters don't even put their logo on their opening slide. The IETF is about technical content, not company boosterism. Slides are often plain black and white for legibility, with color used only when it really adds clarity. Again, the content is the most important part of the slides, not how it's presented.

One thing you might find helpful, and possibly even entertaining, during Working Group sessions is to follow the running commentary on the Jabber room associated with that Working Group. The running commentary is often used as the basis for the minutes of the meeting, but it can also include jokes, sighs, and other extraneous chatter. Jabber is a free, streaming XML technology mainly used for instant messaging. You can find pointers to Jabber clients for many platforms at [https://xmpp.org/xmpp-software/clients]. The Jabber chatrooms have the name of the Working Group followed by "@jabber.ietf.org". Those rooms are, in fact, available year-round, not just during IETF meetings, and some are used by active Working Group participants during protocol development.
4.5 Working Group Mailing Lists

As we mentioned earlier, the IETF announcement and discussion mailing lists are the central mailing lists for IETF activities. However, there are many other mailing lists related to IETF work. For example, every Working Group has its own discussion list. In addition, there are some long-term technical debates that have been moved off of the IETF list onto lists created specifically for those topics. It is highly recommended that you follow the discussions on the mailing lists of the Working Groups that you wish to attend. The more work that is done on the mailing lists, the less work that will need to be done at the meeting, leaving time for cross pollination (i.e., attending Working Groups outside one's primary area of interest in order to broaden one's perspective).

The mailing lists also provide a forum for those who wish to follow, or contribute to, the Working Groups' efforts, but can't attend the IETF meetings. That's why IETF procedures require all decisions to be confirmed "on the list" and you will often hear a WG chair say, "Let's take it to the list" to close a discussion.

Many IETF discussion lists use either mailman or another list manager, Majordomo. They usually have a "-request" address that handles the administrative details of joining and leaving the list. (See Section 2.3 for more information on mailman.) It is generally frowned upon when such administrivia appears on the discussion mailing list.

IETF discussion lists are archived. That is, all of the messages sent to the list are automatically stored and made accessible. Many such archives are listed online at [https://mailarchive.ietf.org/]. If you don't find the list you're looking for, send a message to the list's "-request" address (not to the list itself!). The Working Group charter listings at https://datatracker.ietf.org/wg are a useful source. [https://www6.ietf.org/wg/concluded] is a list of old, concluded WGs.

Some WG lists apply size limits on messages, particularly to avoid large documents or presentations landing in everyone's mailbox. It is well worth remembering that participants do not all have broadband connections (and even those with broadband connections sometimes get their mail on slow connections when they travel), so shorter messages are greatly appreciated. Documents can be posted as Internet-Drafts; presentation material can be posted to a web site controlled by the sender or sent personally to people who ask for it. Some WGs set up special sites to hold these large documents so that senders can post there first, then just send to the list the URL of the document.

4.6 Interim Working Group Meetings

Working Groups sometimes hold interim meetings between IETFs. Interim meetings aren't a substitute for IETF meetings, however — a group can't decide to skip a meeting in a location they're not fond of and meet in Cancun (or even someplace mundane) three weeks later, for example. Interim meetings require AD approval and need to be announced at least one month in advance. Location and timing need to allow fair access for all participants. Like regular IETF meetings, someone needs to take notes and the group needs to take attendance. Decisions tentatively made during an interim WG meeting still must be ratified on the mailing list.

In recent years, some Working Groups have started to have "virtual interim meetings" which take place over the phone and/or online instead of face-to-face. Virtual interim meetings can be useful for getting Working Groups to pay attention to their work between the regular IETF face-to-face meetings, and have a much lower cost for attendance than face-to-face interim meetings. Virtual interim meetings have the same reporting requirements as face-to-face virtual meetings.

The IESG has rules for advance notice on time and place of interim Working Group meetings, as well as reporting the results of the meetings. The purpose of these rules is to make interim meetings accessible to as many Working Group members as possible and to maintain the transparency of the Working Group process.

5. BOFs

In order to form a Working Group, you need a charter and someone who is able to be chair. In order to get those things, you need to get people interested so that they can help focus the charter and convince an Area Director that the project is worthwhile. A face-to-face meeting is useful for this. In fact, very few WGs get started by an Area Director; most start after a face-to-face BOF because attendees have expressed interest in the topic.

A Birds of a Feather (BOF) meeting has to be approved by the Area Director in the relevant Area before it can be scheduled. If you think you really need a new WG, approach an AD informally with your proposal and see what he or she thinks. The next step is to request a meeting slot at the next face-to-face meeting. Of course, you don't need to wait for that meeting to get some work done, such as setting up a mailing list and starting to discuss a charter.

BOF meetings have a very different tone than do WG meetings. The purpose of a BOF is to make sure that a good charter with good milestones can be created and that there are enough people willing to do the work needed in order to create standards. Some BOFs have Internet-Drafts already in process, whereas others start from scratch.

An advantage of having a draft before the BOF is to help focus the discussion. On the other hand, having a draft might tend to limit what the other folks in the BOF want to do in the charter. It's important to remember that most BOFs are held in order to get support for an eventual Working Group, not to get support for a particular document.

Many BOFs don't turn into WGs for a variety of reasons. A common problem is that not enough people can agree on a focus for the work. Another typical reason is that the work wouldn't end up being a standard — if, for example, the document authors don't really want to relinquish change control to a WG. (We'll discuss change control later in this document.) Only two meetings of a BOF can be scheduled on a particular subject; either a WG has to form or the topic should be dropped.

6. RFCs and Internet-Drafts

This section discusses Internet-Drafts and RFCs in the IETF stream, that is, it describes how documents are produced and advanced within the IETF. For a brief note on other RFC streams, see Section 2.2.5.

If you're a new IETF participant and are looking for a particular RFC or Internet-Draft, go to the IETF Datatracker [https://datatracker.ietf.org/]. That site has many search capabilities and can help you find the right document and information about its status, dependencies, potential updates and other information. Another entry point for searching and navigating RFCs is Mark Nottingham's EveryRFC [https://everyrfc.org/].

6.1 Getting an RFC Published

One of the most common questions seasoned IETFers hear from newcomers is, "How do I get an IETF standard published?" A much better question is, "Should I write an IETF standard?" since the answer is not always "yes". If you do decide to try to write a document that becomes an IETF standard, be warned that the overall process may be arduous, even if the individual steps are fairly straightforward. Lots of people get through the process unscathed, though, and there's plenty of written guidance that helps authors emerge with their ego more or less intact.

One of the first things you must decide is whether you want your document to be considered in a Working Group, of you want it to be considered as an individual (that is, non-WG) submission to the IETF. Even though most IETF standards come from Working Groups, some are individual efforts: there might be no appropriate Working Group, or a potentially-appropriate Working Group might be to busy on other work to consider your idea.

Every IETF standard is published as an RFC ("Request for Comments"), and every RFC starts out as an Internet-Draft (often called an "I-D" or just "draft"). The basic steps for getting something published as an IETF standard are as follows:

    - Publish the document as an Internet-Draft.
    - Receive comments on the draft.
    - Edit your draft based on the comments.
    - Repeat steps 1 through 3 a few times.
    - Ask an Area Director to take the draft to the IESG (if it's an individual submission). If the draft is an official Working Group product, the WG chair asks the AD to take it to the IESG.
    - If the Area Director accepts the submission, they will do their own initial review, and maybe ask for updates before they move it forwards.
    - Get reviews from the wider IETF membership. In particular, some of the Areas in the IETF have formed review teams to look over drafts that are ready to go to the IESG.
    - Discuss concerns with the IESG members. Their concerns might be resolved with a simple answer, or they might require additions or changes to the document.
    - Wait for the document to be published by the RFC Editor.

A much more complete explanation of these steps is contained in [BCP9], "The Internet Standards Process". Those who write drafts that they hope will become IETF standards must read BCP 9 so that they can follow the path of their document through the process. You can follow the progress on the IETF Datatracker [https://datatracker.ietf.org]. BCP 9 (and various other documents that update it) goes into great detail on a topic that is very often misunderstood, even by seasoned IETF participants: different types of RFCs go through different processes and have different rankings. There are six kinds of RFCs:

    - Proposed standards
    - Internet standards (sometimes called "full standards")
    - Best current practices (BCP) documents
    - Informational documents
    - Experimental documents
    - Historic documents
    Only the first two, proposed and full, are standards within the IETF. A good summary of this can be found in the aptly titled [RFC 1796], "Not All RFCs Are Standards".

There are also two sub-series of RFCs, known as BCPs and STDs. Best Current Practice documents describe the application of various technologies in the Internet, and are also commonly used to document the many parts of the IETF process. The sub-series of FYIs are comprised of "Informational documents" in the sense of the enumeration above, with special tagging applied. (There was also a "For Your Information" RFC sub-series that was created to document overviews and topics that are introductory or that appeal to a broad audience; however, that series has been officially closed.)

The STD RFC sub-series was created to identify RFCs that do in fact specify Internet standards. Some STDs are actually sets of more than one RFC, and the "standard" designation applies to the whole set of documents.

6.2 Letting Go Gracefully

The biggest reason some people do not want their documents put on the IETF standards track is that they must give up change control of the protocol. That is, as soon as you propose that your protocol become an IETF standard, you must fully relinquish control of the protocol. If there is general agreement, parts of the protocol can be completely changed, whole sections can be ripped out, new things can be added, and the name can be changed.

Some authors find it very hard to give up control of their pet protocol. If you are one of those people, don't even think about trying to get your protocol to become an IETF standard. On the other hand, if your goal is the best standard possible with the widest implementation, then you might find the IETF process to your liking.

Incidentally, the change control on Internet standards doesn't end when the protocol is put on the standards track. The protocol itself can be changed later for a number of reasons, the most common of which is that implementors discover a problem as they implement the standard. These later changes are also under the control of the IETF, not the editors of the standards document.

IETF standards exist so that people will use them to write Internet programs that interoperate. They don't exist to document the (possibly wonderful) ideas of their authors, nor do they exist so that a company can say, "We have an IETF standard". If a standards- track RFC only has one implementation (whereas two are required for it to advance on the standards track), it was probably a mistake to put it on the standards track in the first place.

Note that new authors cannot take someone else's document and pass it off as their own; see [BCP78], section 5.6, point (a).

6.3 Internet-Drafts

First things first. Every document that ends up in the RFC repository starts life as an Internet-Draft. Internet-Drafts are tentative documents — they're meant for readers to comment on, so authors can mull over those comments and decide which ones to incorporate in the draft. In order to remind folks of their tentativeness, Internet-Drafts are automatically removed from the active online directories after six months. They are most definitely not standards. As [BCP9] says:

"An Internet-Draft is NOT a means of 'publishing' a specification; specifications are published through the RFC mechanism.... Internet-Drafts have no formal status, and are subject to change or removal at any time. Under no circumstances should an Internet-Draft be referenced by any paper, report, or Request-for-Proposal, nor should a vendor claim compliance with an Internet-Draft".

You can always tell a person who doesn't understand the IETF (or is intentionally trying to fool people) when he or she brags about having published an Internet-Draft; it takes no significant effort.

When you submit an Internet-Draft, you give some publication rights to the IETF. This is so that your Internet-Draft is freely available to everyone who wants to read and comment on it. The rights you do and don't give to the IETF are described in [BCP78], "IETF Rights in Contributions".

There is a very useful checking tool at [https://tools.ietf.org/tools/idnits]. Using this tool before you turn in an Internet-Draft will help prevent the draft from being rejected due to errors in form and formatting.

An I-D should have approximately the same format as an RFC. Contrary to many people's beliefs, an I-D does not need to look exactly like an RFC, but if you can use the same formatting procedures used by the RFC Editor when you create your I-Ds, it will simplify the RFC Editor's work when your draft is published as an RFC. [RFC2223], "Instructions to RFC Authors", describes the submission format. There is also a tool called "xml2rfc", available from [https://xml2rfc.tools.ietf.org], that takes XML-formatted text and turns it into a valid Internet-Draft, you can also use a tool called kramdown, available from [https://github.com/cabo/kramdown-rfc2629], that takes markdown-formatted text and turns it into a valid Internet-Draft.

An Internet-Draft can be either a Working Group draft or an individual submission. Working Group drafts are usually reviewed by the Working Group before being accepted as a WG item, although the chairs have the final say.

If you're interested in checking the status of a particular draft, or can't remember its exact name, or want to find out which drafts a WG is working on, two handy tools are available. The "Internet-Drafts Database Interface", at https://datatracker.ietf.org/doc, lets you search for a draft by author, Working Group, date, or filename. This is especially useful for authors who want to track the progress of their draft as it makes its way through the publication process.

There are some informal rules for Internet-Draft naming that have evolved over the years. Internet-Drafts that revise existing RFCs often have draft names with "bis" in them, meaning "again" or "twice"; for example, a draft might be called "draft-someone-rfc2345bis-00.txt".

6.3.1 Recommended Reading for Writers

Before you create the first draft of your Internet-Draft, you should read four documents:

    - More important than just explaining formatting, [RFC2223] also explains what needs to be in an Internet-Draft before it can become an RFC. This document describes all the sections and notices that will need to be in your document, and it's good to have them there from the beginning so that readers aren't surprised when you put them in later versions.
    - [BCP22], "Guide for Internet Standards Writers", provides tips that will help you write a standard that leads to interoperability. For instance, it explains how to choose the right number of protocol options, how to respond to out-of-spec behavior, and how to show state diagrams.
    - The online "Guidelines to Authors of Internet-Drafts", [https://www.ietf.org/ietf/1id-guidelines.txt], has up-to-date information about the process for turning in Internet-Drafts, as well as the most current boilerplate information that has to be included in each Internet-Draft.
    - When you think you are finished with the draft process and are ready to request that the draft become an RFC, you should definitely read "Checklist for Internet-Drafts (I-Ds) Submitted for RFC Publication", [https://www.ietf.org/standards/ids/guidelines], a list of common issues that have been known to stop documents in the IESG. In fact, you should probably read that document well before you are finished, so that you don't have to make a bunch of last-minute changes.
    There are also guides specific to important areas to cover in your draft, such as the Security Considerations (RFC3552) and even templates for drafts the occur frequently such as YANG modules (RFC6087) and mibs (RFC4181).
    The templates and scripts from Martin Thomson, [https://github.com/martinthomson/i-d-template], might help you more easily write an Internet-Draft and automate the submission process. 

Also, you should visit the IETF Tools web pages, [https://tools.ietf.org], where you'll find pointers to other tools that will automate some of your work for the IETF.

6.3.2 Filenames and Other Matters

When you're ready to turn in your Internet-Draft, you submit it to [https://datatracker.ietf.org/submit]. The instructions on that web page will walk you through the needed steps, and there is also an email address there in case you need personalized help.

When you submit the first version of the draft, you also tell the draft administrator your proposed filename for the draft. If the draft is an official Working Group product, the name will start with "draft-ietf-" followed by the designation of the WG, followed by a descriptive word or two, followed by "00.txt".

For example, a draft in the S/MIME WG about creating keys might be named "draft-ietf-smime-keying-00.txt". If it's not the product of a Working Group, the name will start with "draft-" and the last name of one of the authors followed by a descriptive word or two, followed by "00.txt". For example, a draft that someone named Smith wrote might be named "draft-smith-keying-00.txt". If a draft is an individual submission but relates to a particular Working Group, authors sometimes follow their name with the name of the Working Group, such as "draft-smith-smime-keying-00.txt". If you follow the naming guidelines given at [https://www.ietf.org/ietf/1id-guidelines.txt], chances are quite good that your suggested filename will be fine.

After the first edition of a draft, the number in the filename is incremented; for instance, the second edition of the S/MIME draft named above would be "draft-ietf-smime-keying-01.txt". Note that there are cases where the filename changes after one or more versions, such as when a personal effort is pulled into a Working Group; when a draft has its filename changed, the number reverts to -00. The WG chairs will let the Internet-Drafts administrator know the previous name of the draft when such a name change occurs so that the databases can be kept accurate.
6.4 Standards-Track RFCs

The procedure for creating and advancing a standard is described in [BCP9]. After an Internet-Draft has been sufficiently discussed and there is rough consensus that what it says would be a useful standard, it is presented to the IESG for consideration. If the draft is an official WG draft, the WG chair sends it to the appropriate Area Director. If the draft is an individual submission, the draft's author or editor submits it to the appropriate Area Director. BCP 9 also describes the appeals process for people who feel that a Working Group chair, an AD, or the IESG has made the wrong decision in considering the creation or advancement of a standard.

After the I-D is submitted to the IESG, the IESG announces an IETF-wide Last Call (often abbreviated as "LC"). This helps get the attention of people who weren't following the progress of the draft, and can sometimes cause further changes to the draft. It is also a time when people in the WG who feel that they weren't heard can make their comments to everyone. The IETF Last Call is at least two weeks for drafts coming from WGs and four weeks for individual submissions.

The purpose of IETF Last Call is to get community-wide discussion on documents before the IESG considers them. Note the word "discussion" here. It is generally considered bad form to send IETF Last Call comments on documents that you have not read, or to send comments but not be prepared to discuss your views. The IETF Last Call is not a vote, and campaigns aimed at getting people to send support or opposition to a document usually backfire. Having said that, IETF Last Call comments that come from people who have just read the document for the first time can expose issues that IETF and WG regulars may have completely missed, which is why the discussion is open to everyone.

If the IESG approves the draft to become a standards-track RFC, they ask the RFC Editor to publish it as a Proposed standard. A few things typically happen at this point. First, it's common to find that some of the specifications in the standard need to be reworded because one implementor thought they meant one thing whereas another implementor thought they meant something else. Another common occurrence is that none of the implementations actually tried to implement a few of the features of the standard; these features get removed not just because no one tested them but also because they weren't needed.

Don't be surprised if a particular standard doesn't progress from Proposed Standard to Internet Standard. To become an Internet Standard, an RFC must have multiple interoperable implementations and the unused features in the Proposed Standard must be removed; there are additional requirements listed in [BCP9]. Most of the standards in common use are Proposed standards and never move forward. This may be because no one took the time to try to get them to Internet Standard, or some of the normative references in the standard are still at Proposed standard, or it may be that everyone found more important things to do.
6.4.1 Telling It Like It Is - Using MUST and SHOULD and MAY

Writing specifications that get implemented the way you want is a bit of an art. You can keep the specification very short, with just a list of requirements, but that tends to cause implementors to take too much leeway. If you instead make the specification very wordy with lots of suggestions, implementors tend to miss the requirements (and often disagree with your suggestions anyway). An optimal specification is somewhere in between.

One way to make it more likely that developers will create interoperable implementations of standards is to be clear about what's being mandated in a specification. Early RFCs used all kinds of expressions to explain what was needed, so implementors didn't always know which parts were suggestions and which were requirements. As a result, standards writers in the IETF generally agreed to limit their wording to a few specific words with a few specific meanings.

[STD3], "Requirements for Internet Hosts -- Application and Support", written way back in 1989, had a short list of words that had appeared to be useful, namely, "must", "should", and "may". These definitions were updated and further refined in [BCP14], "Key words for use in RFCs to Indicate Requirement Levels", which is widely referenced in current Internet standards. BCP 14 also specifically defines "must not" and "should not", and it lists a few synonyms for the words defined.

In a standard, in order to make it clear that you're using the definitions from BCP 14, you should do two things. First, refer to BCP 14 (although most people refer to it as RFC 2119, because that's what BCP 14 tells you to do), so that the reader knows how you're defining your words. Second, you should point out which instances of the words you are using come from BCP 14. The accepted practice for this is to capitalize the words. That is why you see "MUST" and "SHOULD" capitalized in IETF standards.

BCP 14 is a short document, and it should be read by everyone who is reading or writing IETF standards. Although the definitions of "must" and "must not" are fairly clear, the definitions of "should" and "should not" cause a great deal of discussion in many WGs. When reviewing an Internet-Draft, the question is often raised, "Should that sentence have a MUST or a SHOULD in it?" This is, indeed, a very good question, because specifications shouldn't have gratuitous MUSTs, but also should not have SHOULDs where a MUST is needed for interoperability. This goes to the crux of the question of over-specifying and under-specifying requirements in standards.
6.4.2 Normative References in Standards

One aspect of writing IETF standards that trips up many novices (and quite a few long-time IETF folks) is the rule about how to make "normative references" to non-IETF documents or to other RFCs in a standard. A normative reference is a reference to a document that must be followed in order to implement the standard. A non-normative reference (sometimes called an "informative reference") is one that is helpful to an implementor but is not needed.

An IETF standard may make a normative reference to any other standards-track RFC that is at the same standards level or higher, or to any "open standard" that has been developed outside the IETF. The "same level or higher" rule means that before a standard can move from Proposed to Draft, all of the RFCs for which there is a normative reference must also be at Draft or Internet standard. This rule is described in [BCP97]. This rule gives implementors assurance that everything in a Internet standard is quite stable, even the things referenced outside the standard. This can also delay the publication of the Draft or Internet standard by many months (sometimes even years) while the other documents catch up.

There is no hard-and-fast rule about what is an "open standard", but generally this means a stable standard that anyone can get a copy of (although they might have to pay for it) and that was made by a generally recognized standards group. If the external standard changes, you have to reference the particular instantiation of that standard in your specification, as with a designation of the date of the standard. Some external standards bodies don't make old standards available, which is a problem for IETF standards that need to be used in the future. When in doubt, a draft author should ask the WG chair or appropriate Area Director if a particular external standard can be used in an IETF standard.
6.4.3 IANA Considerations

More and more IETF standards require the registration of various protocol parameters, such as named options in the protocol. As we noted in Section 2.2.4, the main registry for all IETF standards has long been IANA. Because of the large and diverse kinds of registries that standards require, IANA needs to have specific information about how to register parameters, what not to register, who (if anyone) will decide what is to be registered, and so on.

Anyone writing an Internet standard that may need a new IANA registry or new values in a current IANA registry needs to read [BCP26], "Guidelines for Writing an IANA Considerations Section in RFCs", which describes how RFC authors should properly ask for IANA to start or take over a registry. IANA also maintains registries that were started long before BCP 26 was produced.

6.4.4 Security Considerations

One thing that's required in every RFC and Internet-Draft is a "Security Considerations" section. This section should describe any known vulnerabilities of the protocol, possible threats, and mechanisms or strategies to address them. Don't gloss over this section — in particular, don't say, "Here's our protocol, if you want security, just use IPsec". This won't do at all, because it doesn't answer the question of how IPsec interacts with your protocol, and vice versa. See [BCP72], "Guidelines for Writing RFC Text on Security Considerations", for more information on writing good security considerations sections.

6.4.5 Patents in IETF Standards

The problems of intellectual property have cropped up more and more often in the past few years, particularly with respect to patents. The goal of the IETF is to have its standards widely used and validated in the marketplace. If creating a product that uses a standard requires getting a license for a patent, people are less likely to implement the standard. Not surprisingly, then, the general rule has been "use good non-patented technology where possible".

Of course, this isn't always possible. Sometimes patents appear after a standard has been established. Sometimes there's a patent on something that is so valuable that there isn't a non-patented equivalent. Sometimes the patent holder is generous and promises to give all implementors of a standard a royalty-free license to the patent, thereby making it almost as easy to implement as it would have been if no patent existed.

The IETF's methods for dealing with patents in standards are a subject of much debate. The official rules for all intellectual property rights (IPR) in IETF documents (not just patents) are covered in [BCP78] and [BCP79], "Intellectual Property Rights in IETF Technology". Everyone who participates in IETF Working Groups will probably find these documents interesting because they lay out the rules that everyone agrees to follow.

Patent holders who freely allow their patents to be used by people implementing IETF standards often get a great deal of goodwill from the folks in the IETF. Such generosity is more common than you might think. For example, RFC 1822 is a license from IBM for one of its security patents in a particular protocol context, and the security community has responded very favorably to IBM for this (whereas a number of other companies have made themselves pariahs for their intractability on their security patents).

If you are writing an Internet-Draft and you know of a patent that applies to the technology you're writing about, don't list the patent in the document. Instead, consult the IETF IPR page at https://datatracker.ietf.org/ipr/about to determine how to proceed. Intellectual property rights aren't mentioned in RFCs because RFCs never change after they are published, but knowledge of IPR can change at any time. Therefore, an IPR list in an RFC could be incomplete and mislead the reader. [BCP79] provides specific text that should be added to RFCs where the author knows of IPR issues.

6.5 Informational and Experimental RFCs

As we noted earlier, not all RFCs are standards. In fact, plenty of important RFCs are not on the standards track at all. Currently, there are two designations for RFCs that are not meant to be standards: Informational, like the Tao, and Experimental. (There is actually a third designation, Historic, but that is reserved for documents that were on the standards track and have been removed due to lack of current use, or that more recent thinking indicates the technology is actually harmful to the Internet.)

The role of Informational RFCs is often debated in the IETF. Many people like having them, particularly for specifications that were created outside the IETF but are referenced by IETF documents. They are also useful for specifications that are the precursors for work being done by IETF Working Groups. On the other hand, some people refer to Informational RFCs as "standards" even though the RFCs are not standards, usually to fool the gullible public about something that the person is selling or supporting. When this happens, the debate about Informational RFCs is renewed.

Experimental RFCs are for specifications that may be interesting, but for which it is unclear if there will be much interest in implementing them, or whether they will work once deployed. That is, a specification might solve a problem, but if it is not clear that many people think that the problem is important, or think that they will bother fixing the problem with the specification, the specification might be labeled an Experimental RFC. If, later, the specification becomes popular (or proves that it works well), it can be re-issued as a standards-track RFC. Experimental RFCs are also used to get people to experiment with a technology that looks like it might be standards-track material, but for which there are still unanswered questions.

The IESG has created guidelines on how it chooses between Informational and Experimental status: [https://ietf.org/standards/process/informational-vs-experimental]. If you are creating a document that you think might become an Experimental RFC, knowing the current thinking will help you justify your proposed choice.

7. How to Contribute to the IETF

7.1 What You Can Do

Read — Review the Internet-Drafts in your area of expertise and comment on them in the Working Groups. Participate in the discussion in a friendly, helpful fashion, with the goal being the best Internet standards possible. Listen much more than you speak. If you disagree, debate the technical issues: never attack the people.

Implement — Write programs that use the current Internet standards. The standards aren't worth much unless they are available to Internet users. Implement even the "minor" standards, since they will become less minor if they appear in more software. Report any problems you find with the standards to the appropriate Working Group so that the standard can be clarified in later revisions. One of the oft-quoted tenets of the IETF is "running code wins", so you can help support the standards you want to become more widespread by creating more running code. You can help the development of protocols before they become standards by implementing (but not deploying) from I-Ds to ensure that the authors have done a good job. If you find errors or omissions, offer improvements based on your implementation experience.

Write — Edit or co-author Internet-Drafts in your area of expertise. Do this for the benefit of the Internet community, not to get your name (or, even worse, your company's name) on a document. Draft authors are subject to all kinds of technical (and sometimes personal) criticism; receive it with equanimity and use it to improve your draft in order to produce the best and most interoperable standard.
7.2 What Your Company Can Do

Share — Avoid proprietary standards. If you are an implementor, exhibit a strong preference for IETF standards. If the IETF standards aren't as good as the proprietary standards, work to make the IETF standards better. If you're a purchaser, avoid products that use proprietary standards that compete with the open standards of the IETF and tell the companies you buy from that you are doing so.

Open Up — If your company controls a patent that is used in an IETF standard, convince the company to make the patent available at no cost to everyone who is implementing the standard. In the past few years, patents have caused a lot of serious problems for Internet standards because they prevent some companies from being able to freely implement the standards. Fortunately, many companies have generously offered unlimited licenses for particular patents in order to help the IETF standards flourish. These companies are usually rewarded with positive publicity for the fact that they are not as greedy or short-sighted as other patent-holders.

Join — Become a member of ISOC. More important, urge any company that has benefited from the Internet to become a corporate member of ISOC, since this has the greatest financial benefit for the group. It will, of course, also benefit the Internet as a whole.

8. IETF and the Outside World
8.1 IETF and Other Standards Groups

As much as many IETF participants would like to think otherwise, the IETF does not exist in a standards vacuum. There are many (perhaps too many) other standards organizations whose decisions affect the Internet. There are also a fair number of standards bodies that ignored the Internet for a long time and now want to get a piece of the action.

In general, the IETF tries to have cordial relationships with other standards bodies. This isn't always easy, since many other bodies have very different structures than the IETF does, and the IETF is mostly run by volunteers who would probably prefer to write standards rather than meet with representatives from other bodies. Even so, some other standards bodies make a great effort to interact well with the IETF despite the obvious cultural differences.

At the time of this writing, the IETF has some liaisons with large standards bodies, including the ITU-T (the Telecommunication Standardization Sector of the International Telecommunication Union), the W3C (World Wide Web Consortium), the IEEE (the Institute of Electrical and Electronics Engineers), and the Unicode Consortium. As stated in the IAB Charter [BCP39], "Liaisons are kept as informal as possible and must be of demonstrable value in improving the quality of IETF specifications". In practice, the IETF prefers liaisons to take place directly at Working Group level, with formal relationships and liaison documents in a backup role.

Some of these liaison tasks fall to the IESG, whereas others fall to the IAB. Detail-oriented readers will learn much about the formal methods for dealing with other standards bodies in [BCP102], "IAB Processes for Management of IETF Liaison Relationships", and [BCP103], "Procedures for Handling Liaison Statements to and from the IETF". The best place to check to see whether the IETF has any formal liaison at all is the list of IETF liaisons, [https://www.ietf.org/about/liaisons].

8.2 Press Coverage of the IETF

Given that the IETF is one of the best-known bodies that is helping move the Internet forward, it's natural for the computer press (and even the trade press) to want to cover its actions. In recent years, a small number of magazines have assigned reporters and editors to cover the IETF in depth over a long period of time. These reporters have ample scars from articles that they got wrong, incorrect statements about the status of Internet-Drafts, quotes from people who are unrelated to the IETF work, and so on.

Major press errors fall into two categories: saying that the IETF is considering something when in fact there is just an Internet-Draft in a Working Group, and saying that the IETF approved something when all that happened was that an Informational RFC was published. In both cases, the press is not fully to blame for the problem, since they are usually alerted to the story by a company trying to get publicity for a protocol that they developed or at least support. The default place that press should look for press contacts for the IETF is [https://www.ietf.org/contact].

The fact that those reporters who've gotten it wrong once still come back to IETF meetings shows that it is possible to get it right eventually. However, IETF meetings are definitely not for reporters who are naive about the IETF process (although if you are a reporter the fact that you are reading this document is a very good sign!). Furthermore, if you think that you'll get a hot story from attending an IETF meeting, you are likely to be disappointed.

Considering all this, it's not surprising that some IETFers would prefer to have the press stay as far away from meetings as possible. Having a bit of press publicity for protocols that are almost near completion and will become significant in the industry in the next year can be a good thing. However, it is the rare reporter who can resist over-hyping a nascent protocol as the next savior for the Internet. Such stories do much more harm than good, both for the readers of the article and for the IETF.

The main reason why a reporter might want to attend an IETF meeting is not to cover hot technologies (since that can be done in the comfort of your office by reading the mailing lists) but to meet people face-to-face. Unfortunately, the most interesting people are the ones who are also the busiest during the IETF meeting, and some folks have a tendency to run away when they see a press badge. However, IETF meetings are excellent places to meet and speak with document authors and Working Group chairs; this can be quite valuable for reporters who are covering the progress of protocols.

Reporters who want to find out about "what the IETF is doing" on a particular topic would be well-advised to talk to more than one person who is active on that topic in the IETF, and should probably try to talk to the WG chair in any case. It's impossible to determine what will happen with a draft by looking at the draft or talking to the draft's author. Fortunately, all WGs have archives that a reporter can look through for recent indications about what the progress of a draft is; unfortunately, few reporters have the time or inclination to do this kind of research. Because the IETF doesn't have a press liaison, magazines or newspapers that run a story with errors won't hear directly from the IETF and therefore often won't know what they did wrong, so they might easily do it again later.

9. Security Considerations

Section 6.4.4 explains why each RFC is required to have a Security Considerations section and gives some idea of what it should and should not contain. Other than that information, this document does not touch on Internet security.

10. Informative References

[BCP9](https://tools.ietf.org/html/bcp9) Bradner, S., “The Internet Standards Process -- Revision 3”, BCP 9, RFC 2026, RFC 6410, October 1996.

[BCP10](https://tools.ietf.org/html/bcp10) Galvin, J., “IAB and IESG Selection, Confirmation, and Recall Process: Operation of the Nominating and Recall Committees”, BCP 10, RFC 3777, June 2004.

[BCP11](https://tools.ietf.org/html/bcp11) Hovey, R. and S. Bradner, “The Organizations Involved in the IETF Standards Process”, BCP 11, RFC 2028, October 1996.

[BCP14](https://tools.ietf.org/html/bcp14) Bradner, S., “Key words for use in RFCs to Indicate Requirement Levels”, BCP 14, RFC 2119, March 1997.

[BCP22](https://tools.ietf.org/html/bcp22) Scott, G., “Guide for Internet Standards Writers”, BCP 22, RFC 2360, June 1998.

[BCP25](https://tools.ietf.org/html/bcp25) Bradner, S., “IETF Working Group Guidelines and Procedures”, BCP 25, RFC 2418, September 1998.

[BCP26](https://tools.ietf.org/html/bcp26) Narten, T. and H. Alvestrand, “Guidelines for Writing an IANA Considerations Section in RFCs”, BCP 26, RFC 5226, May 2008.

[BCP39](https://tools.ietf.org/html/bcp39) Internet Architecture Board and B. Carpenter, “Charter of the Internet Architecture Board (IAB)”, BCP 39, RFC 2850, May 2000.

[BCP45](https://tools.ietf.org/html/bcp45) Harris, S., “IETF Discussion List Charter”, BCP 45, RFC 3005, November 2000.

[BCP72](https://tools.ietf.org/html/bcp72) Rescorla, E. and B. Korver, “Guidelines for Writing RFC Text on Security Considerations”, BCP 72, RFC 3552, July 2003.

[BCP78](https://tools.ietf.org/html/bcp78) Bradner, S., “IETF Rights in Contributions”, BCP 78, RFC 5378, November 2008.

[BCP79](https://tools.ietf.org/html/bcp79) Bradner, S., “Intellectual Property Rights in IETF Technology”, BCP 79, RFC 3979, March 2005.

[BCP95](https://tools.ietf.org/html/bcp95) Alvestrand, H., “A Mission Statement for the IETF”, BCP 95, RFC 3935, October 2004.

[BCP97](https://tools.ietf.org/html/bcp97) Bush, R. and T. Narten, “Clarifying when Standards Track Documents may Refer Normatively to Documents at a Lower Level”, BCP 97, RFC 3967, December 2004.

[BCP101](https://tools.ietf.org/html/bcp101) Austein, R. and B. Wijnen, “Structure of the IETF Administrative Support Activity (IASA)”, BCP 101, RFC 4071, April 2005.

[BCP102](https://tools.ietf.org/html/bcp102) Daigle, L. and Internet Architecture Board, “IAB Processes for Management of IETF Liaison Relationships”, BCP 102, RFC 4052, April 2005.

[BCP103](https://tools.ietf.org/html/bcp103) Trowbridge, S., Bradner, S., and F. Baker, “Procedures for Handling Liaison Statements to and from the IETF”, BCP 103, RFC 4053, April 2005

[RFC1796](https://tools.ietf.org/html/rfc1796) Huitema, C., Postel, J., and S. Crocker, “Not All RFCs are Standards”, RFC 1796, April 1995.

[RFC2223](https://tools.ietf.org/html/rfc2223) Postel, J. and J. Reynolds, “Instructions to RFC Authors”, RFC 2223, October 1997.

[RFC2860](https://tools.ietf.org/html/rfc2860) Carpenter, B., Baker, F., and M. Roberts, “Memorandum of Understanding Concerning the Technical Work of the Internet Assigned Numbers Authority”, RFC 2860, June 2000.

[RFC6635](https://tools.ietf.org/html/rfc6635) Kolkman, O. and J. Halpern, “RFC Editor Model (Version 2)”, RFC 6635, March 2012.

[RFC4677](https://tools.ietf.org/html/rfc4677) Hoffman, P. and S. Harris, “The Tao of IETF - A Novice's Guide to the Internet Engineering Task Force”, RFC 4677, September 2006.

[RFC4858](https://tools.ietf.org/html/rfc4858) Levkowetz, H., Meyer, D., Eggert, L., and A. Mankin, “Document Shepherding from Working Group Last Call to Publication”, RFC 4858, May 2007.

[RFC6722](https://tools.ietf.org/html/rfc6722) Hoffman, P., “Publishing the "Tao of the IETF" as a Web Page”, RFC 6722, August 2012.

[STD3](https://tools.ietf.org/html/std3) Braden, R., “Requirements for Internet Hosts - Application and Support”, STD 3, RFC 1123, October 1989.

A. IETF Guiding Principles

If you've gotten this far in the Tao, you've learned a lot about how the IETF works. What you'll find in this appendix summarizes much of what you've read and adds a few new points to ponder. Be sure to read through all the principles; taken as a whole, they'll give you a new slant on what makes the IETF work.

A.1 General

The IETF works by an open process and by rough consensus. This applies to all aspects of the operation of the IETF, including creation of IETF documents and decisions on the processes that are used. But the IETF also observes experiments and running code with interest, and this should also apply to the operational processes of the organization.

The IETF works in areas where it has, or can find, technical competence.

The IETF depends on a volunteer core of active participants.

Participation in the IETF or of its WGs is not fee-based or organizationally defined, but is based upon self-identification and active participation by individuals.

A.2 Management and Leadership

The IETF recognizes leadership positions and grants power of decision to the leaders, but decisions are subject to appeal.

Delegation of power and responsibility are essential to the effective working of the IETF. As many individuals as possible will be encouraged to take on leadership of IETF tasks.

Dissent, complaint, and appeal are a consequence of the IETF's nature and should be regarded as normal events, but ultimately it is a fact of life that certain decisions cannot be effectively appealed.

Leadership positions are for fixed terms (although we have no formal limitation on the number of terms that may be served).

It is important to develop future leaders within the active community.

A community process is used to select the leadership.

Leaders are empowered to make the judgment that rough consensus has been demonstrated. Without formal membership, there are no formal rules for consensus.

A.3 Process

Although the IETF needs clear and publicly documented process rules for the normal cases, there should be enough flexibility to allow unusual cases to be handled according to common sense. We apply personal judgment and only codify when we're certain. (But we do codify who can make personal judgments.)

Technical development work should be carried out by tightly chartered and focused Working Groups.

Parts of the process that have proved impractical should be removed or made optional.
A.4 Working Groups

Working Groups (WGs) should be primarily responsible for the quality of their output; WG chairs as WG leaders, backed up by the IETF leadership, should act as a quality backstop.

WGs should be primarily responsible for assessing the negative impact of their work on the Internet as a whole, and therefore for obtaining cross-area review; the IETF leadership should act as a cross-area backstop.

Early review of documents, particularly by WGs, is more effective in dealing with major problems than late review.

Area Directors (ADs) are responsible for guiding the formation and chartering of WGs, for giving them direction as necessary, and for terminating them. WG chairs serve at the pleasure of the responsible AD.

WG chairs are responsible for ensuring that WGs execute their charters, meet their milestones, and produce deliverables that are ready for publication. Document editors serve at the pleasure of the WG chair.

ADs are responsible for arranging backstop review and final document approval.
A.5 Documents

IETF standards often start as personal drafts, may become WG drafts, and are approved for permanent publication by a leadership body independent of the WG or individuals that produced them.

IETF standards belong to the community, not to their authors. But authorship is recognized and valued, as are lesser contributions than full authorship.

Technical quality and correctness are the primary criteria for reaching consensus about documents.

IETF specifications may be published as Informational, Experimental, Standards Track, Historic, or Best Current Practice.

IETF Standards Track specifications are not considered to be satisfactory standards until interoperable independent implementations have been demonstrated. (This is the embodiment of the "running code" slogan.) However, the IETF does not take responsibility for interoperability tests and does not certify interoperability.

IETF processes are published as Best Current Practice documents.

Useful information that is neither a specification nor a process may be published as Informational.

Obsolete or deprecated specifications and processes may be downgraded to Historic.

The standards track should distinguish specifications that have been demonstrated to interoperate.

Standards Track and Best Current Practice documents must be subject to IETF wide rough consensus (Last Call process). WG rough consensus is normally sufficient for other documents.

Substantive changes made as a result of IETF Last Call or IESG evaluation must be referred back to the WG.

The IETF determines requirements for publication and archiving of its documents.

