# Build Nextjs ECommerce Website Like Amazon

- Tech: Nextjs 13, Next Auth 4
- UI: Tailwind, chart.js, react-chartjs
- DB: MongoDB, Mongoose
- Content Hosting: cloudinary
- Deploy: Github, MongoDB Atlas

![next amazona](/public/app.PNG)

## Run Locally

1. Clone repo

   ```shell
    $ git clone https://github.com/Rishab1525/Amazon-Clone-.git

   ```

2. Create .env File

   - duplicate .env.example and rename it to .env

3. Setup MongoDB

   - Local MongoDB
   - Install it from [here](https://www.mongodb.com/try/download/community)
   - In .env file update MONGODB_URI=mongodb://localhost/amazona
   - OR Atlas Cloud MongoDB

   - In .env file update MONGODB_URI=mongodb+srv://your-db-connection

4. Install and Run

   ```
   $ npm install
   $ npm run dev
   ```

5. Seed Data

   - Run this on browser: http://localhost:5000/api/seed
   - It returns admin email and password and 6 sample products

6. Admin Login

   - Run http://localhost:3000/login
   - Enter admin email and password and click Login
