# HomelyHub

HomelyHub is a MERN (MongoDB, Express.js, React.js, Node.js) stack project designed to help users manage and discover properties, connect with agents, and streamline the home renting or buying process.

## Tech Stack

<p align="left" style="display: flex; gap: 40px; flex-wrap: wrap;">
  <div style="display: inline-block; text-align: center; margin-right: 30px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" height="60" width="60" style="border-radius: 20px; background: #47A248; padding: 8px;" alt="MongoDB"/>
    <br><span style="font-size: 16px;">MongoDB</span>
  </div>
  <div style="display: inline-block; text-align: center; margin-right: 30px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" height="60" width="60" style="border-radius: 20px; background: #000; padding: 8px;" alt="Express.js"/>
    <br><span style="font-size: 16px;">Express.js</span>
  </div>
  <div style="display: inline-block; text-align: center; margin-right: 30px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" height="60" width="60" style="border-radius: 20px; background: #61DAFB; padding: 8px;" alt="React"/>
    <br><span style="font-size: 16px;">React</span>
  </div>
  <div style="display: inline-block; text-align: center; margin-right: 30px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" height="60" width="60" style="border-radius: 20px; background: #339933; padding: 8px;" alt="Node.js"/>
    <br><span style="font-size: 16px;">Node.js</span>
  </div>
  <div style="display: inline-block; text-align: center; margin-right: 30px;">
    <img src="https://jwt.io/img/icon.svg" height="60" width="60" style="border-radius: 20px; background: #000; padding: 8px;" alt="JWT"/>
    <br><span style="font-size: 16px;">JWT</span>
  </div>
  <div style="display: inline-block; text-align: center; margin-right: 30px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongoose/mongoose-original.svg" height="60" width="60" style="border-radius: 20px; background: #e10098; padding: 8px;" alt="Mongoose"/>
    <br><span style="font-size: 16px;">Mongoose</span>
  </div>
  <div style="display: inline-block; text-align: center;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" height="60" width="60" style="border-radius: 20px; background: #764ABC; padding: 8px;" alt="Redux"/>
    <br><span style="font-size: 16px;">Redux</span>
  </div>
</p>

## Features

- **User Authentication**: Register, login, and secure user sessions.
- **Property Listings**: Browse, search, and filter properties.
- **Add/Edit/Delete Properties**: Agents or admins manage listings.
- **Responsive UI**: Mobile-friendly design using React.
- **Agent/Owner Profiles**: View agent details and contact owners.
- **Favorites**: Save favorite properties for later.
- **Messaging**: Connect with agents or property owners.
- **Admin Dashboard**: Manage users, properties, and site requests.

## Getting Started

1. **Clone the repository**
    ```bash
    git clone https://github.com/<your-username>/homelyhub.git
    cd homelyhub
    ```

2. **Set up Environment Variables**
    - Create a `.env` file in the root for the backend:
      ```
      MONGO_URI=your-mongodb-uri
      JWT_SECRET=your-jwt-secret
      ```

3. **Install dependencies**
    - Backend:
        ```bash
        cd backend
        npm install
        ```
    - Frontend:
        ```bash
        cd ../frontend
        npm install
        ```

4. **Run the app**
    - Backend:
        ```bash
        npm start
        ```
    - Frontend:
        ```bash
        npm start
        ```

5. **Open in browser**
    ```
    http://localhost:3000
    ```

## Folder Structure

```
homelyhub/
│
├── backend/           # Node.js + Express API
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── ...
│
├── frontend/          # React App
│   ├── src/
│   ├── public/
│   ├── ...
│
├── README.md
└── ...
```

## API Endpoints

Example:
- `POST /api/auth/register` — Register user
- `POST /api/auth/login` — Login user
- `GET /api/properties` — Get properties
- `POST /api/properties` — Create property
- More endpoints documented in [backend/routes](./backend/routes)

## Contributing

Contributions welcome! Please open an issue first to discuss changes.

## License

MIT

---

**HomelyHub** — _Your one-stop solution for property management and discovery._
