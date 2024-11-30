# Warranty Claim Request App

## Overview
The Warranty Claim Request App is a comprehensive PowerApps-based solution designed to simplify and streamline the process of submitting and managing warranty claims. Users can provide detailed claim information, upload supporting images and videos, and receive feedback from admins. The app also includes a secure admin login page with user credential validation for administrators to review claims and provide feedback effectively.

---

## Features
- **Dynamic Warranty Claim Form**:
  - Capture essential warranty claim details, including:
    - Product Information
    - Claim Description
    - Customer Details
    - Warranty Tracking Code (auto-generated in ddmmyy-hhmmss format)
- **Media Uploads**:
  - Users can upload images and provide video links to support their warranty claims.
- **Admin Panel**:
  - A secure admin login page with credential validation for admins.
  - Admins can view, review, and provide feedback on claims submitted by users.
- **Feedback Mechanism**:
  - Admins can provide detailed feedback, which is stored and displayed for users.
- **Document and Media Management**:
  - Uploaded images and video links are stored in a SharePoint Document Library for centralized access using Power Automate.
- **Automated Email Notifications**:
  - Notify relevant personnel when a new warranty claim is submitted.
  - Emails include claim details, uploaded media links, and admin feedback.
- **Data Storage**:
  - Claim details are stored in an Excel file for tracking and reporting.
  - Media and documentation are securely stored in SharePoint.
- **User-Friendly Interface**:
  - Intuitive design for both users and admins to navigate and perform tasks efficiently.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **Microsoft Power Automate**:
  - Automated email notifications and document uploads
- **Excel**:
  - Data storage for claim tracking
- **SharePoint**:
  - Backend for document and media storage
- **Office 365 Outlook Integration**:
  - Email functionality

---

## How It Works
1. **Claim Submission**:
   - Users fill out the warranty claim form with all required details, including uploaded images and video links.
   - Data is stored in Excel, and uploaded media is saved to a SharePoint Document Library.
2. **Admin Review**:
   - Admins log in through the secure admin panel to review claims.
   - Admins can provide feedback, which is saved and displayed for users in the app.
3. **Media and Documentation**:
   - Supporting images and video links are stored in SharePoint using Power Automate flows.
4. **Automated Notifications**:
   - Email notifications are sent to the relevant team, including details of the claim, uploaded media links, and feedback.
5. **Unique Tracking**:
   - Each claim is assigned a unique warranty tracking code for efficient tracking and follow-up.

---

## Benefits
- Simplifies warranty claim submissions with a user-friendly interface.
- Enhances claim visibility with image and video uploads.
- Improves communication with automated notifications and feedback sharing.
- Provides secure access for admins with credential validation.
- Centralized media storage for better traceability.

---

## Future Enhancements
- Integration with Power BI for advanced analytics and reporting.
- Workflow automation for multi-level claim approvals.
- Enhanced notification features, such as SMS alerts.

---

