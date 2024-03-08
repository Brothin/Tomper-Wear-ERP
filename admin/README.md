<p align='center'>
<img src='./src/assets/logo.svg'  width='25%'>
</p>
<p align='center'>
<b>ERP (Enterprise Resource Planning) system, designed to manage basic business operations efficiently</b>
</p>
---

<p align='center'>
This is the Admin dashboard of TomperWear build with MERN stack
</p>

## 📷 Link to [Screenshots](./SCREENSHOTS.md)

## 🧾 Description

The goal of this project is to create a simplified interface for an ERP (Enterprise Resource Planning) system, designed to manage basic business operations efficiently. The system will consist of the following pages:

• Dashboard - Provides an overview of the system's features.<br>
• Products Management - Allows for the management of product listings.<br>
• Orders Management - Facilitates viewing and handling orders.

## ✨ Features

The admin panel of TomperWear contains three classes of admins:

**1. Super privileged admin**
Super privileged admins are the topmost in the hierarchy. They have the following permissions:

- [x] Can view, create, update, and delete admin users.
- [x] Can view, create, update, and delete products.
- [x] Can view orders and update their status.
- [x] Can delete orders.

This is privilege is ideal for the owner(s) of the bussiness.

**2. Moderate privileged admin**
Moderate privileged admins comes below Super privileged admins. They have the following permissions:

- [ ] Can view, create, update, and delete admin users.
- [x] Can view, create, update, and delete products.
- [x] Can view orders and update their status.
- [x] Can delete orders.

This is privilege is ideal for the manager(s).

**3. Low privileged admin**
Low privileged admins are the lowermost in the hierarchy and have the least amount of privileges. The have the following permission:

- [ ] Can view, create, update, and delete admin users.
- [ ] Can view, create, update, and delete products.
- [x] Can view orders and update their status.
- [ ] Can delete orders.

This is privilege is ideal for the delivery-agent(s).

**Here is a table dipicting the admin privileges for better clarity**

<table>
<thead>
  <tr>
    <th> </th>
    <th colspan="4">Admins</th>
    <th colspan="4">Product</th>
    <th colspan="3">Orders</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td><b><u>view</u></b></td>
    <td><b><u>create</u></b></td>
    <td><b><u>update</u></b></td>
    <td><b><u>delete</u></b></td>
    <td><b><u>view</u></b></td>
    <td><b><u>create</u></b></td>
    <td><b><u>update</u></b></td>
    <td><b><u>delete</u></b></td>
    <td><b><u>view</u></b></td>
    <td><b><u>update</u></b></td>
    <td><b><u>delete</u></b></td>
  </tr>
  <tr>
    <td><b>Super</b></td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
  </tr>
  <tr>
    <td><b>Moderate</b></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
    <td>✔</td>
  </tr>
  <tr>
    <td><b>Low</b></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>✔</td>
    <td>✔</td>
    <td>-</td>
  </tr>
</tbody>
</table>

## ⚙ Tools and Technologies used

#### [Client](https://github.com/varunKT001/tomper-wear-ecommerce)

1. [React.js](https://reactjs.org/)
2. [React-icons](https://react-icons.github.io/react-icons/)
3. [Styled-Components](https://styled-components.com/)
4. [Firebase](https://firebase.google.com/)
5. [Stripe](https://stripe.com/)
6. [Formspree](https://formspree.io/)

#### [Admin panel](https://github.com/varunKT001/tomper-wear-ecommerce-admin)

1. [React.js](https://reactjs.org/)
2. [Chakra-ui](https://chakra-ui.com/)
3. [React-icons](https://react-icons.github.io/react-icons/)

#### [Backend](https://github.com/varunKT001/tomper-wear-ecommerce-backend)

1. [Node.js](https://nodejs.org/en/)
2. [Express.js](https://expressjs.com/)
3. [MongoDB](https://www.mongodb.com/)
4. [JWT](https://jwt.io/)
5. [Cloudinary](https://cloudinary.com/)
6. [Bcrypt.js](https://github.com/dcodeIO/bcrypt.js)
7. [Stripe](https://stripe.com/)

## 🛠 Installation and setup

1. Clone the repo to your local machine.
2. Install the required dependency for server using :

   ```javascript
   npm install
   ```

3. Create a .env file inside the root folder and provide the following environment variables:

   ```env
   REACT_APP_BACKEND_HOST=<backend_url>
   ```

4. Start the dev server using :

   ```javascript
   npm start
   ```

## 🏎 Creating production built

1. Create a production ready react app using the command :

   ```javascript
   npm run build
   ```

## 🤝 Test admin user credentials

| **Username**  | **E-mail**                   | **Password**     |
| ------------- | ---------------------------- | ---------------- |
| Test Super    | test.super@tomperwear.com    | testsuper1212    |
| Test Moderate | test.moderate@tomperwear.com | testmoderate1212 |
| Test Low      | test.low@tomperwear.com      | testlow1212      |

NOTE: These are just for testing purpose. Please don't:

1. Update or delete an existing product.
2. Delete product reviews.
3. Create new admin users.
4. Delete existing admin users.

For testing out things, you can create a new product, try out things and after that delete the product that you created.
