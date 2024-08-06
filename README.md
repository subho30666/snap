# snap
 A Simplified full stack social media MERN app
<div align="center">

<a href="https://room-liard-ten.vercel.app">visit live app</a>

  <br />
    <a href="https://room-liard-ten.vercel.app" target="_blank">
      <img src="https://github.com/subho30666/snap/blob/main/client/public/assets/snap-modified.png" alt="Project Banner" width="900" style="border-radius:10%;" >
    </a>
  
  <br />

  <div>
    <img src="https://img.icons8.com/?size=100&id=108784&format=png&color=000000" alt="javascript" />
    <img src="https://img.icons8.com/?size=100&id=bzf0DqjXFHIW&format=png&color=000000" alt="react" />
    <img src="https://img.icons8.com/?size=100&id=hsPbhkOH4FMe&format=png&color=000000" alt="node" />
  </div>

  <h3 align="center">A Social Media App Clone</h3>

  
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Assets & Code](#snippets)
6. 🚀 [More](#more)





## <a name="introduction">🤖 Introduction</a>

Built with the React and Nodejs, this project replicates a social media App. It enables users to securely log in, create posts with images, search for friends and add friends.
## <a name="tech-stack">⚙️ Tech Stack</a>

- React
- JavaScript
- Mui
- ReactRedux
- Mongodb
- Jwt


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/subho30666/snap.git
cd snap
```

**Installation**

Install the project dependencies using npm:

```bash
cd server
npm install
cd client
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the server folder and add the following content:

```env
# MongoDB connection string
MONGO_URL=your_mongo_url

# The port your server will listen on
PORT=3001

# Secret key for JWT signing and verification
JWT_SECRET=your_jwt_secret_key

```

Replace the placeholder values with your actual mongodb URl and jwt secret key of your choice.

**Running the Project**

```bash
cd server
npm start
cd client
npm run dev 
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project .




##