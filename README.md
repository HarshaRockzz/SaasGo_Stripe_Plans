# SaasGo , a SaaS WebApp with Stripe Integration

Welcome to the repository of our SaasGo WebApp, a comprehensive platform that offers various subscription plans through the Stripe payment gateway. This application allows users to browse different services, manage subscriptions, and securely process payments.


## Login Credentials :
### SuperAdmin :
email : superadmin@app.com , 
pwd   : asdfghjkl
### Admin :
email : admin@app.com , 
pwd   : asdfghjkl
### User
email : user@app.com , 
pwd   : asdfghjkl

## Features

- **Subscription Plans**: Offers “Basic”, “Standard”, and “Plus” plans.
- **Plan Details**: Displays a list of available plans with detailed descriptions.
- **Shopping Cart**: Users can add desired services to the cart for review and purchase.
- **Stripe Integration**: Secure checkout process with support for multiple subscriptions.
- **User Authentication**: Features Login and SignUp pages for user accounts.
- **Admin Dashboards**: Separate dashboards for Admin and Super Admin for user and plan management.

## Tech Stack

- **Frontend**: React JS, Material UI
- **Backend**: Node JS, Express JS
- **Database**: MongoDB, Mongoose
- **API**: REST API

### Installation

1. **Install Dependencies**
    ```bash
   //For frontend : 
   cd frontend
   npm install

   // For backend :
   cd backend
   npm install
2. **Configure Environment Variables**
   ```bash
   //.env backend
   DATABASE_URL //is mongodb url
   SECRET=ThisIsSecret
   STRIPE_SECRET_KEY

   //.env frontend
   REACT_APP_BASE_URL //is the base url for backend
3. **start backend server & frontend App**
   ```bash
   //backend
   nodemon index.js
   //frontend
   npm start




