# -airbnb-clone-project.

This project is about Airbnb-clone application to test my ability to develop a booking  management system


TEAM ROLES
Business analyst (BA) >>> Understands customer’s business processes, Translates customer business needs into requirements
Product owner (PO) >>> Holds responsibility for a product vision and evolution, Makes sure the final product meets customer requirements
UI/UX designer >>> Transforms a product vision into user-friendly designs,Creates user journeys for the best user experience and highest conversion rates
Software architect >>> Designs a high-level software architecture, Selects appropriate tools and platforms to implement the product vision,Sets up code quality standards and performs code reviews
Software developer >>> Engineers and stabilizes the product, Solves any technical problems emerging during the development lifecycle
Quality assurance (QA) engineer >>> Makes sure an application performs according to requirements,Spots functional and non-functional defects
DevOps engineer >>> Facilitates cooperation between development and operations teams, Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery



TECHNOLOGY STACK

Django: A high-level Python web framework used for building the RESTful API.

Django REST Framework: Provides tools for creating and managing RESTful APIs.

PostgreSQL: A powerful relational database used for data storage.

GraphQL: Allows for flexible and efficient querying of data.

Celery: For handling asynchronous tasks such as sending notifications or processing payments.

Redis: Used for caching and session management.

Docker: Containerization tool for consistent development and deployment environments.

CI/CD Pipelines: Automated pipelines for testing and deploying code changes.


DATABASE DESIGN

Users >a user can have multiple properties.

Properties, Property have reviews rating

Bookings,  booking belongs to a property

Reviews, 
Payments.



FEATURE BREAKDOWN

User Management: Implement a secure system for user registration, authentication, and profile management.

Property Management: Develop features for property listing creation, updates, and retrieval.

Booking System: Create a booking mechanism for users to reserve properties and manage booking details.

Payment Processing: Integrate a payment system to handle transactions and record payment details.

Review System: Allow users to leave reviews and ratings for properties.

Data Optimization: Ensure efficient data retrieval and storage through database optimizations.



API SECURITY

Authentication: Verifying Identity
Authorization: Managing Permissions 
Rate Limiting: Controlling Velocity



CI/CD PIPELINE


GitHub Actions: Built directly into GitHub; uses YAML files to automate workflows on code events like pull requests.GitLab CI/CD: A fully integrated DevOps platform providing built-in pipelines alongside repository management.Jenkins: A highly customisable, open-source automation server backed by a massive plugin ecosystem for complex, self-hosted workflows.CircleCI / Travis CI: Cloud-based CI/CD platforms known for fast setup, speed, and deep integration with various VCS providers.AWS CodePipeline / Azure DevOps: Cloud-native pipeline tools designed to build and deploy seamlessly within specific cloud ecosystems.
