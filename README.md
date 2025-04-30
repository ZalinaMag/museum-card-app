# Museum Card App is a capstone study project featuring a React + Redux + TypeScript front end and a Node.js + Express + PostgreSQL back end.

This interactive web application lets users browse museums via list or map view, explore upcoming events, purchase or renew museum memberships (no real charges), check in on-site, submit reviews, and save their favorites.

## Stack
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" /> <img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white" />

## Features
User Features
- Authentication: Secure login/register as a visitor.
- Museum Discovery: Browse museums in a searchable list or on an interactive map.
- Details & Events: View each museum’s description, opening hours, location and upcoming events.
- Mock Card Purchase: Simulate buying or renewing an electronic museum card through a Stripe sandbox (no real charges).
- QR-Code Check-In: Scan a museum’s unique QR code to record your visit.
- Reviews & Ratings: Leave star ratings and written feedback on museums you’ve visited.
- Favorites: Save and easily revisit your preferred museums.

Administrator Features
- Admin Login: Secure access with elevated privileges.
- Museum & Event Management: Add, update or remove museum profiles and schedule news/events.
- QR-Code Generation: Create unique QR codes for newly added museums.
- Analytics Dashboard: View visit statistics, top-visited museums and user engagement metrics.
  
## Script to run locally

Client

1. Navigate to the client folder:
   
  ### `cd client`

2. Start the development server:
   
  ### `npm run dev`

3. Open your browser at [http://localhost:5173](http://localhost:5173) 
  The page will automatically reload whenever you make changes.

Server

1. Navigate to the server folder:

  ### `cd server`

2. Start the server in development mode:

### `npm run dev`

View the Swagger API docs at [http://localhost:3000/api-docs](http://localhost:3000/api-docs)  

The server will restart automatically whenever you update the code.
