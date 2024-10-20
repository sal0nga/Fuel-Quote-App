# Fuel Quote Web Application

## Overview
This is a web application built with Next.js that offers fuel quote services. Originally, the backend was powered by [Supabase](https://supabase.com/), an open-source database and authentication platform.

## Current Status
⚠️ **This application is no longer functional as the original Supabase database is inaccessible.** As a result:
- The app **does not compile or build properly**.
- Features dependent on the database (like user authentication, data retrieval, etc.) are currently broken.

## How to Use the Repository
If you'd like to explore or work on the codebase:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
   cd <repository-name>

## Yarn and NPM Scripts

These scripts were used to interact with the application during development and testing. 
**Note:** Due to the loss of access to the original Supabase database, these commands may not function as expected.

### Development
- `npm run dev`  
- `yarn dev`  

  **Note:** These commands will attempt to start the development server, but the app will crash due to missing Supabase connections.

### Unit Testing with Jest
- `npm run jest`  
- `yarn jest`  

  **Note:** Test rely on data from Supabase, causing them to fail.

### Code Coverage with Jest
- `npm run jest:coverage`  
- `yarn jest:coverage`  

  **Note:** Coverage tests will run, but results may be incomplete if they rely on data from Supabase.

