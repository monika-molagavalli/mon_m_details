- 👋 Hi, I’m @monika-molagavalli
- 👀 I’m interested in Data Science and Analytics
- 🌱 I’m currently learning Data Science Algorithms
- 💞️ I’m looking to collaborate on Data Science and Analytics Projects
- 📫 How to reach me on email via patilmonikareddy9@gmail.com

<!---
monika-molagavalli/monika-molagavalli is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

My thoughts on designing ERD:

E.R.D.:
- How to read E.R.D.: https://www.ibm.com/docs/en/informix-servers/12.10?topic=SSGU8G_12.1.0/com.ibm.ddi.doc/ids_ddi_179.html
- Cardinality and Modality: https://medium.com/analytics-vidhya/an-in-depth-look-at-database-relationships-cardinality-modality-a3d6bba0ee1e
- Total participation and partial participation: https://www.ques10.com/p/9460/explain-total-participation-and-partial-participat/
- E.R.D. with persistent entities: https://www.modernanalyst.com/Resources/Articles/tabid/115/ID/2008/Data-Modeling-Entity-Relationship-Diagram-ER-Diagram.aspx


Approach to create an E.R.D.:
- Understand business problem.
- Determine entities and details / fields, with key assumptions, that match requirements in business problem.
- Check if entities determined answer key business question or if entities are linked to match key requirements in business problem, required entity to entity linkages (presence of required keys, attributes / details in a table, to map and further join), by doing the following:
- Write down entities, then have a basic flow of required entities and their respective attributes; have all required data and attributes and relevant column assumptions.
- Match business requirements in a clustered way to designed entities, linking entities to entities with attributes listed from above point (make sure of entity to entity linkages via attributes).
- Retain persistent entities with foreign keys for RDBMS (for other DBMS M-M is okay). Check use cases / performance when implemented with this / other E.R.D. designs in RDBMS.
- Check for required normalization level on data, with below captured key SQL principles and check for the consistency in the ERD based on normalization.
>> Column indices and table indices
>> Entity relationships, cardinality and modality, column indices / table indices
>> Optimization techniques, Normalization techniques, transitive dependency

