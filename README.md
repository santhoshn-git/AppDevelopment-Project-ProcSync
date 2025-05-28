# AppDevelopment-Project-ProcSync
  # Chapter 1  
  Introduction

The increasing adoption of digital tools in education has transformed the traditional classroom into a more dynamic and accessible environment. However, many existing platforms either lack the simplicity required for real-time communication or the structure needed for managing academic workflows. To address this gap, ProcSync has been developed as a role-based collaborative education app that blends the core features of classroom management systems like Google Classroom with the intuitive communication style of apps like WhatsApp.
ProcSync empowers educators to create and manage virtual classrooms with ease, enabling them to share announcements, upload academic materials, and monitor student performance. Simultaneously, students are provided with a user-friendly interface to join classes, chat with peers and instructors, and submit academic information and assignments. The app emphasizes security, scalability, and role-based navigation, ensuring that teachers and students each access only the features relevant to their roles.
Leveraging the Flutter framework for cross-platform development and Firebase for real-time database, authentication, and storage solutions, ProcSync offers a seamless, responsive, and secure user experience. By centralizing academic communication and resource sharing, the application aims to foster a more connected and productive digital learning ecosystem.
                                                  
 # Chapter 2
 Hardware and Software Requirements 

2.1 Hardware Requirements
Component	Minimum Requirement
Processor	Intel Core i3 or equivalent (64-bit)
RAM	4 GB (8 GB recommended for development)
Storage	500 MB free space for app (10 GB for development)
Display	1280×720 resolution minimum
Internet	Stable internet connection (required for Firebase  services)
6.Mobile            Device	Android 8.0+ or iOS 12.0+ (for testing or deployment)






2.2 Software Requirements
Software	Description
Flutter SDK	Open-source UI toolkit used to develop the cross-platform mobile application.
Dart Programming Language	The primary language used for writing application logic and UI components.
Android Studio / VS Code	IDEs used for coding, UI design, and running the application on emulators or devices.
Firebase Authentication	Enables secure user login via Google Sign-In and manages role-based access.
Firebase Firestore	A NoSQL real-time database used to store user profiles, messages, and classroom data.
Firebase Storage	Cloud storage solution used for uploading and retrieving shared academic documents.
BLoC (Business Logic Component)	State management architecture that separates UI from business logic for better scalability and testability.
Google Chrome / Mobile Emulator	For web-based or emulator testing of the app during development.
Git	Version control system for managing project changes and team collaboration.
Postman (optional)	API testing tool to simulate and debug backend interactions if required.

# Chapter 3
Design Layouts: Screen Shots of Mobile App / Webpage
   ![image](https://github.com/user-attachments/assets/682a7004-db25-49bc-b349-eda5ad90d9c1)
             
Fig3.1: Login page                                         


![image](https://github.com/user-attachments/assets/ec0cc743-c58f-49dd-a6d5-97387d2585dc)

fig3.2: Procter profile creation
                                

![image](https://github.com/user-attachments/assets/2672961a-a175-4937-90bf-59767f44d1b7)
          
Fig3.3: Group section                                          

![image](https://github.com/user-attachments/assets/61255f72-973a-4397-a960-6f43f2e77f34)

fig3.4: Chat page

![image](https://github.com/user-attachments/assets/6b4d6441-95e2-4dc9-bbd8-b58977cd9d5d)

Fig3.5: Procter dashboard                                 

![image](https://github.com/user-attachments/assets/38565b00-5567-4104-86fd-aa640adf08b3)

fig3.6: Uploads page

![image](https://github.com/user-attachments/assets/9d14b2a3-dae7-45bc-b320-47af2cb9cc78)
              
Fig3.7: Peoples page                                

![image](https://github.com/user-attachments/assets/9e8f8a82-7b64-4cbe-a894-191c0d7a0e32)

fig3.8: Student profile page

 ![image](https://github.com/user-attachments/assets/3c6a5203-39e1-40a7-9dba-6c9e0f1fc189)
                
Fig3.9: Group join page                                   

![image](https://github.com/user-attachments/assets/84660742-4efd-4fd2-a59c-2c63894a01cb)

fig3.10: Student dash board

![image](https://github.com/user-attachments/assets/5791bc6d-8905-45ec-b9d5-3edfb5827bc2)

Fig3.11: Document upload page                        

![image](https://github.com/user-attachments/assets/aa28739f-b6a2-4bcd-a1c6-bc1a7d0202d3)

fig3.12: Student info page

![image](https://github.com/user-attachments/assets/fc6f0739-b8b5-4f3a-9529-2ba77568aa59)

fig3.13: Student personal details                     

![image](https://github.com/user-attachments/assets/9db7ae0f-9ec2-4fac-8261-d95c3767036c)

fig3.14: Student family details           

![image](https://github.com/user-attachments/assets/2e7aa733-dc87-4311-8522-433f40092ed6)
 
Fig3.15: Education updation page






# Chapter 4
Database Table Screen shots
![image](https://github.com/user-attachments/assets/e48038ba-c0c7-40dd-88f3-15c25a9a89d7)

Fig 4.1:database table
 
  ![image](https://github.com/user-attachments/assets/0aef26ce-7c97-48af-8c16-522415a849e1)

Fig 4.2: database table

 ![image](https://github.com/user-attachments/assets/be5a3924-3f2b-4b20-aae5-023e41777240)

Fig 4.3: ER Diagram


# Chapter 5
5.1 Conclusion 
ProcSync is a robust, user-centric educational application designed to bridge the gap between academic communication and structured classroom management. By combining features from traditional learning management systems with real-time messaging and document sharing, it creates a unified platform tailored for both teachers and students. Through secure Google Sign-In, real-time Firestore integration, and intuitive role-based navigation, the app ensures a smooth and secure experience for managing classrooms, sharing resources, and engaging in academic discussions.
The successful implementation of Firebase technologies, along with Flutter’s cross-platform capabilities, showcases the potential of modern frameworks in creating scalable and responsive educational solutions. ProcSync not only simplifies administrative tasks for educators but also provides students with a seamless platform to interact, learn, and stay organized.












5.2Future Work
To enhance the capabilities of ProcSync and meet evolving educational needs, several features are planned for future development:
●	Voice Messaging Support
Enable students and teachers to send quick voice notes within chat    conversations.

●	Image and Document Previews
Add thumbnail and preview functionality for shared images, PDFs, and Word documents.

●	Admin Dashboard
Introduce higher-level administrative roles with dashboards to monitor usage, feedback, and overall app performance.

●	Analytics and Insights
Implement analytics tools to track student engagement, submission frequency, and classroom activity trends.

●	Offline Mode
Allow users to access previously loaded data and draft messages or uploads without internet, syncing once reconnected.

●	Multi-language Support
 Localize the app to support regional languages for broader accessibility.

●	AI-Based Feedback Collection
Integrate AI-driven sentiment analysis for student feedback to help educators  better understand classroom climate.
