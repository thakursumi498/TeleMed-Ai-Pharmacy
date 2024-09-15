TeleMed + AI Pharmacy is a comprehensive virtual healthcare platform designed to connect patients with doctors for real-time consultations and provide AI-driven personalized medication recommendations. It eliminates geographical barriers and ensures precise, timely care from diagnosis to treatment.

![image](https://github.com/user-attachments/assets/ada37cca-05b8-4e1f-8483-7ad732564979)






https://github.com/user-attachments/assets/65523ad6-2bca-4c47-bde3-f920026e354e



Features
![image](https://github.com/user-attachments/assets/bc53de83-a095-47d2-97fd-4ea387918280)

Real-time Video Consultations: Secure, high-quality video calls between patients and healthcare professionals.
AI-driven Pharmacy: Personalized medication recommendations using AI to analyze prescriptions and patient history.
OCR for Document Processing: Automatic extraction of information from medical documents like prescriptions and reports.
Appointment Scheduling: Easy booking and management of upcoming medical consultations.
Electronic Prescriptions: Seamless digital prescription generation and sharing.
Secure Data Storage: HIPAA-compliant storage of medical records and consultation histories.
Mobile-Friendly: Accessible on mobile devices for convenience.
![image](https://github.com/user-attachments/assets/caa81f4e-1132-44fa-82be-8d6ea30bea57)

Installation
Prerequisites
Node.js
MongoDB
Docker
Python 3.x
TensorFlow
OpenCV
![image](https://github.com/user-attachments/assets/368d9cf2-ae10-4e83-ae6f-781eb6df2d60)

Steps
Clone the Repository
bash
Copy code
git clone https://github.com/your-username/telemed-ai-pharmacy.git
cd telemed-ai-pharmacy
Install Backend Dependencies
bash
Copy code
cd server
npm install
Install Frontend Dependencies
bash
Copy code
cd client
npm install
Set Up Environment Variables
Create a .env file in the server directory with the following details:

bash
Copy code
MONGO_URI=your_mongodb_uri
REDIS_URL=your_redis_url
JWT_SECRET=your_jwt_secret
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
Start the Application
bash
Copy code
docker-compose up
This will start the backend server, frontend client, and required services like MongoDB and Redis.

Run the AI Services
Navigate to the AI service directory and set up the environment:

bash
Copy code
cd ai-service
pip install -r requirements.txt
python app.py
Usage
Sign up/Login: Patients and doctors can create accounts and securely log in.
Schedule Appointment: Users can book appointments and choose from a list of available doctors.
Join Video Consultation: At the scheduled time, users can join the video consultation and receive real-time medical advice.
OCR Document Processing: Upload prescriptions or medical reports to auto-extract details.
AI-Driven Recommendations: After the consultation, receive personalized medication suggestions through AI analysis.
Technologies Used
Node.js, Express.js, Socket.io, PeerJS
Python, TensorFlow, OpenCV, Tesseract OCR
MongoDB, Redis
React.js, WebRTC
Docker, Kubernetes, NGINX
AWS (EC2, S3, RDS)
RESTful API, Microservices architecture
JWT authentication, Bootstrap, HTML5, CSS3


License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or issues, please reach out at thakursumit498@gmail.com or create an issue in the repository.

TeleMed + AI Pharmacy: Revolutionizing healthcare by combining virtual consultations with AI-powered personalized medication.
