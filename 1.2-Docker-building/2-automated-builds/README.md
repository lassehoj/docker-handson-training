#  Setting up an automated build

Create a repo on github and commit and push the `Add-a-tron-service` 

Go to the Docker Hub (https://hub.docker.com/).

Select "Create" in the top-right bar, and select "Create Automated Build."

Connect your Docker Hub account to your GitHub account.

Select your user and the repository you just created.

Click Create.

Then go to "Build Settings."

Put `/` in "Dockerfile Location" (or whichever directory the Dockerfile is in).

Click "Trigger" to build the repository immediately (without waiting for a git push).

Subsequent builds will happen automatically, thanks to GitHub hooks.
