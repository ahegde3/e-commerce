### Project Setup

1. Clone the repository:
   `git clone https://github.com/ahegde3/e-commerce.git`
2. Install dependencies:

   - For backend: ` cd backend && npm install`
   - For frontend: `cd frontend && npm install`
   <!-- Set up the database (if applicable):
   Instructions for database setup. -->

3. Run the application:
   - For backend:`npm run start`
   - For frontend:`npm run start`
4. - Access the Backend at http://localhost:3000 .
   - Access the frontend at http://localhost:8000 .

### Database Design

The SQL database schema  is as follows:

```
user (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  username TEXT NOT NULL UNIQUE,
  password TEXT NOT NULL
)
```

```
products(
  id INTEGER PRIMARY KEY,
  name TEXT NOT NULL,
  price REAL NOT NULL,
  description TEXT,
  category TEXT,
  image TEXT
)
```

### API Endpoints

The API endpoints are as follows:

| Method | Endpoint                           |
| ------ | ---------------------------------- |
| GET    | http://localhost:3000/products     |
| GET    | http://localhost:3000/products/:id |
| POST   | http://localhost:3000/users/login  |



### Testing user's credentials

Use this credential to login to the application:
```

username: admin
password: admin

```

```
