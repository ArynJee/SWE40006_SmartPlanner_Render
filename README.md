# SWE40006_SmartPlanner

![Backend CI](https://github.com/maeve34/SWE40006_SmartPlanner/actions/workflows/backend-ci.yml/badge.svg)
![Frontend CI](https://github.com/maeve34/SWE40006_SmartPlanner/actions/workflows/frontend-ci.yml/badge.svg)

To run frontend of the app (Vue):
1. cd smartplanner-src
2. npm install
3. cp .env.example .env
4. npm run build
5. npm run dev

To run backend of the app (Node.js + Express.js):
1. cd backend
2. npm install
3. cp .env.example .env
4. node server.js

To build the Docker images using Docker compose:
<br />
*note that this is only for dev*
<br />
*for staging: Render internally orchestrates and automatically manages containers*
1. from repo root run: docker compose -f docker-compose.dev.yml up --build
2. to stop and remove containers: docker compose -f docker-compose.dev.yml down




