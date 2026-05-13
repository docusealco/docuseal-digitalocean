# DocuSeal DigitalOcean

The deploy button for the DigitalOcean platform. [DocuSeal](https://www.docuseal.com/) is an open source DocuSign alternative.

[![Deploy on DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/docusealco/docuseal-digitalocean/tree/master&refcode=421d50f53990)

## How to use

- Click the "Deploy to DigitalOcean" button above
- Follow the DigitalOcean instructions until the **"Environment Variables"** step
- Click **"Edit"** on the **"Environment Variables"** step
- Set the **SECRET_KEY_BASE** variable to a random value. You can generate one with `openssl rand -hex 64` or any other way you like
- Follow the remaining instructions provided by DigitalOcean
- DocuSeal will be available as soon as the build is completed

## How to update

**Step 1: Open the dashboard and select the deployed DocuSeal instance**

Go to `https://cloud.digitalocean.com/apps` and select your DocuSeal app.

**Step 2: Force rebuild and deploy**

Click the "Actions" drop-down menu and select "Force rebuild and deploy". Follow the instructions in the dialog that appears.

<img src="https://github.com/user-attachments/assets/2f261f26-b39e-4f41-988d-9da363f2d135" width="600">

**Step 3: Wait for the deployment to complete**

Once the deployment is finished, DocuSeal will be running with the latest version.
