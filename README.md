# 🇰🇪 Kenya Life Insurance Premium Calculator

Full-stack web application that calculates life insurance premiums using Kenya Mortality Tables KE 2001–2003 and standard actuarial formulas.

**🔗 Live Demo**: [Add Vercel link here after deployment]  
**📹 60-sec Demo**: [Add Loom link if you record one]

### **Why this exists**
Junior actuarial analysts in Kenya price products using Excel + mortality tables. This app automates the core calculation: present value of benefits vs premiums.

### **Tech Stack**
- **Frontend**: React.js, Tailwind CSS, Chart.js for breakdown
- **Backend**: Node.js, Express.js, REST API
- **Database**: MongoDB for saving quote history
- **Deploy**: Vercel + Render

### **Core Formula Implemented**
Annual Premium = (Sum Assured × A_x:n) / ä_x:n  
Where A_x:n = PV of benefits, ä_x:n = PV of annuity-due  
Based on CS1: Actuarial Statistics, Institute and Faculty of Actuaries

### **Features**
1. Input: Age, Gender, Sum Assured, Term, Interest Rate
2. Output: Annual, Semi-annual, Monthly premium + breakdown chart
3. Compare: Side-by-side quotes for different terms
4. Export: PDF quote download

### **Roadmap**
- [ ] Add riders: Critical illness, Disability
- [ ] M-Pesa integration for premium payment simulation
- [ ] Admin upload for updated mortality tables

### **Built by**
Joel Cornellius  
Full Stack Developer @ Modcom Institute of Technology  
Future BSc Actuarial Science + IT @ Maseno University, 2026

**Open to**: June–Aug 2026 attachments in insurtech, insurance, banking IT  
**Contact**: joelnyabera13@gmail.com | 0725415142

---
*This project demonstrates intersection of software engineering + actuarial science for the Kenyan market.*
