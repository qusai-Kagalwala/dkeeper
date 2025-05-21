# 📝 DKeeper
DKeeper is a decentralized note-taking application built on the Internet Computer platform. It functions similar to Google Keep but operates on a decentralized infrastructure, providing enhanced privacy and data ownership.

## ✨ Features
- 📌 Create, read, update, and delete notes
- 🔄 Persistent storage on the Internet Computer blockchain
- 🔒 Decentralized architecture for enhanced privacy and security
- 📱 Responsive web interface built with React.js
- 🧩 Backend canister written in Motoko

## 🛠️ Technology Stack
- 🖥️ **Frontend**: React.js
- 🔧 **Backend**: Internet Computer/Motoko
- 🧪 **Development Environment**: DFINITY SDK (dfx)

## 📋 Prerequisites
Before you begin, ensure you have the following installed:
- 📦 [Node.js](https://nodejs.org/) (v12 or later)
- 🚀 [DFINITY Canister SDK](https://sdk.dfinity.org/docs/quickstart/local-quickstart.html)
- 🔄 [Git](https://git-scm.com/downloads)

## 🚀 Getting Started
### 📥 Clone the Repository
```bash
git clone https://github.com/qusai-Kagal/DevVault.git
cd DevVault/web-development/dkeeper
```

### 📦 Install Dependencies
```bash
npm install
```

### 🏃‍♂️ Run the Development Environment
1. Start the local Internet Computer replica:
```bash
dfx start --clean
```

2. In a new terminal window, deploy the canisters:
```bash
dfx deploy
```

3. Start the frontend development server:
```bash
npm start
```

4. Open your browser and navigate to:
```
http://localhost:8080/
```

## 🌐 Deployment
To deploy to the Internet Computer mainnet:
1. Make sure you have cycles available in your wallet 💰
2. Deploy using:
```bash
dfx deploy --network ic
```

## 📁 Project Structure
```
DevVault/
└── web-development/
    └── dkeeper/
        ├── dist/
        │   └── dkeeper_assets/  # 📦 Built assets
        ├── src/                 # 💻 Source code
        │   ├── declarations/    # 📝 Type declarations for the canisters
        │   ├── dkeeper/         # 🧠 Main application code
        │   └── dkeeper_assets/  # 🖼️ Static assets for the application
        ├── dfx.json             # ⚙️ DFINITY project configuration
        ├── package.json         # 📦 Node.js dependencies
        ├── package-lock.json    # 🔒 Locked dependencies
        ├── tsconfig.json        # ⚙️ TypeScript configuration
        ├── webpack.config.js    # 🔧 Webpack bundler configuration
        └── README.md            # 📝 This file
```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
1. Fork the project 🍴
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 🎉

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgments
- 💡 Inspired by Google Keep
- 🚀 Built with the Internet Computer platform
- 🙏 Thanks to the DFINITY Foundation for their developer tools and documentation

## 📫 Contact
Qusai Kagalwala - [GitHub Profile](https://github.com/qusai-Kagalwala)
Project Link: [https://github.com/qusai-Kagalwala/dkeeper](https://github.com/qusai-Kagalwala/dkeeper)
