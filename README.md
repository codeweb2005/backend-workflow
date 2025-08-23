<h1>Open the Backend Folder</h1>
<img src="https://github.com/user-attachments/assets/2668fee4-48e6-4f88-84b2-f21c30f1747e" alt="Backend Folder Structure" width="500" />

<p>We need to navigate to the <strong>service</strong> folder inside the backend directory and upload its contents to <strong>Docker Hub</strong> or <strong>Amazon ECR</strong>.</p>

<img src="https://github.com/user-attachments/assets/de7ae018-c6b3-4273-9a09-1678865fc910" alt="Upload Image to Docker/ECR" width="400" />

<h2>Replace the Image Links</h2>
<p>Go to the files above and replace the existing image link with your own Docker or ECR image link.</p>

<img src="https://github.com/user-attachments/assets/745521a2-46e1-401e-be9a-03abc8d5b73a" alt="Update Image Links" width="500" />

<h2>Update Secrets</h2>
<p>The most important step is to update the <strong>secrets</strong> so that they match your environment.</p>

<img src="https://github.com/user-attachments/assets/925a223a-62a9-40f3-a80b-aea06e8419f5" alt="Update Secrets" width="600" />

<h2>Deploy the Manifest</h2>
<p>Simply run <code>git push</code>; this will trigger the GitHub Actions workflow and deploy the Manifest.</p>

<img src="https://github.com/user-attachments/assets/b2152807-14d1-4299-b112-c50d82866bfc" alt="GitHub Actions Deployment" width="700" />
