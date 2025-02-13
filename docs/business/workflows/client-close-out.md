# Client Close-Out Workflow

!!! warning ":construction: Under Construction :construction:"

    This section is still under construction. Facts, information, and data in here may not be complete or accurate yet. 

This workflow documentation outlines the process of closing out a web-development client. It will include a checklist of tasks, templates, and structures to make this process as efficient as possible. 

## 1. Project Deliverables Review

### Overview
Before finalizing a project and handing it over to the client, we conduct a **Project Deliverables Review** to ensure all aspects of the website or application are fully functional, optimized, and meet our quality standards. This step ensures that the client receives a polished, professional product ready for public use.

---

### ✅ Completion Checklist

Use this checklist to verify all essential components before closing out the project:

#### 📌 **General**
- [ ] Website is live and accessible via the **correct domain**
- [ ] SSL certificate is active and properly configured (`https://`)
- [ ] All pages load correctly with no broken links or missing content

#### 🎨 **Design & User Experience**
- [ ] Images are **optimized** (compressed for performance without quality loss)
- [ ] Responsive design functions correctly across **desktop, tablet, and mobile**
- [ ] Website loads in **under 3 seconds** on a standard connection
- [ ] Navigation is intuitive, and no UI elements are misaligned

#### 🔍 **SEO & Analytics**
- [ ] Proper **meta titles and descriptions** are set for each page
- [ ] Images and other tags have appropriate **alt text**
- [ ] **Google Analytics** is installed and tracking user data correctly
- [ ] **Robots.txt and sitemap.xml** are generated and submitted to Google Search Console
- [ ] Open Graph (OG) and Twitter Card tags are implemented for social media previews

#### 🛠 **Functionality**
- [ ] Contact forms submit successfully and send notifications
- [ ] Client login/dashboard (if applicable) is fully operational
- [ ] Any third-party integrations (APIs, CRM, payment processors) function as expected
- [ ] Error pages (`404`, `500`, etc.) are correctly configured and styled

#### 📜 **Legal & Compliance**
- [ ] Privacy Policy and Terms of Service pages are included if required
- [ ] Cookie consent banner is active (if applicable)
- [ ] Accessibility standards (WCAG) are met for inclusivity

---

### 🛡 Quality Assurance (QA) Standards

Before final delivery, the project undergoes **Quality Assurance Testing** to ensure it meets our high standards. The following checks should be performed:

#### 1. **Cross-Browser Testing**  
 - Verify site performance on Chrome, Firefox, Safari, and Edge.
 - Ensure compatibility with both Windows and macOS environments.

#### 2. **Mobile & Tablet Responsiveness**  
   - Test using multiple device screen sizes (can use Chrome DevTools, BrowserStack, or actual devices).
   - Ensure buttons, text, and images scale correctly.

#### 3. **Performance Optimization**  
   - Run a **Google PageSpeed Insights** test and address any major issues.
    - Mobile versions must have higher than 85 score
    - Desktop versions must have higher than 95 score
   - Optimize **CSS, JavaScript, and images** for faster loading.

#### 4. **Security Testing**  
   - Ensure all form inputs are validated to prevent XSS and SQL injection.
   - Check for exposed API keys or sensitive data in the source code.

#### 5. **Final Client Review**  
   - Conduct a walkthrough with the client.
   - Gather feedback and make any last-minute refinements.

---

## 2. Client Approval Process

### Overview  
The **Client Approval Process** is a crucial step before officially closing out the project. This meeting ensures that the client has reviewed the deliverables, tested the functionality, and is satisfied with the outcome. It also provides an opportunity to address any last-minute questions or minor adjustments.

---

### 📅 Scheduling the Final Walkthrough  

To finalize the project, schedule a **Client Approval Meeting** that includes:  

✅ A live walkthrough or recorded video presentation of the final product  
✅ A review of all **Project Deliverables** (checklist completed in the previous step)  
✅ An opportunity for the client to **test functionality** and provide final feedback  

**Best Practices for Scheduling:**  
- **Preferred Format**: Video call (Zoom, Google Meet) or in-person if local  
- **Attendees**: Client, project manager, and key team members  
- **Agenda**: Structured to review final deliverables and next steps  
- **Duration**: 30-60 minutes depending on project complexity  

---

### 📝 Client Approval Process  

Once the walkthrough is complete, obtain **official client approval** to mark the project as complete.  

#### 📌 Approval Options  
1. **Verbal Approval**  
   - Ideal for small projects or clients with ongoing contracts.  
   - Confirm in writing via **email** with a summary of the meeting and next steps.  

2. **Written Approval (Recommended for Final Close-Out)**  
   - Send a **Client Approval Form** that includes:  
     - Final project description  
     - Confirmation that all deliverables meet the agreed-upon requirements  
     - Acknowledgment of transition to post-launch support (if applicable)  
   - Approval can be collected via:  
     - **Email Confirmation** (Client replies “Approved”)  
     - **Digital Signature** (Google Forms, DocuSign, PandaDoc)  

**Example Email for Client Approval:**

```markdown
#### Example Email for Client Approval:

Subject: Final Approval - [Project Name]

Hi [Client's Name],

Thank you for taking the time to review the final version of your [website/application].  
We have completed all project deliverables, and everything is ready for launch.  

Please confirm your approval by replying to this email with “Approved” or by signing the attached approval document.

Next Steps:
- We will proceed with [handover training/post-launch support] as discussed.
- Your project will be considered **officially closed** upon approval.

Let us know if you have any final requests before approval.  

Best,  
[Your Name]  
Dunosis Team

```

---

## 3. Project Documentation

### Overview  
Before closing out a project, ensure that all documentation is properly prepared and accessible to the client. This includes **user manuals, source code documentation, and design specifications**. Providing well-organized documentation enhances the client’s experience, simplifies maintenance, and ensures a smooth transition for any future updates.

---

### 📖 User Manuals & Guides  

The **official project documentation** should be ready and up to date before delivery. This includes: 

✅ An **overview of the system’s functionality**  
✅ Instructions for **managing the website or application**  
✅ Links to **external resources or additional support**  

📌 **Client Documentation Access:**  

Clients should be provided with a direct link to the **official Dunosis documentation page**:  

➡️ **[Dunosis Documentation](https://docs.dunosis.com)**  

Any project-specific manuals should be included in the final delivery folder or as an attached PDF.

---

### 📝 Source Code Documentation  

A well-documented codebase ensures easier maintenance and scalability. Before closing the project, confirm that: 

✅ The **README file** is updated with:  
   - Project description  
   - Installation instructions  
   - Deployment steps  
   - Configuration details (e.g., environment variables)  
✅ Any **inline code comments** are present where necessary to explain complex logic  
✅ API endpoints (if applicable) are documented  

---

### 🎨 Design Specifications

A copy of the final design files should be included in the project handover package. This ensures that the client (or future developers) have access to:

✅ The Figma Design Guide, including typography, colors, and UI components

✅ Final brand assets, such as logos, icons, and illustrations

✅ Any exported assets (SVGs, PNGs, or font files) required for future updates

📌 Deliverable Formats:

 -	Figma File Access: Provide a link to the final design file.
 -	Local File Exports: Deliver high-resolution versions of graphics in Google Drive, Dropbox, or a ZIP archive.

---

## 4. Project Archiving

### Overview  

The **Archiving** process ensures that all project files, assets, and code are securely stored and organized before finalizing the close-out. Proper archiving helps maintain historical records, allows for future retrieval, and provides clients with a structured package of deliverables.

---

### 📂 Organizing & Storing Project Files  

Before completing the project, all relevant files should be stored in a centralized location for historical reference.  

✅ **Backup all project files, including:**  

- Source code and **final commit history**  
- Design files (Figma, logos, branding assets)  
- Documentation (manuals, README, and setup guides)  
- Any other project-related assets (images, videos, fonts, third-party integrations)  

📌 **Storage Location:**  

All files should be **uploaded to Google Drive** under the **Dunosis Historical Content** folder in the corresponding client folder:

➡️ **[Google Drive Archive](https://drive.google.com/your-folder-link-here)**  

**Folder Structure Example:**  

```plaintext
📂 Project_Archive
├── Codebase
│   ├── final_source_code.zip
│   ├── repository_backup.git
│   ├── readme.md
├── Assets
│   ├── branding/
│   ├── images/
│   ├── videos/
├── Documentation
│   ├── project_manual.pdf
│   ├── setup_guide.pdf
├── Design
│   ├── figma_link.txt
│   ├── exported_assets.zip
```

---

### 📦 Bundling the Client Handover Package  

Once all files are organized, create a **final ZIP package** for the client containing:  
✅ **Final Codebase** (excluding unnecessary development files) 

Navigate to the repo directory and use this command to zip the source code and git history.
``` bash
zip -r my_project.zip . -x "*.zip"
``` 
✅ **Documentation** (installation guide, credentials handover, FAQs)  
✅ **Design Assets** (logos, UI elements, exported files)  
✅ **Database Dumps** (if applicable)  

📌 **Delivery Method:**  
- Send via **Google Drive** (preferred)  
- Email the ZIP package (if file size allows)  
- Provide a download link from a **secure cloud storage service**  

---

### 🔒 Privatizing the GitHub Repository  

Once the project is archived and delivered:  

✅ **Change repository visibility to private** (unless agreed otherwise with the client)  
   - Navigate to **GitHub Repo → Settings → Change Repository Visibility**  
   - Confirm the action to restrict future public access  

✅ **Remove external collaborators** (if necessary)  
   - Check **Settings → Manage Access**  
   - Remove non-team members  

✅ **Transfer ownership (if applicable)**  
   - If the client is taking full ownership, transfer the repository to their GitHub organization.  

---

## 5. Collect Final Payment

# Client Close-Out Workflow

## 5️⃣ Collect Final Payment

### Overview  
The **final payment collection** is the last step in closing out a project. Ensuring a smooth and professional payment process helps maintain good client relationships and reinforces your business credibility. This section outlines the available payment methods, invoicing process, and a professional email template for requesting payment.

!!! danger "Important!"
    This step is the MOST important in this entire workflow. It acts as a blocker for the remaining steps. Clients will NOT recieve a ZIP file of the project and the website will be taken down if this payment is not received. 

---

### 💳 Payment Options  

Clients can complete their final payment using any of the following methods:

✅ **Stripe** *(Preferred for Online Payments)*  
   - Secure credit/debit card processing  
   - Client receives an instant receipt  
   - Payment link generated via **Stripe Dashboard**  

✅ **Cash Payment** *(For Local Clients Only)*  
   - Must be confirmed and documented with a receipt  

✅ **POS Terminal** *(For In-Person Transactions)*  
   - Processed through the **Evalon Payment Terminal**  
   - Client receives an emailed receipt  

✅ **Zelle** *(For Direct Bank Transfers)*  
   - Faster than standard bank transfers  
   - No transaction fees  
   - Payments sent to:  
     **[dunosis]**  

---

### 🧾 Invoicing Process  

1. **Generate the Final Invoice**  
   - Use **Odoo Accounting** to create an invoice  
   - Ensure the invoice includes:  
     - **Total Amount Due**  
     - **Payment Due Date**  
     - **Breakdown of Services Rendered**  
     - **Payment Instructions & Accepted Methods**  

2. **Send the Invoice to the Client**  
   - Email the invoice with a clear subject line  
   - Attach a PDF version for easy reference  

3. **Follow Up on Unpaid Invoices**  
   - If no payment is received within **3 business days**, send a **polite reminder**  
   - If overdue, escalate by **calling the client directly**  

---

### 📧 Final Payment Request Email Template  

If you're not discussing payment in person or over the phone, you can use this email template to **professionally request final payment**:

```plaintext
**Subject:** Final Invoice for [Project Name] – Payment Due  

Hi [Client's Name],  

I hope you’re doing well!  

I wanted to follow up regarding the final invoice for [Project Name]. We have now completed all deliverables, and everything is ready for launch. Please find attached the invoice for the final payment of **$[Amount]**, due by [Due Date].  

You can complete the payment using any of the following methods:  
- **Stripe:** [Insert Payment Link]  
- **Zelle:** [Your Zelle Contact Info]  
- **POS Terminal (In-Person Payment)**  
- **Cash (If applicable)**  

Please confirm once the payment has been processed, and let me know if you have any questions.  

Thank you for your partnership on this project—I truly appreciate the opportunity to work with you!  

Best,  
[Your Name]  
Dunosis Team  

```

---

## 6. Transition to Maintenance & Support

### Overview  
Once the project is completed and the final payment is collected, the next step is to transition the client into a **Maintenance & Support Plan** or hand over full control if they choose to manage their own deployment. 

All projects built by Dunosis include **one year of complimentary maintenance and support**, covering:

✅ **Domain management** (renewals, DNS settings)  
✅ **Database and server backups & upgrades**  
✅ **Light content updates** (small text/image changes)  

After the first year, clients can **choose a paid maintenance plan** or take over full responsibility for their site’s upkeep.

---

### 📌 Client Review of Maintenance Options  

Clients can choose from **four levels of ongoing support**:

| Plan | Coverage | Price |
|------|----------|-------|
| **Lite** | Domain management, database backups, and uptime monitoring | $5/month |
| **Basic** | Lite package + light content updates (text/images) | $10/month |
| **Mid** | Basic package + performance optimization and security monitoring | $20/month |
| **Pro** | Mid package + feature updates, integrations, and priority support | $30/month |
| **None** | Client assumes responsibility for hosting, maintenance, and security | Free |

📌 **Clients opting for "None" must:**  
- Handle their own **server updates, security patches, and backups**  
- Renew their **domain and SSL certificates manually**  
- Troubleshoot **any technical issues** independently  

---

### 📅 Scheduling a Follow-Up Plan  

Since Dunosis provides **complimentary maintenance for the first year**, it’s important to schedule a follow-up plan to discuss **ongoing support options**.  

✅ **3-Month Check-In**: Ensure everything is running smoothly  
✅ **6-Month Review**: Discuss content updates, performance, and security improvements  
✅ **9-Month Pre-Renewal Discussion**: Remind the client about their maintenance plan options  
✅ **12-Month Final Review**: If no paid plan is chosen, transition maintenance responsibilities to the client  

---

## 7. Client Relationship Management