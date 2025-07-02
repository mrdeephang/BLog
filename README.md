# Vlog - A Blogging Application
![Image](https://github.com/user-attachments/assets/be384adf-f042-4232-9b6a-1048ea37674f)
![Image](https://github.com/user-attachments/assets/4d84436f-9c65-4ab0-a1c1-4e247bd698a6)
![Image](https://github.com/user-attachments/assets/b3aba1bc-96dc-43a1-be42-66b228041a5b)


## Technologies Used 💻

### Backend

- [Express](https://expressjs.com/) as Node.js web framework
- [MongoDB](https://www.mongodb.com/) as NoSQL Database
- [Mongoose](https://mongoosejs.com/) as ODM library
- [JWT](https://github.com/auth0/node-jsonwebtoken) as a authentication library

### Frontend

- [Nextjs](https://nextjs.org/) as a React framework
- [Material-UI](https://material-ui.com/) as a UI component library
- [react-markdown](https://github.com/remarkjs/react-markdown) as a markdown parser and renderer

## Things to consider 

- Used own Backend.
- Used **JavaScript** instead of **TypeScript** as I think for small projects and working alone, TypeScript is **overkill**.
- Used Nextjs **SSR** for fetching **individual blog** and **blog list**. (Also, replaced them with **SSG** in separate branch)
- Used Material-UI for **fast** and **easier** UI development.
- No **State Management** library is used as I was running **out of time**.
- UI is **inspired** by various **design resources** from internet.
- The whole app is **responsive**.

## Quick Start 

### Clone the repo

```js
git clone **https or ssh url**
```

### Add a .env file in the root of server folder

```js
NODE_ENV=development
PORT=8000
DATABASE=**your mongo database uri**
DATABASE_PASSWORD=**your mongo database password**
JWT_SECRET=**a secrect key**
JWT_EXPIRES_IN=90d
JWT_TOKEN_EXPIRES_IN=90
```

### Install client dependencies

```js
cd client
yarn or yarn install
```

### Install server dependencies

```js
cd server
yarn or yarn install
```

### Run server in one terminal

```js
cd server

yarn prod (Recommended when testing)
or
yarn dev (For local development, not recommended when testing)
```

### Run client in another terminal

```js
cd client

yarn build (I recommend to use Nextjs build version just for testing)
yarn start (After finish running **yarn build**)
or
yarn dev (For local development, not recommended when testing)
```

Check in browser on [http://localhost:3000/](http://localhost:3000/)

## App Info 

### Author

Deephang Thegim

### Version

1.0.0

### License

This project is licensed under the MIT License.
