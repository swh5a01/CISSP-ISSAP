Domain 4: Identity and Access Management (IAM) Architecture
-----------------------------------------------------------

### 4.1 Design Identity Management and Lifecycle

#### a. Establish and Verify Identity

-   Process of validating the credentials of a user, system, or application, ensuring they are genuine and based on reliable sources (like governmental identification).

#### b. Assign Identifiers

-   Assign unique identities to users, services, processes, and devices to manage and track their activities.

#### c. Identity Provisioning and De-provisioning

-   Provisioning: Process of granting access based on roles and permissions.
-   De-provisioning: Revoking access rights, often when an individual leaves an organization or changes roles.

#### d. Define Trust Relationships

-   **Federated:** System where organizations trust identities created by external entities.
-   **Standalone:** System where identity trust is managed internally.

#### e. Define Authentication Methods

-   **MFA (Multi-Factor Authentication):** Requires multiple methods to confirm user identity, typically something they know (password), have (token), and are (biometric).
-   **Risk-based:** Authentication level changes based on risk assessment (e.g., accessing from unfamiliar location).
-   **Location-based:** Authentication based on user's geographic location.
-   **Knowledge-based:** Use of shared knowledge (e.g., mother's maiden name).
-   **Object-based:** Something a user possesses (e.g., a smart card).
-   **Characteristics-based:** Biometrics, such as fingerprints or facial recognition.

#### f. Authentication Protocols and Technologies

-   **SAML (Security Assertion Markup Language):** Allows identity providers to pass authorization credentials to service providers.
-   **RADIUS (Remote Authentication Dial-In User Service):** Provides centralized authentication, authorization, and accounting management.
-   **Kerberos:** A network authentication protocol using tickets to allow nodes to prove their identity securely.

### 4.2 Design Access Control Management and Lifecycle

#### a. Access Control Concepts and Principles

-   **Discretionary/Mandatory:** Access controls either set by owners (discretionary) or enforced by policies (mandatory).
-   **Segregation/Separation of Duties (SoD):** Dividing responsibilities to ensure no one person can perform malicious activities without detection.
-   **Least Privilege:** Ensuring users have the minimum level of access necessary to perform their jobs.

#### b. Access Control Configurations

-   **Physical:** Physical barriers (e.g., doors, gates).
-   **Logical:** Digital restrictions (e.g., password protection).
-   **Administrative:** Policies and procedures governing access.

#### c. Authorization Process and Workflow

-   Governance of how permissions are assigned, including the issuance of permissions, periodic reviews to ensure appropriateness, and revocation when necessary.

### 4.3 Design Identity and Access Solutions

#### a. Access Control Protocols and Technologies

-   **XACML (eXtensible Access Control Markup Language):** A language for access control policies.
-   **LDAP (Lightweight Directory Access Protocol):** Used to access and manage directory information.

#### b. Credential Management Technologies

-   Managing and securing user credentials. Includes password management systems, digital certificates, and physical tokens like smart cards.

#### c. Centralized IAM Architecture

-   **Cloud-based:** IAM solutions hosted on cloud platforms.
-   **On-premise:** IAM solutions hosted on local infrastructure.
-   **Hybrid:** Mix of both cloud-based and on-premise solutions.

* * * * *

### General Notes on IAM Architecture:

-   **Holistic Approach:** IAM isn't just about technology. It combines technology, processes, and policies.

-   **Continuous Monitoring:** Regularly review and update IAM roles and permissions, ensuring they align with user job functions and organizational needs.

-   **Integrate with Other Systems:** Ensure IAM systems are well-integrated with other organizational systems for seamless and secure operations.

-   **Educate Users:** Ensure users understand their responsibilities related to access control, such as not sharing passwords and reporting suspicious activities.

IAM is at the core of ensuring that the right individuals access the right resources at the right times and for the right reasons. Proper IAM architecture is fundamental to both cybersecurity and regulatory compliance.