# DevOps
# DevOps

# overview
https://www.slideshare.net/gauravslide/transform-agile-development-with-practical-devops-86846081

There are lots of tools of technologies comes under DevOPS Practice. But majorly devops focused on these 7 key aspects
* Code — Code development and review, version control tools, code merging.
* Build — Continuous integration tools, build status.
* Test — Test and results determine performance.
* Package — Artifact repository, application pre-deployment staging.
* Release — Change management, release approvals, release automation.
* Configure — Infrastructure configuration and management, Infrastructure–as–Code tools.
* Monitor — Applications performance monitoring, end–user experience.

# DevOps Tools
* **CI Framework** - Jenkins, Bamboo, Hudson, TeamCity
* **Build automation** - Maven, Gradle, Ant
* **Deploy** - CircleCi
* **Issue and project tracking** - JIRA, CA Agile Central, Team Foundation Server, HPE Agile Manager
* **Continuous delivery** - Chef, Puppet
* **Test Management** - QMetry Test Manager, HPE Quality Center Enterprise, ApTest
* **Test Automation** - QMetry Automation Studio, Selenium, Appium
* **Repository management** - Artifactory, Docker
* **Code coverage** - JaCoCo, Atlassian Clover, SonarQube, Cobertura
* **Behavior Driven Development** - jbehave, Cucumber
* **Application performance monitoring** - AppDynamics
* **Application security testing** - HPE Fortify
* **Cloud management** - Open Stack
* **Mobile Device clouds** - Perfecto, Sauce Labs
* **Monitoring** - Dynatrace, Nagios, Monit
* **Version control** -  Git
* **Config** - Consul.io
* **Feature Flags & Lifecycle Management** - LaunchDarkly


DevOps: A Cultural Change for the Win
https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2016/09/1474959371devops.png

# Benefits
* **Accelerated time-to-market:** shorten the time it takes from when an idea is conceived until it’s available for sale or in production.
* **Building the right product:** developers get faster feedback from users with more frequent releases and live testing of ideas (more on this later on the “A/B Testing” section).
* **Cost reduction:** reports average a 20% reduction.
* **Improved productivity:** with continuous delivery, developers and testers save time setting up and fixing their working environments. Also, deployments are significantly faster (more on this later in the “Continuous Integration with Jenkins” section).
* **Reliable releases:** with smaller and more frequent releases, the changes in code — and therefore the bugs introduced and their impact — are also smaller.
* **Improved product quality:** companies report a very significant reduction in open bugs and other issues (in some cases, by more than 90%).
* **Improved customer satisfaction:** this is, not surprisingly, a byproduct of all of the previous improvements.


# SPECIALIZATIONS
* **Infrastructure:** Amazon Web Services, VMware, RackSpace, Microsoft Azure, KVM, Heroku, Amazon OpsWorks, Amazon ElasticBeanstalk, Docker, Vagrant
* **Web / Application Architecture / Site Performance / Load Balancing:** Apache, NGINX, JBoss, Apache Tomcat, Rails, Node.js, DJango, PHP, Amazon CloudFront, Akamai, Amazon AutoScaling, Varnish Software, Memcached, Redis, Amazon ElastiCache, Red Hat Cluster Suite, F5 LTM (Local Traffic Manager) & GTM (Global Traffic Manager), Amazon Elastic Load Balancer, HAProxy
* **Authentication, Authorization, and Access Control OpenLDAP:** RSA Authentication, Radius Authentication, MFA (Multi-Factor Authentication)/Google Authenticator, Centrify/Powerbroker, SAML, OAuth
* **Environment Build and Deployment:** Packer, PXE, Foreman, Red Hat Kickstart, Spacewalk, RedHat Satellite Service, Mrepo, Pulp
* **Orchestration / Service Discovery:** Consul, Registrator, Consul Template, Shipyard, CloudFormation, Terraform
* **Configuration Management / Automation:** Puppet, Chef, SaltStack, Ansible, Beaker, TestKitchen, ServerSpec, Berkshelf, r10k
* **Big Data Operations:** Apache Hadoop, Cloudera, MapR, Hortonworks, Kafka, Storm, Oozie, Sqoop, Pig
* **Operational Visibility (Service Health Monitoring, Capacity Planning, and Reporting):** Elasticsearch, Logstash, Kibana, Splunk, Graphite, Grafana, Cacti, SNMP, Diamond, CollectD, NRPE, Nagios, Sensu, CloudWatch
* **Release Management:** GIT, SVN, Stash, GitLab, GitHub, BitBucket, Docker Registry Hub / Private Registry, Jenkins, Bamboo, TravisCI
* **Message Queuing:** RabbitMQ, ZeroMQ, ActiveMQ, Amazon SQS,
* **Storage:** NFS File Server, iSCSI, Fiber Channel, NAS / SAN, Netapp, 3par, EMC, Multipath / MPIO, device-mapper, PowerPath
* **Security:** Host based Firewalls (Iptables), SSL VPN (OpenVPN), IPSEC VPN (OpenSwan, LibraSwan), Amazon VPC, IAM, Security Groups & ACLs, SELinux, Auditing and hardening Linux servers
* **ITIL Service Operations (Incident, Problem, and Event Management):** Design and implement change control solutions, Design and implement disaster recovery solutions, Design and implement business continuity solutions, Root-cause analysis investigation, Linux Kernel performance troubleshooting and tuning, Application performance troubleshooting and tuning
* **Backup and Recovery:** Tivoli – TSM, HP DataProtector, Bacula, NetBackup, BackupExec, Rsync-based solutions


# DevOps culture 


https://dzone.com/articles/real-world-problems-solved-by-devops
https://techbeacon.com/30-common-challenges-devops-how-resolve-them

# Typical DevOps roles
* Automated Build and Release
  * Though automated nightly builds and smoke tests have been done even in a classic software development environment, such efforts were custom and scripted. The availability of automation platforms such as Hudson and Jenkins standardized such processes. The lead time to deploy changes in production has been minimized as a result.

* Configuration Management
  * This is a very generic term that previously referred to source code control systems (CMS), but in DevOps context, it refers to automation to define and create system components or roles. Though system components are largely software, in virtualized environments, the provisioning of hardware components such as virtual machines and storage volumes are very much in the scope.

  * A typical provisioning of a compute node for a system component or role can start with creating a virtual machine, setting up user accounts and access privileges, and installing baseline software bits specific to that role.

* Deployment Automation
  * Most of the time, deployment automation is tied to configuration management or build and release infrastructure. While configuration management takes care of the baseline setup required for a system component, deployment automation addresses automated processes in getting the application software releases and patches installed on various types of compute nodes regularly. For example, Jenkins integrated with a CMDB system can be used to provision baseline compute nodes for a system component, and the same infrastructure can be used to push code incrementally to same compute nodes as part of the Continuous Integration process.

* Monitoring
  * The last thing that the providers of SasS and web consumer apps want to do is get notified of production issues by client users. The SaaS providers lose credibility and web portals lose ad revenue if features don't work as intended. Even though highly reliable monitoring systems are available, it is impossible to catch all of the issues using out-of-the-box features of such products. Extending the features based on domain knowledge of the application is the key to getting notified of potential issues before customers find it, and that requires a broad set of skills (mainly, scripting and knowing how to consume a wide range of native and REST APIs provided by the third-party tools used and the application being monitored).

* Operational Intelligence
  * A well-instrumented software system can leave tons of information about health and performance, and aggregating such info for troubleshooting and reporting can be a daunting task. Besides gathering info for management reporting, insights into the working of the system can also help improve performance and fine-tune operability, which ultimately contributes to the increased availability of systems.




An integrated tool ecosystem helps achieve the following:              
* Real-time collaboration between development, delivery, and operations tools.
* Continuous planning from requirements capturing and review to design and code analysis.
* Cross-tool traceability for defining relationships between various data objects.
* Test strategy implementation for continuous testing.
* Continuous Integration through automatic triggering of build on successful completion of code check-in.
* Continuous testing through workflow based automatic triggering of both manual and automated test cases.
* Schedule based test automation script execution enabling Continuous Delivery.
* Continuous monitoring of release quality through reports and dashboards.
* Automated defect identification and resolution for faster HelpDesk response.
* End-to-end traceability providing better release predictability and change impact analysis.
* Meaningful reports, metrics, and KPIs for quick decision-making.
* Continuous Delivery through tracking release pipeline.


Here are the benefits stated in the diagram in text form:
1. Immediate start after check-in: no wasted time
2. One new change per new pipeline: transparent debugging
3. Parallel execution: faster feedback
4. All stages e.g., code analysis used as enforceable gates: easy to enforce quality controls
5. Can include infrastructure / environment build as well as application deployment: predictable and consistent behavior
6. Visible project status: easy to understand current stage of delivery execution
7. If a stage fails, the committer of the change can be immediately notified: efficient communication
8. Fully automated: predictable outcomes and minimized manual effort
9. Consistently executed automated test harness: high visibility of code quality and automated test stability
10. Easy to drill down to cause of failure: faster debugging
11. Highly visible historic information: can extract trends which inform planning decisions
12. Tested build package re-used: predictable and consistent behavior
13. Environments are recreated from version control so no need to limit: efficient debugging
14. Infrastructure resources recycled: efficient use of cloud services
15. Some stages may only be triggered manually: compatible with release management approval processes
16. The pipeline runs successively slower and more expensive quality gates: ensures optimized fast feedback

# What problems are solved by DevOps

* **Faster iteration** It gets new features out faster and at higher quality.
* **Faster, more user-friendly software that delivers value more quickly thanks to automation**. Operations becomes part of the engineering applications team enabling the faster development and deployment.
* **A repeatable process** where every member of the team knows where everything is in the process and each team member knows their role. Reliable path, more stable releases, faster. Some manual work with app stores like publishing and beta but documented.
* **The value the customer gets from the end product.** Metrics like mean time to deploy, create, ship features, recovery, and root-cause analysis. Better software, more frequent releases, happier customers, and happier employees.
* The false promise of Agile is to develop more quickly. Long-term, it is faster because you are focusing on business value and building what is really needed and wanted rather than building some shiny new technology. Focus on what both internal and external customers need and begin troubleshooting from day one. **Give customers better quality and business value.**
* Development understands what operations is like, so they make choices that help rather than hinder, and vice versa. **Continuous or at least rapid/pushbutton deployment** so that fixes and features can be rolled out more quickly.
* **Reduce cycle time**, increase velocity of application delivery for apps, self-serve capabilities with no roadblocks. **Increase the quality** of what delivering and how to engage with customers in better ways, everyone understands the role in delivering something better for customer testing, certification, validation. Better teamwork equals better products. 3) Helping developers and ops team understand the impact they have on the business. More of the mindsets of the DevOps professionals use a closed feedback loop to know how to move the business forward. Planning through customer engagement with a view throughout the process.
* **Speed to market**. Coming out with features that are meaningful to customers. Start with the minimum viable product, get customer feedback and quickly iterate to meet customer needs. This reduces wasteful development. 30% improvement in customer satisfaction. Ten times increase in innovation velocity. 2X efficiency increase. 85% test automation. EA feedback from months to weeks. Developer feedback from weeks to minutes.
* DevOps automates a lot of the tasks of developers. Allows developers to focus on functionality and quality to provide a better UX and fewer bugs. Focus on what’s important not running deployment.
* 1) Increase speed to market by having different teams come together. 2) If we implement correctly you increase release quality, release faster and learn. 3) Reduce testing costs because you don’t need to test after release. Customers are using AWS with automation feature scripts to check the capacity of servers. You know the impact of code of making changes running tests on AWS before you deploy scripts and automation to manage costs.
* Continuous delivery more than DevOps. **Faster delivery with shorter feedback loops.** Usability and user experience is more important. Get features out more quickly. Usability is the main driver.
* **Higher quality releases**. Another step in the release process. A mix of people and expertise adding an additional perspective to the release process to enhance the speed and quality of releases and freeing the developer to focus on the code of the product. Having greater awareness from all sides results in higher quality releases with automated processes that validate the accuracy and security of the code.
* **Able to move forward with confidence when deploying code** – from framework capacity to reliability. Deploy code with fewer surprises thanks to increased visibility into processes, tooling, and accountability.
* Increased visibility with DevOps encourages and **enables more people to collaborate and iterate much faster.**

# What is Continuous Integration?

Continuous Integration (CI) is a software practice that require developers to commit their code to the main workspace, at least once, possibly several times a day. Its expected that the developers have run unit tests in their local environment before committing the source code. All developers in the team are following this methodology. The main workspace is checked out, typically after each commit, or possibly at a regular intervals, and then verified for any thing from build issues, integration testing, functional testing, performance, longevity, or any other sort of testing.

![1](http://blog.arungupta.me/wp-content/uploads/2015/02/continuous-integration.png)

The level of testing that is performed in CI can completely vary but the key fundamentals are that multiple integrations from different developers are done through out the day. The biggest advantage of following this approach is that if there are any errors then they are identified early in the cycle, typically soon after the commit. Finding the bugs closer to commit does make them much more easier to fix. 

> Continuous Integrations doesn’t get rid of bugs, but it does make them dramatically easier to find and remove.


There are lots of tools that provide CI capabilities. Most common ones are Jenkins from CloudBees, Travis CI, Go from ThoughtWorks, and Bamboo from Atlassian.



# What is Continuous Delivery?

Continuous Delivery is the next logical step of Continuous Integration. It means that every change to the system, i.e. every commit, can be released for production at the push of a button. This means that every commit made to the workspace is a release candidate for production. This release however is still a manual process and require an explicit push of a button. This manual step may be essential because of business concerns such as slowing the rate of software deployment.

Continuous Delivery

At certain times, you may even push the software to production-like environment to obtain feedback. This allows to get a fast and automated feedback on production-readiness of your software with each commit. A very high degree of automated testing is an essential part to enable Continuous Delivery.

Continuous Delivery is achieved by building Deployment Pipelines. This is best described in Continuous Delivery book by Jez Humble (@jezhumble).

> A deployment pipeline is an automated implementation of your application’s build, deploy, test, and release process.

The actual implementation of the pipeline, tools used, and processes may differ but the fundamental concept of 100% automation is the key.

![1](http://blog.arungupta.me/wp-content/uploads/2015/02/continuous-delivery.png)


What is Continuous Deployment?

Continuous Deployment is often confused with Continuous Delivery. However it is the logical conclusion of Continuous Delivery where the release to production is completely automated. This means that every commit to the workspace is automatically released to production, and thus leading to several deployments of your software during a day.

Continuous Deployment

Continuous Delivery is a basic pre-requisite for Continuous Deployment.

![1](http://blog.arungupta.me/wp-content/uploads/2015/02/continuous-deployment.png)

# For Ideas
https://cdinsight.wordpress.com

# Artifact Repository

https://www.intertech.com/Blog/devops-tutorial-part-3-artifact-management/
http://blog.sonatype.com/2009/04/what-is-a-repository/
https://www.jfrog.com/support-service/whitepapers/6-reasons-devops-use-binary-repository-manager/

# Continuous Delivery Maturity Model

Maturity Models allow a team or organization to assess its methods and process against a clearly defined benchmark. As defined in Capability Maturity Model – The term “maturity” relates to the degree of formality and optimization of processes, from ad hoc practices, to formally defined steps, to managed result metrics, to active optimization of the processes.

The model explains different stages and helps teams to improve by moving from a lower stage to a higher one. Several Continuous Delivery Maturity Models are available, such as InfoQ, UrbanCode, ThoughtWorks, Bekk, and others.

Capability Maturity Model Integration (CMMI) is defined by Software Engineering Institute at Carnegie Mellon University.  CMMI-Dev particularly defines model that provides guidance for applying CMMI best practices in a development organization. It defines five maturity levels:

* Initial
* Managed
* Defined
* Quantitatively Managed
* Optimizing
Each of these Continuous Delivery maturity models mentioned define their own maturity levels. For example, Base, Beginner, Intermediate, Advanced, Expert are used by InfoQ. Expert is changed to Extreme for UrbanCode. ThoughtWorks uses CMMI-Dev maturity levels but does not segregate them into different areas.

Here is another attempt to the maturity model that picks the best pieces from each of those.

![1](http://blog.arungupta.me/wp-content/uploads/2015/02/continuous-delivery-maturity-model-v1.0-1024x734.png)


https://image.slidesharecdn.com/jenkins2-150728163959-lva1-app6892/95/continuous-integration-with-jenkins-and-git-7-638.jpg?cb=1438101733
https://www.xenonstack.com/images/DevOps.png


Our DevOps Professional Services include:
* Single Click Deployments
* Continuous Integration and Continuous Deployment
* Proper Infrastructure Security
* Automated Rollouts & Rollbacks
* Automated Security Alerts
* Supports Microservices & Serverless Computing - Docker and Kubernetes
* Easy Code Management & Code Reviews
* Deploy On-Premises, Public or Hybrid Cloud

https://www.xenonstack.com/images/devops-tools.png
https://www.xenonstack.com/blog/static/public/uploads/media/nexastack-the-ultimate-devops-platform.png


# DevOps Transformation Services
* Painless, End-To-End Cloud enabled Application Life Cycle Management
* Integrated Cloud Management and Orchestration
* DevOps as a Service
* DevOps Automation
* Automated Provisioning
* Deployment Automation
* Centralized Visibility
* Service Visualization
* Hybrid Process Framework
* Continuous Integration & Continuous Deployment in highly agile environment
* Automated Reporting and Dashboards
* Infrastructure Management and Monitoring
* Cloud Strategizing
* Team Assessment
* Security Management
* Configuration Management
Chef Assessment, Architecture & Consulting
Automation Architecture Design
Automated testing
Chef Advance Training
Managed DevOps & Chef implementation services
Continuous Integration & Continuous delivery adoption

• Build Automation 
• Configuration Management 
• Continuous Delivery/Rapid Deploy 
• Functional Testing/Unit Testing/Test Driven Development 
• Monitoring/Alerting 
• Packages/Containers/Virtualization 
• Release Coordination/Orchestration 




# Continuous Release and Deployment
• Technology selection and validation
• Deployment design
• Deployment automation
• Configuration and release management
# Continuous Testing
• UI and integration test automation
• Performance testing
• Service virtualization
• Test optimization
# Continuous Monitoring
• Infrastructure monitoring automation
• Software Development Auditing
• Service health dashboards delivery
• APM tools integration
# Continuous Feedback and Optimization
• Service request and change management
• Performance tuning
• Incident tracking system & analysis tool development
• High-availability & redundancy planning


# DevOps Orchestration Services
* Dev & Deploy Work Stream Automation and Visualization
* Software Delivery Process Automation
* Visual Monitoring of Development & Deployment Pipelines and Work Streams
* Centralized Visibility, Governance and Control


https://msystechnologies.com/wp-content/uploads/2017/08/deveops-img.png

# Continuous Integration and Delivery Process
https://msystechnologies.com/wp-content/uploads/2017/08/deve-automative.png


http://www.karyatech.com/images/devops-img.png



# OUR OFFERINGS
## Infrastructure Management
* Automated Provisioning
* Bringing up Servers in Deploy State (SCR)
* Server State Mismatch Elimination
* Server Scaling up
## Code Inspection & Continuous Integration
* Well-tested Code
* Verified Artifacts Ready for Deployment
* Improved Code Quality
* High quality Build and Code Reports
## Environment Management
* Configuration Mismatch Elimination
* Automated, Error-Free, Faster Configuration Deployment
* Single Tool Management
* Activity Reports Configuration
## Deployment Automation & Orchestration
* Automated, Error-Free, and Faster Deployment
* Single-Tool Deployment
* Single Click or Continuous Deployment
* Deployment Metrics


http://www.nexiilabs.com/img/devops/devops-tools.jpg


![1](https://mobisoftinfotech.com/assets/images/devops/web_performance_matters.png)

https://image.slidesharecdn.com/buildingadevopsorganization-150825132107-lva1-app6892/95/building-a-devops-organization-18-638.jpg



https://image.slidesharecdn.com/buildingadevopsorganization-150825132107-lva1-app6892/95/building-a-devops-organization-21-638.jpg





1. Source Code Management (SCM) System
  * GitHub 
2. Build and Continuous Integration(CI)
Reduce Integration Issues
Improve Code Quality
Improve Communication and Collaboration between Team Members
Faster Releases
Less Bugs
3. Building tools

4. Testing
JUnit: JUnit is a simple framework to write repeatable tests.
Mocha: Mocha is a simple, flexible, fun JavaScript test framework for Node.js.
5. Artifacts Management

6. Configuration Management
Ansible, Chef and Puppet

7. Deployment

8. Orchestration
Software systems that facilitate the automated management, scaling, discovery, and/or deployment of container-based applications or workloads.

* Kubernetes: Kubernetes is an orchestration system for Docker containers. It handles scheduling and manages workloads based on user-defined parameters.
* Docker Swarm: Docker Swarm provides native clustering functionality for Docker containers, which lets you turn a group of Docker engines into a single, virtual Docker engine.

9. Monitoring
 

The end goal for your monitoring is to consolidate tools, reduce the total cost of ownership, and automate the configuration via machine learning.

10. Collaboration & Notification
Rocket Chat: Rocket Chat is an open-source messaging app built with Meteor. It supports video conferencing, file sharing, voice messages, has a fully-featured API, and more. Rocket Chat is great for those who prefer to have full control over their communications.
Slack: Slack is basically a messaging app on steroids. It's meant for teams and workplaces can be used across multiple devices and platforms, and is equipped with robust features that allow you to not only chat one-on-one with associates but also in groups. You're able to upload and share files with them too, as well as integrate with other apps and services, such as Skype for video calls, and you can granularly control almost every setting, including the ability to create custom emoji.


11. Bug Management System
Bugs - Whether they be in the code or in the usability of the program, can be debilitating to any project, potentially causing the entire initiative to fail. 

12. Collaborative Documentation System
It includes:
Wiki basics
Using Media Wiki, Confluence etc.
Documenting DevOps Projects.
Organizing Documents on a Wiki-Based System for the past DevOps Projects.


13. Security
 


Artifacts Management
 

Now that your build pipeline consistently versions your Maven project, you need a place to store your artifacts which are being produced at the end of this pipeline. These artifacts need to be stored much the same way your source code is stored in your SCM.

 

This ensures access to previously released versions of your product. An Artifact Repository is designed to store your war/jar/ear/etc, and distribute it to fellow developers via Maven, Ivy, or the like, share your artifact with you deployment tools, and generally ensure an immutable history of your released products.

 

Using a Standard Artifacts Management System such as Artifactory

Caching Third-Party Tools


https://www.xenonstack.com/blog/static/public/uploads/featured/Data-Ingestion-Using-Apache-Nifi-For-Building-Data-Lakes-Twitter-Data.jpg

https://image.slidesharecdn.com/devopsonaws-acceleratingsoftwaredelivery-awssummitsg2017-170428085530/95/dev-ops-on-aws-accelerating-software-delivery-awssummit-sg-2017-10-638.jpg?cb=1493369876

http://linoxide.com/images/devops-tools-cheatsheet-infographics-700x900.png
https://cdn2.hubspot.net/hubfs/208250/social-suggested-images/DevOps-Infographic-v1.4%20690x690-1.png



## Basic
* [Start here](http://www.happiestminds.com/whitepapers/devops.pdf)
* [Awesome Sysadmin](https://github.com/itech001/awesome-sysadmin)
* [continuous integration and continuous delivery](https://github.com/ciandcd/awesome-ciandcd)
* [DevOps Defined](https://dzone.com/articles/devops-defined)
* [DevOps by Example: Tools, Pros and Cons of a DevOps Culture](https://www.sitepoint.com/devops-by-example-tools-pros-and-cons-of-a-devops-culture/)

# PERIODIC TABLE OF DEVOPS TOOLS
* [PERIODIC TABLE OF DEVOPS TOOLS](https://xebialabs.com/periodic-table-of-devops-tools/)

## Image Speaks
* [Rams infographic](https://github.com/ramyrams/DevOps/blob/master/DevOpsInfoGp.md)

# Containers
* [Getting to Know Containers](https://alexandrebrisebois.wordpress.com/2016/11/22/getting-to-know-containers/)

# DevOps
* [An Explanation of DevOps](https://dzone.com/articles/what-is-devops-2)
* [Understanding DevOps](https://sdarchitect.wordpress.com/2012/07/24/understanding-devops-part-1-defining-devops/)
* [Roles and Responsibilities for DevOps and Agile Teams](https://medium.com/@cote/roles-and-responsibilities-for-devops-and-agile-teams-fdacbffb4cb4#.t8qxwd2h0)
* [Understanding DevOps: Foster a culture for building better apps faster](https://support.rackspace.com/white-paper/understanding-devops-foster-a-culture-for-building-better-apps-faster/)
* [DevOps For Dummies](http://www.ibm.com/ibm/devops/us/en/resources/dummiesbooks/)
* [DevOps the Wall of Confusion understanding the basics of DevOps](https://blogs.msdn.microsoft.com/uk_faculty_connection/2016/06/23/devops-the-wall-of-confusion-understanding-the-basics-of-devops/)
* [The Product Managers’ Guide to Continuous Delivery and DevOps](http://www.mindtheproduct.com/2016/02/what-the-hell-are-ci-cd-and-devops-a-cheatsheet-for-the-rest-of-us/)
* [More IT agility with DevOps and Cloud Computing](http://incyclesoftware.com/services/it-agility-model/)
* [The Agile in DevOps!](http://blog.sciodev.com/2016/03/28/the-agile-in-devops/)
* [DevOps is Neither a Method nor a Tool, it’s a Culture](http://www.edureka.co/blog/devops-is-neither-a-method-nor-a-tool-its-a-culture/)
* [2016 State of DevOps Report](http://www.ciosummits.com/Online_Assets_Puppet_2016_State_of_DevOps_Report.pdf)
* [31 Reference Architectures for DevOps and Continuous Delivery](https://devops.com/2015/04/22/31-reference-architectures-devops-continuous-delivery/)

* [The IT Manager’s Guide To Continuous Delivery](http://cdn2.hubspot.net/hubfs/166743/Ebooks/IT_Managers_Guide_to_Continuous_Delivery.pdf)


* [The DevOps Release Timeline](https://xebialabs.com/assets/files/uploads/The-DevOps-Release-Timeline.pdf)
* [Zero to DevOps](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2017-Launch/190)
* [The Anatomy of a Release Pipeline](https://dzone.com/articles/the-anatomy-of-a-release-pipeline)

## URL

35 Questions to Ask While Creating a Deployment Pipeline 
https://dzone.com/articles/empowering-developers-to-deploy?

The DevOps.com Application Performance Management Leadership Links Guide
https://devops.com/devops-com-application-performance-management-leadership-links-guide/

* [35 Questions to Ask While Creating a Deployment Pipeline](https://dzone.com/articles/empowering-developers-to-deploy/)
* [Now we know DevOps, how to understand DevOps metrics](http://www.computerweekly.com/blog/Open-Source-Insider/Chef-Now-we-know-DevOps-how-to-understand-DevOps-metrics)
* [“DevOps” an Extension of Agile Methodology – How It will Impact QA?](http://www.softwaretestinghelp.com/devops-and-software-testing/)
* [12 Awesome tools to make DevOps effective](https://medium.com/@MarutiTech/12-awesome-tools-to-make-devops-effective-769f6f7b38a3#.fovievmbu)
* [DevOps Architect workshop](https://www.linkedin.com/pulse/3-days-devops-architect-workshop-change-leader-your-kumar)
* [21 DevOps and Docker Reference Architectures](https://dzone.com/articles/21-devops-and-docker-reference-architectures)
* [Continuous Integration for Mobile vs. Web Applications](https://dzone.com/articles/continuous-integration-for-mobile-vs-web-applicati)

* [DevOps, Common use cases, Architectures, Best Practices](http://www.slideshare.net/shivamaan/devops-common-use-cases-architectures-best-practices-48731462)

## DevOps 
* Continuous Deployment
* Automated Testing
* Release Management
* App Performance Monitoring
* Load Testing & Auto-Scale
* Availability Monitoring
* Change/Configuration Management
* Feature Flags
* Automated Environment De-Provisioning
* Self Service Environments
* Automated Recovery (Rollback & Roll-Forward)
* Hypothesis Driven Development
* Testing in Production
* Fault Injection
* Usage Monitoring/User Telemetry

## DevOps Concepts
* Configuration Management
* Streamlining Dev Environment Setup
* Orchestration
* Service Discovery
* Log & Error Management
* Monitoring & Alerting
* Dashboards
* Automated Deployment
* Backup & Disaster Recovery
* Security
* Scalability
* Email Service

## DevOps Values
## DevOps Principles 
## DevOps Methods 
## DevOps Practices
## DevOps Tools 

Implementation and maintenance of internal microservices such as Jenkins, code review system, infrastructure monitor, git server, etc. 

Implemented continuous integration and Continuous Delivery process using Git/SVN, Jenkins, Maven & AWS.
Implemented continuous deployment pipeline using Jenkins, Chef and Shell Scripting.
Implemented continuous testing pipeline using Jenkins, Selenium, Chef and Shell Scripting.

* [3 Key DevOps Needs for Every Development Team](https://stackify.com/key-devops-functions-for-development-team/)

* [What is DevOps? – Give Your Development Team Ownership](https://stackify.com/what-is-devops/)

* [Top DevOps Tools: 50 Reliable, Secure, and Proven Tools for All Your DevOps Needs](https://stackify.com/top-devops-tools/)


http://electric-cloud.com/resources/continuous-delivery-101/continuous-deployment/

# DevOps solutions
	http://electric-cloud.com/solutions/full-stack-provisioning/
	http://electric-cloud.com/solutions/continuous-integration-ci-automation-and-acceleration/
	http://electric-cloud.com/solutions/devops-orchestration/
	http://electric-cloud.com/solutions/deployment-automation/
	http://electric-cloud.com/solutions/release-management/
	http://electric-cloud.com/solutions/chef-puppet-orchestration/
	http://electric-cloud.com/solutions/container-orchestration/
	http://electric-cloud.com/solutions/embrace-extend-jenkins/
	http://electric-cloud.com/solutions/qa-lab-provisioning/
	http://electric-cloud.com/solutions/compliance-and-auditing/
	http://electric-cloud.com/solutions/agile/
	http://electric-cloud.com/solutions/unlock-agile-bottleneck/
	http://electric-cloud.com/solutions/iot-and-embedded/

Service monitoring
Error tracking
Performance metrics
Production debugging
Safety nets


* Configuration Management
* Continuous Integration
* Continuous Inspection
* Containerization
* virtualization

## webinars & Video Discussion
http://electric-cloud.com/resources/webinars/
https://www.cloudbees.com/resources/devops-radio
http://electric-cloud.com/lp/continuous-discussions/

https://continuousdelivery.com/

## Containerization
* Docker


## IT & Configuration Automation Tools
* Puppet
* Chef


## Network and Storage Automation
* Puppet
* [Puppet Labs Moves Into Network and Storage Automation](http://blogs.wsj.com/cio/2014/06/24/puppet-labs-moves-into-network-and-storage-automation/)

# DevOps BootCamp
https://devopsbootcamp.osuosl.org/index.html

## Use Cases for Puppet and chef
https://www.quora.com/Configuration-Management-Can-you-explain-what-are-the-usecases-for-puppet-and-chef
[Chef-use-cases](http://projects.theforeman.org/projects/foreman/wiki/Chef-use-cases)

# Performance Management
* [Digital performance management for the customer-centric era](https://www.dynatrace.com/technologies/)


## Puppet VS chef VS ...
* [Ansible vs. Chef vs. Fabric vs. Puppet vs. SaltStack](http://blog.takipi.com/deployment-management-tools-chef-vs-puppet-vs-ansible-vs-saltstack-vs-fabric/)
* [Chef is for developers, Puppet is for admins (There, that’s settled)](http://venturebeat.com/2015/07/20/chef-is-for-developers-puppet-is-for-admins-there-thats-settled/)
* [Puppet versus Chef](http://bitfieldconsulting.com/puppet-vs-chef)
* [Puppet vs. Chef - The Battle Wages On](https://www.upguard.com/blog/puppet-vs-chef-battle-wages)
* [Puppet vs. Chef Revisited](https://www.upguard.com/articles/puppet-vs.-chef-revisited)


## YAML
* [Learn yaml in Y minutes](https://learnxinyminutes.com/docs/yaml/)
* [Understanding YAML](https://docs.saltstack.com/en/latest/topics/yaml/)


## URL
* [Building and Securing a Modern Backend API](https://scotch.io/tutorials/building-and-securing-a-modern-backend-api)
* [Continuous Delivery of iOS Applications with Team Services](https://blogs.msdn.microsoft.com/visualstudioalm/2016/08/25/continuous-delivery-of-ios-applications-with-team-services/)
* [Continuous Integration for iOS Apps with Visual Studio Team Services](https://blog.xamarin.com/continuous-integration-for-ios-apps-with-visual-studio-team-services/)
* [THE IMPORTANCE OF AGILE AND DEVOPS FOR END-USER EXPERIENCE](http://bitbar.com/the-importance-of-agile-and-devops-for-end-user-experience/)
* [43 free and open-source tools that put the Ops in DevOps](http://techbeacon.com/open-source-tools-put-ops-devops)
* [Mobile antivirus fail: Why secure DevOps is the way forward](http://techbeacon.com/mobile-antivirus-introduces-vulnerability-how-devops-could-have-stopped-mess)
* [Demystifying Scrum for the Ops Crowd](https://devops.com/2016/09/23/demystifying-scrum-ops-crowd/)

Lesson Learned in Scaling Enterprise DevOps
https://www.youtube.com/watch?v=PheuDcnWS_c

# Workshop
http://dtosolutions.com/devops/devops-workshops/

https://www.sonatype.com/all-day-devops-ondemand?submissionGuid=614e059d-3941-46a3-b759-fd07072b04b7

Getting Started with Secure DevOps
https://devops.com/getting-started-secure-devops/


SQL Server Data Tools in your DevOps pipeline
https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/SQL-Server-Data-Tools-in-your-DevOps-pipeline


7 Highly Effective Continuous Delivery Principles
https://devops.com/7-highly-effective-continuous-delivery-principles/

Set up custom process groups for monitoring
https://www.dynatrace.com/blog/set-custom-process-groups-monitoring/

How Capital One Automates Automation Tools 
https://dzone.com/articles/how-capital-one-automates-automation-tools

Embedding Ownership: A DevOps Best Practice 
https://dzone.com/articles/embedding-ownership-a-devops-best-practice


Business impact analysis now provided with each detected problem
https://www.dynatrace.com/blog/business-impact-analysis-now-provided-detected-problem/

https://github.com/ciandcd/awesome-ciandcd

Starting and Scaling DevOps in the Enterprise: Optimizing The Basic Deployment Pipeline 
https://dzone.com/articles/starting-and-scaling-devops-in-the-enterprise-opti


A/B Testing and Web Performance 
https://dzone.com/articles/ab-testing-and-web-performance

# Continuous Planning
![1](https://www.techmahindra.com/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/Continuous-Planning.jpg)

# Continuous-Integration
![1](https://www.techmahindra.com/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/Continuous-Integration.jpg)

# Continuous-Testing
![1](https://www.techmahindra.com/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/Continuous-Testing.jpg)

# Continuous-Deployment
![1](https://www.techmahindra.com/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/Continuous-Deployment.jpg)

# Continuous-Monitoring
![1](https://www.techmahindra.com/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/Continuous-Monitoring.jpg)


![1](https://www.srijan.net/sites/default/files/inline-images/DevOp-Processes.jpg)
![1](http://softcrylic.com/wp-content/uploads/2017/03/infographics-continuous-testing.jpg)
![1](https://cdn.edureka.co/blog/wp-content/uploads/2016/10/2-DevOps-tools.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb665.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb666.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb667.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb668.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb669.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb670.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb671.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb672.png)
![1](https://msdnshared.blob.core.windows.net/media/2016/06/image_thumb677.png)
![1](http://68.media.tumblr.com/fd4468c702022048ee4ac76151723e03/tumblr_onlv4oW7NI1rswam8o1_1280.png)
![1](http://68.media.tumblr.com/06e8ecc5a5fe04347f31ff376965587d/tumblr_onlv4oW7NI1rswam8o2_1280.png)
![1](http://68.media.tumblr.com/dfe46f3c96f07754b624e98a8e470897/tumblr_onlv4oW7NI1rswam8o3_r1_1280.png)
#Building an integrated Agile/DevOps Maturity Model showing how to progress
![1](http://community.hpe.com/legacyfs/online/47878i6F442CC85F4E1B73/image-size/original?v=mpbl-1&px=-1%22)

![1](https://msdnshared.blob.core.windows.net/media/2016/11/SNAGHTMLb41cf97.png)
![1](http://bitbar.com/wp-content/uploads/2015/01/Screen-Shot-2016-10-03-at-11.04.33-PM.png)
![1](http://bitbar.com/wp-content/uploads/old_testdroid/Screen-Shot-2015-01-13-at-10.11.06-AM.png)
![1](http://bitbar.com/wp-content/uploads/2016/10/Screen-Shot-2016-10-04-at-3.08.39-PM.png)
![1](http://bitbar.com/wp-content/uploads/old_testdroid/2015/10/testing_method_apperoach_2015.png)
![1](http://bitbar.com/wp-content/uploads/2016/10/testing_method_v05.png)
![1](http://bitbar.com/wp-content/uploads/old_testdroid/2015/10/time-to-market-2015.png)
![1](http://bitbar.com/wp-content/uploads/old_testdroid/2016/05/mobile-devops-deconstructed.png)
![1](http://bitbar.com/wp-content/uploads/2016/09/Screen-Shot-2016-09-22-at-1.51.46-PM.png)
![1](http://www.hcltech.com/sites/default/files/images/technology_.png)
![1](http://www.hcltech.com/sites/default/files/images/implementation.png)
![1](http://www.cigniti.com/blog/wp-content/uploads/2015/12/Devops.png)
![1](https://www.qa.com/-/media/qa/icons/devops/devops%20diagram%20600x680.jpg)
![1](http://www.cigniti.com/blog/wp-content/uploads/2015/12/Devops-overview.png)
![1](http://www.hcltech.com/sites/default/files/images/customer.png)
![1](http://www.swiftkanban.com/wp-content/uploads/2015/08/kanban-for-devops.png)
![1](https://rhrempel.files.wordpress.com/2015/11/opensourceecosystem.jpg)
![1](https://rhrempel.files.wordpress.com/2015/11/microsoftecosystem.jpg)
![1](https://msdnshared.blob.core.windows.net/media/MSDNBlogsFS/prod.evol.blogs.msdn.com/CommunityServer.Blogs.Components.WeblogFiles/00/00/00/45/92/metablogapi/4743.image_thumb_77E2CDB0.png)
![1](http://coe.aceinfosolutions.com/sites/default/files/maturity.png)
![1](http://1.bp.blogspot.com/-PYQejoom20I/VqOk6Xrg6kI/AAAAAAAACKs/y51cNaKPII8/s400/continuous-delivery-maturity-model-v1.0.png)
![1](https://redhatmiddleware.files.wordpress.com/2016/06/image00.png)
![1](https://s-media-cache-ak0.pinimg.com/564x/6f/15/ec/6f15ecf5239fcc4e0b3b27b6daee14ca.jpg)
![1](http://java.dzone.com/sites/all/files/CD_Infographic.jpeg)
![1](https://s-media-cache-ak0.pinimg.com/564x/06/13/f1/0613f1a0e1af6b5c4fe0ba1df097a5f3.jpg)
![1](http://www.relevancelab.com/RLCatalyst/assets/img/catalyst/blog/devops1-flow.png)
![1](https://xebialabs.com/assets/files/infographics/periodic-table-of-devops-v2.png)
![2](https://blog.xebialabs.com/wp-content/uploads/2016/08/DevOps-Diagram-Generator-Animated.gif)
![1](http://cdn2.hubspot.net/hubfs/381387/Blog-image-tracking/ElasticBox-DevOps_Open_Source_Tools.png)
![2](http://cdn2.hubspot.net/hub/208250/file-2451034899-jpg/Blog_Images/ContinuousTestingBlog1.jpg)
![2](https://www.cloudbees.com/sites/default/files/blog/cd-flow.png)
![1](http://www.getzephyr.com/sites/default/files/Continuous_Delivery_process_diagram.svg.png)
![1](http://www.getzephyr.com/sites/default/files/Webinar%20Image_DevOps.png)
![1](https://devops.com/wp-content/uploads/2015/04/cd-devops.png)
![1](http://cdn.electric-cloud.com/wp-content/uploads/sdlc-tools.jpg)
![1](http://techbeacon.com/sites/default/files/picture1_1.png)
![1](http://techbeacon.com/sites/default/files/picture2_1.png)
![1](http://www.techmahindra.com/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/system-feedback.jpg)
![1](http://www.techmahindra.com/en-US/wwd/services/_LAYOUTS/1033/IMAGES/TechMahindra/services/DevOps/devops-collaboration.jpg)
![1](https://www.cebglobal.com/content/cebglobal/us/en/information-technology/implementing-devops/jcr%3Acontent/content-left/cebimagebox/image.img.png/1474992205921.png)
![1](http://msystechnologies.com/Resources/services/devops.png)
![1](https://s-media-cache-ak0.pinimg.com/564x/5e/38/92/5e3892c5467701035aadf7f1bbc86432.jpg)
![1](https://s-media-cache-ak0.pinimg.com/564x/ea/78/51/ea78519dc9a03e7f2ffefa88f0236a30.jpg)
![1](https://s-media-cache-ak0.pinimg.com/564x/a2/9c/4c/a29c4ccf98ad6e5ac0df9b2406bb8ec5.jpg)
![1](https://www.ibm.com/developerworks/library/d-adoption-paths/fig3.jpg)
![1](https://www.ibm.com/developerworks/library/d-adoption-paths/fig2.jpg)
![1](https://www.ibm.com/developerworks/library/d-adoption-paths/fig1.jpg)
![1](https://continuousdelivery.com/wp-content/uploads/2014/02/01_CD_the_idea_low-res.jpg)
![1](https://continuousdelivery.com/wp-content/uploads/2014/02/02_CD_test_strategy_low-res.jpg)
![1](https://continuousdelivery.com/wp-content/uploads/2014/02/03_CD_automated_acceptance_test_low-res.jpg)
![1](https://continuousdelivery.com/wp-content/uploads/2014/02/04_CD_managing_data_low-res.jpg)
![1](https://s-media-cache-ak0.pinimg.com/564x/38/94/fc/3894fcee128464d7e5d80c4c4b66edad.jpg)
![1](http://techbeacon.com/sites/default/files/picture1_1.png)
![1](https://s-media-cache-ak0.pinimg.com/736x/ba/42/ae/ba42ae98c8133bdd32cf1e02f83c9450.jpg)
![1](http://www.cigniti.com/blog/wp-content/uploads/measuring-success-of-agile.png)
![1](https://msdnshared.blob.core.windows.net/media/MSDNBlogsFS/prod.evol.blogs.msdn.com/CommunityServer.Blogs.Components.WeblogFiles/00/00/01/64/90/metablogapi/7652.clip_image002_thumb_6398D5D6.jpg)
![1](https://s-media-cache-ak0.pinimg.com/564x/36/52/4d/36524dd6703ad74420e54e238e200513.jpg)
![1](https://s-media-cache-ak0.pinimg.com/564x/8a/13/2d/8a132d4723e59c14a65215ec309bd077.jpg)
![1](https://s-media-cache-ak0.pinimg.com/564x/27/fb/4d/27fb4d89329182aa830ba731a8cd9389.jpg)
![1](http://thenewstack.io/wp-content/uploads/2015/12/infrastructure-automation-ecosystem-landscape-infographic.jpg)
![1](https://media.licdn.com/mpr/mpr/shrinknp_800_800/p/3/005/0a3/23b/27ad267.jpg)
![1](https://media.licdn.com/mpr/mpr/shrinknp_800_800/p/1/005/0a3/23b/305f56e.jpg)
![1](https://media.licdn.com/mpr/mpr/shrinknp_800_800/p/1/005/0a3/23b/3658153.jpg)
![1](https://d0.awsstatic.com/product-marketing/CodePipeline/CodePipeline_Workflow.png)
![1](https://d0.awsstatic.com/product-marketing/DevOps/continuous_integration.png)
![1](https://d0.awsstatic.com/product-marketing/DevOps/continuous_delivery.png)
![1](https://image.slidesharecdn.com/microsoftanddevops-presentedbyatidan-160226030051/95/microsoft-and-devops-presented-by-atidan-18-1024.jpg?cb=1456455840)
![1](https://image.slidesharecdn.com/microsoftanddevops-presentedbyatidan-160226030051/95/microsoft-and-devops-presented-by-atidan-19-638.jpg?cb=1456455840)
![1](https://rhrempel.files.wordpress.com/2015/11/opensourceecosystem.jpg?w=1024)
![1](https://rhrempel.files.wordpress.com/2015/11/puppetmaster.jpg?w=1024)
![1](https://s-media-cache-ak0.pinimg.com/564x/c7/a0/ff/c7a0ffa76949884c6db342185821ee13.jpg)


![1](https://cdn.infoq.com/statics_s1_20170321-0330/resource/articles/Continuous-Delivery-Maturity-Model/en/resources/7fig1small.jpg)
![1](https://s-media-cache-ak0.pinimg.com/736x/e1/37/ff/e137ff342760f7a0c0893e3f68e0a057.jpg)
![1](https://media.licdn.com/mpr/mpr/shrinknp_800_800/AAEAAQAAAAAAAAH_AAAAJDBhOTk0NDNmLWZlOTctNGUwNi04YmM2LTFkMDQxYjI0OTMyMA.jpg)
![1](http://techieroop.com/wp-content/uploads/2017/02/7-1024x356.png)
![1](http://techieroop.com/wp-content/uploads/2017/02/BestPractices_for_a_MatureContinuousDeliveryPipeline.png)
![1](https://dzone.com/storage/temp/3557679-devops-cycle.png)
![1](https://dzone.com/storage/temp/3557774-devops-scenario.png)
![1](https://www.accenture.com/t20161130T204327__w__/us-en/_acnmedia/Accenture/Conversion-Assets/Blogs/Images/19/Accenture-Practical-Benefits-Thumbnail.jpg?la=en)
![1](https://cdinsight.files.wordpress.com/2015/07/fit-quality-in-cd-pipeline.jpg)
# DevOps Roadmap
![1](https://camo.githubusercontent.com/bdc81def398a0d13b70066783021b789e922fb91/68747470733a2f2f692e696d6775722e636f6d2f6c324b4e4859492e706e67)
