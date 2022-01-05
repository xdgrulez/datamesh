October 21, 2021

## Working titles

* How to Implement the Data Mesh
* An Implementation of the Data Mesh
* What Happens When You Implement a Data Mesh
* Implementing the Data Mesh
* Data Mesh in Practice
* Data Mesh Practice
* Align Your Digital Organization to Your Business Organization
* Business Digital Organization
* Digital Business Organization
* Organizing Digital Business with the Data Mesh
* Data Mesh to Organize Digital Business
* Beyond Data Mesh
* Data Mesh and Beyond

## TOCs

1. The Digital Organization
2. Data Mesh
3. Business Implementation of the Data Mesh
4. Technological Implementation of the Data Mesh

(or two distinct books - business implementation and technological implementation?)


1. Motivation - The Great Divide  
  1.1 Business Organization: Decentralized  
  1.2 Digital Organization: Centralized  
  1.3 Business Organization vs. Digital Organization - clash contradiction  
  1.4 Consequences
  
2 What is Data Mesh?

3 Data Mesh: Business Implementation

4 Data Mesh: Technological Implementation  
  4.1 What are Microservices  
  4.2 What is Kafka  
  4.3 Microservices in the Data Mesh  
  4.4 Kafka in the Data Mesh  

## Keywords

* Kafka
* Microservices
* Data Mesh (1. Domain Ownership, 2. Data as a Product, 3. Self-Serve Data Infrastructure, 4. Federated Computational Governance; 1. + 2. = Organization, 3. + 4. Technological)
* Divide/Mismatch: Digital Organization vs. Business Organization
* Digital Disorganization
* Decoupling
* Decentralization
* Bounded Context
* Domain-Driven Design -> Business Objects/Domains

## Example Business Organizations

* Business Units (Produktbereiche):
  * AC (Accessories)
  * HG (Home & Garden)
  * BI (Blue Industrial)
  * BE (Blue Emerging)
  * Lawn & Garden
  * MT (Measuring Tools)
  * RT (Rotary Tools)
  * B.V. (?)

* Supporting Functions:
  * ADM
  * Business Development
  * BDO
  * COM
  * Compliance
  * Data Protection
  * Engineering
  * Financial Controlling
  * HR
  * QM
  * Legal
  * Logistics
  * Manufacturing
  * Marketing
  * Purchasing
  * Sales Operations

## Miscellaneous ideas

```
centralized -> de-centralized
     +              + re-connected
connected   -> disconnected
```

* Organization/Software Architecture -> What should rather be centralized and what can be decentralized

* choreography/orchestration

* What does digital/agile transformation mean?
* Key: The only way to unlock/enable agility is modularization = decentralization
* The aim must be to make your organization as decentralized as possible

* Yes, decentralized, but there also needs to be a way to re-connect the organization/share information


* decentralization/decoupling in microservices:
  * decentralization possible:
    * deployment
    * development
    * databases
    * testing
    * security
  * centralization needed
    * monitoring
    * testing
    * security

  * DM node = Data Product Layer/Quantum = Landing Zone (Piethein Strenghold)
    * must include some uniform kind of data storage + API e.g. S3, Kafka
    * plus uniform data catalog/metadata/documentation + API
  * DM node = Landing Zone (LZ) + Data Catalog (DC)
  * One landing zone per set of sub-business domains
  * Central DW becomes the combined/accumulated DC (fed by node DCs)
    * no need to ship all the data to a central place, only the metadata!
  * analytics team split up + moved partly to nodes of the DM/existing business domains, or create new cross-domain business domains

### Conway's Law (1967)

"Any organization that designs a system (broadly defined) will produce a design whose structure is a copy of the organization's communication structure."

(1968 National Symposium on Modular Programming)

### Yourdon/Constantine 1979: Structured Design

"The structure of any system designed by an organization is isomorphic to the structure of the organization."

### Coplien/Harrison 2004: Organizational Patterns of Agile Software Development

"If the parts of an organization (e.g. team departments, or subdivisions) do not closely reflect the essential parts of the product, or if the relationships between organizations do not reflect the relationships between product parts, then the project will be trouble. Therefore: Make sure the organization is compatible with the product architecture."

* Data Mesh theory -> Zhamak's book
* practice         -> Data Mesh in Practice (with microservices and Kafka?)
* Is the Data Mesh a product, platform or a process?
* How does Data mesh gel in with the enterprise stack?- What kind of evolutionary org structures / topologies work?

* Distributed systems metaphor
  * Mesh topology
  * Data Agility
  * Organic Digitalization 
  * IT into the business

* https://www.linkedin.com/in/kiransreewastav/

## Olli Lauren

* https://www.industryweek.com/leadership/article/21145316/is-decentralizing-right-for-your-company

* "operating system" of decentralized companies

* creeping tendency to want to centralize -> save money in the short term, maintain profitability

* centralized companies -> mediocre people can survive for a very long time

* a culture of discontent (in a good way):
  * key aspect: less internal politics, largely because business leaders can make decisions with a high degree of autonomy
  * high level of trust within the organization (-> take risks, make mistakes)
  * high level of transparency among business units

* dc: culture that is more fact-based rather than view-based, tests validity of details, forcing intellectual honesty
