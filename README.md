# 🌐 AWS Static Website Hosting – Portfolio Hosting Project

This project documents how I hosted my personal portfolio (from [Portfolio Repo](https://github.com/ayushdubey025/Portfolio)) using various AWS services:

- **Amazon S3**
- **CloudFront**
- **ACM (SSL)**
- **(Optional) Route 53**

---

## 🚀 Live Website

🔗 [Click here to view my live portfolio](https://your-domain.com)  
🔗 [Portfolio Source Code](https://github.com/ayushdubey025/Portfolio)

---

## 🛠️ Services Used

- **Amazon S3** – For static website hosting
- **CloudFront** – To distribute the site globally & enable HTTPS
- **ACM** – To issue a free SSL certificate
- **Route 53** *(Optional)* – For domain registration or DNS routing
- **IAM** – For configuring permissions and access

---

## 📸 Screenshots

| Step               | Screenshot                           |
|--------------------|--------------------------------------|
| S3 Static Hosting  | ![](screenshots/s3-settings.png)     |
| CloudFront Setup   | ![](screenshots/cloudfront.png)      |
| SSL via ACM        | ![](screenshots/acm.png)             |
| Route 53 (optional)| ![](screenshots/route53.png)         |

---

## 🔧 Deployment Steps

1. Uploaded files from `Portfolio` repo to an S3 bucket
2. Enabled static website hosting in S3
3. Made bucket public (with proper bucket policy)
4. Created CloudFront distribution with S3 bucket as origin
5. Requested SSL certificate in ACM and attached it to CloudFront
6. (Optional) Connected Route 53 domain for custom URL

---

## 🧠 What I Learned

- Hosting static sites securely with AWS
- Using CloudFront and ACM for HTTPS
- Understanding permissions with IAM
- Deploying real-world cloud infrastructure for web projects

---

## 📁 Project Structure

