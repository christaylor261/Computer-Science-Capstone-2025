Artifact Description
Artifact: Weight Tracking Mobile Application
Creation: Developed during the CS 360: Mobile Architecture and Programming course.
This mobile application was originally designed to help users monitor and manage their weight changes and related health metrics. Its core functionalities include user authentication, weight tracking, goal setting, and progress visualization.
Justification for Inclusion in ePortfolio
Selection Reason:
I selected the Weight Tracking app because it effectively demonstrates my skills in mobile development and provides a strong foundation for showcasing database integration techniques. This artifact not only highlights my ability to build functional and user-friendly applications but also offers an opportunity to refine its backend data management for improved performance and scalability.
Showcase of Skills:
The enhancements performed for this milestone specifically showcase my abilities in:
•	Database Optimization: By adding an index to the UserWeight entity, I improved query performance, particularly for operations that sort or filter data by date.
•	Advanced Querying with Room: The introduction of a new DAO method to retrieve weight entries between two dates demonstrates my capability to design custom queries that enhance data retrieval functionality.
•	Overall Database Management: The modifications illustrate a commitment to making the application more efficient and scalable while ensuring that data operations are robust and well-structured.
Enhancements Performed
For this milestone, I implemented two minimal but impactful enhancements focused on database optimization:
1.	Indexing the Date Column:
o	I updated the UserWeight entity to include an index on the “date” field. This change accelerates query operations that order or filter weight entries by date, leading to improved performance as the dataset grows.
2.	New DAO Query for Date Range Filtering:
o	I added a method in the WeightDao interface to retrieve weight entries within a specified date range. This enhancement not only demonstrates advanced query design using Room but also provides a foundation for future features such as generating period-based reports or visualizations.
Reflection on the Enhancement Process
Learning Experience:
Enhancing the database aspect of the Weight Tracking app was a valuable exercise in applying real-world database optimization techniques. I learned that even small changes—like adding an index or creating a custom query—can have a significant impact on application performance. This process reinforced my understanding of Room’s capabilities and the importance of efficient data access patterns.
Challenges Encountered:
•	Balancing Performance with Simplicity: The main challenge was to improve performance without overcomplicating the existing design. I focused on minimal changes that would yield measurable benefits without altering the core functionality of the app.
•	Incremental Testing: Ensuring that the new query method and index did not disrupt existing functionality required careful, iterative testing and validation.
Outcome Alignment and Updates
Course Outcomes Achieved:
•	Databases: The enhancements demonstrate my ability to design and implement efficient database solutions using Room, and to optimize data retrieval through indexing and custom queries.
•	Security Mindset: Although not the primary focus, these changes also contribute to a more robust system by ensuring that data operations are reliable and performant.
Updates to Outcome-Coverage Plans:
These minimal enhancements confirm that targeted improvements to database performance can yield significant benefits. In future iterations, I plan to explore additional techniques, such as advanced indexing strategies and potential integration of NoSQL solutions, if performance requirements demand it.
Part Two: Status Checkpoints Update
Checkpoint	Software Design and Engineering	Algorithms and Data Structures	Databases
Name of Artifact Used	Weight Tracker App (UI/UX, MVVM, security enhancements)	Weight Tracker App (sorting/filtering optimization)	Weight Tracker App (Room + DataStore integration)
Status of Initial Enhancement	

Completed UI modularization, refactored for MVVM, and integrated secure coding practices.
Refactored sorting/filtering routines to improve time complexity without altering core functionality.	Migrated from SharedPreferences to Room and implemented basic indexing for faster queries.
Submission Status	Submitted and feedback integrated	Submitted for review; awaiting instructor feedback on algorithm optimizations.	Polishing final queries and conducting performance tests.
Status of Final Enhancement	Investigating advanced security features (e.g., encryption at rest) for further refinement.	Evaluating further optimization strategies (e.g., exploring balanced trees) for even more efficient data handling.	Evaluating options for partial NoSQL integration to boost scalability.
Uploaded to ePortfolio	Yes – artifact includes detailed design choices and security considerations.	In progress – algorithm documentation is nearly complete.	Pending final testing; narrative detailing database improvements is in progress.
Status of Finalized ePortfolio	In progress – refining commentary on UI design, MVVM benefits, and overall security rationale.	Drafting comprehensive documentation on algorithm efficiency and performance trade-offs.	Planning the final narrative that explains the database transition and its benefits.

Conclusion
The minimal enhancements to the algorithms and data structures within the Weight Tracking app have led to noticeable improvements in performance and scalability. By carefully optimizing the sorting and filtering routines and ensuring robust input validation, I have reinforced the app's ability to efficiently manage growing datasets—a key consideration in real-world mobile applications. This focused enhancement not only underscores my technical skills in algorithms and data structures but also aligns directly with my career goals in cybersecurity. Overall, the process has been a valuable exercise in precision optimization and reinforces my commitment to continuous improvement in software engineering.
