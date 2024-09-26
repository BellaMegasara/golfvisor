# Golfvisor: A Capstone Project

Golfvisor is a dynamic platform for golfers, inspired by Tripadvisor but tailored to the golfing community! It allows users to discover and review golf courses, helping them make informed decisions before hitting the green. Made by an everyday golfer for golfers!

To locally run the application, ensure the following tools are installed:

•	MongoDB (Ensure MongoDB is installed and running locally, or you can use a cloud service like MongoDB Atlas).
•	A Web Browser (preferably Google Chrome).
•	VSCode (preferred code editor).

Setup Instructions:

Follow these steps for a smooth setup:

1.	Clone the repository:

Clone the code from this GitHub repository and store it locally.

git clone https://github.com/yourusername/golfvisor.git

2.	Backend setup:

Inside the backend folder, create a .env file and configure it with the following information:
DB_URI=mongodb://localhost:27017/golfvisor
JWT_KEY="your-jwt-secret"
PORT=8080

3.	Install dependencies:

Install the necessary dependencies for both the backend and frontend:

•	Backend:

In the VSCode terminal, navigate to the backend folder and run:
npm install

•	Frontend:
Navigate to the frontend folder and run:
npm install

4.	Run the application:
•	Backend: In the terminal of the backend folder, run:
npm run dev

•	Frontend: In the terminal of the frontend folder, run:
npm run dev

5.	Access the application:

Open your web browser and go to the following URL: http://localhost:5173/

This guide ensures a smooth setup for Golfvisor, allowing users to experience the platform on their local machines.

