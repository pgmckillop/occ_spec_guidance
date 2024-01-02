---
description: Factors to take into account.
---

# Activity A Part 2 - The Business Context

<div align="left">

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

</div>

This section will describe the internal and external factors affecting the business, such as location, human resources, marketing needs, and so forth.

You should describe the potential effect that these factors might have on the planned development processes.

### Consider viability

Discuss the importance of checking that projects are viable from a variety of standpoints. For example, financial viability, making sure that the company is not put a risk. Also, discuss resource viability in terms of people, software, and hardware.

<div align="left">

<figure><img src=".gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

</div>

### Functional Requirements

Using a data-driven web application as an example, the requirements might be:

1. User Management: This includes the ability for users to register, log in, and manage their profiles.
2. Data Entry and Validation: Facilities for users to input data, which is then validated for correctness and completeness.
3. Data Retrieval: The system should be able to retrieve and display data based on various queries or filters.
4. Reporting Features: Generation of reports based on the data stored in the application.
5. Integration with External Systems: The application may need to integrate with other systems or third-party services for additional functionalities.

<div align="left">

<figure><img src=".gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

</div>

<div align="left">

<figure><img src=".gitbook/assets/create_item_small (1).png" alt=""><figcaption></figcaption></figure>

</div>

### Create a priority scoring for the Functional Requirements



<table><thead><tr><th>Number</th><th>Requirement</th><th width="108">Priority</th><th>Rationale</th></tr></thead><tbody><tr><td>1</td><td>User Management</td><td>High</td><td>Setting up the users is fundamental, especially the superuser.</td></tr><tr><td>2</td><td>Data Entry</td><td>High</td><td>This is an essential component.</td></tr><tr><td>3</td><td>Data retrieval</td><td>High</td><td>This is an essential component.</td></tr><tr><td>4</td><td>Reporting</td><td>Medium</td><td>This should be implemented when the CRUD processes are fully tested</td></tr><tr><td>5</td><td>Integration</td><td>Low</td><td>The application is a standalone prototype, so this is not needed yet</td></tr></tbody></table>

### Non-functional Requirements

Using a data-driven web application as an example, the requirements might be:

1. Performance: The application should load quickly and handle a substantial number of concurrent users without performance degradation.
2. Security: Measures to protect sensitive data from unauthorized access and cyber threats.
3. Scalability: The ability of the system to handle increased load without impacting performance.
4. Usability: The application should be user-friendly, with an intuitive interface and easy navigation.
5. Reliability and Availability: High uptime with minimal downtime, ensuring that the application is consistently available to users.

<div align="left">

<figure><img src=".gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

</div>

<div align="left">

<figure><img src=".gitbook/assets/create_item_small (2).png" alt=""><figcaption></figcaption></figure>

</div>

### Create a priority scoring for the non-functional requirements



<table><thead><tr><th>Number</th><th>Requirement</th><th width="106">Priority</th><th>Rationale</th></tr></thead><tbody><tr><td>1</td><td>Perfomance</td><td>Low</td><td>The prototype does not need to meet high volume requirements. Functional performance is considered through testing.</td></tr><tr><td>2</td><td>Security</td><td>High</td><td>The security offered by Django is crucial for acceptance criteria.</td></tr><tr><td>3</td><td>Scalability</td><td>Medium</td><td>The modularisation of the project will support this in production versions.</td></tr><tr><td>4</td><td>Usability</td><td>High</td><td>Client and user acceptamce will depend on this.</td></tr><tr><td>5</td><td>Reliability and availability</td><td>Low</td><td>The prototype version does not need to focus on this.</td></tr></tbody></table>

### Consider the value of Abstraction, decomposition, and modularisation.

Consider the much-favoured ‘Top Down’ approach, where larger problems are decomposed into smaller ones, and why that can aid the development processes. Effective abstraction from a large scenario will make sure that time spent on the program development focuses on the required aspects only.

With modularisation, discuss how single responsibility works. A code component, such as a class, should have one job to do and one set of data to work with.

<div align="left">

<figure><img src=".gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

</div>

### Consider the value of KPIs, milestones, and acceptance criteria

Discuss how projects should be planned effectively to meet the needs of the client and the capacity of the developer. KPIs give precision to the expectations at the various points where progress is formally assessed and measured.

It is essential to formally define what the end-point functional and non-functional expectations are. Many of the auditing aspects will be formalised in a binding contract.\
Acceptance criteria will often be the basis for payment for the completed work.

<div align="left">

<figure><img src=".gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

</div>

