# Airport_DBMS
An airport management system combines airplane scheduling, luggage handling, and security screening activities to improve resource allocation and reduce delays. A complete management system can make air travel safer and more efficient.

<!--  Created by Dinusha Salith Perera  -->

# Airport Database Management System #

_Entity Relationship Diagram_

![ER-Diagram](documentation/Airport_Management_System_ER.png)

Built using [Diagram Editor](https://www.diagrameditor.com/).

_Extended Entity Relationship (EER) Diagram_

-   An EER Diagram would consist properties like Specialisation & Generalisation.
    -   Suppose, an employee in this system can be **_specialised_** into entities like:
        -   Administration
        -   Security
        -   Engineers
        -   Traffic Monitor
    -   And, different types of flights, like Airbus, Boeing can be **_generalised_** into one single entity _Flight_.

_Steps to map (E)ER into a Relational Schema_

![Mapping-Algorithm](documentation/ER-to-relations-mapping-algortihm.jpg)

_Relational Schema_

-   Mapping the above ER Diagram to a Relational Schema

![relational-schema](documentation/Relational_Schema.png)

Built using [draw.io](draw.io).
