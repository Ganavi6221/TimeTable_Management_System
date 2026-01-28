📅 Class Timetable Automation System

A web-based timetable generation system that automatically creates optimized class schedules with zero conflicts between courses, faculty, and rooms.
Built using HTML, Tailwind CSS, and Vanilla JavaScript, with real-time views for Admin, Students, and Faculty.

🚀 Features:

🛠️ Admin Panel

-Add Courses, Faculty, and Rooms
-Define class duration (1–3 hours)
-Automatically generate an optimized timetable

Ensures:

-No faculty overlap
-No room conflicts
-Balanced faculty workload
-Clear all stored data instantly

🎓 Student View

-Select Student ID
-View personalized timetable
-Real-time updates after generation

👩‍🏫 Faculty View

-Select Faculty name
-View assigned classes and time slots
-Easy availability tracking

🎨 UI & UX

-Modern glassmorphism design
-Light/Dark theme toggle
-Smooth animations and hover effects
-Fully responsive layout

🧠 How It Works (Logic Overview)

-Uses a rule-based optimized scheduling algorithm
-Each course is scheduled for 3 sessions per week
-Faculty workload capped at 6 hours/day
-Supports multi-hour continuous sessions

Prevents:

-Faculty double-booking
-Room clashes
-Partial session overlaps
-All data is stored locally using localStorage, so no backend is required.

🧰 Tech Stack

-HTML5
-Tailwind CSS (CDN)
-JavaScript (ES6)
-LocalStorage API

📁 Project Structure
/
├── index.html   (main file)
└── README.md


