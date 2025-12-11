MediaBudgeter Frontend

A React Native website for tracking media.

Live Deployment

Deployed via snacks Expo EAS:
https://snack.expo.dev/@angenoise/final-project

Backend API: https:
//backendfinalspeitel.onrender.com/api/

Features
- User Registration
- User Login
- Add Media Items
- Edit Media Items
- Delete Media Items
- Track Budgets

 Test Account

You can create a new account in the app, or use:
- Username: testuser777
- Password: test123456

Tech Stack

- Frontend: React Native with Expo
- Backend: Django REST Framework
- Database: PostgreSQL (production)
- Authentication: Token-based
- Deployment: Snack Expo EAS (frontend), Render.com (backend)

Project Structure

frontend/
├── screens/           # UI screens (Login, Register, Media CRUD)
├── context/          # AuthContext for auth state management
├── navigation/       # App navigation setup
├── assets/           # Images and icons
├── App.js            # Main app component
└── package.json      # Dependencies
```

Important Links

- Frontend GitHub: https://github.com/AndreDizon/FrontEndFinalsPEITEL
- Backend GitHub: https://github.com/AndreDizon/BackEndFinalsPEITEL
- Backend API: https://backendfinalspeitel.onrender.com/api/
- Snack Expo Dashboard: https://snack.expo.dev/@angenoise/final-project

Team
BSIT-3A
- Andre Dizon
- Mark Angelo Dela Cruz
- Caryl Louise Dizon
- Zoe Pascua


API Endpoints
- `POST /api/auth/register/` - Register new user
- `POST /api/auth/login/` - Login user
- `GET /api/media-items/` - Get all user's media items
- `POST /api/media-items/` - Create new media item
- `PUT /api/media-items/{id}/` - Update media item
- `DELETE /api/media-items/{id}/` - Delete media item


Status: Live and Running
