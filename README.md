from pathlib import Path
src = Path("/mnt/data/Pasted markdown(3).md")
out = Path("/mnt/data/Angad_Kumar_Minimal_Professional_GitHub_README.md")

text = """# Angad Kumar

**Full-Stack Developer · Backend & Mobile Development**

I build practical web and mobile applications with a focus on clean backend architecture, APIs, databases, and maintainable software.

## About

- 🎓 B.Tech in Computer Science and Engineering at Lovely Professional University
- 💻 Interested in full-stack development, backend systems, distributed applications, and mobile development
- 🔧 Comfortable working with Python, JavaScript/TypeScript, Go, C++, Dart, and modern web frameworks
- 🚀 Building and deploying real-world projects across web, mobile, and backend platforms

## Tech Stack

### Languages
`Python` `JavaScript` `TypeScript` `Go` `C++` `Java` `Dart` `Rust` `C#`

### Frontend & Mobile
`React.js` `Next.js` `Vue.js` `Nuxt.js` `Flutter` `React Native` `HTML` `CSS` `Tailwind CSS`

### Backend
`FastAPI` `Django` `Django REST Framework` `Node.js` `Express.js` `Go Gin` `Go Fiber`

### Databases & Services
`PostgreSQL` `MySQL` `MongoDB` `Redis` `Supabase` `Firebase`

### DevOps & Tools
`Git` `GitHub` `GitHub Actions` `Docker` `Linux` `Postman`

## Selected Projects

### [BintrayX](https://bintrayx.store)
**FastAPI · Vue 3 · PostgreSQL**

A software marketplace focused on application distribution, user roles, digital assets, and administrative workflows.

### Tacto
**Flutter · FastAPI · PostgreSQL**

A board-game application with local gameplay, cloud-backed data, and player-focused application workflows.

### LexiDaily
**Flutter · FastAPI · PostgreSQL · Supabase**

A learning and productivity application combining vocabulary, quizzes, current affairs, news, productivity tools, and social features.

### [Takshnika](https://takshnika.shop)
**Next.js · FastAPI · PostgreSQL**

An e-learning marketplace focused on course content, payments, digital resources, and user workflows.

### PulseCall
**Flutter · Node.js · WebRTC**

A real-time calling application exploring communication workflows and WebRTC-based functionality.

### Cleannova
**Arduino · C++ · Bluetooth · Flutter**

A hardware-software project combining an embedded system with a Flutter-based control interface.

### [SpicarrBlog](https://spicarrblog.vercel.app)
**Nuxt 3 · Go Gin · PostgreSQL**

A content platform with a Nuxt frontend, Go backend, and PostgreSQL database.

## Problem Solving

- Solved **450+ DSA problems on LeetCode**
- Selected for the **Hult Prize Pitching Round**
- Secured **2nd Rank in the CodeHunt Hackathon**

## Training & Certifications

**DevOps & Cloud Computing — CipherSchools**  
Hands-on exposure to Git, GitHub, Linux, Docker, CI/CD, virtualization, containerization, and cloud fundamentals.

Other certifications include:
- Git & GitHub — CipherSchools
- Generative AI Essentials — CipherSchool
- Programming Using C++ — Infosys
- Linux Commands & Shell Scripting — Skillera
- Ethical Hacking — Skillera

## Connect

- [LinkedIn](https://www.linkedin.com/in/angadp11/)
- [GitHub](https://github.com/codeWithOrange)
- [YouTube — Spicarr Coding](https://www.youtube.com/@spicarrcoding)
- Email: angad.kumarp11@gmail.com
"""

out.write_text(text, encoding="utf-8")
print(out)
