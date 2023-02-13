# Azure-900
Certificate Note

Vocabularies: 

      IaaS - Infrastructure as a Service
      PaaS - Platform as a Service    ( Superset of IaaS; has something more than IaaS)
      SaaS - Software as a Service    (have a Apps, pay for it: Microsoft 365)
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
      


Resources: compute, networking, storage

Language of Cloud Computing: 
      
      High Availability | Reliability | Scalability | 
      Security | Predictability | Governance | Manageability 

      High Availability - core = always available; X own, add more servers with a click, replace when it fails, use cluster.
      Reliability - fault tolerance, disaster recovery; deploy in multiple locations, no single point of failure
      Scalability - Automatically adjust resources to meet demand. (increase/decrease number of VMs)
                    Horizontal(sacaling out; typical) vs. Vertical Scaling(scaling up)
      Predictability - performance and costs
      Security - full control of the sloud security posture
      Governance - cloud deployments to meet requirement standards
      Manageability - management of cloud resources and how to interact with them.
      
Language of Cloud Economics:
      
      CapEx:
      OpEx: pay-as-you-go
      
      Pricing Models:
      Hourly Pricing - VMs, APP Services
      Consumption - pay for the resources used
      
Azure Architecture/ Cloud Service Models:

      IaaS provides access to resources such as virtual machines and virtual storage
            infrastructure = actual servers
            scaling is fast; X own hardware
            [VMs + Networks + Physical Buildings + storage]
      PaaS provides execution environments, application development, and deployment tools
            supports web application life cycle
            avoid license hell
            [IaaS + Middleware + Tools] middleware, i.e. database management tools
      SaaS provides software as a service to end-users
            Providing a managed service
            pay an access fee to use
            no maintenance and latest features
            [PaaS + Apps] e.g Office 365
      Serverless 
            Azure is an instance of this
            Extreme PaaS
            [PaaS - extreme]
      
Cloud Architecture Models: 

      Private
            Pros:
                  benefits of public cloud
                  security           
            Cons:
                  Maintenance
                  Staffing
      Public -- Azure, AWS, GCP
            Pros:
                  No purchase of hardware
                  Low monthly fees (monthly usage)
            Cons:
                  No control over features and version
                  No physical access
      Hybrid     
            Pros:
                  Avoid disruptions and outages
                  Adhere to regulation, governance
                  Span both public and private cloud
                  Alleviate CapEx 
            Cons:
                  Complex infrastructure

  Regions & Availigility Zones
  
      Regions:
            Definition:       A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network.          
            How to choose:    Location(minimize the latency), Fetures(limitations according to regions), Price
      Availability Zones:
            Paired Region:    
            
