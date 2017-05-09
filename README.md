# IBM Watson NLP Demo

This application demo's IBM Watson Natural Language Processing APIs

# Setup

## Step 1: Install OS Dependacies
This application used Node.js. Download and install it here: https://nodejs.org/

## Step 2: Installation Nodejs Packages
```
npm install
```

## Step 3: Modify the `sample.env` file
Rename `sample.env` to `.env`.

## Step 4: Create an IBM Bluemix account
Get a 30-day free trial of Bluemix: https://console.ng.bluemix.net/registration/

## Step 5: Provision a Natural Language Understanding Instance
Go to the **Catalog** and select *Services > Watson > Natural Language Understanding*. Select the **Free Plan** and the *Create*.

Wait while Bluemix provisions your instance then get the credentials from **Service Credentials** and then select *View Credentials*. Add them to the appropriate location in your `.env` file.

## Step 6: Run the application
```
npm start
```

The app runs on `http://localhost:3000`.


# Credits: This app started from Mega Boilerplate App (Node.js)

Generated by http://megaboilerplate.com

### Configuration
- **Platform:** node
- **Framework**: express
- **Template Engine**: jade
- **CSS Framework**: bootstrap
- **CSS Preprocessor**: css
- **JavaScript Framework**:
- **Build Tool**: none
- **Unit Testing**: none
- **Database**: sqlite
- **Authentication**: email
- **Deployment**: none