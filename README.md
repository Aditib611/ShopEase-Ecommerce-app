# ShopEase-Ecommerce-app
 A feature-rich MERN stack E-commerce app, employing React for dynamic UI and Express/Node.js for secure back-end. Utilized MongoDB for data storage, integrating a dummy payment gateway and diverse filters for enhanced user experience.

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
- multer (for handling multipart/form-data)
- pdf-lib (To modify PDF files )
- slugify ( For word manipulation)
