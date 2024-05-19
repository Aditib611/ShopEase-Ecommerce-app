# ShopEase - Ecommerce Application
Welcome to the E-Commerce Application, a feature-rich and user-friendly online shopping platform built with the MERN stack. This project demonstrates the integration of React for a dynamic UI, Express/Node.js for a secure back-end, and MongoDB for efficient data storage.
Implements bcrypt for password protection, ensuring secure user authentication and data protection. Additionally, it includes a dummy payment gateway and various filters to enhance the user experience.

## How to run on local machine 💻

 To install server-side dependencies:


```bash
  npm install
```

To install client-side dependencies:
```bash
  cd .\client\
```

```bash
  npm install
```

To Run:

Change directory to main folder
```bash
  npm run dev
```
It will run server and client concurrently. 🚀

## Environment Variables 🔐

To run this project, you will need to add the following environment variables to your .env file

**Server Side Env. Variables:**

`PORT`

`MONGO_URL`

`JWT_SECRET`

For Payment Gateway

`BRAINTREE_MERCHANT_ID`

`BRAINTREE_PUBLIC_KEY`

`BRAINTREE_PRIVATE_KEY`

**Client Side Env. Variables:**

`REACT_APP_API`

## Tech Stack 🧑‍💻

**Client:** React, Bootstrap, antd

**Server:** Node, Express

**Database:** MongoDB Atlas

**Authentication:** bcrypt

## Dependencies ⬇️

**Client:** 

- react
- react-dom
- react-helmet (For document head manager, Better SEO )
- react-hot-toast (mimic push notifications )
- react-icons (Interactive icons)
- react-router-dom (For Routing)
- antd (Prebuild Components)
- axios (For API requests)
- braintree-web-drop-in-react (Braintree Dropin for Payment)
- moment (To manipulate Data object)

**Server:** 

- bcrypt (to hash and store passwords)
- braintree (For Payment integration)
- colors
- concurrently (start the React and Express servers concurrently)
- cors (for authorized resource sharing with external third parties)
- dotenv (keep API keys, and other sensitive data out of your code)
- express
- express-formidable (parsing form data, including multipart/form-data file upload)
- jsonwebtoken (For token)
- mongoose (object modeling tool for MongoDB)
- morgan (To log requests)
- slugify ( For word manipulation)
- 
## Authors ✍️

- [@Aditib611](https://github.com/Aditib611) 


## Support/Feedback ❤️

For support/Feedback, email aditibhavsar26@gmail.com 📩.
