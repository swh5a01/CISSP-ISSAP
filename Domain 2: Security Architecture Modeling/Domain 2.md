# Domain 2: Security Architecture Modeling
----------------------------------------

### 2.1 Identify Security Architecture Approach

#### a. Types and Scope

-   **Enterprise Architecture:** Provides a comprehensive view of IT operations and strategies, linking IT mission, strategy, and processes to its IT architecture and tactical solutions.
-   **Network Architecture:** Details the design of an organization's network, including physical components and their functional organization and configuration.
-   **SOA (Service-Oriented Architecture):** Architectural pattern that structures applications as a collection of loosely coupled services.
-   **Cloud Architecture:** Concerns the design of systems and solutions that incorporate cloud resources, either in public, private, or hybrid deployments.
-   **IoT (Internet of Things):** Network of physical objects embedded with sensors, software, and other technologies for the purpose of connecting and exchanging data.
-   **ICS/SCADA:** Architectures related to industrial control systems and supervisory control and data acquisition, crucial for industrial environments.

#### b. Frameworks

-   **SABSA (Sherwood Applied Business Security Architecture):** A framework for developing risk-driven enterprise information security and information assurance architectures.
-   **SOMF (Service-Oriented Modeling Framework):** Provides a structural guide for service identification and design, including those linked to security services.

#### c. Reference Architectures and Blueprints

-   Standardized architectural patterns and solution designs which serve as a reference for creating specific instances.
-   Helps in achieving consistency, rapid deployment, and facilitates compliance with standards and best practices.

#### d. Security Configuration

-   **Baselines:** Minimum levels of security that every system should meet.
-   **Benchmarks:** Detailed set of security settings for specific software or systems.
-   **Profiles:** Subset of settings from a benchmark, defining configurations tailored to specific use cases or environments.

#### e. Network Configuration

-   **Physical Configuration:** Deals with the physical interconnection of nodes in a network.
-   **Logical Configuration:** Logical interconnections and flow of data within the network.
-   **High Availability:** Network design principles and solutions that ensure availability during both planned and unplanned outages.
-   **Segmentation:** Division of network into smaller parts or segments to improve performance and security.
-   **Zones:** Segregated network sections, often based on trust levels or functionality, like DMZs (Demilitarized Zones).

### 2.2 Verify and Validate Design

#### a. Validate Results of Threat Modeling

-   **Threat Vectors:** Pathways or means by which attackers can gain access.
-   **Impact:** The potential consequences of a realized threat.
-   **Probability:** Likelihood of the threat being realized.

#### b. Identify Gaps and Alternative Solutions

-   Through testing and reviews, identify areas of weakness or omissions in the design.
-   Propose alternative design choices or supplemental controls to address gaps.

#### c. Independent Verification and Validation (IV&V)

-   **Tabletop Exercises:** Scenario-driven, discussion-based sessions where team members navigate hypothetical scenarios.
-   **Modeling and Simulation:** Using software models to simulate system behaviors under various conditions.
-   **Manual Review of Functions:** Manual analysis of system functions and configurations to ensure they meet design specifications and security requirements.

* * * * *

### General Notes on Security Architecture Modeling:

-   **Adaptive Design:** Security architecture should be dynamic and adaptable to emerging threats and changes in the operational environment.

-   **Layered Defense:** Incorporating multiple layers of defense in the design ensures that even if one control fails, others can prevent or detect an attack.

-   **Integration with Business Processes:** Security architecture must integrate seamlessly with business processes to ensure that security does not impede business functions and, conversely, business processes do not introduce vulnerabilities.

-   **Continuous Improvement:** Regularly review and update the architecture based on lessons learned, new threats, and evolving business needs. The architecture should not be static; it must evolve.

Ensuring a solid security architecture model involves balancing between the organization's operational needs and security concerns. It requires a forward-looking approach, anticipating future threats, and preparing the architecture to adapt and respond.