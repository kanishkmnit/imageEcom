🖼️ Image Ecommerce Application
This is a full-stack e-commerce application for selling digital images, built with Next.js. It features a complete user authentication flow, secure payment processing, and efficient product management.

✨ Features
User Authentication: Secure user sign-up, sign-in, and session management using NextAuth.js.

Image Management: Seamless image upload, optimization, and delivery powered by ImageKit.io.

Payment Processing: Integration with Razorpay to handle secure payments in test mode.

Product Management: Full CRUD (Create, Read, Update, Delete) functionality for managing products.

🚀 Technologies Used
Frontend: Next.js (React), Tailwind CSS

Backend: Next.js API Routes, Mongoose, NextAuth.js

Database: MongoDB Atlas

Payments: Razorpay

Image CDN: ImageKit.io

🛠️ Installation & Setup
Follow these steps to get the project running on your local machine.

1. Clone the Repository
git clone https://github.com/kanishkmnit/imageEcom.git
cd imageEcom

2. Install Dependencies
Install all the required npm packages.

npm install

3. Environment Variables
Create a file named .env.local in the root of your project and add the following variables. Replace the placeholder values with your own credentials.

# MongoDB Configuration (from MongoDB Atlas)
MONGODB_URI=mongodb+srv://<db_username>:<db_password>@<cluster_name>.mongodb.net/<db_name>?retryWrites=true&w=majority

# Authentication Secret (generate this yourself)
NEXTAUTH_SECRET=your_32_character_random_string

# ImageKit Configuration (from ImageKit.io dashboard)
NEXT_PUBLIC_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
NEXT_PUBLIC_URL_ENDPOINT=your_imagekit_url_endpoint

# Razorpay Configuration (from Razorpay dashboard in Test Mode)
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_secret
RAZORPAY_WEBHOOK_SECRET=your_webhook_secret

# Mailtrap Configuration (from Mailtrap.io sandbox)
MAILTRAP_HOST=sandbox.smtp.mailtrap.io
MAILTRAP_PORT=2525
MAILTRAP_USER=your_mailtrap_user
MAILTRAP_PASS=your_mailtrap_password

4. Build and Run the Application
First, build the project for production, then start the server.

# Build the project
npm run build

# Start the local server
npm start

🖥️ Usage
After starting the server, open your web browser and navigate to:
http://localhost:3000
