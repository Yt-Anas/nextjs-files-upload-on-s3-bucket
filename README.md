# 📁 Next.js File Upload to AWS S3

This project allows users to upload files through a Next.js application.  
Uploaded files are stored in AWS S3 and a public URL is generated for access.

---

## 🚀 Features

- Upload files directly from the browser  
- Store files securely in AWS S3  
- Generate public URL for file access  
- Minimal and user-friendly interface  

---

## 🛠 Tech Stack

- Next.js  
- AWS S3  
- AWS SDK  

---

## 📦 How It Works

1. User selects a file  
2. File is sent to the backend API  
3. Backend uploads the file to AWS S3  
4. S3 returns a public URL  
5. URL is displayed to the user  

---

## 📥 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Yt-Anas/nextjs-files-upload-on-s3-bucket.git
cd nextjs-files-upload-on-s3-bucket

2. Install dependencies
npm install

3. Setup environment variables

Create a .env.local file in the root directory and add:

AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
AWS_REGION=ap-south-1
S3_BUCKET_NAME=your_bucket

4. Run the development server
npm run dev

5. Open in browser

http://localhost:3000

📌 Future Improvements
Use pre-signed URLs for secure file access
Add file type validation
Implement upload progress indicator
Add authentication for users

👤 Author
Mohd Anas
GitHub: https://github.com/Yt-Anas
LinkedIn: https://www.linkedin.com/in/devops-anas/

⭐ Show Your Support
If you like this project, consider giving it a ⭐ on GitHub!

