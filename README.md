# Welcome

Welcome to my Computer Science ePortfolio. This portfolio highlights projects and enhancements completed as part of my CS-499 Computer Science Capstone at Southern New Hampshire University.

<details class="portfolio-section" open>
  <summary>Professional Self-Assessment</summary>
  <div class="portfolio-section-content" markdown="1">

Throughout my time at Southern New Hampshire University, pursuing my Bachelor of Science in Computer Science has been an opportunity to develop technical skills, strengthen my problem-solving abilities, and prepare for a new direction in my professional career. My school experiences are unconventional. I began by earning my GED while working for Walmart, where I have spent nearly 15 years gaining experience in retail operations, leadership, and customer service. It's been a lot of hard work, planning, and self-discipline to keep learning and continue working in both my professional and academic roles. I've come to the realization that I've learned a lot more than just programming languages and technical concepts as I get ready to graduate. Through my coursework, I have acquired a more analytical mindset in solving problems, an increased appreciation of secure and sustainable software, and the confidence to seek out opportunities in the computer science sector. 

My working experience has also shaped my software development and teamwork approach. As a department manager at Walmart, I learned leadership and communication skills with associates, management and customers. These experiences helped me to learn how important it is to be sensitive towards others, to set a clear understanding of expectations, and to make a decision based on organizational goals, and to the people affected by these goals. I believe these skills are directly transferable to software engineering, where developers must collaborate with team members, understand stakeholder requirements, and develop solutions that provide practical value. While studying computer science, I have developed a greater awareness of the impact of technical decisions on users, organizations and other developers. My goal is to combine this professional experience with my technical education as I transition into a technology-focused role, ideally continuing my career within Walmart’s technology organization. 

The best thing about my education was learning to convey technical information effectively. Writing functional code is only part of software development; it also entails explaining design decisions, documenting the functionality, and presenting information to different audiences. In all of my coursework I have created technical documentation, project reports, diagrams, and presentations which involved describing the operation of a system as well as the justification of selected approaches. These skills were further reinforced in my CS-499 capstone project, which involved a recorded code review, written enhancement narratives, and the creation of this ePortfolio. These materials illustrate how I communicate technical information to various mediums, such as writing, speaking, and visuals, as well as how I organize information for instructors, fellow developers, and potential employers. 

My coursework has also improved my knowledge of software engineering principles, data structures and algorithms. I have found that in order to make a successful application, I must also consider if the software works correctly, as well as how the software works efficiently, reliably and maintainably. I have worked on projects with Java, Python, C++, and Android development, during which I learned about object-oriented programming, application development architecture, debugging, and automated testing. In CS-320 Software Testing, Automation, and Quality Assurance, I got introduced to structured software testing practices with JUnit software, and CS-360 Mobile Architecture and Programming gave experience in creating an Android-based software application that interacts with the local database. These experiences led me to understand that the importance of choosing good data structures, partition application responsibility, and consider the compromises of implementation options. 

Development of databases has also been an integral part of my technical development. In CS-340 Client/Server Development, I worked with Python to interact with MongoDB, and with an interactive dashboard to display information. This book was an introduction to database operations, client/server, authentication, and how performance of applications relates to data stored. The more I learned, the more I realized the importance of database design on scalability, data integrity, and software system reliability. I also learned about SQLite in Android development, trying out different methods of storing and accessing application data. All of these experiences have made me think about the use of databases in a software system, not as a stand-alone entity, but as a whole. 

Security is a very critical aspect of my software assessment criteria. I was pushed to think outside the box about whether an application will deliver the output I want, and whether it will react to unexpected or possibly malicious input when I had to take CS-405 Secure Coding. I learned about how critical it is to find vulnerabilities early on in the course before it becomes a big issue or problem through defensive programming, input validation, integer overflow and underflow, static analysis and software vulnerabilities. This security mentality has been carried over into my capstone enhancements that focused on validation, secure error management, testing, and enhancing credential management. Now I understand that security of user information and reliability of systems is a concern that should be addressed from the beginning of software development and not a concern at the end. 

I have included the three artifacts that have been enhanced in this ePortfolio to show how these technical and professional skills have evolved during my computer science education. The first artefact, the CS-320 Contact Service, is an artefact which is a reflection of my development as a software engineer and software designer. Enhanced a simple Java contact management app to include centralized validation, persistent storage of contacts in CSV files, import/export support, activity logging, command line interface, and more automated testing. WeighPoint, from CS-360, shows some of the knowledge gained about Algorithms and Data Structures, including enhancements for sorting weight history, filtering by date ranges, statistical analysis, moving averages, and trend analysis. The third artifact is a dashboard for the CS-340 Grazioso Salvare, which showcases my database development capabilities in MongoDB aggregation, indexing, retrieval from the server, and enhanced security and validation. In performance-testing, they used indexing to cut down the number of documents to be examined for a query related to rescuing from 10,000 to 17, allowing a measurable example of how database optimization can enhance the application's efficiency. 

While each of these three artifacts is from a different area of computer science, they all focus on making improvements to existing software through careful design, testing, security, and maintainability. Together, they represent my ability to assess an existing application, identify opportunities for improvement, put into practice technical solutions, and communicate the rationale behind my actions. This ePortfolio has been a great way to be able to look back on how far I have come, from learning the basics of programming to utilizing more advanced software engineering practices. I feel this portfolio is both a representation of my current skills and a steppingstone to further learning within my profession. I want to keep learning, get involved in impactful tech projects, and merge my knowledge and experience in computer science education with my operational experience to find solutions that can help organizations and the people that rely on their systems. 

  </div>
</details>

<details class="portfolio-section">
  <summary>Code Review</summary>
  <div class="portfolio-section-content" markdown="1">

As part of my CS-499 Computer Science Capstone, I conducted a code review of three projects developed throughout my computer science program. The purpose of this review was to evaluate the existing functionality, identify opportunities for improvement, and establish a plan for enhancing each application. This process allowed me to examine my previous work from a software engineering perspective and consider how the applications could be improved through stronger design, more efficient algorithms, and better database management.

The code review covers the original implementations of my CS-320 Contact Service, CS-360 WeighPoint application, and CS-340 Grazioso Salvare dashboard. Throughout the presentation, I discuss the functionality of each project, evaluate areas that could benefit from improvement, and explain the enhancements I planned to implement during the capstone. These improvements focus on software engineering and design, algorithms and data structures, and databases, while also considering maintainability, testing, and security.

[Code Review of Artifacts](https://www.youtube.com/watch?v=7S0pSLH24lc)
  </div>
</details>

<details class="portfolio-section">
  <summary>Category 1: Software Engineering and Design</summary>
  <div class="portfolio-section-content" markdown="1">

### CS-320 Contact Service

The CS-320 Contact Service is a Java application originally developed to manage contact information while enforcing specific validation requirements. For my CS-499 capstone, I enhanced the original project into a more complete contact management system with stronger validation, persistent CSV storage, import and export capabilities, activity logging, a command-line interface, and expanded automated testing.

This enhancement demonstrates my growth in software engineering and design by expanding a small service-based application into a more modular and maintainable system. The original functionality was preserved while new components were introduced for persistence, logging, user interaction, and testing.

**Enhancement Highlights**
- Strengthened and centralized contact validation
- Added persistent CSV storage
- Added contact import and export functionality
- Added duplicate protection during imports
- Added application activity logging
- Created a command-line interface
- Expanded JUnit testing and regression coverage
- Preserved compatibility with the original Contact Service

<div class="artifact-links">
  <a href="https://github.com/DKozzy/CS-320" class="artifact-button">View Original Artifact</a>
  <a href="https://github.com/DKozzy/CS-320-Enahnced" class="artifact-button">View Enhanced Artifact</a>
  <a href="software-design-and-engineering-narrative.html" class="artifact-button">Read Enhancement Narrative</a>
</div>

  </div>
</details>


<details class="portfolio-section">
  <summary>Category 2: Algorithms and Data Structures</summary>
  <div class="portfolio-section-content" markdown="1">

### CS-360 WeighPoint

WeighPoint is an Android weight-tracking application originally developed in CS-360 to allow users to record daily weight entries, establish a goal weight, and monitor their progress. For my CS-499 capstone, I enhanced the application with additional algorithms and data-processing features that provide users with more meaningful information about their weight history.

The enhancement introduces structured weight-history data, sorting and date-range filtering, statistical calculations, moving averages, and trend analysis. These features expand the original application beyond basic data storage and demonstrate how algorithms and data structures can be used to transform stored information into useful feedback while preserving the application's existing functionality.

**Enhancement Highlights**
- Added a structured `WeightEntry` model
- Added sorting by newest, oldest, lowest, and highest weight
- Added 7-day, 30-day, 90-day, and all-time filtering
- Added minimum, maximum, average, and overall weight-change calculations
- Added a moving average using recent recorded entries
- Added gaining, losing, and stable trend analysis
- Added an analytics interface for displaying calculated results
- Expanded automated testing and regression coverage
- Preserved compatibility with existing weight-management functionality

<div class="artifact-links">
  <a href="https://github.com/DKozzy/CS-360" class="artifact-button">View Original Artifact</a>
  <a href="https://github.com/DKozzy/CS-360-Enhanced" class="artifact-button">View Enhanced Artifact</a>
  <a href="algorithms-and-data-structures-narrative.html" class="artifact-button">Read Enhancement Narrative</a>
</div>

  </div>
</details>

<details class="portfolio-section">
  <summary>Category 3: Databases</summary>
  <div class="portfolio-section-content" markdown="1">

### CS-340 Grazioso Salvare Dashboard

The CS-340 Grazioso Salvare project is a Python and MongoDB client/server application originally developed to manage and analyze animal shelter data through a reusable CRUD module and interactive Dash dashboard. For my CS-499 capstone, I enhanced the project by expanding the database layer and improving how the application retrieves, validates, analyzes, and displays shelter data.

The enhancement introduces MongoDB aggregation pipelines, compound indexing, server-side pagination and sorting, query performance analysis, data validation and normalization, and improved credential security. These changes improve the efficiency, scalability, integrity, and security of the original database application while preserving its existing CRUD and dashboard functionality.

**Enhancement Highlights**
- Added server-side MongoDB pagination and sorting
- Added aggregation pipelines for breed analysis
- Added compound indexing for rescue-related queries
- Added query execution and performance analysis
- Reduced documents examined from 10,000 to 17 during indexed rescue-query testing
- Added document normalization and validation
- Added validation for create and update operations
- Removed hardcoded database credentials
- Added environment-based password management
- Updated the Dash dashboard to use server-side data retrieval
- Centralized rescue-filter query construction
- Preserved compatibility with the original CRUD functionality

<div class="artifact-links">
  <a href="https://github.com/DKozzy/CS-340" class="artifact-button">View Original Artifact</a>
  <a href="https://github.com/DKozzy/CS-340-Enhanced" class="artifact-button">View Enhanced Artifact</a>
  <a href="databases-narrative.html" class="artifact-button">Read Enhancement Narrative</a>
</div>

  </div>
</details>
