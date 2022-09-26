Admin Dashboard Full Stack Application

How to Run it locally:

Clone this Repository using the --recursive Flag

```
git clone https://github.com/Castrosteven/FullStackAdminDashboardApp  --recursive
```

```bash

npm run start

```

1. Client will run on localhost:3000
2. GQL will run on localhost:5000/graphql

**The Client Side Application**
:

1. Built using Next JS Framework with SSR Rendered Pages.
2. Data fetching using GraphQL Apollo Client
3. Central State using createContext() & useContext()
4. Styled with Tailwind CSS

Other Project Dependencies

React Table
React Icons

**The Server Side Application**

1. This is a Apollo Server GraphQL Api, using the Express MiddleWare.
2. The GQL SDL Schema is generate using Nexus & Typescript
3. Uses PRISMA ORM (Object Relational Mapper) to query a NoSQL MongoDB Database in the cloud.

**SCHEMA DESIGN**


![alt text](https://github.com/Castrosteven/FullStackAdminDashboardApp/blob/main/DOCS/DB.png)

**Auth Flow**


![alt text](https://github.com/Castrosteven/FullStackAdminDashboardApp/blob/main/DOCS/Authentication%20Flow.png)

**Post Flow**


![alt text](https://github.com/Castrosteven/FullStackAdminDashboardApp/blob/main/DOCS/Post%20Operation%20Flow.png)
