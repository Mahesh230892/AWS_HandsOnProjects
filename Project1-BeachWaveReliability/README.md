# 🌊 AWS SimuLearn Project – Beach Wave Conditions Page Reliability

This project is part of the AWS SimuLearn training, where I designed and implemented a solution to improve the reliability of a fictional web team's **Beach Wave Conditions** page by migrating it to Amazon S3 static website hosting.

---

## 🧩 Business Scenario

The web team is experiencing reliability issues with their beach wave conditions page. They requested a scalable, cost-effective solution to ensure consistent availability and performance for city residents accessing beach wave data.

---

## 🛠️ Solution Overview

To meet the reliability and scalability requirements, the solution involves migrating the web page to **Amazon S3 static website hosting**, eliminating the need for traditional web server infrastructure.

### ✅ Key Benefits:
- Handles unlimited traffic volumes
- Cost-effective and highly available
- Simplified management with no server maintenance

---

## 🚀 AWS Services Used

- **Amazon S3** – for hosting static website content (HTML, CSS, JS)
- **S3 Bucket Policies** – for access control using JSON-based permissions

---

## 📋 Implementation Steps

1. **Create an S3 Bucket**  
   - Enable static website hosting  
   - Set the root object (e.g., `index.html` or `waves.html`)

2. **Upload Website Files**  
   - HTML file (main page)  
   - Supporting assets (CSS, JS, images)

3. **Configure Bucket Permissions**  
   - Define a bucket policy in JSON format to allow public read access

4. **Access the Website**  
   - Use the S3-generated URL to serve the static content  
   - Browser GET requests retrieve the root object

5. **Optional Customization**  
   - Rename root object from `index.html` to `waves.html`  
   - Update S3 settings to reflect the new filename

---

## 📂 Repository Contents

- `step-by-step-guide.md` – Detailed instructions for implementation
- `waves.html` – Sample root object for beach wave data
- `bucket-policy.json` – Example policy for public access
- `architecture-diagram.png` – Visual overview of the solution

---

## 🙋‍♂️ Author

**MaheshChary**  
Cloud Security Learner | SOC Analyst | AI Governance Enthusiast  
📎 [LinkedIn](https://www.linkedin.com/in/your-profile)  
📘 [GitHub](https://github.com/your-username)

---

This project demonstrates my ability to design scalable, secure, and cost-effective cloud solutions using AWS. It reflects both technical proficiency and real-world problem-solving through simulated customer interaction.
