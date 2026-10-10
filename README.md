# express-mongo-auth

API del laboratorio de la semana 8 con Express y MongoDB Atlas.

## Ejecutar

1. Ejecutar `npm install`.
2. Copiar `.env.example` a `.env` y configurar MongoDB Atlas.
3. Ejecutar `npm run dev`.

Puerto por defecto: 3000. El servidor inicia al conectar con MongoDB.

## Rutas

- GET /api/users
- GET /api/users/:id
- POST /api/users
- PUT /api/users/:id
- DELETE /api/users/:id

POST y PUT reciben JSON con `name` y `email`.

En produccion, ejecutar `npm start` y configurar `MONGO_URI`.
