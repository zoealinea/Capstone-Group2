# Capstone-Group2

# Real-time Log Processing and Analysis using Apache Kafka, MongoDB, and MySQL

## Team Members: Korey, Nicholas, TJ, James, Zoe

## Project Overview
This project simulates a real-world data processing pipeline that ingests, processes, and analyzes streaming server logs. We aim to capture real-time logs from servers, store them in MongoDB as raw data, transform the data to generate summaries, and store these processed records in MySQL. The project also includes advanced monitoring, alerting, containerized deployment, CI/CD integration, and observability-driven development.

## Project Goals and Objectives

### Primary Objectives
- Capture real-time server logs using Apache Kafka.
- Store unprocessed logs in MongoDB as a NoSQL data store.
- Transform data to generate summaries and insights.
- Store processed summaries in MySQL as a structured, relational database.

### Secondary Objectives
- Automate the deployment of services using Docker and Kubernetes.
- Set up CI/CD pipelines for continuous deployment and integration.
- Monitor service health and performance using Prometheus and Grafana.
- Implement distributed tracing for detailed visibility into request flows.
- Experiment with chaos engineering to assess system resilience.

## Tools and Technologies
- **Apache Kafka**: Streaming platform for real-time data ingestion.
- **MongoDB**: NoSQL database to store unprocessed logs.
- **MySQL**: Relational database for structured data storage.
- **Docker & Kubernetes**: Containerized deployment and orchestration.
- **CI/CD Tools**: Jenkins, GitHub Actions, or GitLab CI for pipeline automation.
- **Monitoring & Observability**: Prometheus, Grafana, Jaeger/OpenTelemetry.
- **Chaos Engineering**: Kubernetes-native tools for simulating failures.
- **Programming Languages and Frameworks**: Python for scripting, SQL for MySQL queries, Pymongo for MongoDB interactions.

## Proposed Architecture
- **Data Ingestion**: Apache Kafka streams server logs.
- **Data Storage**: MongoDB stores raw logs; MySQL stores processed summaries.
- **Data Transformation**: Scripts transform data from MongoDB and store summaries in MySQL.
- **Deployment**: Services run within a Kubernetes cluster, containerized with Docker.
- **Monitoring & Alerting**: Prometheus and Grafana monitor services; alerts notify the team of issues.
- **Distributed Tracing & Chaos Engineering**: Jaeger/OpenTelemetry for tracing; chaos engineering tests for resilience.

## Project Phases and Deliverables

### Phase 1: Project Proposal and Environment Setup
- Complete the project proposal and initial architecture design.
- Configure Docker, Kafka, MongoDB, and Kubernetes environment.

### Phase 2: Data Ingestion and Storage
- Develop scripts to simulate server logs.
- Set up Kafka producers for streaming logs and Kafka consumers for data capture.
- Design MongoDB schema and implement raw log storage.

### Phase 3: Data Transformation and Relational Storage
- Create transformation scripts to extract, process, and generate summaries.
- Store processed data in MySQL with appropriate schema design.

### Phase 4: Monitoring, Alerting, and Tracing
- Integrate Prometheus and Grafana for monitoring.
- Configure alerting mechanisms and distributed tracing with Jaeger.

### Phase 5: CI/CD Integration and Testing
- Develop CI/CD pipelines with automated testing and deployment.
- Perform functional, load, and performance testing.

### Phase 6: Final Testing and Presentation
- Validate the end-to-end pipeline, fix issues, and finalize documentation.
- Prepare a slide deck and demo for presentation.

## Challenges and Mitigation Strategies
- **Data Processing Load**: Use Kafka Streams to handle large volumes of data effectively.
- **Database Scaling and Optimization**: Optimize MongoDB and MySQL for storage and query performance.
- **System Resilience**: Conduct chaos engineering tests to evaluate stability and configure automatic recovery mechanisms.
- **Monitoring Complexity**: Use predefined Prometheus metrics and customizable alerts to catch issues early.

## GitHub Repository
[Capstone Group 2 Repository](https://github.com/zoealinea/Capstone-Group2)

## Linux Environment
Docker Desktop

## Architecture Diagram
*Placeholder for the final architecture diagram to be created by the team.*

