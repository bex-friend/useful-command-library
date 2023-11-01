# Create Your Own Data Repository

## Overview
This README provides a step-by-step guide on how to create your own personal data repository using Google Cloud Storage.

## Prerequisites
- Google Cloud account
- Google Cloud SDK installed on your computer

## Steps

### Step 1: Login to Google Cloud Console
- Go to [Google Cloud Console](https://console.cloud.google.com/).
- Log in if you're not already logged in.

### Step 2: Navigate to Storage
- Click on the hamburger menu (three horizontal lines) in the top-left corner.
- Find and click on "Storage," then click on "Browser."

### Step 3: Create a New Bucket
- Click on the "Create Bucket" button.
- Follow the on-screen instructions to name and configure your bucket.

### Step 4: Create Folders Inside the Bucket
- Click on your newly created bucket.
- Inside, click on "Create Folder" to start organizing your data into folders.

### Step 5: Upload Files
- Inside each folder, you can click on "Upload Files" to start uploading your data.

### Step 6: Set Permissions
- For each folder or file, click on the three dots next to it and choose "Edit permissions" to set who can view or edit it.

### Step 7: Install Google Cloud SDK (if not already done)
- Download and install the [Google Cloud SDK](https://cloud.google.com/sdk/docs/install).

### Step 8: Basic Commands to Interact with Your Bucket
- To upload a file: `gsutil cp [LOCAL_FILE_PATH] gs://[BUCKET_NAME]/[REMOTE_FOLDER]/`
- To download a file: `gsutil cp gs://[BUCKET_NAME]/[REMOTE_FOLDER]/[FILE_NAME] [LOCAL_FOLDER]`
- To delete a file: `gsutil rm gs://[BUCKET_NAME]/[REMOTE_FOLDER]/[FILE_NAME]`

## Caution
- Be careful when using the `gsutil rm` command as it will permanently delete your files.

## Conclusion
Congratulations! You've successfully created your own personal data repository in Google Cloud Storage. You can now upload, download, and manage your data securely.
