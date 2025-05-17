npm install

npm start

WebAPI folder must be run seperately on a different port


This is a full-stack web application built with React.js for the frontend and ASP.NET Web API for the backend. It demonstrates integration between modern JavaScript frameworks and .NET server-side technologies.

🚀 Getting Started
Prerequisites
Node.js (v14+)

.NET Framework (4.7.2+)

Visual Studio (for WebAPI)

npm / yarn

```
cd React-.Net-Web-App-Main
npm install
npm start
```
Backend Setup (ASP.NET Web API)
Open React-.Net-Web-App-Main/WebAPI/ in Visual Studio.

Build the solution.

Run the Web API (usually available at http://localhost:5000 or similar).

Ensure CORS is configured properly to allow React to call the API.

```
GET /api/home
POST /api/home
PUT /api/home/{id}
DELETE /api/home/{id}
```

✨ Features
CRUD operations

React components for Home and Edit

Integration with ASP.NET backend

Separation of concerns for frontend/backend


