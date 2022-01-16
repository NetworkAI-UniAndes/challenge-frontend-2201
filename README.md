# Challenge: Front-end Technical Leader

Document in Spanish with additional images: https://drive.google.com/file/d/1f2wcdRGlGyR2sG-mki_7EGCqNCMMP7ir/view?usp=sharing

### Configuración inicial 🔧

1. Fork the repository

2. Clone the repository

3. Install npm modules (in root)

   ```bash
   npm install
   ```

4. Install npm modules (inside _frontreact_ folder)

   ```bash
   cd frontreact
   npm install
   ```

5. Run server (nodemon, static file server). Located at the root of the repository run:

   ```bash
   npm run start
   ```

   The above command will deploy the application backend on port 3001. Go to **http://localhost:3001/img/products/N0CA_430.png** You should see an image of a product which is exposed by the server.

6. Run development server for react. Located in the _frontreact_ directory run:

   ```bash
   npm run start
   ```

   The above command will deploy the app's frontend to port 3000. Go to **http://localhost:3000/home** and you should see the app's main page in react.

7. If you want to run the application in production mode. Follow these steps:

- Go to the _frontreact_ directory and run:
  ```bash
  npm run build
  ```
- Then, on the root of the repository, execute:
  ```bash
  npm run start
  ```
- Now when you go to **http://localhost:3001** you should see the app in react
