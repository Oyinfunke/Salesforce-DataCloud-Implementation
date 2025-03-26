# Salesforce-DataCloud-Implementation
## Clicked Admin Sprint- DataCloud Implementation for Delta Airlines.

This implementation is not affiliated with or endorsed by Delta Airlines or any other airline. The data used in this project was randomly generated and is intended for educational and learning purposes only. Any references to Delta Airlines or its logo are purely for illustrative purposes to provide context to the learning scenario. The inclusion of the Delta Airlines logo does not imply sponsorship, partnership, or support from Delta Airlines.

- **Introduction**
    - **Objective**
         To unify Delta Airlines’ siloed customer data into Salesforce Data Cloud, creating a single source of truth for each customer.

    - **Key Features**

        - Data Streaming
        - Data Mapping
        - Profile Unification

- **Business Use case**
    
    - **Problem Statement**

      Delta Airlines faces challenges in staying competitive due to data silos and a lack of actionable insights. The company’s data is scattered across siloed systems making it difficult to gain a unified view of customer profiles. This fragmentation leads to inefficiencies in resolving customer issues, a lack of actionable business insights, and an inability to devise data-driven strategies.
    
    - **User Story**
    
        - **Data Administrator**
        
            As a **Data Administrator**, I need to integrate customer data from multiple sources like Amazon S3, other Salesforce orgs and local files into Salesforce Data Cloud so that I can manage all data from a single platform (Data Cloud)
        
        - **Acceptance Criteria**
        
            - Data streaming from all sources is automated and validated for accuracy.
            - Source data is appropriately mapped to Data Model Objects (DMO)
            - A unified profile of each customer is created
        - **Customer Service Agent**
        
            As a **Customer Service Agent**, I need a 360-degree view of customer profiles so that I can resolve customer inquiries quickly and provide personalized support.
        
            - **Acceptance Criteria**
                
                - Access to a 360-degree view of customer profile
                - Service requests resolution with a 20% reduction in handling time.

- **Solution Design**

    

