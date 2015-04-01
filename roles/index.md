---
layout: default
title: Roles and Responsibilities
---

# E-Commerce Group Roles and Responsibilities

Our teams consist of collections of technologists and product people who collectively create and extend the in-house developed technology platform which best helps HauteLook succeed in its operational and business goals. We create software which allows us to track what items we have for sale, present them to our customers (in both flash sale and persistent formats), execute sales transactions, communicate order information to our warehouse, ship orders from our warehouse to our customers, provide visibility for the business into those things and provide tooling which helps us provide excellent customer service.

We also are responsible for the infrastructure used to bridge between our internal systems and Nordstrom’s and also between ours and the third party solutions we employ.

## Collective Responsibilities

As a department we hold ourselves to the following expectations, regardless of role:

   1. Understand HauteLook’s business model, goals and competitors.
   1. Understand how the work we do advances HauteLook’s business and operational goals.
   1. Be excellent partners with our colleagues in Marketing, Member Care and Production to ensure we give them the best tools and support possible.
   1. Be excellent partners with our Product Managers to design and implement the best possible experiences for our members and internal customers.
   1. Communicate with our non-technologist colleagues in language and concepts comprehensible and relevant to them. Understand their world views and the challenges they face.

## Engineer

The primary job of an engineer at HauteLook is to ship a lot of excellent code as quickly as possible that has a positive impact for our customers and colleagues. An engineer should create quality solutions to business problems in the most pragmatic way possible. Value [bazaar over cathedral](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar). Value [flexibility over reusability](citation needed).

An engineer should focus on learning the technology and best practices to become an effective contribtor on your team. A good indication of effectiveness is how well your Pull Requests are received by your colleagues. Once an engineer has proven to be an effective member of the team, the engineer should start fulfilling one or two responsibilities of a [senior engineer](#senior-engineer).

Responsibilities:

   1. Participate as team member in creating user stories.
   1. Participate as team member in estimating the complexity and/or needed development and testing time of user stories.
   1. Design and implement the simplest solutions to problems defined by user stories.
   1. Act as a responsible custodian of our software:
      1. Only deliberately introduce technical debt, communicating when this is happening and why.
      1. Adhere to HauteLook-identified best development, testing and documentation practices.
      1. Help to identify and socialize additional best practices and challenge misguided ones (even those currently accepted as best practices).
   1. Share in the ownership of the finished/live product, ensuring it actually accomplishes what it is supposed to do.
   1. Actively seek help from others when blocked.


### QA Engineer

People in QA roles should think critically about what level of testing (e.g. none, manual, automated) makes sense for each change they are working on, in each stage of that change's lifecycle (e.g. design, development, QA, release). The result of testing should be valuable feedback to engineers and product managers concerning the change's likelihood of defectiveness and confidence level of correctness.

Some QA responsibilities:

   * Partner with engineers in designing new functionality, ensuring the proposed design is testable.
   * Partner with engineers in defining test plans around new functionality.
   * Assess the risk of changes in flight in order to inform our decision of if, when and how to deploy them.
   * Write automated testing around new and existing functionality, in order to minimize the rate and risk of regressions. 

### <a name="senior-engineer"></a>Senior Engineer

Senior development and QA engineers are capable of affecting significant positive change within the business and software. A senior engineer is actively involved in the sprint planning and helps create execution plans within the given constraints of the product and technical design. They are comfortable working with product managers and architects to come up with iterative solutions to business problems.

Some Senior Enigneer responsibilities:

   * Create and participate in the RFC process.
   * Suggest better abstractions for the code during the design and review process.
   * Solicit feedback from colleagues.
   * Proactively fix pain points.

### Staff Engineer

Staff Engineers are people who have a significant amount of domain knowledge. A Staff Engineer will have spent a number of years working at HauteLook as a Senior Engineer diving deep into product spaces and successfully shipping code. A Staff Engineer helps other Engineers understand how an existing code works (and sometimes doesn't work) to provide solution to a Product space. A Staff Engineer has a great working relationship with the entire Product Management department.

### Senior Staff Engineer

A Senior Staff Engineer holds mastery over one or more business critical Product spaces.

### Principal Engineer

A Principal Engineer is the de facto leader of all the engineers. They have enormous influence over the choices of technology and code design. This is a person you will rarely find in meetings with managers. They are given the most challenging tasks to solve. In addition to doing the work on their own, they are able to lead a group of engineers to solve large problems that may involve the concerted effort of multiple high-functioning engineers months to solve.

### Agile Coach

### Technical Agile Coach

## Architect

Architects are the midwives of our technology choices. They are responsible for identifying which of our problems are best solved through technology and leading our evaluation of candidate solutions. They are accountable for the results of our choices. 

Architects are also responsible for making sure we introduce changes into our ecosystem in ways which neither disrupt our development, qa and production environments nor degrade the performance of those systems (unless done deliberately, for compelling reasons). This means (amongst other things) communicating to all potentially affected parties what we are proposing we introduce and why, helping our engineers understand the considerations they should be aware of as we start making use of new technologies and proving the value of our choices, using data and examples.

Architects are responsible for the health of our implementations. They can pursue this responsibility through establishing our best practices (for development, quality assurance, deployment, monitoring and alerting, etc), code reviews, by providing mentorship (and no doubt through other ways they identify).

Some Architect responsibilities:

   * Coordinate the interactions between systems (HauteLook to Hautelook and HauteLook to third party) to ensure that the affordances they offer are correct, performant and easy to use effectively.
   * Help decide what trade-offs are to be made in the design for a given system. They own the responsibility of documenting and communicating these changes to all affected parties.
   * Solicit feedback from engineers on the challenges in implementing the technical design.
   * Create proof of concepts and prototypes to validate architecture and designs.
   * Assist in release planning to minimize the risk and downtime of deployments.

### Enterprise Architect

Identify the changes in our components and the interactions between them necessary to accomplish business initiatives.

Some Principal Architect responsibilities:

   * Ensure that all the architects are creating systems that allow for [semantic interoperability](https://www.wikipedia.com/wiki/Semantic_Interoperability).
   * Have a very clear understanding of how the technology fits within the HauteLook business.

## Engineering Management

The primary responsibility of engineering management roles is to create an environment in which highly motivated, highly capable technologists can thrive.

Some Engineering Management responsibilities:

   * Help technologists understand what the business is trying to do and making our department navigable to the business.
   * Promote a culture of feedback.
   * Set people up for success, by assigning well defined responsibilities, and commensurate decision making authority.
   * Establish a culture which [embraces failure](http://queue.acm.org/detail.cfm?id=2499552).
   * Practice [Fair Process](http://hbr.org/2003/01/fair-process-managing-in-the-knowledge-economy/ar/1).

### Lead Engineer

Lead Engineers are people who have been successful Senior Engineers and want to take a more active role in the day to day management of the development process.

Responsibilities of this role:

Responsibility for codebase

   * Oversee the general and day-to-day development and maintenance of the HauteLook and Rack iOS apps to ensure they deliver the best possible experience for OLOP customers and the business.
   * Work with the Mobile Product Manager to understand business needs and design technical solutions to meet those needs in the most efficient and reliable way possible.
   * Monitor, respond to, and manage any urgent issues that arise from the iOS apps, at any and all times of day/week/year.
   * Thoroughly assess risks to the business relating to the iOS apps and vigilantly manage them.

Leading the development work

   * Work with team members individually to help them ship code that improves the experience for OLOP members and the business in the fastest, most reliable way possible.
   * Organize development sprints into tickets and assign work to team members. 
   * Delegate technical tasks to others on the team in line with their capabilities and preferences to maximize team productivity.
   * Engage team members and get their feedback on designs, development process, sprints, and other issues.
   * Be the top contributor of code to the project.
   * Serve as the primary code reviewer for the project.
   * Continuously monitor software development progress, be aware of obstacles and risks, and address them.
   * Proactively fix pain points.
   * Coordinate interactions between systems (internally and with third-party vendors) to ensure interfaces are designed to maximize accuracy, reliability, performance, and ease-of-use.

Code design and feature development

   * Create prototypes to validate architecture and designs.
   * Design code architecture to maximize performance, stability, and maintainability in a pragmatic way.
   * Help decide what trade-offs are to be made in the design for a given system. Manage documenting and communicating these changes to all affected parties.
   * Take any other steps related to code design, development, and management that are necessary for the success of the iOS apps and the Mobile team.
   * Collaborate with engineers on other teams, such as API engineers, to ensure two-way communication, with clear expectations and constructive feedback.

Responsibilities that are not part of this role

   * Having 1-on-1’s with team members.
   * Performing annual reviews of team members.
   * Managing hiring and firing of team members.
   * Determining promotions or compensation changes for team members.

### Engineering Manager

Engineering Managers manage teams of individual contributors. As the managers working most directly with our technologists, they have the greatest insight into their team members' daily experiences, both good and bad, and are best positioned to provide both help and remediation.

Some Engineering Manager responsibilities:

   * Ensure our development process helps the team execute at a highly productive predictable and sustainable level. Constantly look for ways to improve how we pursue these goals. 
   * Chase down team blockers and remove them, escalating if unable to do so.
   * Communicate with other teams where there are dependencies, and make sure they are able to meet them before making sprint commitments which cannot be met without those dependencies.
   * Identify challenges/opportunities for improvement within the team, give that feedback to those members and management as appropriate.
   * Help the team identify useful metrics to measure themselves by, and help them understand their progress as measured by those metrics. Use those measurements to improve the accuracy of team estimates.
   * Recognition of team and individual achievements, and socialization thereof up and out.
   * Set clear expectations and hold team members accountable. Swiftly address performance concerns.

### Engineering Director

Where Engineering Managers focus on helping teams of individual contributors thrive, Engineering Directors focus on setting their Engineering Managers up for success. They work to empower those managers to do well by their teams, help facilitate communication between teams and between departments.

Engineering Directors are responsible for understanding the technological needs of our department and advocating for their prioritization. They are responsible for identifying the values embodied in our department as currently constructed and ensuring we hire for the values they would have for the department. 

Some Engineering Director responsibilities:

   * Create a clear and meaningful path for career progression.
   * Establish and maintaining clear lines of communication within the team and outside the team.
   * Ensure compensation accurately reflects the work being performed by the individual.
   * Provide mentorship for both team managers and individual contributors
   * Recognition of departmental achievements, and socialization thereof up and out.
   * Remediation of teams which are struggling to perform.
   * The recruiting and retention of team members.
   * Create a technical roadmap that supports the creation of excellent software.
