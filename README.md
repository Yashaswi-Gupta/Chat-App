# Chat-App
## 📁 Project structure
```terminal
├── client/
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── src/
│   │   ├── animations/
│   │   │   └── typing.json
│   │   ├── components/
│   │   │   ├── Authentication/
│   │   │   │   ├── Login.jsx
│   │   │   │   └── Signup.jsx
│   │   │   ├── UserAvatar/
│   │   │   │   ├── UserBadgeItem.jsx
│   │   │   │   └── UserListItem.jsx
│   │   │   ├── miscellaneous/
│   │   │   │   ├── GroupChatModal.jsx
│   │   │   │   ├── ProfileModal.jsx
│   │   │   │   ├── SideDrawer.jsx
│   │   │   │   └── UpdateGroupChatModal.jsx
│   │   │   ├── ChatBox.jsx
│   │   │   ├── ChatLoading.jsx
│   │   │   ├── MyChats.jsx
│   │   │   ├── ScrollableChat.jsx
│   │   │   ├── SingleChat.jsx
│   │   │   └── index.js
│   │   ├── config/
│   │   │   └── ChatLogics.js
│   │   ├── context/
│   │   │   └── ChatProvider.js
│   │   ├── pages/
│   │   │   ├── Chat.jsx
│   │   │   ├── Home.jsx
│   │   │   └── index.js
│   │   ├── App.css
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── config/
│   ├── connectToMongoDb.js
│   ├── generateHashedPassword.js
│   ├── generateToken.js
│   ├── index.js
│   └── verifyPassword.js
├── controllers/
│   ├── chatControllers.js
│   ├── index.js
│   ├── messageControllers.js
│   └── userControllers.js
├── middleware/
│   ├── authMiddleware.js
│   ├── errorMiddleware.js
│   └── index.js
├── models/
│   ├── Chat.js
│   ├── Message.js
│   ├── User.js
│   └── index.js
├── routes/
│   ├── chatRoutes.js
│   ├── index.js
│   ├── messageRoutes.js
│   └── userRoutes.js
├── .env.example
├── .gitignore
├── LICENSE
├── package-lock.json
├── package.json
├── README.md
└── server.js
```
