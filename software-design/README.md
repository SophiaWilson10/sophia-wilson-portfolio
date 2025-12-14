# Software Design and Engineering Enhancement

## Artifact Overview
The artifact selected for the Software Design and Engineering category is my **Event-Tracking Android application**, originally developed in **CS360: Mobile Architecture and Programming**. The application allows users to create, edit, delete, and organize personal events using a simple interface supported by a Room database.

The original version of the application met course requirements and functioned correctly, but it lacked architectural structure, modern design patterns, and a cohesive user experience. Because this project represented a major milestone in my mobile development learning and had clear opportunities for professional refinement, I selected it as the foundation for my software design enhancement in CS499.

## Justification for Inclusion
This artifact demonstrates my ability to work across multiple layers of a mobile application, including user interface design, data persistence, and architectural organization. The enhancements completed during the capstone project significantly improved the quality, maintainability, and scalability of the application.

The most impactful enhancement was refactoring the project to use the **MVVM (Model–View–ViewModel) architecture with a Repository pattern**. This redesign separates concerns by limiting Activities to UI responsibilities, delegating business logic to the ViewModel, and managing data access through a Repository connected to Room. This structure makes the application easier to test, extend, and maintain, aligning it with industry-standard software engineering practices.

Additional improvements focused on usability and user experience. These included adding a search feature, implementing sorting functionality, applying modern date formatting, and creating a dedicated **Past Events** screen that automatically filters completed events. Together, these updates align the application with real-world expectations for mobile software and highlight my skills in clean architecture, usability, and interactive design.

## Course Outcomes and Skills Demonstrated
The enhancements completed for this artifact closely align with the goals established at the start of the term. Refactoring the application to MVVM directly supports the software design and engineering outcome by improving modularity and maintainability. Implementing search, sorting, and time-based filtering required algorithmic thinking and improved data handling, reinforcing problem-solving and development best practices.

Overall, this enhancement strengthened both the technical foundation and the user-facing experience of the application, resulting in a product that reflects professional-level mobile development standards.

## Reflection on the Enhancement Process
Enhancing this artifact deepened my understanding of long-term application maintainability and architectural decision-making. Converting the project to MVVM required separating tightly coupled responsibilities, which reinforced the importance of clean design for scalability. I also gained experience working with LiveData and ViewModel lifecycle management, improving my ability to build reactive and reliable user interfaces.

From a usability perspective, implementing search and sorting features required careful consideration of user interaction patterns, while creating the Past Events screen pushed me to think critically about how users interpret time-based data. One of the main challenges was ensuring consistent synchronization between the main event list and filtered views after updates or deletions. Debugging these issues strengthened my understanding of state management in a mobile environment.

Overall, this enhancement process significantly increased my confidence in Android development and reinforced core software engineering principles that I will carry forward into future projects.
