# 💸 ExpensePro Flow – AI-Powered Expense Approval Workflow

> A smart web app that predicts the right approver, covers for people on vacation, and auto-approves routine expenses, so bills get approved faster with far less manual effort.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![BERT](https://img.shields.io/badge/BERT-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📖 Overview

**ExpensePro Flow** takes the waiting out of expense approvals. Staff upload a bill, and the system decides who should approve it, who steps in if the approver is away, and whether the expense is routine enough to approve automatically.

- 🧾 Simple bill submission and tracking
- 🤖 ML-driven routing and decisions
- 🏖️ No more stuck bills when approvers are on leave

---

## 🚀 Key Features

- 🎯 **Predictive Approver Routing**: sends each expense to the right approver using historical data and spending limits
- 🏖️ **Automatic Vacation Substitution**: reroutes bills to a substitute when the approver is away
- ⚡ **Auto-Approval**: instantly approves routine expenses that pass compliance checks
- 🧾 **Expense Dashboard**: upload bills with date, amount, category and image
- ✏️ **Edit Before Review**: update a submitted expense or swap the bill image
- 🚦 **Live Status Tracking**: Pending 🟡 → Approved 🟢 or Rejected 🔴
- 👨‍💼 **Approver Dashboard**: view the bill, then approve or reject in one click
- 🔐 **Secure Login**: role-based access for staff, approvers and substitutes

---

## 👥 User Roles

| Role | What they can do |
|---|---|
| 🙋 **Staff** | Upload bills, edit them, track approval status |
| 👨‍💼 **Approver** | Review bills, approve or reject, mark vacation status |
| 🔄 **Substitute** | Approve bills while the main approver is away |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Core language |
| **Django** | Backend, REST APIs, authentication and UI |
| **BERT** | Understands text and context to support routing decisions |
| **ELECTRA** | Improves predictive routing using patterns in historical data |
| **Git** | Version control |

---

## 📸 Screenshots

| Login | Expense Dashboard | Approver Dashboard |
|:---:|:---:|:---:|
| ![Login](https://github.com/shriniha/SAP/blob/main/Login_Screen.png) | ![Expense Dashboard](https://github.com/shriniha/SAP/blob/main/Expense_Dashboard.png) | ![Approver Dashboard](https://github.com/shriniha/SAP/blob/main/Approver_Dashboard.png) |

---

## 📱 Installation & Setup

### Prerequisites

- Python >= 3.9
- pip
- Git

### Setup Steps

```bash
git clone https://github.com/shriniha/SAP.git
cd SAP
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## 🔮 Future Work

- 📊 Add more factors to the models, such as department needs and performance metrics
- 🔗 Integrate with existing HR systems

---
