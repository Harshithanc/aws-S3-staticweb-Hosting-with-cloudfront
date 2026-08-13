# 🚀 Static Website Hosting using AWS S3 & CloudFront

This project demonstrates how I deployed a static website using **Amazon S3** and delivered it globally using **Amazon CloudFront**.

Through this hands-on project, I learned about static website hosting, S3 bucket permissions, CDN, edge locations, and content delivery.

## 📜 Steps I Performed

### 1. Create an S3 Bucket

* Created an S3 bucket for hosting the static website.
* Configured the required public access settings.

### 2. Configure Static Website Hosting

* Enabled **Static Website Hosting**.
* Set `index.html` as the entry point.

### 3. Upload Website Files

Uploaded:

* HTML files
* CSS files
* JavaScript files
* Images

### 4. Configure Bucket Policy

Added a bucket policy to allow public access to the website objects.

### 5. Test the S3 Website

Accessed the S3 static website endpoint through a web browser.

### 6. Create CloudFront Distribution

* Opened **AWS CloudFront**.
* Created a new distribution.
* Selected the S3 bucket as the origin.
* Configured the distribution settings.
* Selected the required CloudFront price class / edge locations.
* Set `index.html` as the root object.

### 7. Access Website Through CloudFront

After the distribution was deployed, I accessed the website using the **CloudFront distribution domain name**.

## ⚠️ Challenges I Faced

* Images were not loading initially.
* The `images` folder was missing from the S3 bucket.
* Encountered a `404 NoSuchKey` error for `index.html`.
* Had issues with incorrect file paths and folder structure.

## ✅ How I Fixed the Issues

* Uploaded the missing `images` folder.
* Verified the S3 folder and object structure.
* Corrected file paths in the HTML files.
* Verified the bucket policy and public access settings.
* Checked that `index.html` was correctly uploaded.

## 💡 Key Learnings

* Learned how to host a static website using **Amazon S3**.
* Understood how **S3 bucket policies** control access to objects.
* Learned how incorrect object paths can cause `404 NoSuchKey` errors.
* Understood the basic concept of **Content Delivery Networks (CDN)**.
* Learned how **CloudFront edge locations** help deliver content closer to users.
* Gained hands-on experience connecting **S3 with CloudFront**.

## 🎯 AWS Services Used

* Amazon S3
* Amazon CloudFront

## 🚀 Future Improvements

* Configure HTTPS using CloudFront.
* Use **Origin Access Control (OAC)**.
* Keep the S3 bucket private and allow access through CloudFront.
* Automate deployment using GitHub Actions.

---

☁️ **Learning by building — AWS & DevOps**






