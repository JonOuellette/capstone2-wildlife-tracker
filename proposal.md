# Wildlife Tracker Project Proposal

## Tech Stack
For the Wildlife Tracker project, I will be utilizing React for the front end, Node.js for the back end, and PostgreSQL for database management. This will allow for a highly interactive and responsive web application that can handle real-time data processing. I intend to use some external API’s to assist with the project - some possibilities are US Fish and Wildlife Service Open Data, Wildlife Insights, Movebank, and/or NatureServe.

## Project Focus
The Wildlife Tracker will be a full-stack application with an even focus on both the front-end UI and the back-end server logic. The front end will be designed to offer users an intuitive and engaging platform to report wildlife sightings and access wildlife conservation information. The back end will focus on data management, API integration, and serving the front-end application with the necessary data in real-time.

## Platform Type
The project will be developed as a web application. With a possible future of it being built into a phone app as well. The choice of the web application, however, ensures broad accessibility for users across different devices and platforms without needing to download additional software.

## Project Goal
The goal of the Wildlife Tracker is to foster community engagement in wildlife conservation efforts by providing a platform where users can report wildlife sightings, access educational content about wildlife conservation, and contribute to a global database of wildlife information. This platform aims to raise awareness about the importance of wildlife conservation and encourage active participation in conservation efforts.

## Target Users
The Wildlife Tracker is aimed at a broad demographic including wildlife enthusiasts, researchers, educators, conservationists, and the general public. Anyone with an interest in wildlife and conservation, regardless of their level of expertise, can benefit and contribute to the platform.

## Data Usage and Collection
We plan to utilize data from existing wildlife and conservation APIs, such as those provided by global wildlife databases and conservation organizations. This will include data on wildlife species, their locations, conservation status, and possibly user-reported sightings. If necessary, we will also consider creating our own API to manage user-generated content and reports. This custom API would be populated with user reports, photographs, and sightings, all of which would be stored in our database after undergoing validation to ensure data quality and consistency.

## Project Approach
- **Database Schema**: The database will include tables for Users, Sightings (including location, time, species, and user comments), Species Information (sourced from APIs or curated content), and Conservation Efforts. Relationships between these tables will be established to efficiently query and manage data.
- **API Challenges**: Integrating external APIs may present challenges such as rate limiting, data format inconsistencies, and downtime. For our custom API, ensuring data integrity and handling large volumes of user submissions will be critical.
- **Security**: Sensitive information such as user data will be secured using best practices, including encryption, secure authentication mechanisms, and regular security audits.
- **Functionality**: The app will include features such as user registration/login, reporting wildlife sightings, viewing sightings on a map, accessing detailed species information, and educational content on conservation efforts.
- **User Flow**: Users will start at the landing page where they can choose to explore sightings, learn about species, or log in to report their own sightings. The navigation will be intuitive, guiding users through reporting processes, educational content, and community insights.
- **Stretch Goals and Features**: Beyond basic CRUD operations, stretch goals include real-time updates of sightings on a global map, community forums for discussion, gamification elements to encourage user engagement (e.g., badges for reporting sightings), and personalized wildlife newsfeeds.
