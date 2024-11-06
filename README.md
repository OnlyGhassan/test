### Elaboration on Diagrams with Descriptive Text and Tools Used for Initial Design

---

#### **1. Use Case Diagrams: User and Admin**

- **Description**: 
  - The **User Use Case Diagram** illustrates the primary interactions for a candidate or job applicant within the VR Interview Simulator. Key actions include user registration, CV upload, accessing the interview simulation, receiving real-time feedback, and viewing a performance report.
  - The **Admin Use Case Diagram** highlights the actions available to administrators, such as adding interview questions, reviewing user performance, and generating analytical reports. These roles allow admins to keep the system updated with relevant content and manage assessments effectively.
  
- **Tool Used**: 
  - **Visual Paradigm**: Used for creating both use case diagrams.
  - **Purpose**: Visual Paradigm provided a comprehensive environment for constructing use case diagrams with customizable actors and use case icons, making it easy to map out different user roles and their interactions.
  - **Limitations**: Although Visual Paradigm is powerful for creating standardized diagrams, it has limited flexibility in design customization, which restricted some visual enhancements we wanted to incorporate.

---

#### **2. Class Diagram**

- **Description**: 
  - The **Class Diagram** represents the main structure of the system, outlining key classes like `InterviewSimulator`, `Interview`, `Candidate`, and `Interviewer` with their attributes and methods. This diagram defines the relationships among classes, organizing components such as interview questions, candidate responses, and performance reports, ensuring that all system parts are connected and accessible.
  
- **Tool Used**: 
  - **Visual Paradigm**: Used for designing the class diagram.
  - **Purpose**: Visual Paradigm allowed us to define classes with attributes, methods, and relationships, providing a clear structure for implementing the system's core elements.
  - **Limitations**: Visual Paradigm’s class diagram feature met most of our needs, but it could be limited in handling more complex class relationships in certain layouts, which required manual adjustments to maintain readability.

---

#### **3. Sequence Diagrams: User and Admin**

- **Description**: 
  - **User Sequence Diagram**: This diagram shows the sequence of interactions a candidate follows, from uploading their CV to participating in the VR interview. It highlights real-time interactions with the virtual interviewer and the steps for receiving feedback.
  - **Admin Sequence Diagram**: Illustrates the sequence of actions an admin performs to manage content and review candidate performance. Admin actions include adding questions, generating reports, and monitoring user progress, ensuring that all backend processes run smoothly.
  
- **Tool Used**: 
  - **Visual Paradigm**: Used for developing both sequence diagrams.
  - **Purpose**: Visual Paradigm provided an intuitive interface for managing lifelines, messages, and timing constraints, allowing for clear visual representation of sequential interactions in the system.
  - **Limitations**: The main limitation with Visual Paradigm in sequence diagram creation was the lack of advanced animation features, which would have been helpful for illustrating complex interactions dynamically. 

---

#### **4. Entity-Relationship (ER) Diagram**

- **Description**: 
  - The **ER Diagram** defines the database structure for the VR Interview Simulator, detailing key entities such as `User`, `CV`, `Interview`, `Question`, and `Response`. This diagram maps out the relationships between entities, ensuring that the system can store and manage information related to candidates, interview sessions, and feedback effectively.
  
- **Tool Used**: 
  - **Visual Paradigm**: Used for creating the ER diagram.
  - **Purpose**: Visual Paradigm facilitated the creation of clear relationships between entities, defining primary and foreign keys to model database structure accurately. Its data modeling tools supported the logical design for data storage and retrieval.
  - **Limitations**: While Visual Paradigm was effective for basic ER diagrams, it lacks some advanced database-specific features like real-time SQL preview or direct integration with database management systems, which would have streamlined the design-to-implementation process.

---

#### **5. Unity Prototype Design**

- **Description**: 
  - The **Unity Prototype** provides the preliminary VR interface where candidates interact with virtual interviewers. The prototype includes a basic VR interview room, avatars for interviewers, and voice-to-text functionality for user responses. This setup allowed us to test and refine key interaction requirements, such as user navigation and real-time feedback.
  
- **Tool Used**: 
  - **Unity**: Used for VR prototype development.
  - **Purpose**: Unity’s 3D modeling and VR capabilities enabled us to create an immersive environment for the interview simulator, supporting basic interactions and allowing early testing of the VR user experience.
  - **Limitations**: Developing in Unity was resource-intensive, and creating lifelike avatar animations required additional plug-ins. These limitations meant that initial prototypes had reduced complexity, focusing on core interactions rather than complete environment details.

---

### Summary

These diagrams, created using Visual Paradigm (except for the Unity prototype), serve as the foundation for visualizing and documenting the VR Interview Simulator system. Visual Paradigm allowed us to develop clear and organized diagrams for use cases, classes, sequences, and database entities, despite some limitations in customization and real-time database integration. Unity’s VR-specific tools provided a hands-on approach for the prototype, giving us practical insights into user interaction in a virtual environment. Together, these tools support a structured design process that aligns with the project's functional and technical requirements.
