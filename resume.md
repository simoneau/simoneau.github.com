---
layout: page
title: Resume
permalink: /resume/
published: true
---
A full-stack software engineer in Boston with more than 20 years of experience, seeking interesting technical challenges and opportunities to grow as a leader.

* simoneau@gmail.com
* 617-529-2285

### Toast

#### Staff Software Engineer, Payments (2018-present)
The Payments team is a small group of engineers tasked with maintaining, scaling, and enhancing our payment processing platform, which authorizes, captures, and settles tens of millions of dollars worth of transactions every day. My focus is on our server architecture, especially on our collection of Java-based microservices.  My contributions include:

* Designing and implementing enhancements to allow Toast to accept new types of transactions, including eCommerce, card on file, and contactless EMV. I worked most directly on the interface with Worldpay, from design all the way through certification.

* Architecting a system to sync the results of contract negotiation, including credit card rates, from Salesforce into our internal systems. This included producing several reusable systems which were adopted by other teams for other projects.

#### Online Ordering Team Lead (2016-2018)
As engineering team lead for online ordering, my role was to oversee the full software development cycle. Responsibilities included:

* Working with program management to set priorities and schedules.
* Working with UX to finalize designs.
* Running weekly iteration meetings and daily scrums.
* Performing code reviews.
* Ensuring unit and integration testing.
* Coordinating weekly deployments.
* Providing real-time monitoring and performance metrics.
* Facilitating RCAs.

In addition, I contributed to development, including both front-end interface (Angular) and back-end services (Java).

Accomplishments:
* 4x increase in B2B customers, 5x increase in revenue, 9% increase in B2C conversions, 0 to hundreds of thousands of saved accounts.
* Introduced many new features, including saved user accounts (e-mail validation, saved credit cards), client-side credit card encryption, improved checkout flow (fewer steps, better feedback), chain restaurant support.
* Grew an agile team from 4 to 11 (team lead, 5 engineers, 2 engineer co-ops, 1 PM, 1 QA, 1 UX),
* Separated our back-end code from a monolith (Play) into individual microservices (Dropwizard).
* Modernized or JavaScript build (webpack), 
* Implemented back-end monitoring and alerting (Datadog), front-end metrics (GA), operator help (Appcues), and user session usability tracking (FullStory).
* Introduced an architecture for cross-service feature flagging

### MathWorks (1997-2016)

#### Example Manager Team Lead (2009-2016)
Designed and implemented a unified system to manage code examples shipped with MATLAB, included in documentation, and shown on the website. Writers, developers, and technical marketers have used it to author 12,361 examples.

- Created an authoring environment integrated with MATLAB.
- Implemented as a single-page web app using jQuery UI. Presented in a window in the MATLAB desktop. Built on top of a Ruby on Rails API and a SOLR database.
- Integrated the app with internal tools, including Perforce, Arbortext, the bug tracking system, the gmake-based product build, the DocBook-based content, and the testing system.
- Grew the development team to a cross-functional group of 10 people, including 4 developers.
- Project is rooted in previous improvements, beginning in 2002, to the presentation of examples in MATLAB. This included automatically publishing MATLAB scripts (see below) during the product build using MATLAB and gmake and presenting the HTML in the Help Browser using XSLT.

#### MATLAB Publishing Developer (2002-2011)
Principal designer and developer of [MATLAB Publishing](http://www.mathworks.com/help/matlab/matlab_prog/publishing-matlab-code.html). This feature creates rich documents from MATLAB code by recognizing markup in the comments and running the code to collect its output.

- Implemented mostly in the MATLAB language, additionally  XSLT is used to generate the HTML and LaTeX, FOP to create PDF, and ActiveX for the Word and PowerPoint formats.
- Collaborated with the MATLAB Editor team on the design of the corresponding UI enhancements, especially code “sections”.
- Related to this work, co-authored patent US8762956, [Generating a report document from code](http://patft.uspto.gov/netacgi/nph-Parser?Sect2=PTO1&Sect2=HITOFF&p=1&u=/netahtml/PTO/search-bool.html&r=1&f=G&l=50&d=PALL&RefSrch=yes&Query=PN/8762956).

#### Internet APIs Developer (2001-2005)
Designed and implemented APIs to access the Internet from MATLAB.

- Developed a suite that included accessing URLs, sending e-mail, connecting to FTP sites, autogenerating a SOAP client, and reading/writing zip files. Implemented in the MATLAB language and built on top of core Java classes and libraries from Apache Commons.
- Served on the Language Design Team.
- Worked with Quality Engineering to implement new testing services.

#### MATLAB Central Developer (2001-2011)
Helped design and implement [the MATLAB user community site](https://www.mathworks.com/matlabcentral/).

- Contributed heavily to the design of the site and the initial two apps, File Exchange and Newsreader, and later to the Link Exchange and MATLAB Answers.
- Evangelized the site to users and served as the administrator of the File Exchange.
- Implemented the Blogs, using Wordpress, and the Community Wiki, using MediaWiki.
- Authored a web service to provided static analysis of File Exchange submissions, written JSP and MATLAB.
- Authored a cross-application tagging service, written in Ruby on Rails.

#### Curve Fitting Toolbox Developer (1998-2001)
Developed the [Curve Fitting Toolbox](http://www.mathworks.com/products/curvefitting/) from idea to 1.0 as a core member of a small team.

- Contributed to all aspects of project, including market analysis, use case development, feature prioritization, API and UI design, implementation, testing, and collecting beta feedback.
- Implemented the Java AWT-based user interface.
- Contributed to the MATLAB API implementation.

#### MATLAB Contest Developer (1999-2009)
Lead developer for the [MATLAB Contest](http://www.mathworks.com/matlabcentral/contest/) through most of its life.

- Developed a harness for automatically scoring entries, including security checks for malicious code, mostly written in MATLAB.
- Enhanced to the site’s front end, written in Perl and SQL.
- Contributed to the design for many of the puzzles, including problem statement, sample code, and test data.
- Administered many contests, from announcing the dates to declaring the winner.
- Provided some [analysis](http://www.mathworks.com/matlabcentral/contest/contests/19/statistics.html) of the entries and [other commentary](http://blogs.mathworks.com/contest/2002/11/08/a-contest-story/).

#### External Developer Liaison and Internal Technical Lead (1997-2001)
Served as the interface between MathWorks and external developers of Mapping Toolbox and Neural Network Toolbox.

- Aligned external development efforts with internal plans, standards, and schedule.
- Trained external authors on internal tools and monitored the code quality.
- Served as internal expert for technical support, marketing, consulting, and sales. This included conducting training, attending trade shows, sitting in on conference calls, and [writing marketing collateral](http://www.mathworks.com/company/newsletters/articles/neural-networks-provide-solutions-to-real-world-problems-powerful-new-algorithms-to-explore-classify-and-identify-patterns-in-data.html).
- Scheduled and conducted author on-site visits several times a year. This included conducting usability testing to help set development goals.

#### Selected Other Projects
- 2011: Connected the DocBook/XSLT-based documentation build system to to the Java-based infrastructure used by the Editor to provide automated build-time syntax highlighting of code.
- 2009: Created a JavaScript/SOLR/Lucene-based web app to search for the internal bug tracking system. This was used by hundreds of developers and tech support engineers daily and was adopted by that team wholesale in 2015.
- 2007: Presented  the first internal talk about Amazon’s EC2, now an important part of the [MATLAB Online](http://www.mathworks.com/products/matlab-online/) infrastructure.
- 2007: Created the official [MATLAB Facebook](https://www.facebook.com/MATLAB) page. Served as administrator until 2009, when its ownership transferred to Marketing.
- 2004: Began role as [liaison](https://en.wikipedia.org/wiki/User:Simoneau) to the Wikipedia community and developed internal policies toward employee contributions.
- 2001: Implemented and evangelized the use of an internal Wiki, first based on a simple Perl code base and later converted to use MediaWiki. Transferred maintenance of the app to the intranet team several years later. About half of all employees still make edits each month, even though SharePoint is now the recommended solution.
- 1999: Created a nightly report of employees ranked by tenure. Your spot on this list has become known across the company as your Simoneau Number.

### University of Massachusetts Amherst (1992-1997)
Mathematics major with an interest in computer science and physics.

#### Researcher (1996)
Worked for a summer in the Mesoscopic Physics lab.

- Designed and performed experiments to measure quantum conductance.

#### Webmaster, Lab Assistant (1995)
Worked for a summer in the Medium Energy Nuclear Physics group.

- Designed and implemented the website for the Physics department.
- Assisted in conducting an experiment at the MIT-Bates Linear Accelerator.

#### Università per Stranieri di Siena (1994)
Studied Italian language and culture in a semester abroad.
