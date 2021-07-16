# Introductory Security Resources
A list of resources that Aditi Chaudhry and I found to be helpful
on our specific journey from software engineering into
cybersecurity. Accompanying slides for our talk "How to Spark
Your Journey into Cybersecurity as a Software Engineer" can be
found in this repository as well.

- [Educational Opportunities](#educational-opportunities)
  - [Academic Classes](#academic-classes)
  - [YouTube Videos](#youtube-videos)
  - [Workshops](#workshops)
  - [Books](#books)
  - [Blogs](#blogs)
  - [Podcasts](#podcasts)
  - [Forums](#forums)
- [Hands-On Experiences](#hands-on-experiences)
  - [Capture the Flags (CTFs)](#capture-the-flags-ctfs)
  - [Bug Bounty Programs](#bug-bounty-programs)
  - [Home Labs](#home-labs)
  - [Web Guides/Challenges](#web-guideschallenges)
- [Certifications](#certifications)
- [Networking Opportunities](#networking-opportunities)
  - [Conferences](#conferences)
  - [Meetups](#meetups)
  - [Professional Security Organizations](#professional-security-organizations)
  - [Mentorship](#mentorship)
  - [Social Media](#social-media)
- [Projects](#projects)
  - [Hackathons](#hackathons)
  - [School Projects](#school-projects)
  - [Personal Projects](#personal-projects)
- [Career Links](#career-links)
------

<a href="educational-oppportunities"></a>
## Educational Opportunities

<a href="academic-classes"></a>
### Academic Classes
A good place to start if you like academic settings are massive
open online courses (MOOCs). There are a number of different
platforms, but here are a few:
- https://ocw.mit.edu/index.htm - MIT has a lot of its courses
  free online (fun fact: 
  [6.858](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-858-computer-systems-security-fall-2014/)
  was my very first security class!).
- https://www.edx.org/ - A huge source of many universities' online
  classes (originally created by Harvard and MIT, but now has more).
- https://www.coursera.org/ - Plenty of good content on here, much
  of which is still free!
- https://www.udemy.com/ - Another MOOC which offers good courses,
  though some of them need to be paid for (like Coursera).
- https://www.pluralsight.com/ - Has different technical courses and
  paths, some of which you need to pay before but can give training
  for certifications.
  
<a href="youtube-videos"></a>
### YouTube Videos
There are a lot of YouTube videos out there which provide a surprising
amount of content. This can vary from a lot of posted lectures from
different universities that are worth looking into all the way down
to individual YouTubers doing stuff for fun. 

Some YouTubers definitely give very technical rundowns that are good
like [LiveOverflow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w),
[Hak5](https://www.youtube.com/channel/UC3s0BtrBJpwNDaflRSoiieQ), 
[The Cyber Mentor](https://www.youtube.com/channel/UC0ArlFuFYMpEewyRBzdLHiw),
etc. Other ones, including some of my personal favorites, are still
educational but definitely more down the fun vein of "let's see what
malware does" like [danooct1](https://www.youtube.com/channel/UCqbkm47qBxDj-P3lI9voIAw),
[rogueamp](https://www.youtube.com/user/rogueamp), 
[onNeutral](https://www.youtube.com/user/onNeutral/videos), etc.
(mind you some of these are quite old).

<a href="workshops"></a>
### Workshops
There are a variety of workshops that exist that you can search for
or might be provided by a number of different professional
organizations. Personally, I've found https://training.owasp.org/
to have some good and digestible content.

<a href="books"></a>
### Books
There are many gems in the realm of security knowledge that exist 
in text. Shout out to Brian Smith-Sweeney for providing many of
these references:
- https://www.paloaltonetworks.com/blog/category/canon/ - A good general list to
  start out with.
- [Hacking Exposed Series](https://www.paloaltonetworks.com/blog/2016/09/the-cybersecurity-canon-hacking-exposed-series/) - 
  Kind of old, but it's very high-level, and a pretty good intro.
- [TaoSecurity](https://www.taosecurity.com/) - Bejtlich has written
  a ton of good books. *Tao of Network Security Monitoring* is a good
  place to start if not the newer [*The Practice of Network Security Monitoring*](https://www.amazon.com/s?k=the+practice+of+network+security+monitoring&i=stripbooks&language=en_US&crid=1GTOOS8ID9FEO&linkCode=sl2&linkId=212953637424e9ec172331c38d8bf1a2&sprefix=the+practice+of+network%2Cstripbooks%2C115&tag=taosecurity0c-20&ref=nb_sb_ss_i_1_23).
- [Hacking: The Art of Exploitation](https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441/ref=sr_1_1?keywords=hacking%3A+the+art+of+exploitation&qid=1580755998&s=books&sr=1-1) -
  A deep, technical book that covers the first tech principles of modern
  security issues.
- [Spam Nation](https://www.amazon.com/Spam-Nation-Organized-Cybercrime-Epidemic/dp/1492603236/ref=sr_1_1?s=books&ie=UTF8&qid=1496301705&sr=1-1&keywords=Spam+Nation+by+Brian+Krebs) -
  Old but good! Gives an idea of the commercialization of malware and
  exploitation, which is particularly relevant especially given the huge
  presence of ransomware right now.
- [Threat Modeling](https://www.amazon.com/Threat-Modeling-Designing-Adam-Shostack/dp/1118809998/ref=sr_1_1?s=books&ie=UTF8&qid=1494936434&sr=1-1&keywords=threat+modelling) -
  Shostack's book on this is good, as he pioneered the work at Microsoft.
- [Gray Hat Hacking Python](https://www.amazon.com/Gray-Hat-Python-Programming-Engineers/dp/1593271921/ref=dp_rm_title_1) -
  Talks about how to use Python for a variety of security purposes.
- [How to Measure Anything (Series)](https://www.howtomeasureanything.com/) -
  A quantitative view on many things in life, but in particular some
  security-specific books are great for developing any kind of risk
  assessment mindset (especially if that area of security is most appealing).
- [Worm: The First Digital War](https://www.amazon.com/Worm-First-Digital-World-War/dp/0802145949) -
  A good treatment of earlier malware.
- [Smashing the Stack for Fun and Profit](https://insecure.org/stf/smashstack.html) -
  Not a book, but a historical post that outlines some of the earliest
  examples of buffer overflows, and more broadly gives insight in how
  to approach and attack systems by understanding how they work.
- [An Evening with Berferd](http://cheswick.com/ches/papers/berferd.pdf) -
  Also not a book, but an article which outlines the basis of modern
  forensics. 
- [The Nmap Man Page](https://nmap.org/book/man.html) - Teaches a lot
  about the security implications of network packets and also teaches
  nmap, a great network analysis tool.
- [The Web Application Hacker's Handbook](https://www.goodreads.com/book/show/1914619.The_Web_Application_Hacker_s_Handbook) -
  A great intro to web app hacking, and even though it's pretty outdated
  plenty of the discussed issues still come up (and it also talks about
  Burp Suite, one of the best web hacking tools out there).
- [Data-Driven Security: Analysis, Visualization and Dashboards](https://www.goodreads.com/book/show/18182108-data-driven-security) -
  Details the process of approaching security with a data focused
  mindset (might be helpful if you come to security with a background
  in data, as the overlap can actually be quite significant).

<a href="blogs"></a>
### Blogs
Blogs are a good in-between to books and social media. A lot of 
security professionals will post interesting topics on their blogs,
so they are for sure worth checking out. Here are some to get
started:
- https://krebsonsecurity.com/ - Brian Krebs is a well-known name
  in the security community. He is a journalist and investigative
  reporter that looks into a lot of security topics and posts
  about them.
- https://tldrsec.com/ - A fantastic newsletter ran by Clint Gibler.
  It's one of my personal favorite weekly reads as it covers a 
  variety of security topics and often has good resources for learning
  in them.
- https://cloudseclist.com/ - Another weekly newsletter that
  highlights security-related news on the cloud front.
- https://www.thesecurityblogger.com/ - A blog ran by Joseph Muniz
  that covers a variety of security topics.

<a href="podcasts"></a>
### Podcasts
There exist some podcasts that talk about security topics. Here are
a few I've heard recommended but personally haven't listened to:
- https://securityweekly.com/shows - Different podcasts on security
  topics that vary from application security to business security.
  They also have a YouTube channel.
- https://darknetdiaries.com/ - Covers true stories about hackers,
  breaches, hacktivism, cybercrime, and more.

<a href="forums"></a>
### Forums
Forums are a great place to actively engage with a lot of different
security professionals and enthusiasts. To broadly call out a few
places from our own experience/coworkers:
- https://reddit.com/r/blueteamsec - Focuses on blue/purple team
  technical intelligence and research
- https://www.reddit.com/r/homelab - A place where people share labs,
  projects, builds, etc.
- https://www.reddit.com/r/Malware/ - A place for malware reports and information.
- https://www.reddit.com/r/netsec/ - A community for technical news and
  discussions of information security topics.
- https://www.reddit.com/r/sysadmin - A subreddit dedicated to 
  computer system administration.

<a href="hands-on-experiences"></a>
## Hands-On Experiences

<a href="capture-the-flags-ctfs"></a>
### Capture the Flags (CTFs)

Capture the flags (CTFs) are cybersecurity challenges where 
competitors exploit or defend vulnerabilities in systems. In
essence, these are kind of like security-focused puzzle hunts.
CTFs are some of the best ways to get hands-on experience for a
number of different topics. Here are some helpful resources:
- https://ctftime.org/ - A general hub of CTFs that also keep
  track of points for different teams. This is good for looking
  at upcoming CTFs.
- https://www.majorleaguecyber.org/ - Similar to CTFtime, also a
  general hub of events and teams (as well as point tracking).
- https://ctfs.github.io/resources/ - A beginner-friendly high-level
  overview of CTFs and the kinds of challenges they might have.
- https://github.com/apsdehal/awesome-ctf - A list of frameworks and
  tools to refer to when you get around to doing CTFs.
- https://picoctf.org/resources - More resources from a very 
  beginner-friendly CTF (keep an eye out for it!).
- [The Diana Initiative](https://www.dianainitiative.org/capture-the-flag-village/)
  is hosting a CTF as well!
  
<a href="bug-bounty-programs"></a>
### Bug Bounty Programs

Bug bounty programs are programs where companies give permissions
and recognition to external, unaffiliated third parties who find and
report bugs and vulnerabilities on affected platforms. Often times
there is some form of compensation. This is a great opportunity to
essentially do some kind of live "hacking" within the scopes that
participating companies provide. Here are some resources to check
out:
- https://bugbountyforum.com/getting-started/intro/ - An introduction
  on what bug bounties are.
- https://www.hackerone.com/ - A platform which lists different bug
  bounty programs to check out.
- https://www.bugcrowd.com/ - Another crowdsourced bug bounty 
  platform that can link to different bug bounty programs companies
  are hosting.
- https://www.synack.com/ - Yet another platform to check out if you
  want to do some bug bounties.
- Lastly, many companies have their own programs. You can check this
  out by searching "[company name] bug bounty program" in your search
  engine of choice.

**Note:** Avoid asking for "beg bounties." These are essentially
reports asking for compensation on otherwise meaningless/innocuous
issues, especially when they are low risk, and the company in question
has no formal bug bounty program.

<a href="home-labs"></a>
### Home Labs
These are essentially hacking environments that you can host
locally. They are designed to be very vulnerable and can provide a
scopes-free instance of something to attack end-to-end. Here are
some that I've personally found useful (there are way more):
- https://owasp.org/www-project-webgoat/ - A deliberately insecure
  application that is Java-based.
- https://docs.rapid7.com/metasploit/metasploitable-2/ - An
  intentionally vulnerable Ubuntu Linux VM.
- https://dvwa.co.uk/ - A PHP/MySQL web application with many
  vulnerabilities.

<a href="web-guideschallenges"></a>
### Web Guides/Challenges
There are a number of online challenges/resources that you can tap
into and solve locally as well. These are similar to home labs,
but separated out as there is somewhat of a stricter guide or list
of challenges provided. Some are listed below:
- https://github.com/RhinoSecurityLabs/cloudgoat - A deliberately
  vulnerable AWS deployment tool that is structured as a set of
  AWS CTF challenges. 
- https://cryptopals.com/ - A set of cryptography challenges that
  I've personally had a lot of fun doing.
- https://guyinatuxedo.github.io/ - A set of reverse engineering
  challenges presented in a CTF style.
- https://overthewire.org/wargames/natas/ - A set of web security
  challenges also done in a CTF style.
- https://github.com/orangetw/My-CTF-Web-Challenges - More CTF web
  challenges.
  
<a href="certifications"></a>
## Certifications
Certifications are a rather large part of security. As a software
engineer the existence of certifications definitely felt more vague
and particular to certain subsets (though still common), whereas in
security it definitely felt more present as a "foot-in-the-door"
kind of experience. Though hands-on experience is usually the best,
I think there's no denying that certifications and studying for them
can really only benefit you. 

There are a lot of different certifications out there. 
[I mean a LOT](https://www.google.com/search?q=paul+jeremy+certification+roadmap&oq=pauljerimy+cer&aqs=chrome.1.69i57j0i10.5121j0j7&sourceid=chrome&ie=UTF-8).
Definitely pursue what is most interesting and relevant, but for
something introductory I often see 
[CompTIA Network+](https://www.comptia.org/certifications/network)
and [Security+](https://www.comptia.org/certifications/security)
cited as good starting points. [CISSP](https://www.isc2.org/Certifications/CISSP)
is also a good one to aim for.

<a href="networking-opportunities"></a>
## Networking Opportunities

<a href="conferences"></a>
### Conferences

Conferences are a great way to both meet new people and to learn a 
lot of new information! Anyone coming to this page from The Diana
Initiative is already off to a great start. Here's a short list of
some security conferences Aditi and I have attended (as well as 
some of our close friends):
- https://www.dianainitiative.org/ - A conference committed to
  helping all those underrepresented in Information Security.
- https://www.wicys.org/ - Women in cybersecurity organization that
  annually holds a conference.
- https://www.blackhat.com/ - A large computer security conference
  that tends to have more of a professional focus.
- https://en.wikipedia.org/wiki/DEF_CON - One of the most well known
  hacker conventions. 
- http://www.securitybsides.com/w/page/12194156/FrontPage - A series
  of loosely affiliated security conferences that tend to be set up
  a bit more ad hoc.
- https://www.shmoocon.org/ - An annual east coast hacker convention.
- https://www.summercon.org/ - One of the oldest hacker conventions. 
- https://hackermaps.org/ - A site where different conventions and
  meetups are aggregated on a map.

An honorable mention goes out to 
[Grace Hopper Celebration](https://ghc.anitab.org/) for being an 
excellent general tech conference centered around celebrating women
in computing.

<a href="meetups"></a>
### Meetups
This kind of overlaps with some data mentioned in
[hackermaps](https://hackermaps.org/) in the 
[Conferences](#conferences) section, but meetups are a great way to
informally meet other information security professionals. Some
examples and tools you can use for this are:
- https://www.meetup.com/home/ - You can search "security" or "tech"
  or whatever else might interest you here.
- https://devslop.co/ - OWASP sponsored project where different 
  information security professionals present topics, which also comes
  with an affiliated meetup group.
- https://owasp.org/www-committee-wia/ - OWASP sponsored committee
  that promotes contributions and leadership opportunities for
  women in application security.
- https://www.empirehacking.nyc/ - Informal meetups in New York City
  where information security professionals meet up and discuss
  research casually.
  
<a href="professional-security-organizations"></a>
### Professional Security Organizations
We already mentioned [WiCys](https://www.wicys.org/) before, but in
general professional organizations are a good way to stay current
with information, have a source of different meetups, and also a
great way to get involved. Here are some more:
- https://www.isc2.org/ - A non-profit which focuses on certifications
  and training for cybersecurity professionals.
- https://www.sans.org/ - Another organization which provides
  cybersecurity training, certifications, degrees, and resources.

<a href="social-media"></a>
### Mentorship
Mentorship is one of the easiest ways to get a ton of resources
that you know worked for someone, as well as having a direct source
for any questions or concerns. Here are some tips for finding and
actively engaging in a good mentorship relationship:
- https://hbr.org/2014/02/engage-a-mentor-with-a-short-term-project -
  A blog post that advises how to approach a relationship with a mentor.
- https://hbr.org/2020/01/how-to-build-a-great-relationship-with-a-mentor -
  Discusses how your relationship can be furthered with a mentor.
- https://hbr.org/2011/02/demystifying-mentoring.html - Clears up some
  misconceptions about mentoring and discusses what it practically means.
- https://www.linkedin.com/pulse/3-ways-foster-mentorship-dr-terri-cooper -
  Advise on how to foster a mentoring relationship.
  
<a href="social-media"></a>
### Social Media
Social media is a surprisingly used avenue of communicating security
information. Many people post interesting snippets and otherwise
noteworthy events. I usually find out about big security incidents
and news from social media before anywhere else. The most common
platforms are:
- https://twitter.com/ - A number of security professionals
  are active on here. Many, many people post on here so definitely
  look online for some starter lists or reach out to ask for some
  recommendations (shameless plug for 
  [@metorres20](https://twitter.com/metorres20) and 
  [@aditichaudhry92](https://twitter.com/aditichaudhry92) ;) ).
- https://www.linkedin.com/ - Very obvious but worth mentioning,
  since many professional are active on here and also are sometimes
  open to talking. I've personally spoken to a handful people who
  have reached out to me in DMs asking career questions.

<a href="projects"></a>
## Projects

<a href="hackathons"></a>
### Hackathons

For the uninitiated, hackathons are events which encourage
working on a problem or project (often from scratch)
continuously over a brief period (typically on the order of a
few days). These are great chances to hack away alone or in a 
team on various project ideas. Some tips/resources for that are:

- [Major League Hacking](https://mlh.io/) - You can browse
  different events here.
- [Eventbrite](https://www.eventbrite.com/) - You can search
  "hackathons" very broadly and usually find stuff going on
  around you.
- Many universities host them annually, so check in with those.
- Smaller hack days or hackathons hosted at companies are also
  fairly common.
  
<a href="school-projects"></a>
### School Projects

These can basically overlap in security always if you want it 
to, so if you have some general tech project overlap with some
area of security isn't too bad. Some (non-exhaustive) examples:
- Mathematics - Cryptography intersects with many fields of
  math and is always great to learn more about.
- Machine Learning - A very hot topic, and its intersection
  with security works twofold--model security and preventing
  data poisoning attacks on one end (i.e. securing the ML
  process) and things like anomaly detection, intrusion
  detection, filtering, etc. on the other end (i.e. applying
  machine learning to security).
- Distributed Systems - Can ensure security between distributed
  communication channels or design systems like anonymity 
  networks, reputation servers, etc. which are designed around
  secure principles and defaults.
- Databases - Can enforce secure database practices and 
  technologies (e.g. making sure queries are sanitized).
    
<a href="personal-projects"></a>
### Personal Projects

These are similar to school projects in that you can generally
apply security in whatever manner you want, except with these
you can explicitly make security a core objective (or even just
make security tooling).

There are a lot of ideas out there that you can search for, but
one particular thing to call out is that many security tools that
are widely used by the community are FOSS, so please go ahead and
look at public repositories and contribute to them. This will not
only help out others, but can help you learn a ton about the tool
and what particular areas it addresses.

<a href="career-links"></a>
## Career Links

Below are some referral links to some of Two Sigma's openings:
- [SWE Intern @ Two Sigma](https://careers.twosigma.com/careers/Careers?jobId=8471&source=Conference&tags=dianainitiative2021)
- [New Grad SWE @ Two Sigma](https://careers.twosigma.com/careers/Careers?jobId=8473&source=Conference&tags=dianainitiative2021)
- [General Experienced SWE @ Two Sigma](https://careers.twosigma.com/careers/Careers?jobId=389&source=Conference&tags=dianainitiative2021)
