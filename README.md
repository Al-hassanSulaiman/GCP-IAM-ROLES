# GCP-IAM-ROLES
This repository demonstrates how to configure IAM in Google Cloud using the Console.
#scenario
We want to give a user access to Cloud Storage with the **Storage Admin** role.
#steps (console)
1. In your Google Cloud Console,  Go to **IAM & Admin → IAM**
2. Click grant access, Enter the user’s email (e.g., 'alhassnasulaiman5star@gmail.com`), in new principals. The principal's mail is the one that'll have access to your cloud storage. You are not limited to adding 1 principal, you can add as many principal as you wish.
3. select role: storage ->storage admin
4. click save
5. verify the user now appears in the IAM list, with the role assigned
