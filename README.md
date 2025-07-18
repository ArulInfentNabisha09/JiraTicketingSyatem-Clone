# JiraTicketingSyatem-Clone

# Jira Ticketing System (Full Stack)

A simple full-stack ticketing app built with:

- Backend: AdonisJS (v6), PostgreSQL
- Frontend: React (Vite, Redux Toolkit, Redux-Saga, Tailwind)
- Auth: JWT
- Features: Roles (admin/advisor), ticket creation, file upload, comment thread, close with resolution.

## How to Run

### Backend

cd backend
cp .env.example .env
# Update DB credentials, then:
npm install
node ace migration:run
npm run dev

->FrontEnd
cd frontend
cp .env.example .env
# Set VITE_API_URL
npm install
npm run dev
