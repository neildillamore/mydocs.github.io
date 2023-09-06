Title:          Overarching Principles
Authors:        Neil Dillamore, James Shepherd

# Principles to Follow
Overview of the main principles to follow with any Digital Project.

## 1. User Centred Design
Make sure that the user is at the centre of all efforts.
### User Research
Understand users, their needs and goals, their behaviour.
### User Experience
- Is the application easy and efficient to use by the user?
- Is it accessible to all users and not exclude any subset of users?
- Is the interface consistent?
### Wireframes
Use mockups and wireframes to get user feedback at an early stage.
Use them to enable testing to be planned in parallel with development.

## 2. Work in the Open
Be open about all work - document everything, including a decision log and a risk log.
Allow access to all who might be interested to all documentation, code and work trackers (e.g. JIRA).
### Merge Review process
Conduct code reviews on all code before accepting it.
Use tools to that allow code reviews that enable a record of the conversation to be visible.

## 3. Reuse before Rewrite
Consider what might already exist before building new.
### Discovering what exists
Look to open source libraries and frameworks before building afresh.
Always think about creating shared libraries across applications or components of applications.

## 4. Prioritise Open Standards
Build and use open source wherever possible.
Use open languages, libraries, and frameworks.

## 5. Continuous Iteration
Expect and plan for iterations. Start small, think big, scale fast.
### Agile
Use the principles of the [Agile Manifesto](https://agilemanifesto.org/).
Adapt them to the organisation and role you find yourself in.
### Continuous Integration and Continuous Delivery/Deployment
CI means try to keep the time between writing the code and its successful integration into the deployable
codebase as small as possible. To achieve this you will probably need automated testing.
CD means try to keep the time between writing the code and its successful deployment to production
as small as possible, again automation will enable this. Minimising these, while also minimising the risk of defects,
enables value to be realised more quickly.
### Security
Security should be thought of at all points of the software lifecycle, sometimes called DevSecOps.
### Cost and Performance optimisation
While trying to increase the performance a solution consider the whole cost. This includes things such as
cloud hosting costs, licence costs, labour costs.

## 6. Ensure It's Sustainable
### Sustainable Technology Choices
Consider:
- Using serverless technologies that do not utilise a server that is always on
- Turning off resources outside office hours
- Right sizing
- Technology that fits in with the organisation
### Maintainability
Endeavour to create software that can be maintained by choosing languages, libraries and frameworks
that are themselves maintained. Create code that is readable and follows
[clean code](https://www.amazon.co.uk/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) principles.

## 7. Cloud First
The lead time for deployment of hardware and applications leads most organisations to consider cloud first
for their hosting. Also, considerations of hardware lifecycle, who is going to hold the pager to fix servers
in the middle of the night, reliability, availability, security, and the sustainability of shared infrastructure
give weight to the argument.
### Cloud native
Historically people were worried about cloud agnosticism but
we have come to realise that using cloud native services, such
as SQS on AWS, Google Firestore, Azure DevOps enables solutions
to be developed quicker, with scalability and disaster recovery
benefits that outweigh the cost of a re-platforming that may
never happen.

## 8. Automate All The Things
Automation promotes quality by its accuracy, repeatability, auditability, and transparency.
### Monitoring, Metrics and Alarms (Observability)
While code has tests to ensure quality, environments have monitoring, metrics, and alarms.
These should be considered just as important. Consider logging standards and defining
Service Level Objectives (SLOs).
### Test automation
Using a build server to automate the execution of tests promotes quality.

## 9. Promote an Enjoyable Developer Experience
Known as DevEx or Developer Productivity Engineering, consider the environment and tools that
everyone has to work in and with.
### Developer Experience
Consider what are the pain points at each point in the software delivery lifecycle.

## 10. Bringing Ingenuity to Life
Foster creativity, be open to new ideas, and bring ingenuity to life.
