# Professional Data Engineer Certification exam guide

## Designing Data Procesing Systems

1. Selecting the appropriate storage technologies. Considerations include:

    - Mapping storage sytems to business requirements
    - Data modeling
    - Tradeoffs involving latency, throughput, transactions
    - Distributed systems
    - Schema design

2. Designing data pipelines. Considerations include:

    - Data publishing and visualisation (e.g., BigQuery)
    - Batch and streaming data (e.g., Cloud Dataflow, Cloud Dataproc, Apache Beam)
    - Online  (interactive) vs. batch predictions
    - Job automation and orchestration (e.g., Cloud Composer)

3. Designing a data processing solution. Considerations include:

    - Choice of infrastructure
    - System availability and fault tolerance
    - Use of distributed systems
    - Capacity planning
    - Hybrid cloud and edge computing
    - Architecture options (e.g., message brokers, message queues, middleware, service-oriented architecture, serverless functions)
    - At least once, in-order, and exactly once, etc., event processing

4. Migrating data warehousing and data processing. Considerations include:

    - Awareness of current state and how to migrate a design to a future state
    - Migrating from on-premises to cloud (Data Transfer Service, Transfer Appliance, Cloud Networking)
    - Validating a migration

## Building and operationalising data processing systems

1. Building and operationalising storage systems. Considerations include:

    - Effective use of managed services (Cloud Bigtable, Cloud Spanner, Cloud SQL, BigQuery, Cloud Storage, Cloud Datastore, Cloud Memorystore)
    - Storage costs and performance
    - Lifecycle management of data

2. Building and operationalising pipelines. Considerations include:

    - Data cleansing
    - Batch and streaming
    - Transformation
    - Data acquisition and import
    - Integration with new data sources

3. Building and operationalising processing infrastructure. Considerations include:

    - Provisioning resources
    - Monitoring pipelines
    - Adjusting pipelines
    - Testing and quality control

## Operationalising machine learning models

1. Leveraging pre-built ML models as a service. Considerations include:

    - ML APIs (e.g., Vision API, Speech API)
    - Customising ML APIs (e.g., AutoML Vision, Auto ML text)
    - Conversational experiences (e.g., DialogFlow)

2. Deploying an ML pipeline. Considerations include:

    - Ingesting appropriate data
    - Retraining of machine learning models (Cloud Machine Learning Engine, BigQuery ML, Kubeflow, Spark ML)
    - Continuous  evaluation

3. Choosing the appropriate traiinig and serving infrastructure. Considerations include:

    - Distributed vs. single machine
    - Use of edge compute
    - Hardware accelerators (e.g., GPU, TPU)

4. Measuring, monitoring and troubleshooting machine learning models. Considerations include:

    - Machine learning terminology (e.g., features, labels, models, regression, classification, recommendation, supervised and unsupervised learning, evaluation metrics)
    - Impact of dependencies of machine learning models
    - Common sources of error (e.g., assumptions about data)

## Ensuring solution quality

1. Designing for security and compliance. Considerations include:

    - Identity and access management (e.g., Cloud IAM)
    - Data security (encryption, key management)
    - Ensuring privacy (e.g., Data Loss Prevention APOI)
    - Legal compliance (e.g. Health Insurance Portability and Accountability Act (HIPAA), Children's Online Privacy Protection Act (COPPA), FedRAMP, General Data Protection (GDPR))

2. Ensuring scalabiltiy and efficiency. Considerations include:

    - Building and running test suites
    - Pipeline monitoring (e.g., Stackdriver)
    - Assessing, troubleshooting and improving data representations and data processing infrastructure
    - Resizing and qutoscaling resources

3. Ensuring reliabitlity and fidelity. Considerations include:

    - Performing data preparation and quality control (e.g., Cloud Dataprep)
    - Verification and monitoring
    - Planning, executing and stress testing data recovery (fault tolerance, rerunning failed jobs, performing retrospective re-analysis)
    - Choosing between ACID, idempotent, eventually consistent requirements

4. Ensuring flexibility and portability. Considerations include:

    - Mapping to current and future business requirements
    - Designing for data and application portability (e.g., multi-cloud, data residency requiremnets)
    - Data staging, cataloging and discovery
