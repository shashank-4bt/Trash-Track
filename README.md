# Trash Tracker

Trash Tracker is a platform aimed at streamlining and enhancing civic engagement between citizens and their government. It empowers users to report civic issues, collaborate, and monitor their resolution process. With features like real-time mapping, issue tracking, and emergency alerts, Trash Tracker revolutionizes public services.

## How to Run

### Frontend
1. Navigate to the frontend directory: `cd frontend/`
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`

### Backend
1. Navigate to the backend directory: `cd Backend/`
2. Set up a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - On Windows: `./venv/Scripts/activate`
   - On macOS/Linux: `source venv/bin/activate`
4. Install Python dependencies: `pip install -r requirements.txt`
5. Navigate to the `hack24` directory: `cd hack24/`
6. Apply database migrations: `python manage.py migrate` (when there are database changes)
7. Run the Django development server: `python manage.py runserver 8001`

#### Creating a Superuser
- To create a superuser for accessing the Django admin interface, run: `python manage.py createsuperuser` and follow the prompts.

## Description

In a world marked by communication gaps between citizens and government, Trash Tracker emerges as the solution to streamline and enhance civic engagement. Frustrated with potholes, garbage collection issues, or other civic concerns? Trash Tracker empowers users to report problems with images and precise locations. Our unique platform allows users to collaborate, upvote, and comment on reported issues, fostering a community-driven approach to problem-solving.

By integrating the Google Maps API, Trash Tracker provides a real-time, visual map of open issues, promoting transparency. Government officials actively engage, updating the status of each problem and ensuring accountability. With a comprehensive issue tracking system, users can monitor the progress of their reported problems—from being open, under review, to resolved—complete with a timeline for enhanced visibility into the resolution process.

In emergencies, Trash Tracker delivers instant alerts directly to users' phones, keeping citizens informed about road blockades, water, or electricity-related issues. Trash Tracker isn't just a platform; it's a game-changer, transforming the dynamics between citizens and their government. Join us in revolutionizing public services, where your voice matters, and Trash Tracker is the conduit for change.

