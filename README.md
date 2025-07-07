# Coding-resources_Full-stack


### Detailed Weekly Roadmap for Full-Stack Development (6 Months)  

| **Week** | **Focus Area**                          | **Goals and Skills**                                                                                                                                           | **Resources/Tasks/Projects**                                                                                                      |
|----------|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| 1        | **HTML, CSS, and DOM**                  | - Understand HTML structure, forms, and semantics.<br>- Learn CSS basics and responsive design.<br>- Explore the DOM and JavaScript integration.               | - Build a static webpage.<br>- Add interactivity with DOM manipulation.                                                          |
| 2        | **JavaScript Basics**                   | - Master variables, loops, functions, and arrays.<br>- Explore ES6 features like `let`, `const`, and arrow functions.                                           | - Create a to-do list app.<br>- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)                          |
| 3        | **Node.js Basics**                      | - Understand the JavaScript runtime environment.<br>- Write HTTP servers.<br>- Explore Node.js vs other runtimes (e.g., Bun, Cloudflare).                      | - Build a simple Node.js server.<br>- Compare runtimes.                                                                           |
| 4        | **HTTP Servers & Express**              | - Learn HTTP basics, request-response cycle.<br>- Create REST APIs using Node.js and Express.                                                                  | - Build a REST API for a blog platform.                                                                                          |
| 5        | **NoSQL Databases (MongoDB)**           | - Understand NoSQL concepts.<br>- Perform CRUD operations with MongoDB.<br>- Explore schema design and indexing.                                               | - Build a database for a "Bookshelf App" using MongoDB.                                                                           |
| 6        | **SQL Basics**                          | - Learn SQL syntax.<br>- Perform CRUD operations with SQL databases (e.g., MySQL or PostgreSQL).                                                               | - Build a simple database for user data.                                                                                         |
| 7        | **ORMs (Sequelize/Mongoose)**           | - Learn about Object-Relational Mapping.<br>- Use Sequelize for SQL and Mongoose for MongoDB.<br>- Understand model relationships.                              | - Build a project that integrates Sequelize or Mongoose.                                                                         |
| 8        | **React Basics**                        | - Learn React fundamentals: JSX, components, props, and state.<br>- Use React Developer Tools.                                                                 | - Build a task tracker app.                                                                                                      |
| 9        | **Styling React Apps**                  | - Style React apps using Tailwind CSS or styled-components.<br>- Learn responsive design in React.                                                             | - Restyle your task tracker app.<br>- [Tailwind CSS Docs](https://tailwindcss.com/docs)                                          |
| 10       | **TypeScript Basics**                   | - Learn TypeScript syntax and static typing.<br>- Integrate TypeScript with React.<br>- Explore type declarations for APIs and models.                          | - Refactor the task tracker app to TypeScript.                                                                                   |
| 11       | **Next.js Basics**                      | - Learn server-side rendering (SSR) and static site generation (SSG).<br>- Build SEO-friendly apps.                                                            | - Build a blog site using Next.js.                                                                                               |
| 12       | **Monorepos and Turborepo**             | - Understand monorepos and how to organize multiple projects.<br>- Use Turborepo for performance optimization.                                                  | - Create a monorepo for shared libraries in React and Node.js.                                                                   |
| 13       | **Websockets & RTC Basics**             | - Understand real-time communication with Websockets.<br>- Learn RTC for video/audio communication.                                                            | - Build a chat app with Websockets.<br>- Explore RTC for a video conferencing feature.                                            |
| 14       | **Testing Basics**                      | - Learn unit and integration testing.<br>- Use Jest and React Testing Library.<br>- Test APIs and frontend components.                                         | - Write tests for your REST API and React components.                                                                            |
| 15       | **Authentication & JWT**                | - Understand secure user authentication.<br>- Use JWT and cookies for session management.                                                                      | - Add login/logout functionality to your blog platform.                                                                          |
| 16       | **Database Optimization**               | - Explore database optimization techniques (e.g., indexing, query optimization).                                                                               | - Optimize queries for existing projects.                                                                                       |
| 17       | **Advanced Backend Concepts**           | - Dive deeper into asynchronous programming and error handling.<br>- Learn middleware chaining.<br>- Implement complex backend logic.                          | - Refactor APIs with advanced features like rate limiting and complex queries.                                                   |
| 18       | **Ref, Populate, and API Design**       | - Use `ref` and `populate` in Mongoose for relationships.<br>- Learn API versioning and documentation (Swagger).                                               | - Add relationships to your MongoDB models.                                                                                      |
| 19       | **Advanced Frontend Features**          | - Learn dynamic form handling, animations, and accessibility features in React.<br>- Explore Framer Motion for animations.                                      | - Add form validation and animations to the task tracker.                                                                        |
| 20       | **Project Planning**                    | - Plan a capstone project.<br>- Define features, create high-level (HLD) and low-level designs (LLD).                                                          | - Create a project blueprint (e.g., e-commerce app or task tracker).                                                             |
| 21       | **Capstone Backend Development**        | - Build the backend for your capstone project.<br>- Implement CRUD APIs, authentication, and error handling.                                                   | - Set up Express.js, MongoDB, and authentication for the project.                                                                |
| 22       | **Capstone Frontend Development**       | - Build the frontend for your capstone project.<br>- Use React or Next.js for user interface.<br>- Style the app with Tailwind CSS.                             | - Integrate the backend with the frontend.                                                                                       |
| 23       | **Real-Time Features in Capstone**      | - Add real-time features using Websockets or RTC.<br>- Implement live chat or real-time notifications.                                                         | - Enhance the capstone app with real-time functionality.                                                                         |
| 24       | **Testing and Deployment**              | - Test the app thoroughly.<br>- Deploy the app to a cloud platform (e.g., Vercel, Heroku).                                                                     | - Write unit and integration tests.<br>- Deploy the capstone project.                                                            |
| 25       | **Linting and Performance Optimization** | - Set up linting tools (e.g., ESLint, Prettier).<br>- Optimize frontend and backend performance.<br>- Learn about caching strategies.                           | - Add ESLint and Prettier to your projects.<br>- Optimize API response times and frontend load times.                            |
| 26       | **Final Enhancements & Portfolio**      | - Polish the capstone project.<br>- Add the project to a portfolio site.<br>- Prepare for interviews with projects and a resume.                               | - Create a personal portfolio using Next.js.<br>- Showcase all 10 projects in your portfolio.                                    |

---

Here’s a list of **10 project ideas** aligned with the roadmap, along with a guide to building them in a tabular format:

| **Project Name**                | **Description**                                                                                                  | **Steps to Build**                                                                                                       | **Tech Stack**                   |
|---------------------------------|------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| **Task Tracker App**            | A React app to track daily tasks with add, edit, and delete functionality.                                       | 1. Set up React. <br>2. Build a task list UI. <br>3. Add state management with React hooks. <br>4. Store tasks locally.  | React, CSS                      |
| **Bookshelf App**               | A MongoDB-powered app to manage a collection of books with search and CRUD operations.                          | 1. Set up MongoDB.<br>2. Create Express APIs for CRUD operations.<br>3. Connect backend to a React frontend.            | Node.js, Express, MongoDB, React|
| **Blog Platform**               | A platform for users to post, edit, and delete blog entries. Includes JWT-based authentication.                 | 1. Build REST APIs with Express. <br>2. Use MongoDB or PostgreSQL for storing blogs. <br>3. Add authentication.         | Node.js, MongoDB/PostgreSQL, React|
| **Chat App**                    | Real-time chat app using Websockets with user authentication.                                                   | 1. Set up Websockets on the backend. <br>2. Implement chat UI in React.<br>3. Add JWT authentication.                   | Node.js, Websockets, React      |
| **E-Commerce Store**            | A store with product listings, a cart system, and checkout functionality.                                       | 1. Design product APIs. <br>2. Add cart logic in React.<br>3. Integrate Razorpay/Stripe for payments.                   | React, Node.js, MongoDB, Payment APIs |
| **Portfolio Website**           | A personal portfolio to showcase projects and skills.                                                           | 1. Use Next.js for SSR.<br>2. Style with Tailwind CSS.<br>3. Add portfolio content dynamically using JSON.              | Next.js, Tailwind CSS           |
| **Expense Tracker**             | A tool to track income and expenses with visualizations.                                                        | 1. Create React components for transactions.<br>2. Store data in MongoDB.<br>3. Visualize data using Chart.js.          | React, MongoDB, Chart.js        |
| **Online Classroom Platform**   | A platform for faculty to share documents, conduct live sessions, and create assignments.                      | 1. Build backend with Express.<br>2. Implement user roles.<br>3. Add WebRTC for live classes.                           | Node.js, WebRTC, React          |
| **Video Conferencing App**      | A basic conferencing app using WebRTC for real-time communication.                                              | 1. Set up WebRTC APIs.<br>2. Build React frontend.<br>3. Manage connections using signaling servers.                    | WebRTC, React                   |
| **Capstone E-Commerce App**     | A fully-featured app with real-time notifications, authentication, and performance optimization.                | 1. Plan HLD and LLD.<br>2. Develop backend APIs.<br>3. Add Websocket-based notifications.<br>4. Deploy on the cloud.    | Node.js, React, MongoDB, Websockets |

### Details on Building the Projects:

1. **Progressive Complexity**: Projects grow in difficulty from simple React apps (e.g., Task Tracker) to advanced, multi-featured applications (e.g., Capstone E-Commerce App).
2. **Full Stack Integration**: Emphasizes both frontend and backend skills, including databases, APIs, and real-time communication.
3. **Deployment**: Includes a deployment step (e.g., using Vercel, Heroku, or AWS) to simulate production environments.

Let me know if you need detailed guides for specific projects!



---------------
---------------
---------------



## 📚 Useful Resource Links

* 🔗 [Off-Campus Internship Calendar 2025](https://aicteinternship.in/off-campus-internship-calendar-2025/)
* 🔗 [All Hacks – Reskilll Events](https://reskilll.com/allhacks)
* 🔗 [YouTube – Content Creation Tips](https://youtu.be/RHi26oDdKQI?si=HDvXGBkcJSITNq7s)
* 🔗 [📄 Placement Resources (Google Sheet)](https://docs.google.com/spreadsheets/d/1WM1qg_gjJRms5d4mcZslO7dEgMqxlbnu0UIYw-7WgAA/edit?gid=0#gid=0)
* 🔗 [📘 Ebooks Collection (Google Sheet)](https://docs.google.com/spreadsheets/d/1mNvWvTQaA_GXLAiHICi70BYRXBPX-yTpTdfZNyJGgcM/htmlview?fbclid=PAQ0xDSwLLd4xleHRuA2FlbQIxMAABp8YcseXFPCW9nxElHKPo9E_jZQRlStrvsAt0Oc1vE8I6_SxC0B4uQLfm8UyS_aem_dcyIZ7MblR0C4Fp89zkYtg)

---

## 💼 Indian IT Companies – Mass & Mid-Level Recruiters

| Company             | Min CGPA | Job Roles               | Approx CTC       | Important Topics                          |
| ------------------- | -------- | ----------------------- | ---------------- | ----------------------------------------- |
| TCS                 | 6.0+     | Ninja, Digital          | ₹3.36 – ₹7 LPA   | Aptitude, Programming, DSA, Email Writing |
| Infosys             | 6.5+     | SE, SP, DSE             | ₹3.6 – ₹9 LPA    | Aptitude, DSA, Pseudocode, DBMS           |
| Wipro               | 6.0+     | Project Engineer, Turbo | ₹3.5 – ₹6.5 LPA  | Aptitude, Coding, OOPs, OS                |
| HCLTech             | 6.0+     | GET                     | ₹3.5 – ₹4 LPA    | Reasoning, Java/C, OS, DBMS               |
| Cognizant           | 6.5+     | GenC, GenC Elevate      | ₹4 – ₹6.75 LPA   | DSA, SQL, OS, CN                          |
| Capgemini           | 6.0+     | Analyst, Sr Analyst     | ₹3.8 – ₹7.5 LPA  | Pseudocode, Game Aptitude, OOPs           |
| Tech Mahindra       | 6.0+     | ASE                     | ₹3.25 – ₹5 LPA   | Aptitude, Basic Programming, SDLC         |
| Accenture           | 6.5+     | ASE                     | ₹4.5 – ₹6.5 LPA  | Aptitude, Cloud Basics, Comm Skills       |
| LTIMindtree         | 6.0+     | Software Engineer       | ₹3.5 – ₹6 LPA    | Java/Python, OS, DBMS, Projects           |
| IBM India           | 6.0+     | ASE                     | ₹4.25 – ₹6.5 LPA | Java, Cloud, SQL, DSA                     |
| Persistent Systems  | 6.0+     | Software Developer      | ₹4.5 – ₹7.5 LPA  | DSA, Java, OS, DBMS                       |
| Mindtree            | 6.0+     | Software Engineer       | ₹3.5 – ₹5 LPA    | Java, OOPs, OS                            |
| Deloitte India      | 6.5+     | Analyst                 | ₹6.5 – ₹8.5 LPA  | SQL, Aptitude, Case Studies               |
| Hexaware            | 6.0+     | Graduate Trainee        | ₹3.5 – ₹4 LPA    | Reasoning, Coding, Java Basics            |
| Zensar              | 6.0+     | Trainee Engineer        | ₹3.5 – ₹4 LPA    | Aptitude, Java, SQL                       |
| Mphasis             | 6.0+     | Trainee Associate       | ₹3.25 – ₹4.5 LPA | Aptitude, C/C++, DBMS                     |
| Birlasoft           | 6.0+     | Trainee Engineer        | ₹3.6 LPA         | Logical Reasoning, Java Basics            |
| L\&T Tech Services  | 6.0+     | Engineer                | ₹3.6 – ₹5 LPA    | Embedded C, Aptitude, Electronics         |
| NTT Data            | 6.0+     | Associate Engineer      | ₹3.5 – ₹4.5 LPA  | Aptitude, SQL, Programming                |
| KPIT Technologies   | 6.0+     | Engineer                | ₹4 – ₹5.5 LPA    | C/C++, Automotive Basics                  |
| Virtusa             | 6.0+     | Engineer Trainee        | ₹3.5 – ₹5 LPA    | Coding, Java, SQL                         |
| Sonata Software     | 6.0+     | Software Trainee        | ₹3.6 LPA         | Aptitude, OOPs                            |
| Cyient              | 6.0+     | Graduate Engineer       | ₹3.2 – ₹4.2 LPA  | Aptitude, CAD, Engineering Basics         |
| UST Global          | 6.0+     | Software Trainee        | ₹3.6 – ₹5 LPA    | Aptitude, Programming Basics              |
| Torry Harris        | 6.0+     | Software Engineer       | ₹3.5 – ₹4.5 LPA  | Java, Spring, DBMS                        |
| NIIT Technologies   | 6.0+     | Associate Software Engg | ₹3.5 – ₹4.5 LPA  | DSA, DBMS                                 |
| Sasken Technologies | 6.0+     | Engineer                | ₹3.5 – ₹5 LPA    | Embedded C, Aptitude                      |
| ZenQ                | 6.0+     | QA Engineer             | ₹3 – ₹4 LPA      | Testing, Manual QA, SQL                   |
| Sutherland          | 6.0+     | Engineer Associate      | ₹3.25 – ₹4.5 LPA | Communication, Tech Support               |
| Yash Technologies   | 6.0+     | Software Trainee        | ₹3.5 – ₹4.5 LPA  | SAP Basics, Java                          |
| eClerx              | 6.0+     | Analyst                 | ₹3.5 – ₹4.5 LPA  | Excel, Data Analytics                     |
| Incedo              | 6.0+     | Software Engineer       | ₹3.5 – ₹5 LPA    | Aptitude, DSA, Java                       |
| Happiest Minds      | 6.0+     | Trainee Engineer        | ₹3.6 – ₹5 LPA    | Python, Java, SQL                         |
| Syntel              | 6.0+     | Trainee Engineer        | ₹3.5 LPA         | Aptitude, Basic C++                       |
| GlobalLogic         | 6.0+     | Software Trainee        | ₹3.6 – ₹5 LPA    | C++, Aptitude                             |

---

## 🚀 High-Paying Product-Based Companies

| Company         | Min CGPA | Job Role           | Approx CTC    | Important Topics               |
| --------------- | -------- | ------------------ | ------------- | ------------------------------ |
| Zycus           | 6.5+     | Software Engineer  | ₹5 – ₹8 LPA   | DSA, Java, SQL                 |
| Icertis         | 6.5+     | Engineer           | ₹6 – ₹8 LPA   | Contract Lifecycle Mgmt, DSA   |
| PubMatic        | 6.5+     | Software Engineer  | ₹6 – ₹9 LPA   | Data Structures, Web Tech      |
| MAQ Software    | 6.0+     | Software Engineer  | ₹5 – ₹7 LPA   | SQL Server, Azure              |
| Nagarro         | 6.0+     | Trainee Technology | ₹4 – ₹6 LPA   | Java, C#, DSA                  |
| Google India    | 7.0+     | Software Engineer  | ₹30 – ₹40 LPA | DSA, System Design, OS, CN, ML |
| Microsoft India | 7.0+     | Software Engineer  | ₹30 – ₹45 LPA | DSA, OOPs, OS, DBMS, Projects  |
| Amazon India    | 7.0+     | SDE-1              | ₹25 – ₹30 LPA | DSA, Problem Solving, CN       |


, DBMS                 |
\| Adobe India         | 7.0+     | Software Engineer       | ₹25 – ₹30 LPA        | Algorithms, DBMS, Aptitude                     |
\| VMware              | 7.0+     | MTS                     | ₹20 – ₹25 LPA        | System Programming, OS, Virtualization         |
\| Atlassian           | 7.0+     | Software Engineer       | ₹25 – ₹28 LPA        | DSA, Backend Dev, Cloud                        |
\| Uber                | 7.0+     | Software Engineer       | ₹35 – ₹40 LPA        | DSA, ML, System Design                         |
\| Arcesium            | 7.0+     | Software Engineer       | ₹25 – ₹30 LPA        | Data Structures, Finance + Programming         |
\| Salesforce          | 7.0+     | Software Engineer       | ₹24 – ₹28 LPA        | OOPs, Apex, Cloud Tech                         |
\| LinkedIn            | 7.0+     | Software Engineer       | ₹35 – ₹40 LPA        | Web Dev, DSA, Product Thinking                 |
\| Sprinklr            | 7.0+     | Product Engineer        | ₹20 – ₹22 LPA        | DSA, Backend, DevOps                           |
\| Flipkart            | 7.0+     | SDE-1                   | ₹20 – ₹26 LPA        | DSA, Projects, System Design                   |
\| CRED                | 7.0+     | Software Developer      | ₹23 – ₹30 LPA        | Web Dev, Product Development, DSA              |
\| Media.net           | 7.0+     | Software Engineer       | ₹10 – ₹12 LPA        | DSA, OS, CN                                    |
\| DE Shaw             | 7.0+     | Software Engineer       | ₹25 – ₹28 LPA        | Math, Algorithms, DBMS                         |
\| Goldman Sachs       | 7.0+     | Engineer Analyst        | ₹10 – ₹15 LPA        | Aptitude, Programming, DBMS                    |
\| Rubrik              | 7.0+     | Software Engineer       | ₹30 – ₹35 LPA        | Distributed Systems, DSA                       |
\| Nutanix             | 7.0+     | Software Developer      | ₹28 – ₹32 LPA        | Systems Programming, DSA, OS                   |
\| Tower Research      | 7.0+     | Software Developer      | ₹35 – ₹40 LPA        | Maths, C++, Algorithms                         |
\| Zeta (Directi)      | 7.0+     | Software Engineer       | ₹25 – ₹30 LPA        | Web Backend, OS, Networking                    |

---

Let me know if you’d like a downloadable **PDF**, **Notion page**, or **Excel format** of this content!
