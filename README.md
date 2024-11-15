# p10node Website

This repository houses the documentation, development roadmap, and resources for the p10node website, designed to support blockchain infrastructure services and streamline client onboarding and partnerships.

> **Note**: This repository is an initial proposal and has not yet received any feedback or endorsement from the p10 team. Additionally, the repository is maintained with advisory input from an external collaborator, [@rolodexter](https://github.com/rolodexter), who is not affiliated with the p10 team. All suggestions and contributions are provided independently and have no bearing or influence on p10node's operations whatsoever.

## Project Overview

The p10node website operates with two core focuses:

1. **[Marketing and Business Development](docs/marketing_business_dev/)**: This area of the site is dedicated to attracting new clients, partners, and stakeholders. It includes resources for the **[Client Intake and Pre-Qualification](docs/marketing_business_dev/client_intake_prequalification.md)** process to collect essential project details from prospective clients, as well as [client onboarding](docs/marketing_business_dev/onboarding.md), [partnership information](docs/marketing_business_dev/partnerships_and_collaborations.md), [pricing models](docs/marketing_business_dev/pricing_models.md), and marketing assets.

2. **[Service Delivery](docs/service_delivery/)**: This section is focused on delivering and supporting blockchain infrastructure services, including **[Node-as-a-Service (NaaS)](docs/service_delivery/naas_services.md)**, **[RPC services](docs/service_delivery/public_rpcs.md)**, **[validator operations](docs/service_delivery/validator.md)**, and other Cosmos ecosystem integrations.

## Collaborative Client Space

The **[Collaborative Space](docs/marketing_business_dev/collaborative_space.md)** is a pivotal element in p10node’s operations, serving as more than a client engagement tool. It is a vital resource for gathering insights into the blockchain economy and powering big data analytics. By enabling real-time collaboration between p10 and prospective clients, this space facilitates:

- **[Business Insights](docs/marketing_business_dev/business_insights.md)**: Provides actionable intelligence into client needs, preferences, and project goals, allowing p10node to refine its service offerings.
- **[Economic Analysis](docs/marketing_business_dev/economic_analysis.md)**: Captures data trends in **[RPC](docs/service_delivery/public_rpcs.md)** and **[NodeFi economics](docs/marketing_business_dev/nodefi_economics.md)**, contributing to a deeper understanding of the global blockchain ecosystem.
- **[Big Data Development](docs/marketing_business_dev/big_data_development.md)**:
  - Aggregates and structures data from multiple clients, creating a robust dataset for analytics.
  - Supports predictive modeling for market trends, enabling p10node to stay ahead of industry shifts.

The collaborative space’s dynamic and flexible design allows for tailored interactions, empowering **[administrators](docs/service_delivery/administrators.md)** to gather critical information while fostering productive partnerships.

## Key Operational Areas and Functions

### Marketing and Business Development

- **[Stake with Us](docs/marketing_business_dev/stake_with_us.md)**: Provides information for potential stakers looking to delegate tokens and earn rewards through p10node’s validators.
- **[Chain Services](docs/service_delivery/)**: Details Cosmos and blockchain services offered, focusing on **[Node-as-a-Service (NaaS)](docs/service_delivery/naas_services.md)**, **[RPC services](docs/service_delivery/public_rpcs.md)**, and **[validation operations](docs/service_delivery/validator.md)**.
- **[Client Intake and Pre-Qualification](docs/marketing_business_dev/client_intake_prequalification.md)**: A structured process for gathering critical project information. This includes a **collaborative space**—a simplified version of tools like Miro or Jira—where p10 and the prospective client can brainstorm and take notes on project terms and requirements. The notes captured in this space will help draft terms of engagement automatically and provide valuable insights into the global RPC/NaaS economy.
- **[Onboarding](docs/marketing_business_dev/onboarding.md)**: Resources for new clients and partners, including tutorials and structured documentation.
- **[CosScan](docs/cosscan.md)**: p10node’s blockchain explorer, designed specifically for Cosmos networks, providing transaction tracking, validator monitoring, and IBC functionality.
- **[Pricing Models](docs/marketing_business_dev/pricing_models.md)**: Overview of pricing plans for validator services, public RPCs, and custom whitelabel validator solutions.

### Service Delivery and Infrastructure

- **[Node Running](docs/service_delivery/node_running.md)**: Continuous operation and monitoring of nodes to ensure uptime and reliability.
- **[Validator](docs/service_delivery/validator.md)**: Customizable validator service that supports transaction validation and network security.
- **[Public RPCs](docs/service_delivery/public_rpcs.md)**: Publicly accessible RPC endpoints for seamless blockchain interaction.
- **[Whitelabel Validator Service](docs/service_delivery/whitelabel_validator.md)**: Branded validator services tailored for enterprise clients.
- **[Data Indexers and APIs](docs/service_delivery/data_indexers_apis.md)**: APIs providing blockchain data access to support analytics and dApp development.
- **[No-Code Node Creation (P10node SDK)](docs/service_delivery/no_code_sdk.md)**: An SDK enabling users to deploy nodes without any coding knowledge, broadening access to node operations and making it easier for non-technical users to participate in infrastructure deployment.
- **Additional Functional Features**:
  - **[Statesync](docs/service_delivery/statesync.md)**: Enables rapid node setup with state synchronization.
  - **[Addbook](docs/service_delivery/addbook.md)** and **[Livepeers](docs/service_delivery/livepeers.md)**: Tools for network connectivity and node discovery.
  - **[Snapshots](docs/service_delivery/snapshots.md)**: Ready-to-use blockchain snapshots for efficient node setup.

## Documentation Structure

The `docs` directory is organized to facilitate easy access to resources across different aspects of the website’s operations:

```
├── README.md
├── docs/
│   ├── marketing_business_dev/
│   │   ├── onboarding.md
│   │   ├── partnerships_and_collaborations.md
│   │   ├── pricing_models.md
│   │   ├── client_intake_prequalification.md
│   ├── service_delivery/
│   │   ├── node_running.md
│   │   ├── validator.md
│   │   ├── public_rpcs.md
│   │   ├── whitelabel_validator.md
│   │   ├── data_indexers_apis.md
│   │   ├── no_code_sdk.md
│   │   ├── statesync.md
│   │   ├── addbook.md
│   │   ├── livepeers.md
│   │   ├── snapshots.md
│   ├── cosscan.md
│   └── roadmap.md
```
