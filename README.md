RedBus Clone

This project is a full-stack clone of the popular bus ticketing and bus-hire platform redBus.
redBus is an Indian online bus ticketing service that connects travelers with more than 2500 bus operators across India, Southeast Asia, and Latin America.

In this project, we have attempted to replicate the core features of redbus.in, including:

Searching buses

Booking seats

Google login

Stripe payments

Viewing trips

Bus hire functionality

🔗 Live Demo

https://redbus.netlify.app

🚀 Installation Guide
1. Install Prerequisites

Before running the project, make sure the following are installed:

Node.js

VS Code

Git

2. Clone and Install Dependencies

Open the project in VS Code and install dependencies for both frontend and backend.

Backend setup
cd redbus/back-end-redbus
npm install

Frontend setup
cd redbus/front-end-redbus
npm install

3. Run the Project
Start Backend (Terminal 1)
cd back-end-redbus
npm start

Start Frontend (Terminal 2)
cd front-end-redbus
npm start


Once both are running, access the application at:
👉 http://localhost:3000

🛠 Technologies Used
Frontend

React

CSS

Backend

Express

MongoDB

Mongoose

Libraries

Redux

React-Redux

Redux-Thunk

Material-UI

UUID

React-Icons

React-Google-Login

React-Modal

React-Stripe-Checkout

React-DOM

🧭 How to Use the App
1. Start the app

Run npm start in both backend and frontend.

2. Landing Page

New users can log in using Google Sign-In from the navbar dropdown.
Currently implemented routes: Lucknow → Faizabad

3. Bus Listings

Users can filter and sort buses based on their requirements.

4. Seat Selection

You can select available seats (red seats = already booked).

5. Passenger Details + Payment

After selecting the boarding and dropping points, fill out the passenger details.

Continue to Stripe payment:

Card Number: 4242 4242 4242 4242

Expiry: 12/21

CVV: 123

6. View Your Bookings

🚌 Bus Hire Feature
1. Navigate to Bus Hire Page

2. Fill the Trip Details

3. Select a Vehicle

4. Book the Vehicle

5. Complete Payment

Use Stripe test card:

Card Number: 4242 4242 4242 4242

Expiry: 12/21

CVV: 123

📌 End Notes

We have tried to replicate most features of the real redBus platform, including ticket booking, seat selection, payments, user authentication, and bus hire.
Feel free to modify or enhance the project according to your needs.
