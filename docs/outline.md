# Plan 
- Bullet points for major principles
- Templates for different types of doc
- Example of each different type of doc

# Technology Code of Practice

## User Centred Design
- What is user centred design?
- What is UX?
- What are User Stories?
- User research methods

## Accessible and Inclusive
- Introduction to [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)
- Introduction Screen Readers and [ARIA](https://www.w3.org/WAI/ARIA/apg/)
- The tools used for development should be accessible too, e.g. dyslexic, colour blind, or visually impaired developers

## Work in the open/transparency/collaboration
- All code committed to a repo
- Pull/Merge requests as a record of work
- Ticket system as transparent means of planning work
- Documentation available to all.
- Documentation as code e.g. this
- Document design decisions as transparency
- Using open source code
- Introduction to open source licences e.g. copyleft, apache/BSD
- Publishing open source software
- Publishing thought leadership e.g. Medium, LinkedIn

## Share/Reuse
- Shared libraries
- Shared build code e.g. gradle plugins, npm scripts
- Shared testing code
- Sharing pipeline code e.g. Jenkins
- Having a platform team that maintains all the tools and standards for other teams

## Use Open standards
- Open source / free languages
- Open source tooling
- Open source application servers
- Data standards, e.g. HTML, JSON, XML, Markdown, Parquet

## Cloud First
- Lead time to deployment of hardware and applications
- Hardware lifecycle
- Holding the pager
- Reliability, availability
- Sustainability argument (shared infrastructure)

## Cloud native
- Historically people were worried about cloud agnosticism but
we have come to realise that using cloud native services, such
as SQS on AWS, Google Firestore, Azure DevOps enables solutions
to be developed quicker, with scalability and disaster recovery
benefits that outweigh the cost of a re-platforming that may
never happen

## Secure by design / Continuous security
- Security of your toolchain/development
    - Use maintained laptops, e.g. PA Laptop with virus protection and ability to
be 'bricked'
    - Use tools/libraries from reputable software houses
    - Use tools/libraries that are maintained and covered by vulnerability scanning
tools
    - Update tools regularly e.g. IDE
    - SBOMs/nightly builds to check for vulnerabilities
    - Secure repositories
    - Secure build servers
    - Secure deployment methods e.g. not sharing cloud creds wider than necessary
- Risk register
- Principle of least privilege for users
- Not having secrets on the client side that give access to other users' data/permissions
- No credentials in code / using a secret store
- Separation of prod and non-prod
- MFA
- Data encryption in transit and in rest
- Recommended TLS
- SSH key standards

## Sustainable by design
- Using serverless
- Turning off resources outside office hours
- Right sizing
- Fits in with existing technology and existing knowledge in the organisation

## Continual Improvement
- Horizon scanning / tech radar
- Using new Cloud tech
- Meetups internal and external
- Coding standards / peer review / pair programming

## Pipelines / Automation / Release strategies
- Explain CI/CD
- Automate all the things (Build, security scan, test, deploy, CI/CD, IaC)
- Monolith / Microservices
- Git branching/tagging strategies
- Monorepo / polyrepo
- Deployment strategies (Rolling, Blue/Green, Canary)
- Release independent of deploy (dark live, feature switches)

## Monitor/measure and analysis
- Build/test/deploy times
- Code has tests, environments have monitoring, metrics, and alarms

## Developer experience
- Empowered Developers - able to make changes to dependencies
- Empowered Teams - cross-functional team able to remove blockers themselves /
everything they need to deliver in the gift of the team
- Local build time e.g. build caches
- Local test time e.g. ability to run a subset of tests
- Availability of a local environment or short cycle time dev env
- CI build time
- Deployment time

# Agile?







