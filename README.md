# Excel Analyst MERN

A full-stack web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack for advanced Excel file analysis and data visualization.

## 🚀 Features

- **Excel File Upload & Processing**: Upload and parse Excel files (.xlsx, .xls)
- **Data Visualization**: Interactive charts and graphs using modern visualization libraries
- **Data Analysis Tools**: Statistical analysis, filtering, and data manipulation
- **Real-time Updates**: Live data processing and updates
- **User Authentication**: Secure user registration and login system
- **Dashboard**: Comprehensive analytics dashboard
- **Export Functionality**: Export processed data and visualizations

## 🛠️ Tech Stack

### Frontend
- **React.js** - User interface library
- **CSS3/SCSS** - Styling
- **Chart.js/D3.js** - Data visualization
- **Axios** - HTTP client for API calls

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

### Additional Tools
- **Multer** - File upload handling
- **XLSX** - Excel file parsing
- **JWT** - Authentication tokens
- **Bcrypt** - Password hashing

## 📋 Prerequisites

Before running this application, make sure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local installation or MongoDB Atlas)
- Git

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abhaytiwari303/Excel-Analyst-MERN.git
   cd Excel-Analyst-MERN
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Setup**
   
   Create a `.env` file in the backend directory:
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/excel-analyst
   JWT_SECRET=your_jwt_secret_key
   NODE_ENV=development
   ```

5. **Start the application**
   
   Backend (from backend directory):
   ```bash
   npm run dev
   ```
   
   Frontend (from frontend directory):
   ```bash
   npm start
   ```

## 🚀 Usage

1. **Register/Login**: Create an account or login to access the application
2. **Upload Excel File**: Use the upload feature to import your Excel files
3. **Analyze Data**: Utilize the built-in analysis tools to process your data
4. **Visualize**: Create charts and graphs from your data
5. **Export Results**: Download processed data or save visualizations

## 📁 Project Structure

```
Excel-Analyst-MERN/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── utils/
│   │   └── App.js
│   └── package.json
├── uploads/
├── .gitignore
└── README.md
```

## 🔗 API Endpoints

### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/auth/profile` - Get user profile

### File Operations
- `POST /api/files/upload` - Upload Excel file
- `GET /api/files` - Get user's uploaded files
- `DELETE /api/files/:id` - Delete a file

### Data Analysis
- `POST /api/analysis/process` - Process Excel data
- `GET /api/analysis/results/:id` - Get analysis results
- `POST /api/analysis/visualize` - Generate visualizations

## 🧪 Testing

Run tests using:
```bash
# Backend tests
cd backend
npm test

# Frontend tests  
cd frontend
npm test
```

## 🚀 Deployment

### Backend Deployment (Heroku)
1. Install Heroku CLI
2. Login to Heroku: `heroku login`
3. Create app: `heroku create excel-analyst-backend`
4. Set environment variables: `heroku config:set MONGODB_URI=your_mongodb_atlas_uri`
5. Deploy: `git push heroku main`

### Frontend Deployment (Netlify/Vercel)
1. Build the project: `npm run build`
2. Deploy the `build` folder to your preferred hosting service

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Abhay Tiwari**
- GitHub: [@Abhaytiwari303](https://github.com/Abhaytiwari303)
- Email: [your-email@example.com](mailto:your-email@example.com)

## 🙏 Acknowledgments

- Thanks to the MERN stack community for excellent documentation
- Chart.js and D3.js for powerful visualization capabilities
- MongoDB Atlas for cloud database hosting
- All contributors who helped improve this project

## 📞 Support

If you have any questions or need help with the project, please:
- Open an issue on GitHub
- Contact me via email
- Check the documentation in the `/docs` folder

---

⭐ **If you found this project helpful, please give it a star!** ⭐
