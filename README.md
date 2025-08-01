---

### ✅ Bash Command (for Linux, macOS, or Git Bash on Windows)

```bash
mkdir -p backend/src/{config,controllers,middleware,models,routes,types/express,utils} && \
touch backend/src/config/db.ts \
backend/src/controllers/userController.ts \
backend/src/middleware/authMiddleware.ts \
backend/src/models/User.ts \
backend/src/routes/userRoutes.ts \
backend/src/types/express/index.d.ts \
backend/src/utils/generateToken.ts \
backend/src/app.ts \
backend/src/server.ts \
backend/.env \
backend/.env.example \
backend/tsconfig.json \
backend/package.json \
backend/nodemon.json \
backend/README.md
```

---

### 📦 What This Command Does:

* `mkdir -p`: creates directories (nested)
* `touch`: creates empty files
* `\` is used to break the long line for readability

---

### 💡 After Running:

You’ll have this full structure instantly:

```
backend/
├── src/
│   ├── config/db.ts
│   ├── controllers/userController.ts
│   ├── middleware/authMiddleware.ts
│   ├── models/User.ts
│   ├── routes/userRoutes.ts
│   ├── types/express/index.d.ts
│   ├── utils/generateToken.ts
│   ├── app.ts
│   └── server.ts
├── .env
├── .env.example
├── tsconfig.json
├── package.json
├── nodemon.json
└── README.md
```

---


