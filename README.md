# Professional Self-Assessment  
Over the course of my Computer Science program at SNHU, I have grown not only as a developer but also as a project-focused problem solver. This ePortfolio showcases the technical and professional progress I’ve made by highlighting artifacts that demonstrate my capabilities in software development, algorithm design, data analysis, and system architecture. These projects and the enhancements I’ve completed reflect my readiness to contribute to real-world software projects as either a developer or a project coordinator (roles that align with my concentration in project management).

## My Strenghths and Professional Growth
Throughout the program, I developed core technical skills such as full-stack web development using Angular, Express, and MongoDB; writing clean, testable code; and implementing algorithms and data-driven features that improve software performance and user experience. Just as importantly, I strengthened my ability to manage projects holistically from breaking down problems and planning enhancements to executing and validating code.

Through this ePortfolio, I am able to reflect on my learning and development. My enhancements reflect an evolution in how I think about software from simply “making it work” to making it reliable, efficient, scalable, and understandable. I’ve also grown more confident in testing, debugging, and communicating technical decisions clearly, which are important for both solo work and team collaboration.

### Collaboration and Communication
One of my strengths is the ability to bridge technical detail and high-level goals. In my coursework, I often had to communicate design choices and trade-offs in both technical and non-technical contexts. I learned how to adapt documentation and presentations depending on whether I was addressing teammates, instructors, or simulated stakeholders. My code review video, as well as my written narratives, demonstrate my ability to clearly explain system functionality, propose improvements, and justify enhancement decisions using best practices and sound logic.

Although most of my coursework was completed independently, I also developed collaborative skills through group projects and by learning to follow team-oriented workflows. For example, I adopted version control practices with Git and GitHub that mirror those used in professional environments. These experiences have prepared me to work smoothly in cross-functional teams where communication and clarity are as important as code quality.

## Summary of Artifacts
My artifact enhancements represent my technical depth in each of the following three key computer science categories. 
- **Software Design and Engineering**: I enhanced a full-stack application by building a dynamic Trip Detail View, implementing new frontend-backend communication patterns, and introducing robust unit and integration testing. These enhancements demonstrate my ability to design and maintain scalable, modular systems using Angular, Node.js, and testing frameworks.
- **Algorithms and Data Structures**: I implemented a custom keyword-based search algorithm that ranks trip results by relevance. This required careful use of arrays, maps, and efficient sorting logic, and showcased my understanding of algorithmic trade-offs and data manipulation within the backend.
- **Databases**: I created a Trip Popularity Analysis feature using MongoDB’s aggregation pipeline. This feature captures real user behavior and surfaces it in the UI, combining backend analytics with frontend display. It reflects my ability to work with real-world data and deliver actionable insights.

### How My Artifacts Work Together
Each artifact in this portfolio is based on the same core project, which is a full stack travel site, but represents a different enhancement that maps to a specific course outcome. This intentional reuse allows me to demonstrate layered improvements within a cohesive system. As you move through my portfolio, you’ll see how I built on my original work to make it more modular, searchable, data-driven, and insight-rich. Together, these artifacts represent not just a series of assignments but a holistic demonstration of my skillset in action.

# Code Review
The following video reviews my source code and how my enhancements will work. 
[Code Review](https://youtu.be/Jjmwa9_vUKg)

# Artifact 1: Unit and Integration Test
The code for the first enhancement that shows the Unit and Integration Test has been pushed to the repository as a branch called [Enhancement 1](https://github.com/swathisiva11/cs465-fullstack/tree/enhancement1). 
## Narrative 1:
This artifact is an enhancement of a full-stack web application I worked on using Angular for the frontend and Express with MongoDB for the backend. I added a Trip Detail View feature and built a full set of tests to make sure everything worked correctly. On the frontend, I created a TripDataService to handle creating, reading, updating, and deleting trips. I used testing tools like Karma and Jasmine to test frontend services and components, and I used Jest and Supertest-like methods to test the backend. I also made sure that the frontend was successfully sending and receiving data from the backend using HTTP requests.

I chose to include this artifact in my ePortfolio because it shows my ability to work across the full stack. It highlights important skills such as building and testing features, connecting frontend services to backend APIs, and making sure everything works together smoothly. This project demonstrates that I can write clean, organized code and test it thoroughly. The backend tests checked whether the right endpoints were being used and whether the responses were accurate. On the frontend, I confirmed that the services made correct HTTP calls and that components displayed and updated data as expected.

This artifact helped me achieve the goals I set in Module One for this course. My goal was to improve my skills in both client-side and server-side development, including testing. I feel that I not only met this goal but also made more progress than I expected. I added integration tests and became more confident in debugging issues that happen between the frontend and backend parts of the application. These are valuable skills that are often used in real software development jobs.

The process of enhancing and testing this application taught me a lot. At first, I faced some technical issues like NullInjectorError and missing dependencies in my tests. These challenges pushed me to understand Angular’s dependency injection better. I learned how to use the HttpClientTestingModule to isolate service logic and create useful mock data. I also saw how detailed Angular’s testing tools can be, especially when working with expected URLs and responses. This helped me become more careful and precise in my code.

Overall, this project helped me grow as a developer. I learned how to approach debugging with a clear plan, how to connect the frontend and backend effectively, and how important it is to write tests early in the development process. These skills are useful not only for developers but also for people who manage software projects. I look forward to include this artifact in my ePortfolio because it represents my progress in both building and testing real-world software applications.

# Artifact 2: Search and Ranking
The code for the first enhancement that shows the Unit and Integration Test has been pushed to the repository as a branch called [Enhancement 2](https://github.com/swathisiva11/cs465-fullstack/tree/enhancement2). 
## Narrative 2:
As part of the enhancements to the Travlr application, I worked on adding a keyword-based search feature with a ranking system. This feature lets users type in a keyword and see a list of trips that best match what they’re looking for. I built this feature to improve how easily users can find relevant trips, making the overall experience faster and more helpful.

On the backend, I used Node.js, Express, and MongoDB to create a new GET endpoint: /api/trips/search?q=keyword. I wrote a scoring algorithm that gives each trip a rank based on how well it matches the search term. The trip name gets 2 points for a match, while the resort name and description each get 1 point. Only trips with a score above zero are shown, and they are sorted by how relevant they are to the keyword. The rank is calculated in real-time and not stored in the database, which helps keep the data clean.

On the frontend, I used Angular to add a search input box and button in the TripListingComponent. I connected this to the backend search using the TripDataService. The search results are shown with a label like “X Stars” to indicate how relevant they are. I also made sure that the user interface gives feedback as users search, such as showing messages in the results. To keep the code safe and clean, I made the rank score optional in the Trip interface.

I chose to include this enhancement in my ePortfolio because it shows my skills in both algorithms and data structures. It uses arrays and maps, as well as logic to filter and sort the data in a meaningful way. It also highlights my ability to connect backend logic to frontend components in a full-stack application. This artifact shows that I can solve real-world problems with practical code and design.

This enhancement helped me meet the course outcomes I set out to achieve at the beginning of the project. I applied data structure and algorithm knowledge to improve an existing project and documented and tested the solution. Through the process, I learned more about writing clean and efficient search algorithms and how to make the results meaningful for users. One challenge was balancing performance with clarity in the ranking system, but testing helped me fine-tune it. Overall, this project taught me how to combine backend logic with frontend usability to create a feature that adds real value.

# Artifact 3: Trip Popularity Analysis
The code for the first enhancement that shows the Unit and Integration Test has been pushed to the repository as a branch called [Enhancement 3](https://github.com/swathisiva11/cs465-fullstack/tree/enhancement3). 
## Narrative 3:
To meet the requirement for the database category, I implemented a Trip Popularity Analysis feature that combines data mining techniques with RESTful API design to track and analyze user search behavior. The goal was to simulate a real-world use case where backend analytics can enhance frontend user experience.

Each time a user performs a keyword search for a trip, the search term is automatically logged into a new MongoDB collection called SearchLog. This functionality was integrated into the existing search controller using Mongoose. A new REST API endpoint, /api/trips/topsearches, was developed to query this collection using MongoDB’s aggregation framework. This endpoint returns the top five most frequently searched terms, effectively surfacing popular destinations in real time.

On the frontend, I built a standalone Angular component (TopSearchesComponent) to consume this REST API and display the results under “Trending Destinations.” The component dynamically updates every 10 seconds, allowing users to see search trends without refreshing the page. This demonstrates the use of REST APIs for exposing backend analytics, as well as how databases can support dynamic, user-driven features that improve the overall application experience. 

This enhancement helped me meet multiple course outcomes I had set in Module One, including demonstrating an ability to enhance existing software with new features, applying software development principles in a full-stack environment, and documenting my process clearly.

## 🔧 Projects

### 1. Full Stack Development
**Description**: In this project, I implemented several types of frontend development, including static HTML files, server-rendered pages using Express with Handlebars templates, and a dynamic Single Page Application (SPA) built using Angular.
- [GitHub Repository](https://github.com/swathisiva11/cs465-fullstack) 

