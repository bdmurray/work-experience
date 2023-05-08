# Architecture

* Azure Next Gen
  * Push to Support Dev/Test Pricing
* Digital Factory
  * lots of \"digital\" resistance to the amount of data and cost of the program
    * continued to educate on cloud and buy vs build (NIH)
    * org never formed due to pandemic prioritization
    * discussions starting again and teams are leveraging the framework
    * provided architecture support for multiple POC efforts by both AWS and Microsoft
  * led discussions regarding movement of data from historians to cloud
  * year long committee to create new digital manufacturing ops group
  * worked with Rockwell Automation on their product roadmap to support effort
  * created strategies around data movement for hot/warm/cold data use cases
* Greenville
  * 1st manufacturing data science project at 3M
    * successfully detected anomalies on the manufacturing line
    * in production for 3 years, anomaly response has had $5M/yr waste reduction impact
  * worked with another developer on zero touch POC
    * Used today by Process Labs / TTS and Digital Factory
  * travelled with team to help with cloud infrastructure and edge container deployment
  * provided end to end data lifecycle map, ML ops and process flow diagrams
* KCI / Acelity
  * business review
    * wound color classification
    * depth measurement harder without lidar
    * found area for wound boundary identification opportunity
      * JIT manufacturing effort
        * Deployed to 3 research projects
      * project team established
        * Wound condition and boundary detection algo deployed to business
  * architecture review
    * made suggestions to improve onboarding / 3M security review
      * Onboarded in a month vs three
    * helped optimize IoT data movement
      * Payload savings roughly $200/mo
  * 3M acquisition onboarding support
  * IoT connectivity solutioning for remote wound care device
* LeanTec Acquisition
  * Asked to do architecture evaluation by senior leaders under NDA
  * Spent 3 days sequestered reviewing Leantec Infrastructure / Code
  * Leveraged 12 factors to evaluate systems
    * Using as an example of 12 factors in CBG to improve quality
    * LeanTec Acquired
    * Created a roadmap of improvements and team sizing/estimates
    * Created a full report used by division and M&A
* Material Informatics
  * API Strategy
  * Custom file ingest
  * Split apart the monolith
* MX
  * architecture
    * implemented cloud infrastructure POC used by program
    * provided education to team / stakeholders on cloud / iot / edge
    * created data flow for various communication channels to support model development
    * consolidation ideas around a single set of diagrams
    * filed 2 individual / 3 team IS
      * 1 ind / 2 team patent being filed globally
      * mesh network capture of communication information
  * multiple division application
    * digital factory
      * archived to transfer for future internal \"in the dark\" manufacturing efforts
    * connected safety
      * transferred and leveraged architecture pattern for several projects
  * predicted $500M impact once commercialized  ($4.3B market and number based on projected sales)
  * global team
* Process Informatics
  * zero touch
    * evaluated outpost / snow device options but feature limited or cost prohibitive
    * brought in vendor (Zededa) and also explored EKS/ECS Anywhere as they were released
    * educated out to stakeholders on updating edge device from cloud
      * removed internal politics from team
  * azure to aws migration
    * adopted agnostic replacements of Azure specific services
      * Event Hub -> Kafka
      * blob -> Min.IO
      * SQL -> Influx (upstream match)
    * agnostic allowed for in flight work to continue and incrementally migrate
      * team is still making progress today, deployed to 3 lines and 5 more planned for 2022/2023
    * leveraged GGv2 as Azure IoT common Docker
  * edge manufacturing architecture

# Bluebird

* Combine 7 Existing Processes
  * 1 Tooling Request
  * 2 AAD Requests (Tooling / Azure)
  * 4 Subscription Requests
  * Reduction of 6 months to 2 weeks
* Plan Trip
  * Locked in room for a week
  * Travel to Redmond
  * Work with Managers in TTS / ISRC
  * Built Out Automation
    * Returned with 90% functional system
  * Topics
    * Policies / Roles
    * DevOps / Release Tooling
    * Subscription Structure
  * Still heavily in use
    * Helped build a large 3M network of trust
    * Adapts as \"close to core\"
    * 60+ active projects

# CBG

* Command Mobile Backend / Image Service
* Event Based Decouple
  * Saw the opportunity to decouple systems by produce/consume event streams
  * Transition difficulties so needed an incremental win to build trust
  * Won over the developer community
    * Schema registry is validating data
      * increased trust between teams
    * Started the conversation around Contracts/SLAs to introduce Data mesh incrementally
    * Now overseeing an integration that will generate millions of events/day and feed ML experiments that was previously deemed \"impossible\" by the teams.
* Grand Central / Data Mesh
  * Reviewed their existing roadmap and talked with divisions
  * Currently working on education / culture discussions
    * CBG would be first BG with E2E data access
  * Leadership agreed to 2023 budgeting
  * Built confidence over the first month incrementally
  * Saw a lot of opportunity for a data mesh architecture
* PostIt CEO Summit
  * RG to Sub mistake
    * Redid scaffold to support use case
      * Leveraged savings to bring on additional LT GitOps lead
      * Avoided a $200k estimate from MSFT proserve
    * Made E2E GitOps corrections a priority
  * Architecture Tasks
    * Constantly working to support long time vendor
      * Helping to walk back some of the larger bloat
      * Scaffold GitOps pipelines to reduce maintenance burden
        * Leveraging as an example for all CBG
    * Secure K8S environment available
    * Support PCI/SOC2 compliance screenings
    * Existing AWS backend conversion (political)
    * Microsoft/3M CEO Summit
    * Brought in as Architect while in CRSL
      * Good work helped me get my role in CBG
    * Support Azure Next Gen
* SQL Hyperscale
  * Reviewed E2E architecture for all systems
    * Dug into the \"why\" with stakeholders, found it was used for a single retailer (Walmart)
    * Found a SQL instance running 24x7 tuned to hyperscale (large data/memory pool)
  * Proposed Synapse SQL Serverless Pool
    * Created a POC and scripted all existing retailers
    * Naturally integrated with Delta tables without conversion
    * 1st month workload is $100 vs previous $5k
  * Another transition item to help build trust
* Transition
  * Worked to identify key leaders and provided 1:1 training on concepts like events and serverless
    * Agreement to start business group wide data mesh discussion
    * Provided more direct influence
    * Built out user stories to support \"leader\" PO
  * Built out full architectural roadmap to implement the leadership plan in a shorter timeframe
  * Built confidence incrementally through small wins with developers
  * Took on the role but even leader was adverse to \"research\" mindset

# CPO

* Alignment / Team Topologies
  * Created a share out around team topologies
  * Warring CPOs and bad politics (resources/budget)
  * Assigned an entire metascrum structure
  * Shifted all teams under my meta scrum to Enablement to support others
    * Change the way R&D work was presented to leadership (proactive vs reactive)
    * Less in fighting and alignment
* AWS IoT
  * Made decision to focus on OSS Solutions
  * Worked with AWS
    * Limited window/investment to align to need
    * Did a proper archive and built out internal docs
      * 1 year later it is being picked up again by an internal team
    * Found a way for Azure IoT team to get much needed AWS skills
    * Short ProServe engagement to get access to Connected Devices Framework
  * Determined there would still be a need one day
  * 3M shifted to AWS focus
  * No additional IoT projects in corporate hoppe
* Cloud Transition
* MaaS
  * Young PO
    * helped build the feature roadmap for next 2 quarters
      * Decreased the cycle time on model improvements from days to minutes
      * top internal tool with 100s of statistical models deployed
      * Put the ability for the customers to fine tune the model parameters without the modelrs
    * Setup mentorship for PO with internal product manager
  * Took over CPO where I had to understand the full domain
    * M&S Customers
      * Looked for features in HPC not surfaced (Altair)
      * Canvased their work flow
      * Talked to their customers
    * HPC
  * Provided initial architecture centered around data movement/security
    * licensing complexities but APIs
    * black box
* OnePlace
  * Realized quickly "not invented here" was the core logic
    * Educated on pros of buy vs build
      * Saturated market with clear leaders
      * 0 IP Potential
      * No significant feature not already present
    * Created a small working group of tech experts to evaluate
      * Shifted focus to upstream data intake problems and low/no code
      * Immediately delivered value to stakeholders
      * Reduced CW team members saving more than cost of 1st year licenese
      * Long term partnership with TTS leaders
    * Still leveraging in CBG
    * Worked with IT to canvas existing vendors
  * Did a full canvas, persona development, architecture review, stakeholder roundtable
  * Was viewed as a boondoggle project by a departed leader
* Oral Care ML Ops
  * Approached by division partner
    * had asked leadership but no commitment
  * leverage 15% time under the radar
    * division leadership reached out thanking team members to director
      * helped expose some negative qualities to current manager (politics over process)
      * recognized by lab director
    * established a team motto of giving
      * "free" backlog item creation as long as they mapped effort to value
        * increased story/PBI quality
    * total investment of time more like 5%
    * created POC in 1 week and production deployment two weeks later
    * established a team motto of giving
      * team recognized for large 15% contributions
  * I / my team had the skillsets
    * researched reference patterns / examples (early)
    * Created initial architecture against reference patterns
    * stood up POC leveraging tooling
    * pulled in team members to flesh out POC
* Org Structure
  * Made a mock org chart to spur conversation
  * Pulled into reorg conversations
  * Focused on talents of leaders and matched to people
  * Conversation still slow so I slotted in names
    * Resulted in having a dialog and adopted roughly 80% of original
* Portfolio Review
  * Building the Edge &  Data Platform
    * I also made sure to seek experts / advocates to contribute to narrative
      * Resulted in defense of ideas by others
    * Present / anonymous feedback
    * Feedback largely critical due to digital vs material
    * After first year I added an action item to de-anonymize feedback
      * Resulted in great conversations

# Hackathon

* Drone
  * OneWeek 2018
    * Drone projects were completed with 3 divisions
      * connected safety / fire fighter location
      * corporate campus building mapping
      * IATD: inspecting exterior tape applications
  * Led a team of 5 developers to Redmond
  * Met Satya Nadella
  * Helped debug odd behaviors
  * Did work in AirSim before hackathon
  * Trained model / image capture / tag recognition
  * Worked with DJI to get unreleased SDK
* Flex Lab Application Engineers
  * Proposed using HL2 Remote Assistant / Guides
    * Worked to educate AEs on HL2 and platform
    * Imported 3D models of facilities/process to create guide overlay
      * Still used today and scaled out to digital factory by requesting team
      * Unblocked $2M in sales with 1 week effort
    * Created a small team through 15% & hackathon
  * T6 presented me with pandemic issue
  * AEs couldn't go to customer sites to help consult
* IAM Hack
* Inception    
  * Attended Microsoft OneWeek as part of large clients in 2018
    * Made a drone afraid of a chair
  * Microsoft had created a framework for developing hackathons
  * Spent time with the organizer at OneWeek planning a roll out at 3M
  * Lots of manager push back / large \"not my idea\"
    * Finally asked simply to present the concept to the lab director
      * Has resulted in a large number of projects / impact for the company
      * Still growing year over year
      * Lab director loved it and became the champion of it / scaled it
      * 2nd year (pandemic) global participation of 900+ individuals (all remote)
      * 1st year 500 in person participants with AWS/Microsoft/GitHub sponsors at RiverCenter
    * Partnered with Legal to remove the largest hurdles
    * Completed the framework with Microsoft
    * Worked to measure interest with Divisions
    * Built a large amount of advocacy
* IoT Hackathon
  * presented training materials and helped debug for 3 days of hackathon
    * devices were used in a handful of additional research projects
    * IoT knowledge share with 120 participants
    * helped me create a large network / be recognized as IoT leader at 3M
  * led awards ceremony
  * built out curriculum with Microsoft on IoT test kits
  * 1st year of hackathon
  * worked to bulk procure 200 devices
* MkDocs Automation
  * established a github template
    * internal innersouce example / docs standard
    * Used by 100+ projects over 4 years
  * add features over time
    * working on E2E automation using Az Static Web Apps / AWS
    * github pages hosted
    * improved template
    * github actions
  * Created a simple git / pipeline based solution
* Pandemic Response
  * key issue identified as environmental impact and stockpile management
    * finalist in global hackathon
    * timeline exceeded expected pandemic
    * worked to estimate roll out / implementation
    * proposed smart collection and ULD marketplace
  * captured architecture of current enterprise connected systems for mask distribution
  * team across 13 time zones, was going to work at 3 a.m.
  * spoke with pandemic response leaders in key countries and 3M's global leader
* Pfizer Sustainability Partner Hack
  * Analyzed their clinical trial supply chain
    * Personal learnings
  * Used to analyze / score each step of their supply chain
    * On target to hit their sustainability goals
    * Completed a roll out of the solution
  * Created a prototype mobile app
    * scoring app in production today
  * Reduced scope due to hack, targeted scoring / measurement
* Quantum Inspired Optimization
  * determined cost over improvement QIO wasn't efficient enough
    * ongoing quantum user group being formed
    * still being evaluated in material discovery
  * worked with researchers to validate use case
  * Found a use case in supply chain
  * worked with both cloud tool kits to compare results
* Social Justice

# Introduction

* 25 years experience
* 3Ms digital journey
  * cloud adoption
  * open source
  * IAM / Security
  * DevOps processes
* Architect last 16 years
  * complex
  * ambiguous
* Current role
* IoT Opportunity
  * IT / Research / BG
  * projects
    * edge / jit manufacturing
    * digital factory
    * retail analytics
    * commercial product launches
    * now more big data / ai / ml
  * manufacturing to digital
* Prior
  * 14 years technical sales CSA
  * ever changing landscape of problems
* role
  * working with their leadership / executive stakeholders
  * get back to customers
* tinkerer/smart home
  * 3M IoT

# IoT

* Connected Safety
  * Field Trials
    * Beacon Device Position
    * Lead Acid Battery Plant
    * Remote Device FW Updates
      * 7 IS / 5 patents in progress, program transferred but not released
      * Launch was scheduled but program terminated due to Covid focus
  * Multi Tenancy
    * surveyed customer trust increased from 40% to 75% with security details
  * GDPR Data Isolation & Requirements
    * Successful device provisioning test of 100 EU devices
  * Complex Distributor Network
    * Global Device Provisioning
* EMD Grid Modernization
  * Cloud Selection
    * AWS IoT Platform Partnership
      * 18 IS / 9 patents in progress, $40M projected sales
      * Transfer but not deployed
  * Highly regulated environment
    * Isolated Tenancy Model
      * Achieved their device and energy grid certification
  * Grid Algo Optimization
    * Established ML Ops Loop
      * New models are deployment: weeks and manual update to hours
  * Long term partnership
  * Firmware Process Improvement
    * Azure RTOS vs Free RTOS
* Filtrete Product Launch
  * 200k+ users, sales of $10M/year, 8 IS, 2 patents in progress
  * Streaming Data Ingest
    * Eliminated batch ETL
      * Databricks Structured Streaming
        * Data more predictable & real time views
    * Removed stream analyitces
      * Unnecessary for use case
        * Saved $300/mo
  * Cost Optimization
    * Payload Batching
      * Reduced number of messages
        * Modified OSS to Create Simulator
        * Innersourced / Reused by others
        * Create / Ran Unit Tests
        * Produced Reports
          * Saved $800/mo
            * production 3 years with increased load
    * ML Ops Setup
      * Established a Training/Test data lifecycle
    * VM to Serverless ML
      * Scale Out
      * Event Based / Queue
        * Remove tight decouple to improve maintenance
      * App Services Containers
        * Cost savings of over $1500/mo
    * ML Ops Setup
      * Models to production in under 1 hour
* First OSS Project
  * Worked with Microsoft / 3M Legal
    * All but AGPLv3, established MIT as outgoing standard
    * Contributed back all changes including multi-tenancy
    * First OSS Platform at 3M
  * Reduce Tech Debt
    * allowed external contributions from Microsoft
    * eliminate original code base
  * Improve Team Morale
    * Retrospective happiness from 1 to 8
  * Migration Planning / roadmap established
    * Increased system features by 3x
    * Migrated all 3 divisions in under 2 months
* Japan / Taiwan Projects
  * Smart Water Filtration
    * Industrial Product Launch
  * Train Electric Grid Improvements
    * Research Deployed
  * Isolated Team
    * Hackathon and Networking
      * Trust / Team Visibility
  * Cultural Nuances
    * Researched Interaction
      * Working Rapport
* Platform
  * Product Owner
    * Improve Delivery
      * Limit Access to Upper Environments
        * improved dev/prod parity
      * Establish Release Manager
        * 1 week to daily release to customer dev
      * Documented / knowledge shared metrics
        * patterns used by dozens of teams
      * Worked with managers to reward peer reviews
    * Reduce CW Team Size / Vendor
      * Cost Reduction of $500k/year
  * Transfer to TTS
    * Decision to Archive
* Secure device provision / mfg
  * Manufacturing
    * Worked with New Ulm Plant
      * (R) Capability & pattern established that used today / 10k devices and growing
    * FW Upload Process
      * Existing PC Health Check Mod - Catalog Device
      * Post Inspection
      * Pre Signed TPM
  * Education to Stakeholders
    * Importance
      * Avoid Brand Damage
    * Cost
      * SuperMicro
      * Azure IoT
  * Policy / Security Reviews
    * BOM HW Exception
    * Additional Provisioning Checks

# Mentorship

* 1:1 Training
  * Has resulted in 6 new architects for 3M, some have left for other large orgs
  * Take them through basic architecture process on project
    * System/Business/User KPIS
    * Will also do a well architected review
    * Evaluate against metrics
      * Ops
      * Cost
      * Measurement
      * Security
      * Reliability
      * Legal
      * Performance
    * Simplified TOGAF
  * Help to build their network by doing architecture \"road show\" internally
  * Time box effort to two weeks to garner wide acceptance
  * Work with managers to find capable engineers
* Always refer/support team members
* Architecture Corner
  * Opened it up to non-technical
  * Impacted more than 50 programs over 3 years
  * CRSL: Monthly with 15 to 30 people
* Art Fry
  * Learned a lot about determination and failure
  * 8 sessions over 16 weeks with inventor of PostIt Note
* GTLA Speech: Delivering Digital Product
  * Subjects included
    * Understanding Data Value / Product Ecosystems
    * Architecture / Cloud 101
    * Ideation / design thinking
    * hackathons / community building
    * Building a team / roles
    * Lean Startup / Scrum
  * Presented to an internal audience of over 100 people
  * Now part of 3Ms Tech Wizards and have presented to 2 high schools and 1 community college
* Mentorship Monday
  * Cross Lab Mentorship Program

# Older

* Consolidated Communications
* Harley Davidson
* MVTL
* Pearson Innerview
* RLWS
* UpOnGreen