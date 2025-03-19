Tech Stack
1. Next.js – Framework for React
2. MongoDB – Database for storing prompts
3. NextAuth – Secure Google authentication
4. TailwindCSS – Styling


Features
✔️ Discover, share, and manage AI prompts
✔️ User authentication via Google (NextAuth)
✔️ Search by tags and copy prompts easily
✔️ Fully responsive modern UI


How To Run It:
git clone https://github.com/Zidane-Virani/ai-query.git
cd ai-query
npm install


Environment Variables
Create a .env file in the project root:

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_secret
GOOGLE_ID=your_google_id
GOOGLE_CLIENT_SECRET=your_google_secret
MONGODB_URI=your_mongodb_uri


Run the Project
npm run dev


Visit http://localhost:3000 in your browser.
