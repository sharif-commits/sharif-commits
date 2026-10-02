<h1 align="center">Hi, I'm Sharif 👋</h1>

<p align="center">
  CS undergrad at <b>IIIT Hyderabad</b> · research on <b>sign-language avatars & accessibility</b><br>
  I like building things close to the metal — shells, file systems, packet sniffers — and shipping full-stack apps on top.
</p>

<p align="center">
  <a href="mailto:masthansharif.shaik@students.iiit.ac.in"><img src="https://img.shields.io/badge/Email-IIIT%20H-0A66C2?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://sharif-commits.github.io/ISL-AVATAR-PROJECT/"><img src="https://img.shields.io/badge/Live%20Demo-SignPlug-E8590C?style=flat-square&logo=googlechrome&logoColor=white" alt="SignPlug live demo"></a>
</p>

---

### 📄 Publication

<table>
<tr>
<td>

#### 🤟 SignPlug — ISL Plugin on the Web
<img src="https://img.shields.io/badge/ICVGIP-2026-8A2BE2?style=flat-square" alt="ICVGIP 2026">
<img src="https://img.shields.io/badge/Indian%20Sign%20Language-3D%20Avatar-E8590C?style=flat-square" alt="ISL">
<img src="https://img.shields.io/badge/SMPL--X-Web%20Rendering-1971C2?style=flat-square" alt="SMPL-X">

A lightweight, real-time framework that turns **sentences into continuous Indian Sign Language animation, right in the browser**, so Deaf and hard-of-hearing users can get sign-language support on any webpage.

<p>
  <a href="https://sharif-commits.github.io/ISL-AVATAR-PROJECT/"><img src="https://img.shields.io/badge/▶%20Try%20the%20live%20demo-SignPlug%20on%20the%20web-E8590C?style=for-the-badge" alt="Try the live demo"></a>
</p>

> The demo embeds the SignPlug 3D avatar widget into an ISL course webpage. It runs entirely in the browser, with no install and no GPU needed.

- **Motion from real signers, not notation.** We reconstruct SMPL-X keyposes from monocular ISL dictionary videos and refine them with *Gizmo*, a custom sparse-correction annotation tool. The result is a motion-capture-quality **gloss–pose dictionary of 1,000 signs** with corrected body, hand and finger articulation.
- **No GPU motion model at inference.** Predicted glosses are retrieved from the dictionary, retargeted onto a canonical avatar, and stitched together with SLERP.
- **Fast enough for live use.** Animation plays at **25 FPS**, the same rate as the source footage, and a sentence is ready in **0.13 s (2 glosses) to 1.42 s (20 glosses)**.
- **Validated with Deaf ISL signers.** In a user study with **11 Deaf and hard-of-hearing signers**, the motion was rated markedly smoother and more natural than notation-driven (HamNoSys/SiGML) avatars.

🌐 **[Live demo](https://sharif-commits.github.io/ISL-AVATAR-PROJECT/)** &nbsp;·&nbsp; 🔗 **[Source (early prototype)](https://github.com/sharif-commits/ISL-AVATAR-PROJECT)**

</td>
</tr>
</table>

---

### 🛠️ Tech I work with

**Languages**&nbsp;
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

**Vision & Graphics**&nbsp;
![SMPL-X](https://img.shields.io/badge/SMPL--X-555?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Web**&nbsp;
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Systems & Tools**&nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![libpcap](https://img.shields.io/badge/libpcap-555?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### ⚙️ Systems Programming (C)

| Project | What it is |
|---|---|
| 🦈 **[C-Shark](https://github.com/sharif-commits/C-Shark)** | Terminal packet sniffer built on `libpcap`. Captures live traffic, applies BPF filters, and decodes Ethernet → IPv4/IPv6/ARP → TCP/UDP → payload, with post-capture session inspection. |
| 🗂️ **[Distributed File System](https://github.com/sharif-commits/File-System)** | Networked file system with a central **name server**, multiple **storage servers**, and **clients** talking over a custom protocol. |
| 🐚 **[C-shell](https://github.com/sharif-commits/C-shell)** | A Unix-style shell from scratch: tokenizer + parser, custom built-ins (`hop`, `reveal`, `log`), background jobs, and signal-based job control. |

### 🌐 Full-Stack Web

| Project | What it is |
|---|---|
| 🎉 **[Felicity Event Management](https://github.com/sharif-commits/DASS-A1)** | MERN app for a college fest with three roles (participant / organizer / admin): JWT auth, event registration, QR tickets, merch payment approval, CSV exports, and a real-time Socket.IO forum. |

### 📊 Algorithms & Data

| Project | What it is |
|---|---|
| 🧬 **[String Matching on Genomic Data](https://github.com/sharif-commits/Subproblem-solvers)** | Benchmarks exact and fuzzy matching (KMP, Boyer-Moore, Shift-Or, Ukkonen suffix tree, Levenshtein) for finding gene motifs in synthetic and real *E. coli* DNA, comparing latency, memory, and preprocessing cost. |
| 👁️ **[Computer Vision Task](https://github.com/sharif-commits/Precog-Task-CV)** | Image-classification experiments in Jupyter, including ResNet-based models. |

### ✅ Software Testing

| Project | What it is |
|---|---|
| 🧪 **[White-, Integration- & Black-Box Testing](https://github.com/sharif-commits/DASS-A2)** | A full testing pass over two codebases: white-box tests and pylint cleanup for a Monopoly-style game, integration tests, and black-box API tests against a Dockerized shopping-cart service. |

---

<p align="center"><i>Interested in accessibility, vision & graphics, and systems. Always happy to connect!</i></p>
