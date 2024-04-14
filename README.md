# Deploy Apps on Streamlit Tutorial

#### Author : Rahul Bhoyar

Streamlit Community Cloud provides an easy way to deploy your apps with just one click. If you're new to Python and Streamlit, don't worry! Follow these simple steps to get your app up and running in minutes.

### Step 1. Prepare Your App:
If you don't have an app ready, you can find sample apps in the App Gallery. These apps cover various topics like Machine learning, Data Visualization, and more. You can also fork and deploy samples directly from the "New app" button.

### Step 2. Add Your App to GitHub:
Before deploying your app, ensure your app code and dependencies are on GitHub. Your directory structure should look like this:

```
your-repository/
├── .streamlit/
│   └── config.toml
│   └── secrets.toml
├── your_app.py
└── requirements.txt
```
If you're using custom configurations or theming, save your config file as **.streamlit/config.toml** in the root directory. You can also add the secrets in **.streamlit/secrets.toml** file. 

### Step 3. Deploy Your App:

Go to your workspace at share.streamlit.io.
Click "New app" and fill in your repo, branch, and file path. You can also paste a GitHub URL directly.
Optionally, set a custom subdomain for your app.
Click "Deploy" to start the deployment process.

### Step 4. Advanced Settings:
If needed, you can specify the Python version or manage secrets before deploying your app. These settings help customize your app deployment according to your requirements.

### Step 5. Watch Your App Launch:
Sit back and watch as your app deploys. It usually takes just a couple of minutes. Once deployed, any changes you make should show up immediately.

### Step 6. Share Your App:
Congratulations, your app is now live with a unique subdomain URL! Share it with others to showcase your work and collaborate.

**Custom Subdomains:**
You can choose a custom subdomain to make your app's URL more memorable. Simply pick a name between 6 and 63 characters and save it in the app settings. Access your app using the customized URL.

For more information, you can visit : [Deploy your app using Streamlit](https://docs.streamlit.io/deploy/streamlit-community-cloud/deploy-your-app)



