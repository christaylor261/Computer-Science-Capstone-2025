Artifact Description
Artifact: Weight Tracking Mobile Application
Creation: Developed during the CS 360: Mobile Architecture and Programming course.
This mobile application was originally created to help users monitor and manage their weight changes and health metrics effectively. It includes functionalities such as user authentication, weight tracking, goal setting, and progress visualization.
Justification for Inclusion in ePortfolio
Selection Reason:
I selected the Weight Tracking app for my ePortfolio because it encapsulates my skills in software design, particularly in mobile development. This application demonstrates my ability to craft user-centric solutions that are both functional and scalable, while also addressing key aspects of security and performance.
Showcase of Skills:
The planned enhancements showcase several core skills:
•	UI/UX Design: Enhancing the user interface to improve usability and visual appeal.
•	Database Management: Upgrading data handling by transitioning from SharedPreferences to a robust Room database.
•	Software Architecture: Implementing the MVVM pattern to separate business logic from UI code, making the app more modular and testable.
•	Data Handling & Validation: Incorporating input validation and safe arithmetic operations to ensure data integrity.
•	Documentation & Code Quality: Centralizing common UI code, using constants, and expanding inline documentation for better maintainability.
Enhancements Performed
To elevate the app’s functionality and maintainability, I executed the following six enhancement steps:
1.	DataStore Integration:
o	Update Gradle Dependencies: Updated dependencies to use Jetpack DataStore instead of SharedPreferences.
o	Finalize DataStoreManager.kt: Created and tested the DataStoreManager class to handle user settings, such as saving and retrieving preferred weight units and goal weight.
o	Authentication Screens: Modified login and account creation screens to use DataStore for persisting user settings.
2.	UI Code Centralization:
o	Refactor for Reusability: Refactored MainActivity.kt to extend from a centralized BaseActivity, consolidating common UI setup tasks.
o	Utility Class Creation: Identified and moved repetitive UI initialization code into BaseActivity or a dedicated utility class to reduce redundancy and simplify maintenance.
3.	Room Database Setup:
o	Add Room Dependencies: Integrated Room into the project by adding its dependencies and updating the Gradle configuration.
o	Create Entities and DAO: Developed a UserWeight entity and corresponding DAO to handle weight entries.
o	Repository Integration: Implemented a repository for managing weight data and connected it with the Weight Entry screen for seamless data operations.
4.	MVVM Implementation:
o	Create MainViewModel: Shifted business logic from composables to a new MainViewModel, which manages data operations using a WeightRepository.
o	State Observation: Updated UI components to observe state changes via LiveData (or StateFlow), ensuring a reactive interface that reflects real-time data updates.
5.	Documentation & Constants Management:
o	Constants.kt: Created a Constants.kt file to centralize frequently used values and configurations, eliminating hard-coded strings and numbers.
o	Enhanced Comments: Updated code comments throughout the project to explain complex functions, architectural decisions, and critical logic, making the codebase easier to understand and maintain.
6.	Numerical Data Handling:
o	Input Validation: Added input validation to the weight entry process, ensuring that users can only enter valid, realistic weight values.
o	Safe Arithmetic Operations: Implemented safe arithmetic methods that handle potential precision loss and errors gracefully, ensuring calculations (e.g., progress toward goal) are reliable.
Reflection on the Enhancement Process
Learning Experience:
The process of enhancing the Weight Tracking app was highly educational. I applied advanced concepts like DataStore integration, Room for robust data management, and the MVVM architecture to decouple business logic from UI code. This project challenged me to think critically about modularity, reusability, and maintaining data integrity.
Challenges Encountered:
•	DataStore Transition: Moving from SharedPreferences to DataStore required careful changes in the authentication and settings management screens.
•	Room Integration: Implementing the Room database without disrupting existing functionalities demanded thorough testing and debugging.
•	MVVM Adoption: Refactoring legacy code to adopt MVVM was a steep learning curve, particularly in decoupling UI from business logic.
•	Validation & Error Handling: Adding robust input validation and safe arithmetic operations required thoughtful error handling to ensure a smooth user experience.
Outcome Alignment and Updates
Course Outcomes Achieved:
•	Software Engineering/Design: Demonstrated by the implementation of MVVM, UI improvements, and overall architectural refinement.
•	Data Structures and Algorithms: Enhanced by optimizing data handling through Room and safe numerical processing.
•	Security Mindset: Strengthened by integrating DataStore for secure data management and by centralizing constants to reduce code errors.
Updates to Outcome-Coverage Plans:
The enhancements have reinforced my ability to design, develop, and secure complex software solutions. This project directly supports my career goals in cybersecurity and mobile app development by emphasizing secure coding practices, efficient data management, and modular architecture.
Conclusion
The enhancements to the Weight Tracking app have significantly improved its functionality, maintainability, and security. Each step—from DataStore integration to MVVM implementation—has deepened my understanding of advanced software engineering principles. This process not only demonstrates my technical acumen but also my commitment to continuous improvement and best practices in mobile app development. The refined application now stands as a comprehensive showcase of my skills, ready to support my career ambitions in cybersecurity and technology innovation.
