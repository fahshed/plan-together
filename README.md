# PlanTogether

CIS 658 Semester Project.

Deployed URL: http://34.49.45.45/

### Repositories

- Frontend Application: https://github.com/fahshed/plan-together-app
- Auth Service: https://github.com/fahshed/plan-together-auth-service
- Trip Service: https://github.com/fahshed/plan-together-trip-service
- Transaction Servie: https://github.com/fahshed/plan-together-transaction-service

### TechStack

- Frontend: Next.js (Page Router) + ChakraUI V3, Cypress
- Backend: Express, JWT, Jest
- Datastore: Firebase, Cloud Storage Bucket
- Cloud: Docker, GCP (GKE, Cloud Build, Ingress)

### Testing

- Unit Test: `computeLedger()` method in transaction-service has a test suite with 4 unit tests with `Jest`. To run do `npm install`, and then `npm test`.
- E2E Test: Trip and event flow is tested with `cypress` in the front end. To run:
  - do `npm install`
  - have `.env` file setup
  - start the app with `npm run dev`
  - then do `npx cypress open`.
  - click on the `trip_flow.cy.js` file on cypress browser window.
