GradeRocket 🚀
A comprehensive web-based GPA calculator and student productivity platform that helps students track their academic performance, manage tasks, take quizzes, and stay organized—all in one place.
🌐 Live Deployment
Visit the live site: https://yourusername.github.io/graderocket/

Note: Replace yourusername with your actual GitHub username in all links above.
✨ Major Features

📊 Smart GPA Calculator - Calculate your semester GPA using the absolute grading system (4.0 scale) with support for multiple assessment types including assignments, quizzes, sessionals, finals, and projects. Track your performance against class averages with real-time visual feedback and animated progress indicators.
📅 Intelligent Task Scheduler - Never miss a deadline with our comprehensive task management system. Create, organize, and track assignments with priority levels, due dates, status filters (pending, in-progress, completed), and subject categorization—all persisted locally using browser storage.
📝 Interactive Subject Quizzes - Test your knowledge with timed quizzes covering six core subjects: Programming Fundamentals, Calculus, Applied Physics, ICT, Pakistan Studies, and Functional English. Get instant scoring, review correct/incorrect answers, and track your quiz history to measure improvement over time.
🛠 Core Technologies
<img width="685" height="238" alt="image" src="https://github.com/user-attachments/assets/53b485dd-aab2-487a-9128-6e125a9810b2" />
Technology Stack Details:
<img width="684" height="175" alt="image" src="https://github.com/user-attachments/assets/3df2bd89-aec0-498a-b1e2-f4641fa5608a" />
Key JavaScript Features Used:

Arrow Functions
Template Literals
Destructuring
Array Methods (map, filter, reduce)
Async/Await
Modules Pattern
Event Delegation

Key CSS Features Used:

CSS Grid & Flexbox
CSS Variables (Custom Properties)
CSS Animations & Transitions
Media Queries
Pseudo-classes & Pseudo-elements
📋 Table of Contents

About
Features
Installation
Usage Guide
Git Commit History
Learning Outcomes
LocalStorage Implementation
Project Structure
Contributors
License

🎯 About
GradeRocket is a feature-rich web application designed to help university and college students manage their academic performance effectively. Built as an ICT semester project using vanilla HTML, CSS, and JavaScript (no frameworks), it demonstrates modern web development practices while solving real student problems.
Why GradeRocket?
Students juggle multiple courses, assignments, exams, and deadlines. GradeRocket centralizes academic management by providing:

Accurate GPA tracking with absolute grading
Organized task and deadline management
Self-assessment through interactive quizzes
Brain-training through educational games
All data stored locally—no account required!

🎨 Features in Detail
1. 🧮 Smart GPA Calculator
2. 
Capabilities:

✅ Support for 8 default subjects (Programming, Calculus, Physics, etc.)
✅ Add custom subjects with configurable credits
✅ Multiple assessment types per subject
✅ Real-time calculation with animated displays
✅ Class average comparison
✅ Circular progress visualization
✅ Fireworks celebration for high GPA (≥3.0)
✅ Performance tips and suggestions
✅ Persistent data across sessions
Assessment Types:

Assignments
Quizzes
Sessional 1 (Midterm 1)
Sessional 2 (Midterm 2)
Final Exam
Projects (for applicable courses)

2. 📅 Task Scheduler

Features:

✅ Create tasks with title, description, subject
✅ Set priority levels (Low, Medium, High)
✅ Due date and time tracking
✅ Status management (Pending, In Progress, Completed)
✅ Filter by status
✅ Overdue task highlighting
✅ Statistics dashboard
✅ Edit and delete functionality

Task Statistics:

Pending count
In-progress count
Completed count
Overdue count

3. 📝 Interactive QuizzesAvailable Subjects:

Programming Fundamentals (10 questions, 15 mins)
Calculus (10 questions, 20 mins)
Applied Physics (10 questions, 15 mins)
ICT (10 questions, 10 mins)
Pakistan Studies (10 questions, 15 mins)
Functional English (10 questions, 15 mins)

Features:

✅ Countdown timer
✅ Question progress tracker
✅ Multiple-choice format
✅ Instant scoring
✅ Performance feedback
✅ Answer review mode
✅ Score history tracking
✅ Retake option


4. 🎮 Memory Game
Game Features:

🎯 8 pairs of educational emoji cards
🎯 Move counter
🎯 Timer
🎯 Match tracking
🎯 Victory animation
🎯 Reset functionality
5. 🎨 Modern UI/UX

Design Highlights:

🌓 Dark/Light theme toggle
📱 Fully responsive (mobile, tablet, desktop)
✨ Smooth animations and transitions
🎨 Modern color palette
♿ Accessible (ARIA labels, keyboard navigation)
🚀 Vector graphics (SVG)
⚡ Fast loading times

🚀 Installation
Method 1: Direct Download

Download the ZIP file from GitHub
Extract to your desired location
Open index.html in your browser

Method 2: Git Clone

# Clone the repository
git clone https://github.com/yourusername/graderocket.git

# Navigate to project directory
cd graderocket

# Open in browser (or use local server)
open index.html

📊 Git Commit History (Milestones)

Required Minimum: 5 Major Milestones ✅
Milestone 1: Project Initialization 🎬

commit: "Initial project setup with basic structure"
Date: October 26, 2024

Changes:
- Created index.html with navigation structure
- Added styles.css with CSS variables and theme system
- Implemented responsive navigation bar
- Added hero section with animated rocket SVG
- Setup project folder structure

Files Added:

index.html
styles.css
app.js (theme toggle, navigation)
README.md

Milestone 2: GPA Calculator Implementation 📊

Files Added:

calculator.html
calculator.css
calculator.js

Key Functions:

calculateGPA()
addEntry()
updateEntry()
saveToLocalStorage()
loadFromLocalStorage()

Milestone 3: Task Scheduler Development 📅

Files Added:

tasks.html
tasks.css
tasks.js

Key Functions:

addTask()
editTask()
deleteTask()
filterTasks()
updateStats()

🎓 Learning Outcomes
1. HTML5 Mastery

Skills Gained:

✅ Semantic HTML structure
✅ Form handling and validation
✅ Accessibility with ARIA
✅ SVG integration
✅ Meta tags and SEO

5. Problem-Solving Skills
Challenges Solved:

✅ Complex GPA calculation algorithm
✅ Dynamic content rendering
✅ Data persistence without backend
✅ Responsive design across devices
✅ Timer implementation
✅ Animation coordination

💾 LocalStorage Implementation
Why LocalStorage?
Benefits:

✅ No server required (pure client-side)
✅ No user accounts needed
✅ Instant data access
✅ Works offline
✅ Privacy (data never leaves device)
✅ 5-10MB storage capacity

Limitations:

❌ Only stores strings
❌ Synchronous (blocks main thread)
❌ No encryption
❌ Per-domain storage
❌ Can be cleared by user

👥 Contributors
Development Team
<table>
  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/100/6366f1/ffffff?text=AR" width="100px;" alt="Ans Rizwan"/><br />
      <sub><b>Ans Rizwan</b></sub><br />
      <sub>24F-0779</sub><br />
      <sub>Lead Developer</sub>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/100/8b5cf6/ffffff?text=SN" width="100px;" alt="Suleman Naeem"/><br />
      <sub><b>Suleman Naeem</b></sub><br />
      <sub>25F-0747</sub><br />
      <sub>JavaScript Developer</sub>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/100/10b981/ffffff?text=MT" width="100px;" alt="Muhammad Talha"/><br />
      <sub><b>Muhammad Talha</b></sub><br />
      <sub>25F-0592</sub><br />
      <sub>UI/UX Designer</sub>
    </td>
  </tr>
</table>

📝 License

MIT License

Copyright (c) 2024 GradeRocket Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO
