# Angular JS Ecommerce App
![Angular JS Ecommerce App](https://cosmicjs.com/uploads/ca5cc070-4ae2-11e7-a6d3-9950c5658967-Screen%20Shot%202017-06-06%20at%201.05.28%20PM.png)
<img align="right" width="119" src="https://ecommerce-app.cosmicapp.co/dist/img/powered_by_stripe@2x.png">

### [View a demo here](https://cosmicjs.com/apps/ecommerce-app)

An Angular JS ecommerce app that allows you to:
1. Process orders from customers and accept Stripe payments for goods and services.
2. Manage inventory in your Cosmic JS Dashboard or in the admin area on the website.

### Get Started
[Sign up for Cosmic JS](https://cosmicjs.com/) to start managing content for your websites and applications faster and easier.

#### Building and running the server (performs a gulp command prestart):
```
git clone https://github.com/khanhnamle1994/ecommerce-app/
cd ecommerce-app
npm install
COSMIC_BUCKET=your-bucket-slug READ_KEY=your-read-key WRITE_KEY=your-write-key STRIPE_KEY=your-public-key STRIPE_SECRET=your-private-key npm start
```
Then go to [http://localhost:3000](http://localhost:3000)

### Admin area
Go to http://localhost:3000/#/login to manage your products and orders.

### In Production
#### Deploy to Cosmic JS
[Deploy this app to Cosmic JS in a few clicks.](https://cosmicjs.com/apps/ecommerce-app)

#### Add Stripe Keys
After you deploy go to Deploy Web App > Set Environment Variables to add your STRIPE_KEY and STRIPE_SECRET environment variables.  Screenshot below:
![Add Env Vars](https://cosmicjs.com/uploads/f1066a70-4b17-11e7-937c-a1254a7b329a-Screen%20Shot%202017-06-06%20at%207.26.01%20PM.png)
