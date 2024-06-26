# SuPassOp

SuPassOp is a secure password management application built with React.js, Tailwind CSS, and Node.js. This application helps users manage their passwords efficiently and securely.

## Features

- User authentication
- Secure password storage
- Password generation
- Responsive design
- Easy-to-use interface

## Technologies Used

- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Node.js (https://nodejs.org/)
- MongoDB (https://www.mongodb.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sudhaanshuu/SuPassOp.git
   cd SuPassOp
   ```
2. **Install backend dependencies:**
    ```bash
     cd backend
     npm install
    ```
3. **Install frontend dependencies:**
    ```bash
     cd ../frontend
     npm install
    ```
### Configuration
1. **Backend:**
 - Create a .env file in the backend directory.
 - Add the following environment variables:
    ```bash
       PORT=5000
       MONGODB_URI=your_mongodb_connection_string
       JWT_SECRET=your_jwt_secret
    ```
2. **Frontend:**
  - No additional configuration required.

### Running the Application
1. **Start the backend server:**
```bash
cd backend
npm start
```
2. **Start the frontend server:**
```bash
cd ../frontend
npm start
```
3. **Access the application:**
- Open your browser and navigate to `http://localhost:3000`.

### Project Structure
```plaintext
  SuPassOp/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
└── README.md
```
### MIT License

```plaintext
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

### Contact
Sudhanshu Kumar - Sudhaanshuu@gmail.com
Project Link: https://github.com/Sudhaanshuu/SuPassOp


