# Mern-Social-Media-App
README - MERN Social Media App with Voting and Trending Tags
# Features
User Authentication
- Secure login/signup with hashed passwords
- Profile with bio, profile picture, and uploaded posts
Image Upload with Tags
- Upload images with captions and tags (e.g., #nature, #sunset)
- Supports cloud/local image storage
Voting System
- App shows 2–4 random posts with the same tag for voting
- Votes recorded and updated in real-time (optional timer)
Trending Tags
- Most used tags in the last 24 hours
- Tags with most votes and uploads
- Shown on homepage or sidebar
Feed & Explore
- Feed shows latest uploads or posts by followed users
- Explore page with tag-based search/filter
- (Optional) Top Voted Posts by tag
# Tech Stack
# Folder Structure
root/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
# Setup Instructions
Backend Setup
cd backend
npm install
touch .env
# Add the following to .env
# MONGO_URI=your_mongo_connection_string
# JWT_SECRET=your_secret_key
npm run dev
Frontend Setup
cd frontend
npm install
npm start
# API Endpoints
Auth
Posts
🗳️ Voting
📈 Trending
# Contribution Notes
If this is a team project, please list your contributions:
- Pratyaksh Bhandari – Frontend components, voting UI
- Jay Sharma– Backend APIs, authentication
- Utkarsh Pratap Singh – MongoDB models, trending tag logic
# Future Improvements (Bonus Features)
Comments and likes
Real-time vote updates via WebSockets
Notifications on new voting rounds
Admin moderation panel
Leaderboard for top contributors

# GitHub Link
https://github.com/utkarshprat/Mern-Social-Media-App
# Submitted By-

Name: Utkarsh Pratap Singh
Sap_id: 590018959
Batch: MCA AI/ML B3
