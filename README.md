# Software-Architecture-Domain-Driven-Design

**Domain-Driven Design** is intended to expand gradually over time. It existed prior to agile and microservices. However, the overall design is excellent and remains relevant today. 

**Domain-Driven Design** has the following characteristics :

1. **Collaborative** : Throughout the project, business executives and developers must collaborate on a daily basis.

2. **Modeling** : Domain-Driven Design is built on the notion of modeling that is the structure of the code models one-to-one to the domain structure. By glancing at the overall code, all collaborators can understand the structure of the code, and when changes are made inside the domain, we will know exactly where to look at the code due to the one-to-one mapping between code and domain.  

3. **Incremental** : Create only enough architecture to solve the immediate challenge. The code then evolves as we learn more about the problem, and more architecture is added later. 

**Domain** influences the **System** and **System** influences the **Domain**. 

**Domain-Driven Design (DDD)** complements agile in a collaborative setting where business folks will contribute more to the design of our code than technical people will. Because when we evaluate the domain, we are also examining the code. The structure of the domain is the structure of the code. So the businessperson's understanding of how the domain works tell us exactly how the code must function.

**Agile** is based on the work loop called the **inspect and adapt loop** as following:

1. Make a small change.
2. Assess (feedback).
3. Inspect and adapt. 
