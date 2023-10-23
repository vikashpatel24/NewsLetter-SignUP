# Deploy a Node Express App on Render

You can easily deploy a Node Express application on Render in just a few steps. Here's a quick guide to get you started:

1. **Fork the Express Hello World Repository**
   - Go to the [Express Hello World GitHub repository](https://github.com/render-examples/express-hello-world).
   - Click on the "Fork" button in the top right corner to create your copy of the repository.

2. **Create a New Web Service on Render**
   - Visit the [Render](https://render.com/) website and log in to your account (or sign up if you don't have one).

3. **Give Render Access to Your New Repository**
   - In your Render dashboard, click on the "Add a New Service" button.
   - Select the repository you forked in step 1 and give Render the necessary permissions to access it.

4. **Configure Your Service on Render**
   - In the service creation form, set the following values:
     - **Runtime:** Node
     - **Build Command:** yarn
     - **Start Command:** node app.js

5. **Deploy Your Application**
   - Click the "Create Service" button.
   - Render will automatically build and deploy your Node Express application.
   - Your web service will be live on your Render URL as soon as the build process finishes.

6. **Customize Node.js Version (if needed)**
   - If you need to specify a specific Node.js version for your app, refer to the "Specifying a Node Version" documentation on Render.

That's it! Your Node Express application is now live on Render. You can access it using the URL provided by Render.

For more advanced configurations and additional settings, be sure to check the Render documentation.

Happy coding!
