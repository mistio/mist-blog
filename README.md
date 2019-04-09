## Mist.io Blog

https://blog.mist.io/

### Install

The documentation site runs in Google App Engine, using the App Engine Python
standard environment. Before you start you'll need the following prerequisites:

-   Python 2.7
-   [Google Cloud SDK](https://cloud.google.com/sdk/)
-   App Engine Python standard environment. Ensure this is installed by running
    the following command:

        gcloud components install app-engine-python

    Or, if you installed via apt:

        sudo apt-get install google-cloud-sdk-app-engine-python

Set up your repo:

    git clone 
    cd docs
    npm install


### Running the site

The first time you run the site, run `npm run build` to build the site in its
entirety:

    npm run build

Then start the App Engine dev server:

    npm run serve

The site will be served from http://localhost:8080.


### Deployment

Build and deploy a new version of the site:

    npm run deploy
