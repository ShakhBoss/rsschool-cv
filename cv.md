# Shakhbozjon Tursunboyev

📞 +998 94 445 19 99  
✉️ shakhboztursunboev@gmail.com  
📍 Tashkent, Uzbekistan  
🔗 [GitHub](https://github.com/ShakhBoss)

---

## Summary
I have extensive experience in designing and implementing scalable server-side applications using Node.js.  
Proficient with frameworks like **Express** and **Nest.js**, as well as **PostgreSQL** and **Prisma** for database management.  
Skilled in deploying applications on **DigitalOcean** and configuring **Nginx** for optimal performance.  
Passionate about writing efficient, secure, and maintainable code.

---

## Skills
- **Programming Languages**: JavaScript, TypeScript  
- **Databases**: PostgreSQL, MongoDB, MySQL, Redis, Prisma  
- **Frameworks**: Node.js, Express.js, Nest.js  
- **Cloud & DevOps**: AWS, DigitalOcean, TimeWeb, Docker, NGINX  
- **API & Tools**: Swagger, Postman, GraphQL  
- **Version Control**: GitHub, Git, GitLab  

---

## Experience

### Software Engineer — Kimyo International University  
📍 Tashkent, Uzbekistan | 🗓 07/2024 – Present  
- Worked on **Smart Home Project** using Node.js, Express.js, Prisma, MQTT, Raspberry Pi, and Docker.  
- Developed and integrated various components of the smart home system.  
- Focused on efficient communication and seamless operation between devices.  

---

### Internship Program — Robbit  
📍 Tashkent, Uzbekistan | 🗓 07/2024 – 08/2024  
- Learning about robotics, focusing on programming, sensor integration, and robotic systems.  
- Enhanced knowledge of both hardware and software aspects of robotics.  

---

### Teacher — Kimyo International University  
📍 Tashkent, Uzbekistan | 🗓 02/2023 – Present  
- Teaching courses on **Programmable Logic Controllers (PLC)** and **MATLAB**.  
- Developed and delivered lectures, created lab sessions, and guided students.  

---

### Lab Assistant — Kimyo International University  
📍 Tashkent, Uzbekistan | 🗓 09/2021 – 02/2023  
- Worked on projects involving **3D modeling and design** using **SolidWorks** and **Siemens NX**.  
- Supported project development, created detailed 3D models, and assisted with technical design and simulation tasks.  

---

## Education

- 🎓 **MSc — Robotics and Mechatronics**  
  Kimyo International University, Tashkent, Uzbekistan | 06/2024  

- 🎓 **MSc — Engineering Technology, Mechanics and Mechanical Engineering**  
  Riga Technical University, Riga, Latvia | 06/2023  

- 🎓 **BSc — Renewable Energy**  
  Yeoju Technical Institute, Tashkent, Uzbekistan | 06/2022  

---

## Languages
- English  
- Russian  

---

## Certificates
- Najot Ta’lim  
- SAP  

---

## Code Examples

### Example 1 — Express.js API
```javascript
const express = require("express");
const app = express();

app.use(express.json());

// Simple API endpoint
app.get("/api/hello", (req, res) => {
  res.json({ message: "Hello, RS School!" });
});

// Start server
app.listen(3000, () => {
  console.log("Server is running on port 3000");
});
