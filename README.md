# AWS S3 Static Website Hosting

This project demonstrates how to host a simple static website using AWS S3 with only an HTML file.

#Steps to Deploy

### 1 Create an S3 Bucket  
- Go to the AWS S3 Console  
- Click **Create bucket**  
- Enter a **unique bucket name** (e.g., `my-static-site`)  
- Select **Region**  
- **Uncheck "Block all public access"**  
- Click **Create bucket**  

### 2 Upload HTML File  
- Open the **S3 bucket**  
- Click **Upload**  
- Drag and drop your `index.html` file  
- Click **Upload**  

### 3 Enable Static Website Hosting  
- Go to **Properties** → **Static Website Hosting**  
- Click **Edit** and enable  
- Set:  
  - **Index document:** `index.html`  
- Save the settings  

## Author  
Gokul
