<h1 align="center">Tinder Clone ✨</h1>

- 🔐 Authentication System with JWT
- 🛡️ Route Protection
- 👤 User Profile Creation and Updates
- 🖼️ Image Upload for Profiles
- 🔄 Swipe Right/Left Feature
- 💬 Real-time Chat Messaging
- 🔔 Real-time Notifications
- 🤝 Matching Algorithm
- 📱 Responsive Mobile Design

Future plans:
- Age filter
- Time, status in messages
- Bio filter(maybe with AI tool)
- Region filter(geolocation and radius)
- Redis useage
- microservise architecture + upgrage modules
- better upload(paginations)
- Mods(To find parther or find friends)
- Збірник колоди(один раз в день як окримий сервіс в кеші - перевірка чи не змінилися префернс)
- Kafka
- 
-try to immigrate to Postgres(PostGIS   ACID bag) an Java Spring(migration)
-clondinary to Amazon S3(CDN)

### Setup .env file

```bash
PORT=5000
MONGO_URI=<your_mongo_uri>

JWT_SECRET=<your_very_strong_secret>

NODE_ENV=development
CLIENT_URL=http://localhost:5173

CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>

```

### Run this app locally

- Set `NODE_ENV=production` and build the app 👇

```shell
npm run build
```

### Start the app

```shell
npm run start
```
