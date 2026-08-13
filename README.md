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

<img width="1629" height="649" alt="Screenshot from 2026-08-13 17-27-55" src="https://github.com/user-attachments/assets/deca3c70-2b04-40bc-9afe-e8de5825e4c0" />
<img width="1629" height="649" alt="Screenshot from 2026-08-13 17-28-13" src="https://github.com/user-attachments/assets/51402c8b-7eb2-493e-8555-783ce23a7da4" />
<img width="1650" height="690" alt="Screenshot from 2026-08-13 17-29-20" src="https://github.com/user-attachments/assets/c92cd82c-8eda-4d9d-93dd-215a8ab054a7" />
<img width="1650" height="690" alt="Screenshot from 2026-08-13 17-30-18" src="https://github.com/user-attachments/assets/29d80813-b3e7-44e3-a666-4b8baea72c05" />
<img width="1650" height="690" alt="Screenshot from 2026-08-13 17-32-00" src="https://github.com/user-attachments/assets/0625874f-7612-4fa8-8b41-f6e30c0ae8d4" />
<img width="1628" height="493" alt="Screenshot from 2026-08-13 17-34-46" src="https://github.com/user-attachments/assets/678459f1-0383-459a-b079-9c9f2358ce48" />
<img width="1831" height="1014" alt="Screenshot from 2026-08-13 17-36-06" src="https://github.com/user-attachments/assets/025e1271-2d7f-4cdc-aca1-2aa461e02a55" />
<img width="1635" height="393" alt="Screenshot from 2026-08-13 17-36-31" src="https://github.com/user-attachments/assets/a21dd15d-3d01-4457-8e49-ef602c39e1c3" />
<img width="1704" height="852" alt="Screenshot from 2026-08-13 17-37-36" src="https://github.com/user-attachments/assets/ddc72ca9-a737-47da-9d0a-6d5aa7e5c30f" />
<img width="1703" height="392" alt="Screenshot from 2026-08-13 17-38-28" src="https://github.com/user-attachments/assets/0c7d26a6-22b3-41cb-ae25-90c7b05abc8d" />
<img width="1920" height="1080" alt="Screenshot from 2026-08-13 17-39-02" src="https://github.com/user-attachments/assets/b17d2708-6882-48cb-86fe-0389bce54a63" />
<img width="1920" height="1080" alt="Screenshot from 2026-08-13 17-43-47" src="https://github.com/user-attachments/assets/85c6c63e-3463-407d-a9ef-5be7d526fd34" />
<img width="1703" height="392" alt="Screenshot from 2026-08-13 17-45-15" src="https://github.com/user-attachments/assets/9817429f-1e3d-45c2-8043-e092ec29431f" />



