# Incident-Flow
# 🚀 **Incident Flow: Automated Incident Assignment & Notification System**

## 📌 **Project Overview**
This project automates the assignment of incidents related to **Strawberry Fone issues** to the appropriate **Strawberry Support** team within **ServiceNow**. Additionally, it configures email notifications for critical incidents, ensuring rapid response and efficient incident resolution.

## 🔥 **Why This is Needed?**
Manually assigning incidents can lead to:
- Delays in resolution
- Misassignment to incorrect support teams
- Lack of immediate attention for critical issues

By automating the assignment and email notifications, this project **reduces manual intervention**, improves efficiency, and ensures **timely resolution** of incidents.

---

## 🛠 **Project Features**
### ✅ **Incident Auto-Assignment**
- Incidents related to **Strawberry Fone** are automatically assigned to the correct **support group** based on predefined rules.
- Uses **ServiceNow's baseline assignment feature** for seamless routing.

### 📩 **Email Notification for Critical Incidents**
- Sends automated email alerts when an incident is marked as **critical**, ensuring urgent attention.
- Configurable to notify relevant team members based on severity level.

---

## 🏗 **Step-by-Step Implementation**
### **1️⃣ Login to ServiceNow Developer Instance**
- Go to [ServiceNow Developer Portal](https://developer.servicenow.com/)
- Sign in with your credentials.
- Click **Start Building** and access your instance.

### **2️⃣ Creating Services and Service Offerings**
1. Navigate to **All > Configuration > Services**
2. Click **New**, enter details for **Strawberry Fone**, and click **Save**
3. Scroll to **Offerings**, create new offerings, and submit.
4. Verify under **All > Configurations > Service Offerings**.

### **3️⃣ Creating the Strawberry Fone Support Group**
1. Navigate to **All > Users and Groups > Groups**
2. Click **New**, enter **Strawberry Fone Support**, and click **Submit**
3. Open the created group, go to **Group Members**, and add users.

### **4️⃣ Setting Up Assignment Rule**
1. Navigate to **All > Assignment**
2. Click **New**, enter rule details, and click **Save**
3. Under **Applies To**, configure assignment conditions
4. Under **Assign To**, select the **Strawberry Fone Support** group

### **5️⃣ Testing Auto-Assignment**
1. Navigate to **All > Incident > Open > New**
2. Enter details but **leave Assignment Group empty**
3. Click **Save**, and the system will automatically assign the correct group

### **6️⃣ Setting Up Email Notifications for Critical Incidents**
1. Navigate to **All > System Notifications > Email > Notifications**
2. Click **New**, enter details, and click **Save**
3. Under **When to Send**, define conditions for **Critical Incidents**
4. Under **Who Will Receive**, specify recipients
5. Click **Update**
6. Test by creating a **critical** incident and verifying email notifications under **All > Outbox**

---

## 🎯 **Verification & Testing**
1. **Impersonate a user** assigned to the Strawberry Support group
2. Go to **Incident > Open**, check if incidents are correctly assigned
3. Verify email notifications for critical incidents under **All > Outbox**

---

## 📌 **Conclusion**
This project successfully automates **incident assignment** and **critical incident notifications** within **ServiceNow**. By leveraging **baseline assignment rules and email alerts**, it reduces manual workload, minimizes errors, and ensures faster resolution times.

---

## ✍️ **Author**
- **Ashish Kodumuru**
- 📅 **Date of Documentation**: November 11, 2024

---

# Documentation
Here is the detailed step by step demonstration for the above 
[Document](https://automated-incident-assignment-and-notification-system.hashnode.space/default-guide/what-are-we-going-to-do)

