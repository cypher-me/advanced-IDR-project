# **Advanced Intrusion Detection System (IDS) with Web Dashboard**  
*A School Project by Emmanuel Ngugi*  

**🏫 Course:** Bachelor of Science in Information Security and Forensics (BISF)  
**🏛️ University:** KCA University  
**📅 Year:** 2025  

---

## **📌 Project Overview**  
This project is an **enhanced Intrusion Detection System (IDS)** with:  
✅ **Python-based detection engine** (Scapy, YARA, Regex)  
✅ **Flask (Python) backend** for processing alerts  
✅ **React.js frontend** for real-time attack visualization  
✅ **PostgreSQL database** for logging  

**Key Features:**  
- Real-time **network traffic analysis**  
- **Log monitoring** (SSH, HTTP, auth logs)  
- **Interactive dashboard** (attack maps, threat statistics)  
- **User authentication** (JWT-based login)  

*(Developed as part of my **school project** for ICT Project Management.)*  

---

## **🛠️ Tech Stack**  
| **Component**       | **Technology**               |  
|---------------------|-----------------------------|  
| **Frontend**        | React.js, Chart.js, MUI     |  
| **Backend**         | Flask (Python)              |  
| **Database**        | PostgreSQL                  |  
| **Detection Engine**| Scapy, YARA, Regex          |  
| **Authentication**  | JWT (JSON Web Tokens)       |  
| **Deployment**      | Docker                      |  

---

## **⚙️ Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/cypher-me/advanced-IDR-project.git  
cd advanced-IDR-project  
```

### **2. Backend Setup (Flask)**  
```bash
cd backend  
pip install -r requirements.txt  
flask run  # Runs on http://localhost:5000  
```

### **3. Frontend Setup (React)**  
```bash
cd frontend  
npm install  
npm start  # Runs on http://localhost:3000  
```
---

## **📂 Project Structure**  
```
advanced-IDR-project/  
├── backend/                  # Flask server  
│   ├── app.py                # Main Flask app  
│   ├── detection_engine/     # Scapy/YARA logic  
│   ├── models/               # SQLAlchemy DB models  
│   └── requirements.txt  
├── frontend/                 # React dashboard  
│   ├── src/  
│   │   ├── components/       # React UI  
│   │   ├── pages/            # Dashboard views  
│   │   └── App.js  
│   └── package.json  
├── docs/                     # School project report  
├── Dockerfile                # Containerization  
└── README.md  
```

---

## **🎓 School Project Deliverables**  
This project was developed for **academic purposes** and includes:  
📄 **Project Report** (`docs/report.pdf`)  
📊 **Presentation Slides** (`docs/presentation.pptx`)  
📹 **Demo Video** (Link in submission)  

**Objectives Met:**  
✔ Implemented **real-time attack detection**  
✔ Built a **secure web dashboard** (JWT auth)  
✔ Tested on **Ubuntu Server VM** for low-cost deployment  

---

## **📊 Features for Academic Evaluation**  

### **1. Real-Time Attack Dashboard**  
- **Live attack maps** (IP geolocation)  
- **Threat severity charts** (Chart.js)  
- **Filterable logs** (React Table)  


### **2. User Authentication**  
- **Role-based access** (Admin vs. Viewer)  
- **JWT token security**  

### **3. Automated Reporting**  
- **Weekly PDF reports** (for faculty review)  
- **CSV export** of attack logs  

---

## **🚀 Deployment Options**  

### **1. Local Development**  
```bash
# Run Flask backend  
cd backend && flask run  

# Run React frontend  
cd frontend && npm start  
```

### **2. Docker (Recommended)**  
```bash
docker-compose up --build  
```
*(Access at `http://localhost:3454`)*  

---
## **✅ Project TODOs**  

### **🔐 Authentication**  
- [ ] **Implement SSH Key Authentication**  
  - [ ] Add Ed25519 key pair generation in React frontend  
  - [ ] Create Flask endpoint for public key validation/storage  
  - [ ] Replace JWT middleware with SSH key verification  
  - [ ] Add key revocation mechanism  

### **📊 Dashboard Migration**  
- [ ] **Replace React Dashboard with Grafana**  
  - [ ] Set up Prometheus + Grafana containers (`docker-compose`)  
  - [ ] Instrument Flask backend with Prometheus metrics  
  - [ ] Build Grafana dashboards for:  
    - [ ] Attack heatmaps  
    - [ ] Traffic analysis  
    - [ ] Real-time alert streams  

### **🛡️ Security Enhancements**  
- [ ] Add Suricata rule import support  
- [ ] Implement automated IP blocking (iptables integration)  
- [ ] Set up fail2ban-style protection for SSH/Flask  

### **📦 Deployment**  
- [ ] Optimize Docker image for Raspberry Pi  
- [ ] Write Ansible playbook for automated Pi deployment  

### **📝 Academic Requirements**  
- [ ] Compare SSH vs JWT auth in project report  
- [ ] Benchmark Grafana vs React performance  
- [ ] Document attack detection false positives/negatives  

---

## **📜 License**  
**MIT License**  

---

## **📈 Future Work (For Research)**  
🔹 **Integrate machine learning** (Anomaly detection)  
🔹 **Expand detection rules** (Suricata-compatible)  
🔹 **Publish research paper** on findings  

---

## **📌 References & Citations**  
1. Scapy Documentation - https://scapy.readthedocs.io/  
2. OWASP IDS Guidelines - https://owasp.org/  
3. KCA University Cybersecurity Course Materials  

---

**👨‍🎓 Developed by Emmanuel Ngugi(cypher-me)**  
**📧 Contact: emmanuelngugi8@outlook.com**  
**🔗 GitHub: [https://github.com/cypher-me](https://github.com/cypher-me)**  

**🌟 Star this repo if you find it useful !**  

--- 

