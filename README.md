# azure-custom-role-controlplane-dataplane
This repository demonstrates the concept of the **Control Plane and Data Plane** in Azure, with a hands-on lab that includes the creation and assignment of a **custom role** based on specific access requirements.


# 🔐 Azure Custom Role | Control Plane vs Data Plane Explained

---

## 🧠 Key Concepts

### ✅ Control Plane
The Control Plane governs **who can manage** the Azure resource (create, delete, update configurations).

> Think of it as **managing the resource** itself (e.g., create VM, delete storage account, assign roles).

---

### ✅ Data Plane
The Data Plane controls **access to the data** within the resource.

> Think of it as **working with the content/data** stored (e.g., reading from blob storage, accessing secrets in a Key Vault).

---

## 🧱 Why Custom Roles?

Azure provides many built-in roles, but sometimes they are **too broad or too restrictive**. In such cases, you need to:

- Define only the exact permissions required (least privilege)
- Control both control and data plane operations precisely
- Meet **specific business or compliance requirements**

---

## 🧪 What This Lab Demonstrates

✔️ Creating a **custom Azure role** with selected permissions  
✔️ Assigning the custom role to a user  
✔️ Understanding **how that role affects access** at both the control and data plane level  
✔️ Working with role scope and definitions

---

## 📸 Screenshots

azure-custom-role-controlplane-dataplane/
│
├── README.md
├── screenshots/
│   ├── custom-role-definition.png
│   ├── custom-role-assignment.png
│   └── control-vs-data-plane.png
└── custom-role-template.json     # JSON definition of the custom role

---

## 🧰 Files Included

- `custom-role-template.json` → JSON template used to define the custom Azure role.

---

## 💬 Summary

- The **Control Plane** decides *who can manage* resources.
- The **Data Plane** controls *who can use or interact* with the data.
- Creating **custom roles** helps implement **least privilege access** that better suits real-world scenarios.

---

## 🧠 Motivation

> Not every client or organization fits perfectly within predefined Azure roles.  
> That’s why it’s critical to learn how to customize access so that you **deliver secure and specific access models** that meet your goals.

---

## 🚀 More Coming Soon

This lab is part of a larger series exploring:

- Role-Based Access Control (RBAC)
- Azure Governance
- Identity and Access in Entra ID

Stay tuned for more!
