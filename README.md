# AWS-Cloud-Practitioner-Essentials

---

## 🌩️ Questions & Answers

### 1️⃣ Client-Server Model
**Q:** Which statement BEST describes the client-server model and its relationship to cloud computing?  
**A:** In the client-server model, the client sends requests to the server, which processes them and sends back responses. Cloud computing provides scalable server resources accessible over the internet.  
**Explanation:** Cloud computing builds on the client-server model, offering elastic, on-demand servers worldwide.

---

### 2️⃣ Shared Responsibility (Physical Security)
**Q:** Who secures the physical infrastructure in AWS Cloud?  
**A:** AWS is responsible for securing the physical infrastructure, and the company secures its data and applications within the cloud.  
**Explanation:** AWS handles data centers and hardware; customers handle data, apps, and access controls.

---

### 3️⃣ AWS Global Infrastructure Benefits
**Q:** Which AWS Global Infrastructure benefits improve performance and reliability? *(Select TWO)*  
- **A:** Fault tolerance  
- **A:** High availability  
**Explanation:** AWS Regions and Availability Zones ensure apps stay online and resilient against failures.

---

### 4️⃣ Customer Responsibility in Security
**Q:** What are the customer’s responsibilities in AWS? *(Select TWO)*  
- **A:** Managing operating system (OS) patches  
- **A:** Encrypting client-side data  
**Explanation:** Customers manage what’s *in* the cloud (OS, apps, data); AWS manages the cloud (hardware, data centers).

---

### 5️⃣ Cloud Advantage for Cost Reduction
**Q:** Which cloud advantage helps lower operational costs?  
**A:** Stop spending money running and maintaining data centers.  
**Explanation:** Cloud eliminates the need to own and maintain physical infrastructure.

---

### 6️⃣ EC2 Instance Type for Rendering
**Q:** Which EC2 instance type is best for visual effects rendering?  
**A:** Accelerated computing  
**Explanation:** GPU-based instances are ideal for high-performance tasks like simulations and rendering.

---

### 7️⃣ Compute Resource Provisioning
**Q:** How are compute resources managed in the cloud?  
**A:** Resources are provisioned based on demand, allowing for scaling and management.  
**Explanation:** Cloud resources scale automatically up or down to match workload needs.

---

### 8️⃣ Notification System for Bug Reports
**Q:** Which service should notify the team immediately when a new bug is reported?  
**A:** Amazon Simple Notification Service (Amazon SNS)  
**Explanation:** SNS sends instant notifications (email, SMS, or API) to subscribers.

---

### 9️⃣ Amazon EC2 Auto Scaling Function
**Q:** How does Amazon EC2 Auto Scaling work?  
**A:** Automatically adds or removes instances based on performance data and metrics.  
**Explanation:** Maintains performance and cost efficiency by scaling up or down automatically.

---

### 🔟 GUI Management Tool
**Q:** Which tool provides a graphical user interface to manage AWS services?  
**A:** AWS Management Console  
**Explanation:** A web-based GUI for creating, managing, and monitoring AWS resources.

---

### 11️⃣ Cost Optimization with Savings Plans & Spot
**Q:** How should a company combine EC2 Savings Plans and Spot Instances?  
**A:** Use Savings Plans for critical workloads and Spot Instances for jobs that are not time-sensitive.  
**Explanation:** Combine predictable-cost Savings Plans with low-cost Spot for flexible workloads.

---

### 12️⃣ Multi-Tenancy Concept
**Q:** What does multi-tenancy mean in Amazon EC2?  
**A:** Multiple users share the same EC2 hardware while maintaining isolation.  
**Explanation:** AWS uses virtualization to securely share physical infrastructure among customers.

---

### 13️⃣ General Purpose Instance Reason
**Q:** Why choose general purpose EC2 instances for a web app?  
**A:** They provide a balanced mix of compute, memory, and networking at efficient cost.  
**Explanation:** Ideal for web servers, development environments, and small databases.

---

### 14️⃣ Loosely Coupled Architecture
**Q:** What happens if one component fails in a loosely coupled system?  
**A:** The system continues functioning as other components are independent.  
**Explanation:** Loosely coupled systems reduce dependency and increase fault tolerance.

---

### 15️⃣ Cost Optimization for Predictable Workloads
**Q:** Which option is best for 3-year predictable workloads?  
**A:** Reserved Instances  
**Explanation:** Long-term commitment offers deep discounts for steady-state workloads.

---

### 16️⃣ EC2 Auto Scaling + ELB
**Q:** How do EC2 Auto Scaling and ELB work together?  
**A:** Auto Scaling adjusts the number of instances, and ELB distributes traffic across them.  
**Explanation:** Together they maintain performance and availability automatically.

**Diagram:**  
![Auto Scaling + ELB Diagram](https://via.placeholder.com/600x300?text=Auto+Scaling+%2B+ELB+Diagram)  
*Illustrates how traffic is balanced across Auto Scaling instances.*

---

### 17️⃣ Compute-Optimized Instances Use Case
**Q:** Why are compute-optimized instances ideal for climate simulations?  
**A:** They are ideal for tasks that require significant CPU power to perform computations.  
**Explanation:** Perfect for scientific modeling, HPC, and data analysis that need strong CPU performance.

---

## 🔹 EC2 Instance Type Cheat Sheet (Visual Reference)

| Instance Type        | Best Use Case |
|---------------------|---------------|
| General Purpose (T3, M5) | Balanced CPU, memory, networking; web servers, dev/test |
| Compute Optimized (C5, C6i) | CPU-intensive workloads; HPC, batch processing, simulations |
| Memory Optimized (R5, X1) | Memory-intensive workloads; databases, analytics |
| Accelerated Computing (P4, G5) | GPU/FPGA tasks; ML training, rendering |
| Storage Optimized (I3, D2) | High storage throughput; large databases, big data |

**Diagram Placeholder:**  
![EC2 Instance Types](https://via.placeholder.com/600x300?text=EC2+Instance+Types+Diagram)

---

## 🔹 SNS vs SQS

| Service | Type | Use Case |
|---------|------|---------|
| Amazon SNS | Pub/Sub | Push notifications to multiple subscribers instantly |
| Amazon SQS | Message Queue | Pull-based message processing; decouples components |

**Diagram Placeholder:**  
![SNS vs SQS](https://via.placeholder.com/600x300?text=SNS+vs+SQS+Diagram)

---


