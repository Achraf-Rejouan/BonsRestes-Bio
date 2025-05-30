# BonsRestes-Bio 🌱

A sustainable food waste reduction platform that connects users with organic food surplus, promoting eco-friendly consumption and reducing environmental impact.

## 🌟 Overview

BonsRestes-Bio is a web application designed to tackle food waste by creating a marketplace for organic and bio products that would otherwise go to waste. The platform enables users to discover, share, and purchase surplus organic food items at reduced prices, contributing to a more sustainable food ecosystem.

## ✨ Features

- **Organic Food Marketplace**: Browse and purchase surplus organic products
- **Image Upload**: Share photos of available food items using Cloudinary integration
- **User Management**: Secure user authentication and profile management
- **Real-time Updates**: Dynamic content updates for fresh listings
- **Responsive Design**: Optimized for desktop and mobile devices
- **Environmental Impact**: Track your contribution to reducing food waste

## 🛠️ Tech Stack

### Backend
- **Node.js**: Server-side JavaScript runtime
- **Express.js**: Web application framework
- **MongoDB**: NoSQL database for data storage
- **Cloudinary**: Cloud-based image management

### Frontend
- **React**: Modern JavaScript library for building user interfaces
- **Modern CSS**: Responsive and accessible styling

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager
- MongoDB instance (local or cloud)
- Cloudinary account for image uploads

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Achraf-Rejouan/BonsRestes-Bio.git
   cd BonsRestes-Bio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   
   Create a `.env` file in the root directory with the following variables:
   ```env
   PORT=5001
   MONGO_URI=your_mongo_uri
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   CLIENT_URL=http://localhost:5173
   NODE_ENV=development
   ```

4. **Build the application**
   ```bash
   npm run build
   ```

5. **Start the application**
   ```bash
   npm run start
   ```

The application will be available at `http://localhost:5001`

## 📁 Project Structure

```
BonsRestes-Bio/
├── client/                 # Frontend React application
├── server/                 # Backend Node.js application
├── public/                 # Static assets
├── .env.example           # Environment variables template
├── package.json           # Project dependencies
└── README.md             # Project documentation
```

## 🌍 Environmental Impact

BonsRestes-Bio contributes to:
- **Reducing Food Waste**: Preventing organic food from ending up in landfills
- **Lowering Carbon Footprint**: Minimizing greenhouse gas emissions from food waste
- **Supporting Sustainable Agriculture**: Promoting organic and bio products
- **Community Building**: Connecting environmentally conscious consumers

## 🤝 Contributing

We welcome contributions to BonsRestes-Bio! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Development Guidelines

- Follow ESLint configuration for code style
- Write meaningful commit messages
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation when needed

## 🔧 Scripts

- `npm run start` - Start the production server
- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the application for production
- `npm run test` - Run the test suite
- `npm run lint` - Run ESLint for code quality

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/Achraf-Rejouan/BonsRestes-Bio/issues) page
2. Create a new issue with detailed information
3. Contact the maintainer: [Achraf Rejouan](https://github.com/Achraf-Rejouan)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all contributors who help make this project better
- Inspired by the global movement to reduce food waste
- Built with sustainability and community in mind

---

**Made with ❤️ for a more sustainable future**
