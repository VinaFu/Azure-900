# Azure-900
Certificate Note

Vocabularies: 

      IaaS - Infrastructure as a Service
      PaaS - Platform as a Service    ( Superset of IaaS; has something more than IaaS)
      SaaS - Software as a Service    (have a Apps, pay for it: Microsoft 365)
      FaaS - Function as a Service    (on serverless)
      CLI - Command Line Interface - bash
      VM - virtual machine is a computer file, typically called an image, that behaves like an actual computer
      Power Shell - commonly used for automating the management of systems. It is also used to build, test, and deploy solutions, often in CI/CD environments.
      Cloud Shell - 
      ARM template - ARM: Azure Resource Manager
      scalability - 可扩展性
      CapEx - Capital Expenditure 资本支出
      OpEx - Operational Expenditure 运营支出
      latency - the time it takes data to travel
      datacenters -physical location
      latency-defined perimeter - within this area/perimeter, the datacenters are not too far from each other, low latency
      API - Application Programming Interface 应用程序接口
      ACI -Azure Container Instance


Resources: compute, networking, storage

Language of Cloud Computing: 
      
      High Availability | Reliability | Scalability | 
      Security | Predictability | Governance | Manageability 

      High Availability - core = always available; X own, add more servers with a click, replace when it fails, use cluster.
      Reliability - fault tolerance, disaster recovery; deploy in multiple locations, no single point of failure
      Scalability - Not have to automatically adjust resources to meet demand. (increase/decrease number of VMs)
                    Horizontal(sacaling out; typical) vs. Vertical Scaling(scaling up)
      Elasticity - based on current needs are added or decreased dynamically to meet those needs, from the most advantageous geographic location. Automatically
      Predictability - performance and costs
      Security - full control of the sloud security posture
      Governance - cloud deployments to meet requirement standards
      Manageability - management of cloud resources and how to interact with them.
      
Language of Cloud Economics:
      
      CapEx: one-time expenditure to buy tangible assets, such as building the data center
      OpEx: ongoing expenses incurred on services and products. pay-as-you-go
      
Pricing Models:
      Fixed price pricing - Hourly Pricing 
                          - charged for instances you have procured. VMs, APP Services
      
      Consumption - pay for the resources used
                  - pay as you go
                  - x buy and manage costly on-premise infrastructure
                  - no direct or up-front costs
                  - pay for more resources when they are required
                  - stop paying for resources when they not needed.
      
      
Azure Architecture/ Cloud Service Models:

      IaaS provides access to resources such as virtual machines and virtual storage: Google compute engine
            infrastructure = actual servers
            scaling is fast; X own hardware
            pay-as-you-go
            [VMs + Networks + Physical Buildings + storage]
      PaaS provides execution environments, application development, and deployment tools: Azure, AWS
            supports web application life cycle
            avoid license hell
            [IaaS + Middleware + Tools] middleware, i.e. database management tools
      SaaS provides software as a service to end-users: Google, Salesforce
            Providing a managed service
            pay an access fee to use
            no maintenance and latest features
            [PaaS + Apps] e.g Office 365
      FaaS Function as a server
            uses a service-hosted remote procedure call.
      Serverless 
            Azure is an instance of this
            Extreme PaaS
            [PaaS - extreme]
      
Cloud Architecture Models: 

      Private - resources exclusively owned, managed by single organization
            Pros:
                  scalability and efficiency
                  security           
            Cons:
                  Maintenance
                  Staffing
      Public -- Azure, AWS, GCP - owned, managed by vendor alone
            Pros:
                  No purchase/maintenance of hardware and software
                  only pays for the services that they consume
                  Lcost-effective reliability
                  scalability is unlimited
                  high reliability - a vast network of servers ensures against failure
            Cons:
                  No control over features and version
                  No physical access
      Hybrid     
            Pros:
                  Avoid disruptions and outages
                  Adhere to regulation, governance
                  Span both public and private cloud
                  Alleviate CapEx 
                  flexibility
                  control
                  ease
            Cons:
                  Complex infrastructure
      Community - collaborative effort between multiple organiaztions. Multiple organizations are working on joint projects
            Pros:
            Cons:


  Regions & Availigility Zones
  
      Regions:
            Definition:      A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network.          
            How to choose:     Location(minimize the latency), Fetures(limitations according to regions), Price
            Paired Region:     配对区域 two Azure regions within the same geographic area to provide geographically redundant solutions
            
      Availability Zones:
            Within a region and each zone has its own separate power, cooling and networking. Used for protection data from failures.    
            
Virtual Machine:

      VMs is the core of Azure compute 
      A virtual machine is your machine exclusively
      X buy, own or control any hardware
      An IaaS offering, u responsible
      take advantage of Azure tools
      Price goes up as resources go up
      
Scale sets: automaticaaly adjust to the volumn/ capacity.

App Services: An easy way to host and manage your web application

      A PaaS offering on Azure
      Web Apps are used to host web sites and web aaplications
      Web Apps for containers can host your existing container images
      API Apps can host your data backend services

Azure Container Instance - put all the things together?

Azure Kubernetes Service/ K8s - manage lots of containers in Azure (Greek for "governor/ capitain")
      
      replicate container architectures
      Standard Azure Services Included
      ACR - Azure Ccontainer Registry 
      












