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
* Bluebird
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
* CBG
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
* CPO
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