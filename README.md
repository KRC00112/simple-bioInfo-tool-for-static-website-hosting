# Secure Cloud-Hosted Bioinformatics Web App

## 📘 Project Overview

This project demonstrates how to deploy a static web application using a secure cloud architecture that prevents direct access to storage while improving performance through caching.

The application analyzes biological nucleotide sequences and determines whether the input is **DNA or RNA**. It also performs basic sequence analysis such as:

- generating complementary sequences
- counting codons
- translating protein sequences
- visualizing nucleotide and amino acid distributions

---

## ☁️ Deployment Architecture Benefits

The deployment architecture ensures:

- ✅ **Private origin storage** (not publicly accessible)
- ✅ **Fast global delivery** through CDN edge caching
- ✅ **Secure resource access** using origin restrictions
- ✅ **Reduced origin requests** through caching, improving performance and efficiency

---

## ☁️ Cloud Architecture

### ⚙️ Technologies Used

#### Frontend
- React (Vite) — component-based UI architecture
- JavaScript — sequence processing and validation logic
- CSS — layout and styling

#### Cloud & Deployment
- **Amazon S3** — hosts static website files
- **S3 Bucket Policies** — enforce secure access permissions
- **Amazon CloudFront** — global CDN distribution and caching
- **Origin Access Control (OAC)** — restricts direct access to S3 origin

#### Development Tools
- Node.js & npm
- Git & GitHub

---
