### REST API

* REST: Stands for `Representational State Transfer`. It is a software architectural style focused on stateless and uniform communication of CRUD (Create, Read, Update, and Delete) operations. 

* API: Stands for `Application Programing Interface`. An API powers the backend of an application.

* Resources: 
    - https://restfulapi.net/

    - https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en

    - https://www.geeksforgeeks.org/mvc-design-pattern/

    - https://www.npmjs.com/package/body-parser

* Vocabulary:
    - Middleware: In Express.js (and some other web frameworks), a function that helps process a request to the server. Each middleware receives the request and response object, does some operation, and then passes the request and response to the next middleware function in line.

    - Parse (request body): to take the data stored in the request body and transform it into a format that can easily interact with other code.

    - Frontend Development: Development relating to the client-side user interface of a software application. This interface is commonly in-browser, but can also be through a mobile or voice app, or anywhere a human interacts with a computer.

    - Backend Development: Development relating to the server side of an application. 
    Backend developers create systems containing business logic and persistent storage that communicate with frontend clients via APIs.

    - Full-Stack Development: Denotes development of both the frontend and backend of an application by the same person or team.


### REACT
* REACT: Is an open-source JavaScript library for building user interfaces or UI components.

* TEMPLATE: Templates allow documents to declare what output will look like

* REACT COMPONENT: A Template in React terms is a React Component


* Resources:
    - https://styled-components.com/

    - https://enzymejs.github.io/enzyme/

    - https://www.npmjs.com/package/react-router-dom

    - https://www.npmjs.com/package/concurrently

    - https://reactjs.org/docs/hooks-effect.html


* Vocabulary: 
    - Mono Repo: a repository that contains two distinct but connected application in a single place, allowing them to share resources.

    - useEffect: a React hook which allows you have code that is run in response to changes in state variables.
    
    - Dumb Components: also called presentational components because their only responsibility is to present something to the DOM.

    - Actions: an app design pattern where the code responsible for reaching out to the API is separated into stand alone functions.

    - `<base>`: an HTML element that specifies the base URL to use for all relative URLs in a document.

    - Enzyme: a library that allows you to mount React components for testing purposes.

    - Higher-Order Component: a function that takes a component and returns a new component.

    - Fragment: a React element that allows us to wrap sibling elements such that React treats them as a single element but we are not introducing an unneeded parent into our DOM.

    - children: in React, a prop that is passed to an element which represents any elements that are nested inside of the element to which it is passed.


### MONGO, MYSQL and Databases Relations
* MONGODB: A general purpose, document-based, distributed database built for modern application developers and for the cloud.

* MYSQL: A fully managed database service to deploy cloud-native applications using an open source database.

* SEQUELIZE: A promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server. It features solid transaction support, relations, eager and lazy loading, read replication and more.


* Resources:
    - https://dev.mysql.com/doc/refman/8.0/en/data-types.html

    - https://www.lucidchart.com/pages/

    - https://www.mongodb.com/

    - https://www.freecodecamp.org/news/mongodb-node-express-project/

    - https://blog.kevinchisholm.com/javascript/mongodb/getting-started-with-mongo-shell-scripting-basic-crud-operations/

    - https://www.w3schools.com/nodejs/nodejs_mongodb.asp

    - https://www.w3schools.com/nodejs/nodejs_mysql.asp

    - https://dev.to/mcarpenter/sequelize-model-guide-5efk

    - https://gist.github.com/zcaceres/742744b708393c022703b615d1bffbb1

* Vocabulary:
    - Data Model: an abstract model specifying how entities relate to one another in the real world

    - Entity: a “thing” with a distinct identity that we can represent in data

    - Update Conflict: when repetitive data in is only partially changed, resulting in some instances maintaining the old version of the data while others update to the new version

    - Delete Conflict: when facts that should be persisted are accidentally deleted in the process of intentionally deleting another fact

    - Database Normalization: organizing database entities and relationships to minimize fact duplication and enforce integrity constraints

    - One-to-One Relationship: when a single record in one table is tied to a single record in another table

    - One-to-Many Relationship: when a single record from one table will be associated with many records from the other table

    - Many-to-Many Relationship: when a given record from one table can be associated with many records from a second table, and vice versa. This relationship requires a third table called a linking table

    - Linking Table: a database table that ties two tables together through foreign keys. This table can have other columns that store information about the relationship, but are sometimes are made up of only the two foreign key columns

    - Compound Key: a primary key made up of more than one column

    - Entity Relationship Diagram (ERD): a specific type of diagram that lays out database tables with all their columns and relationships in a visual manner
