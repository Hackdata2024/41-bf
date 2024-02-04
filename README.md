Team Details:
1)Pooja Bansal (Team Leader)
 Role: Full Stack Developer 
 Contribution: Make Website frontend
2)Mukul Dahiya
 Role: Full Stack Developer 
 Contribution: Make Website Backend
3)Sahil Aggarwal
 Role: ML Developer 
 Contribution: Make AIML Developer 
4)Lakshay Yadav
 Role: Data Scientist
 Contribution: Make Chatbot


:::::::Original Repository::::::
https://github.com/PoojaBansal2003/HackData_Binary_Fusion
https://github.com/PoojaBansal2003/HackData_Binary_Fusion/tree/master


Problem:
Gangrene, a serious condition resulting from tissue death due to reduced blood supply and severe infection, can be particularly concerning when affecting extremities. Recognizable by symptoms such as skin discoloration, intense pain, and swelling, prompt medical attention is crucial. Treatment involves surgery, antibiotics, and measures to improve blood flow, with the possibility of amputation in severe cases. On a different note, ulcers, painful sores triggered by factors like pressure or poor circulation, require early recognition to prevent complications. Symptoms include pain and open sores, with treatment focusing on addressing the cause and promoting healing. If not identified in the early stages, both gangrene and ulcers may necessitate amputation as a last resort, underscoring the importance of timely and comprehensive medical care.

Purpose:
The purpose of our website is to leverage AI and the MERN stack to provide personalized care and innovative solutions for gangrene patients, enhancing their treatment experience and contributing to more effective healthcare management.

SOLUTION: 
Introducing our revolutionary website – a cutting-edge platform designed to empower users in assessing their health with simplicity and innovation. With our state-of-the-art deep learning model, featuring a robust 132-layer architecture for intricate tasks like texture recognition, pattern identification, color analysis, and pixel sizing, we bring you accurate results at your fingertips. Our model, powered by Darknet 53 and Pannet, utilizes the latest YOLOv8 updates for precise evaluations. But that's not all! Our website is not just about visuals – we've incorporated a chatbot with speech recognition, trained on a neural network with 8 hidden layers. This intelligent chatbot engages with users, answering questions related to gangrene. Plus, we go the extra mile by connecting users with Gangrene Doctors nearby for swift consultations. Embrace simplicity, accuracy, and convenience – your health journey starts here!

FUTURE CHALLANGES:
1)Our website addresses gangrene while creating a vast data hub of gangrene images.
2)This data hub benefits Big MNCs, hospitals, and medical institutes for improved treatments.
3)Potential for advancements in diagnostic tools and research within the medical community.
4)Challenges include ensuring data security, privacy, and ethical use of information.
5)Continuous refinement of technologies to stay at the forefront of medical progress is a priority.

TECHNOLOGIES/FRAMEWORKS/TOOLS:
Implemented a robust MERN (MongoDB, Express.js, React, Node.js) stack for seamless integration of frontend and backend, coupling advanced technologies like a 132-layer deep learning model (Darknet 53 backbone, Pannet neck, YOLOv8 model) and a chatbot with speech recognition (trained on an 8-hidden-layer neural network). This cohesive approach enhances user engagement and diagnostic capabilities through a unified, user-friendly platform.

Features:
1)AI-driven Diagnosis
2)Personalized Treatment Plans
3)Remote Monitoring
4)Educational Resources
5)User-Friendly Interface

Impact:
The project aims to significantly impact healthcare by providing early detection and personalized care for gangrene patients through AI. This could lead to improved patient outcomes, reduced amputations, and enhanced overall quality of life for those affected by gangrene.


How to run the project and setup:
 
Prerequisites:

Ensure you have Node.js and npm installed on your machine.
MongoDB should be installed and running.
Steps:

Clone the Repository:

bash
Copy code
git clone [repository_url]
cd HealHub
Install Dependencies:

bash
Copy code
cd client
npm install
cd ../server
npm install
Set Up MongoDB:

Create a .env file in the server directory.
Add the following content to the .env file:
makefile
Copy code
MONGODB_URI=your_mongodb_connection_string
Run the Server:

bash
Copy code
cd ../server
npm start
Run the Client:

bash
Copy code
cd ../client
npm start
Access the Application:

Open your browser and navigate to http://localhost:3000/.

******if you want to run the AI models, at the end of the file, i am sharing the drive link, you can access it from there.*******

Core code:
AI MODEL - 
Image Processing: The images uploaded by users are preprocessed to enhance features and ensure consistency in the input data for the AI model.

Model Prediction: The preprocessed images are fed into the trained AI model. The code handles the interaction with the model, sending requests and receiving predictions.

Result Presentation: The predicted results are then presented to the users, indicating whether the affected area is likely to be gangrene or an ulcer. The code manages the user interface to display these results in a clear and understandable manner.

Database Interaction:
Database Schema: The definition of MongoDB schemas to structure and organize data. This involves creating models for users, images, and predictions.

Data Storage: Code snippets that handle the storage of user information, uploaded images, and corresponding AI predictions in the database.






******IMPORTANT********
https://drive.google.com/drive/folders/1NycmWknYQbY_DzoHQNNnhJkXjJhdP-Em?usp=drive_link 
