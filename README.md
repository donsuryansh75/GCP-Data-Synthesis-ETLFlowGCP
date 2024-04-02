# ETLFlowGCP
 ETLFlowGCP is a data integration and processing project designed for Google Cloud Platform (GCP). It streamlines the Extract, Transform, Load (ETL) process, enabling users to efficiently collect, transform, and store data on GCP.

#Technology Stack:

Google Cloud Platform (GCP): The project is hosted on and fully utilizes GCP's services for data storage, processing, and analytics.

Cloud Storage: GCP Cloud Storage is employed to store both raw and processed data. Data extraction and transformation results are stored here.
![image](https://github.com/Ankit01010/ETLFlowGCP/assets/97511749/60a1d290-0278-40ee-a912-fac0fe15abf4)


Cloud Dataflow: Google Cloud Dataflow, powered by Apache Beam, is used for parallelized data processing. It executes data transformations at scale.
![image](https://github.com/Ankit01010/ETLFlowGCP/assets/97511749/17fd6f84-ec6f-4fde-94e0-511fc1fc2e07)


BigQuery: Google BigQuery serves as the primary data warehousing and analytical platform for storing and querying processed data.
![image](https://github.com/Ankit01010/ETLFlowGCP/assets/97511749/cef98c11-1df8-47e7-b423-82a382d96c42)
![image](https://github.com/Ankit01010/ETLFlowGCP/assets/97511749/1e34b783-6d33-4706-8d8f-c3df5a5a5f49)



Python: Python is the primary programming language for implementing data transformation logic. Google Dataflow and Cloud Storage client libraries in Python are used for this purpose.


----IN FUTURE-----
Automation and CI/CD: Infrastructure as Code (IaC) tools, like Terraform, are used for automation and provisioning of resources. Continuous Integration and Continuous Deployment (CI/CD) pipelines automate testing and deployment of changes to the project.
