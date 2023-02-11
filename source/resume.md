<link rel="stylesheet" type="text/css" href="resume.css">

<span class="name">Tsz Shun Chow (Jason)</span>

<span class="info">

[![Mail](https://simpleicons.org/icons/minutemailer.svg) jasition@gmail.com](mailto:jasition@gmail.com)
[![GitHub](https://simpleicons.org/icons/github.svg) github.com/jasition](https://github.com/jasition)
[![LinkedIn](https://simpleicons.org/icons/linkedin.svg) linkedin.com/in/jason-chow-b7418624](https://linkedin.com/in/jason-chow-b7418624)

</span>

#### Highly motivated, passionate and detail-oriented Kotlin / Java engineer with more than 20 years hands-on experience. Strong technical background in low-latency financial systems.

## Specialties
Low-latency trading systems | Core banking systems and integration | Product-oriented engineering | A/B testing experiment design | Public API designer and writer | Event-driven systems | Multi-threaded real-time systems | CQRS | Event sourcing | Domain-driven development

## Professional experiences
### Webinars
- *"Transitioning to
Kotlin"* [sourcegroupinternational.com/events/transitioning-to-kotlin](https://sourcegroupinternational.com/events/transitioning-to-kotlin)

### Publications
- *"Building a bank? Here’s why you should use Kotlin"* [content.11fs.com/article/building-a-bank-heres-why-you-should-use-kotlin](https://content.11fs.com/article/building-a-bank-heres-why-you-should-use-kotlin)
- Technical blog:   *Strictly Programming* [jasition.github.io](https://jasition.github.io)

### Community contributions
- quickfixj: [github.com/quickfix-j/quickfixj/pull/212](https://github.com/quickfix-j/quickfixj/pull/212)

## Skills
### Languages
Kotlin | Core Java | Bash | SQL | PL/SQL

### Frameworks
Spring Boot | Micronaut | Ktor | Arrow | Disruptor | Flyway | Exposed | Jooq | JDBI | Resilience4J | Jupiter | Kotest | Mockk | Testcontainers

### Transports
REST | GraphQL | Rabbit MQ | Kafka | Confinity Low-latency Messaging | RFA | TREP | FIX | Quickfix | Kinesis | SQS | SNS | Protobuf | Avro | Json

### Databases
Oracle | mySQL | Postgres | Invision | InfluxDB | Metabase

### Methodologies
A/B Testing | Functional Programming | SOLID Principles | Event Sourcing | CQRS | Ports and Adapters | TDD | BDD | Scrum | Kanban | Continuous Delivery | Trunk-based development

### Source repositories
Github | Gitlab | Bitbucket | Perforce

### Build / CI / CD
Gradle | Maven | Docker | Kubectl | Github Actions | Gitlab CI | ArgoCD | Kubernetes | Kustomize | Jenkins | Bamboo

### Infrastructure
Terraform | CDKTF

### Observability
DataDog | Kibana | Splunk | PagerDuty | Opsgenie

### Platforms
AWS | Azure | GCP | Bare Metal | Mac OSX | Linux | Windows

### Other tools
Jira | Confluence | Figma | Miro | Notions | Lucidcharts

## Services
### Principal Engineer, 11:FS Group | <location> London </location> <time> May 2021 - Present </time>
#### Foundry, [11fs.com/products/11fs-foundry](https://11fs.com/products/11fs-foundry)
- Implemented the transaction aggregation with persistence.
- Platforms - GCP | Infra - Terraform | CI/CD - Github Actions, ArgoCD, Kubernetes | Languages - Kotlin, Scala | Transports - REST, GraphQL, Kafka | Databases - Postgres, H2 | Frameworks - Exposed, Ktor, Arrow, Flyway

#### Venture project template, [11fs.com](https://11fs.com)
- Implemented a backend project template for future client engagement.
- Platforms - Azure | Infra - AKS, Terraform | CI/CD - Gitlab CI, ArgoCD, Kustomize | Languages - Kotlin | Transports - REST, GraphQL, Kafka | Databases - Postgres | Frameworks - Exposed, Spring Boot, Flyway

#### NYDIG, [nydig.com](https://nydig.com)
- Designed and built the Bitcoin saving product with MVB Financial Corp [mvbbanking.com](https://mvbbanking.com/). Integrated with the core banking system via Helix API [docs.helix.q2.com](https://docs.helix.q2.com), in order that employees' salary was paid in Bitcoin.
- Developed the backend-for-frontend service that served onboarding, wallet, buy/sell and account flows. 
- Integrated with Taxbit [apidocs.taxbit.com](https://apidocs.taxbit.com/) to report transactions and to download W9 documents. 
- Configured and implemented retrying anddead lettering mechanism using RabbitMQ. 
- Platforms - AWS | Infra - Terraform | CI/CD - Github Actions, Kubernetes | Languages - Kotlin, Python | Transports - REST, Kafka, RabbitMQ, SQS, SNS, AMQP, files | Databases - Postgres | Frameworks - JDBI, Micronaut, Flyway

### Tech Lead, N26 | <location>Barcelona</location> <time> Mar 2019 - May 2021 </time>
#### Product Service [www.n26.com](http://www.n26.com)
- Re-architected the monolithic service that manages premium membership subscriptions and promotes customers the values of premium memberships.
- Split the monolithic service into microservices, and each microservice went through CQRS analysis and event storming to re-define the bounded-contexts.
- Conducted event-driven design, hexagonal architecture, and domain-driven design principles in the re-architecting.
- Designed and run A/B testing in verifying product ideas before fully invested in full solutions. 
- Platforms - AWS | Infra - Terraform | CI/CD - Jenkins, Kubernetes | Languages - Kotlin, Java | Transports - REST, Kafka, Kinesis, SQS, SNS | Databases - Postgres, Metabase | Frameworks - Spring Boot, Arrow, Flyway

### Technical Lead, IG Group | <location> London </lcation> <time> Jun 2015 - Mar 2019 </time>
#### Spectrum Markets [spectrum-markets.com](https://spectrum-markets.com)
- Designed and written the matching algorithms, benchmarked using JMH. Matching latency was down to 9 microseconds for 5-level depth book.
- Written the public FIX Rules of Engagement for the Exchange.
- Combined Event-Sourcing, CQRS, SOLID Principles, Functional Programming, Full TDD / BDD at all levels in Testing Pyramid. Used Hexagonal Architecture as application methodology.
- Platforms - Bare Metal | Infra - Puppet | CI/CD - Bamboo, Docker | Languages - Java, PL/SQL, Bash | Transports - REST, Kafka, Confinity LLM, RFA, TREP, FIX | Databases - Oracle, InfluxDB | Frameworks - Spring Boot, JMH, Disruptor, Resilience4J

#### NADEX [nadex.com](https://www.nadex.com)
- Scaled by the exchange system as it finally saturated by trade volume doubled every two years.
- Replaced Terracotta FX by local cache. 
- Replaced Redhat MRG QPID by Confinity LLM. 
- Used Reuters RFA to distribute Market data. Quote throughput was boosted from 3000 to 6000 per second, and order latency was
down to sub-milliseconds.
- Platforms - Bare Metal | Infra - Puppet | CI/CD - Bamboo | Languages - Java, PL/SQL, Bash | Transports - REST, AMQP, Confinity LLM, RFA, FIX | Databases - Oracle, Invision | Frameworks - Spring, Disruptor

#### FX price aggregator and smart order routing
- Maintained the public FIX Rules of Engagement for the system.
- Connected with 14 liquidity providers (e.g. BAML, Barclays, Morgan Stanley, HSBC) in setting up and onboarding of the new price FIX feeds and new trade FIX feeds. 
- Performed conformity testing and conducted live test trades with the dealers.
- Platforms - Bare Metal | Infra - Puppet | CI/CD - Bamboo | Languages - Java, PL/SQL, Bash | Transports - REST, Confinity LLM, RFA, FIX | Databases - Oracle, Invision | Frameworks - Spring

### AVP, Bank of America Merrill Lynch | <location> London </location> <time> Oct 2013  - Jun 2015 </time>
- Supported front office traders on the Interests Rate Swaps trading application. 
- Enhanced EURIBOR and LIBOR Interests Rate Swaps real-time trading GUI between the bank and other systems such as iSwap, Bloomberg, Tradeweb, etc. 
- Worked as a part of the global team including New York, Singapore and India. 
- Introduced the feature in the GUI to support Sterling swaps with multi-legs. Added the support for IMM and MAC swaps. Fixed urgent bugs and investigated queries from traders.
- Worked with traders on urgent issues and GUI upgrade. The GUI was written in Java/Swing/JIDE.
- Platforms - Bare Metal | Languages - Java | Transports - REST, JMS | Frameworks - Swing, JIDE

### Technical Lead, IG Index | <location> London </location> <time> April 2008 - Oct 2013 </time>
#### NADEX [nadex.com](https://www.nadex.com)
- Re-written the HedgeStreet system with Terracotta and QPID. 
- Utilised data grid technology Terracotta to achieve data partitioning and high availability. 
- Designed and maintained the public NADEX FIX Specifications.
- Built the framework for messaging for JMS and FIX. Profiled java code and debugged memory leaks. 
- Designed data-driven test framework for order matching. 
- Designed concurrent and multi-threaded distributed caching mechanism. 
- Revamped the ledgering component in Clearing House. 
- Built the frameworks and utilities for Swing GUI using JIDE.
- Platforms - Bare Metal | Infra - Puppet | CI/CD - Bamboo | Languages - Java, PL/SQL, Bash | Transports - REST, AMQP, RFA, FIX | Databases - Oracle, Invision | Frameworks - Spring, JIDE

#### HedgeStreet
- The first internet-based futures exchange regulated by CFTC in Chicago. 
- This n-tier J2EE system consists of a Designated Contract Market (Exchange), a Derivatives Clearing Organisation (Clearing House), FIX connectivity for Order Entry and Market Data, and a JSP / Servlet website. 
- Analysed and re-architected to boost trading throughput from 20 orders per second to 1000.
- Platforms - Bare Metal, Weblogic | CI/CD - Bamboo | Languages - Java | Transports - HTTP, JMS, RFA, FIX | Databases - Oracle | Frameworks - JSP, Servlet

### Systems Analyst, Hong Kong Housing Authority | <location> Hong Kong </location> <time> Sep 2006 - Dec 2007 </time>
#### Domestic Tenancy Management System
- Led a team of 4 engineers to analyse, design and develop a n-tier J2EE housing management system using Websphere and DB2, with agile methodologies and Paired Programming. 
- Gathered user requirements.
- Platforms - Bare Metal, Websphere | Languages - Java | Transports - HTTP, JMS | Databases - DB2

### Technical Analyst, OOCL Limited | <location> Hong Kong </location> <time> Jul 2005 - Sep 2006 </time>
#### Real-time Event Engine
- A Real-time multi-threaded messaging system based on JMS. 
- Developed a proprietary multiple-read-single-write object cache to boost performance by 50%.
- Platforms - Bare Metal, Weblogic | Languages - Java, PL/SQL | Transports - HTTP, JMS | Databases - Oracle

### Systems Analyst, Peopleware Systems Limited <location> Hong Kong </location> <time> May 2004 - Jul 2005 </time>
#### Clearing House System of the Trans Link Systems
- The national public transport backoffice system in The Netherlands.
- Led the team of 2 engineers on this n-tier J2EE system used Weblogic and Oracle. 
- Enhanced the multi-threaded framework to complete clearing and settlement for 16 million transactions within 2 hours.
- Platforms - Bare Metal, Weblogic | Languages - Java | Transports - HTTP, JMS | Databases - Oracle

### Software Engineer, Agile Software | <location> Hong Kong </location> <time> Oct 2002 - May 2004 </time>
#### Product Lifecycle Management [oracle.com/uk/scm/product-lifecycle-management](https://www.oracle.com/uk/scm/product-lifecycle-management)
- Led a team of 3 engineers working on a n-tier J2EE content management system based on Weblogic and Oracle. 
- Enhanced the proprietary distributed object cache and reduced application response time by 30%.
- Platforms - Bare Metal, Weblogic | Languages - Java | Transports - HTTP, JMS | Databases - Oracle

### Software Specialist, Intelligence Plus Limited | <location> Hong Kong </location> <time> Jul 2001 - Oct 2002 </time>
#### Learning Plus
- A Core Java e-learning system using mySQL, JDBC, Swing, Java2D, multi-threading, and UML.
- Languages - Java | Databases - mySQL | Frameworks - Swing, Java2D, Servlet

## Education
### The Chinese University of Hong Kong | <location> Hong Kong </location> <time> 2004 - 2006 </time>
- Master of Sceience in Computer Science | Average GPA 3.3

### The University of Hong Kong | <location> Hong Kong </location> <time> 1998 – 2001 </time>
- Bachelor of Cognitive Science | 2.1 Degree | Average GPA 3.1

## Extras
### Nationality
- British Citizen

### Languages
- English (native) | Cantonese (native) | Mandarin (fluent) | Spanish (elementary)

### Availability
- 2 months

### Hobbies
- Yoga | Tango

<!-- Detail checks: 1. No period for each bullet; 2. Past tense for previous work; 3. Present tense for current work; 4. Spell check passed; 5. Grammarly check passed; 6. Sync with Linkedin; 7. Check paper format -->
