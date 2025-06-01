# VenueSphere

**VenueSphere** is a venue listing and booking platform built using Node.js and Express. It allows users to explore, create, and manage venue listings with ease.

## Features

- Create and manage venue listings
- Server-rendered views with EJS templating
- MongoDB for data storage
- User-friendly UI with responsive design
- Modular structure for scalability

## 🛠 Tech Stack

- **Backend:** Node.js, Express.js
- **Templating:** EJS
- **Database:** MongoDB (via Mongoose)
- **Styling:** CSS, Bootstrap (optional)
- **Utilities:** dotenv, method-override, body-parser

## Project Structure

```
VenueSphere/
├── app.js                 # Main server file
├── package.json
├── init/                 # Seed data and initialization scripts
│   ├── data.js
│   └── index.js
├── models/               # Mongoose schemas
│   └── listing.js
├── routes/               # Application routes (not listed but assumed)
├── views/                # EJS templates (assumed)
└── public/               # Static assets (assumed)
```

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/VenueSphere.git
cd VenueSphere
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**

Create a `.env` file in the root directory and add your MongoDB URI:

```
MONGODB_URI=your_mongodb_connection_string
PORT=3000
```

4. **Seed the database (optional)**

If you want to seed sample data:

```bash
node init/index.js
```

5. **Start the server**

```bash
npm start
```

Visit [http://localhost:8080](http://localhost:8080) in your browser.

## Scripts

```bash
npm start         # Start the app
npm run dev       # Start with nodemon (if configured)
```

## Screenshots

### Home Page (Venue Grid)
![Home Page](./assets/home.png)

### Venue Details Page
![Venue Details](./assets/home2.png)

### Add New Listing
![Add Listing Form](./assets/listing.png)


## License

This project is licensed under the [MIT License](LICENSE).
