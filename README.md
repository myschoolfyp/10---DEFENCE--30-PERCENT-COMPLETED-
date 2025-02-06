

🏫 MySchoolFYP – School Management System
📌 Overview
MySchoolFYP is a full-stack school management system built with Next.js and TypeScript, featuring authentication, user management, student and teacher profiles, and CRUD operations.

The system includes:
✅ Authentication (Login & Registration)
✅ User Profile Management (Edit & Update Profile)
✅ Student & Teacher Management
✅ Admin Dashboard
✅ Database Integration with Models
✅ Secure API Endpoints

myschoolfyp/
│── src/
│   ├── app/
│   │   ├── api/
│   │   │   ├── admin/           # Admin-related API routes
│   │   │   ├── editprofile/     # API for updating user profiles
│   │   │   ├── login/           # User login API
│   │   │   ├── register/        # User registration API
│   │   │   ├── profile/         # Fetch user profile API
│   │   │   ├── students/        # CRUD operations for students
│   │   │   ├── teachers/        # CRUD operations for teachers
│   │   ├── dashboard/
│   │   │   ├── profile/         # Profile dashboard UI
│   │   ├── editprofile/         # UI for editing user profile
│   │   ├── login/               # Login page UI
│   │   ├── register/            # Registration page UI
│   ├── lib/                     # Utility functions (Auth, Validation)
│   ├── models/                  # Database models (User, Student, Teacher)
│   ├── styles/                   # Global styles (CSS/Tailwind)
│── public/                       # Static assets (favicons, images)
│── next.config.mjs               # Next.js configuration
│── tailwind.config.ts            # TailwindCSS configuration
│── tsconfig.json                  # TypeScript configuration
│── package.json                   # Project dependencies
│── README.md                      # This README file

🔑 Authentication
Login (/login)
Secure user authentication system.
API: POST /api/login – Validates credentials and returns a token.
Registration (/register)
Allows new users to sign up.
API: POST /api/register – Stores user details securely.
User Profile (/dashboard/profile)
Displays user details stored in the database.
API: GET /api/profile – Fetches authenticated user info.
Edit Profile (/editprofile)
Users can edit their name, email, and profile picture.
API: PUT /api/editprofile – Updates profile data.
🎓 Student & Teacher Management
Students (/students)
Add, update, delete, and view student records.
API:
POST /api/students – Add a new student.
GET /api/students – Fetch all students.
PUT /api/students/:id – Update student info.
DELETE /api/students/:id – Remove a student.
Teachers (/teachers)
Manage teacher profiles and schedules.
API:
POST /api/teachers – Add a new teacher.
GET /api/teachers – Fetch all teachers.
PUT /api/teachers/:id – Update teacher info.
DELETE /api/teachers/:id – Remove a teacher.
🛠️ Technologies Used
Technology	Usage
Next.js	Frontend & API routes
TypeScript	Type safety & scalability
Tailwind CSS	Styling
PostgreSQL / MySQL	Database
Prisma ORM	Database management
JWT (JSON Web Token)	Authentication
Cloud / Local Storage	Profile picture uploads



