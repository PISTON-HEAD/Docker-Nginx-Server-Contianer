# IBE Integration – Customer Onboarding Information

This file contains all required information to onboard a new hospital into the IBE Integration Platform. Please fill all mandatory fields carefully before triggering the onboarding pipeline.

---

## 🏥 **1. Customer Details**

| Field                       | Value                          |
| --------------------------- | ------------------------------ |
| **Hospital Name**           | `<enter-hospital-name>`        |
| **Sales Order Number (SO)** | `<enter-sales-order-number>`   |

---

## 🧩 **2. Container Resource Requirements**

### **Compute Resources**

| Resource         | Required Value |
| ---------------- | -------------- |
| **CPU (cores)**  | `<e.g., 2>`    |
| **Memory (Gi)**  | `<e.g., 4Gi>`  |
| **Storage (Gi)** | `<e.g., 50Gi>` |

---

## ⚙️ **3. Deployment Configuration**

| Parameter                | Value                        |
| ------------------------ | ---------------------------- |
| **Namespace**            | `<k8s-namespace>`            |
| **Environment**          | `<dev / qa / stage / prod>`  |
| **Deployment Frequency** | `<daily / weekly / monthly>` |

---

## 🛠 **4. Networking (Optional)**

| Parameter                 | Value                    |
| ------------------------- | ------------------------ |
| **Inbound Ports**         | `<list or N/A>`          |


---

## 📝 **6. Additional Notes**

```
<Add any special requirements, constraints, or custom instructions here>
```

---
