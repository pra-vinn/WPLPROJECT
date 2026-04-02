# WPLPROJECT
SkillShare - Micro-Learning Platform
SkillShare is a lightweight, localized video and image tutorial platform designed for quick, practical learning. This platform focuses on short, digestible content that users can upload directly from their devices.

Features
Local File Uploads: Users can upload tutorial videos or images directly from their PC.

Dual-Role System: Includes an Admin Panel for managing content and a User Dashboard for exploring and uploading tutorials.

Interactive Learning: Dedicated tutorial pages featuring a media player, descriptions, and a local comment system.

Search and Filter: Quickly find tutorials by title or category (Coding, Fitness, Cooking).

Persistent Storage: Uses localStorage to save user profiles, uploaded tutorials, and comments without needing a complex backend.

Tech Stack
Frontend: HTML5, CSS3 (Inter Font Family)

Logic: Vanilla JavaScript (ES6+)

Storage: Browser LocalStorage and Base64 encoding for media

Project Structure
index.html: Landing page with hero video.

auth.html: Login and Registration with validation.

explore.html: Main gallery for tutorial discovery.

upload.html: PC file upload and preview system.

profile.html: User-specific content and profile view.

tutorial.html: Media player and comment section.

admin.html: Admin dashboard for user and content management.

assets/: Project images and videos.

Setup and Usage
Clone the repository:
git clone https://github.com/your-username/skillshare.git

Open index.html in any modern web browser.

To Login as Admin: Select "Admin" from the dropdown on the auth.html page.

To Upload: Go to the "Upload" tab, select a file (Image/Video) from your PC, and fill in the details.

Important Notes
Storage Limit: This project uses localStorage, which is limited to approximately 5MB depending on your browser. Please upload small, compressed files for the best experience.

Browser Compatibility: Best viewed in Chrome, Edge, or Firefox.
