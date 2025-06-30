# Random Ideas Project
This is a fullstack application for sharing random ideas. It was built as part of my learning journey with backend development and MongoDB.

The app includes a Node.js/Express REST API that uses MongoDB for persistent storage. The frontend can be integrated separately and communicates with the API through standard HTTP methods.

## 🚀 Features
- Full CRUD API for ideas
- MongoDB for persistent data storage
- Handles HTTP requests in a clean and modular way
- Data validation with Mongoose
- UUID or Mongo _id for unique idea identification
- Easy to extend and deploy

## 📦 Installation
```bash
git clone https://github.com/SanskrutiNijai/random_ideas_api_project.git
cd random_ideas_api_project
```

### Install Dependencies
Install dependencies on the front-end and back-end
```bash
npm install
cd client
npm install
```

### Back-end/Express Server
```bash
npm start
```
or
```bash
npm run dev (Nodemon)
```
Visit ```bash http://localhost:5000 ```

To build front-end production files
```bash
cd client
npm run build
```
Visit ```bash http://localhost:3000 ```

The production build will be put into the public folder, which is the Express static folder.

### Environment Variables
```bash
MONGO_URI=your_mongodb_uri
```

### 📡 API Endpoints
| Method | Endpoint         | Description     |
| ------ | ---------------- | --------------- |
| GET    | `/api/ideas`     | Get all ideas   |
| POST   | `/api/ideas`     | Create new idea |
| GET    | `/api/ideas/:id` | Get idea by ID  |
| PUT    | `/api/ideas/:id` | Update idea     |
| DELETE | `/api/ideas/:id` | Delete idea     |

### 📝 Sample Request
```bash
{
  "text": "Sample Idea 5",
  "tag": "Technology",
  "username": "XYZ"
}
```
### 🧪 Testing the API
Use Postman to test the API endpoints.

### 🙌 Credits
This project was created as part of the Modern JavaScript From The Beginning 2.0 (2024) course by [Brad Traversy](https://github.com/bradtraversy). Many thanks for the great content and guidance.

