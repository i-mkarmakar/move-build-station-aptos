# 🩺 Decentralized Imaging Report Registry

## 📌 Project Title
**Decentralized Imaging Report Registry using Move and Aptos Blockchain**

## 📖 Project Description
This project provides a blockchain-based solution to securely store and access medical imaging reports in a decentralized manner. It enables healthcare professionals to upload reports and ensures that only the intended patients can view them. Built using the Move language on the Aptos blockchain, the system promotes transparency, ownership, and immutability of critical medical records.

## 🎯 Project Vision
To create a trusted and tamper-proof registry for medical imaging reports where:
- Doctors can upload patient-specific reports.
- Patients have exclusive access to view their reports.
- The system is transparent, secure, and censorship-resistant.
- Health data privacy and ownership are preserved using blockchain principles.

## 🚀 Future Scope
- ✅ Add support for storing **multiple reports per patient** using vectors.
- 🔐 Implement **encryption or hashing** for report URLs to protect sensitive data.
- 👥 Introduce **role-based access control** for doctors and patients.
- 🕒 Include **timestamps** to track report history and updates.
- 🗂 Enable **report categorization** (e.g., X-ray, MRI, CT Scan).
- 📊 Provide **analytics** and audit logs for medical institutions.

## 📜 Contract Details
- **Module Name**: `ImagingReportRegistry`
- **Functions**:
  - `upload_report(doctor, patient, report_url)` — Uploads a new imaging report.
  - `view_report(requester, doctor_address)` — Allows a patient to view their report if authorized.
- **Contract Address**: `0x<your_contract_address_here>`

> `0x59ab37cd2507dddc15482efe39e441df5220b0bdcc024dcea3414d9d52b1d00captos`
> 
> ```bash
> aptos account show --profile default
> ```

---

Feel free to contribute or raise issues for improvements.
