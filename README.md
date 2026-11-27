<!-- DRAFT for github.com/pphiraphat/pphiraphat (README.md)
     Before pasting: replace LINKEDIN_URL and RESUME_URL (use a resume version WITHOUT phone number). -->

# Hi, I'm Phiraphat Boonsodakorn 👋

IoT and Information Engineering student at **KMITL** (B.Eng., expected May 2028), based in Bangkok.
I build across **machine learning, IoT/embedded systems and web development**.

🔎 **Looking for a Summer 2027 internship in Software / AI Engineering.**

[LinkedIn](LINKEDIN_URL) · [Resume](RESUME_URL) · [pphiraphat.b@gmail.com](mailto:pphiraphat.b@gmail.com)

---
<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/pphiraphat/pphiraphat/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/pphiraphat/pphiraphat/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="GitHub contribution snake"
    src="https://raw.githubusercontent.com/pphiraphat/pphiraphat/output/github-contribution-grid-snake.svg"
  />
</picture>

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**AI / Data**
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat&logoColor=black)
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=flat&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![Teachable Machine](https://img.shields.io/badge/Teachable_Machine-FF8F00?style=flat&logoColor=white)

**Web & Backend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat&logo=nuxt&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat&logo=google&logoColor=white)

**Embedded / IoT**
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat&logo=platformio&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

---

## 🚀 Projects

> Most of my projects are team projects hosted in private repositories, so I describe my own part of each one here.

### 🧴 AcneCare: Browser-based Acne Detection · Oct 2026
`YOLO26s` `Python` `Roboflow` · team app: `Next.js` `ONNX Runtime Web`
- Cleaned a 6-class Roboflow dataset (blackheads, whiteheads, papules, pustules, nodules, cysts).
- Trained and evaluated the YOLO26s detector used in the final app: **51.1% mAP@0.5** (59.3% precision, 49.5% recall) on a 2,068-image validation set.
- The model runs entirely in the browser, so user photos never leave the device.
- 🔗 [Live demo](https://acne-care-six.vercel.app) · [Repository](https://github.com/77Henvi/AcneCare)

### 🌊 Smart Water Salinity Monitoring Device · Jan – Mar 2026
`ESP32` `C++` `PlatformIO`
- Designed the device workflow and control logic: sensor acquisition, auto/manual calibration, temperature compensation, salinity calculation and data transmission to a web dashboard.
- Wrote the C++ LCD interface (monitor, calibration, system-info screens) and helped test the hardware.
- The team device (GPS tagging, web dashboard, Telegram alerts) reached an average error **below 5%** against 1–10 ppt standard solutions.
- 🔗 [Dashboard](https://iews.kmitl.ac.th)

### 📦 Smart Parcel Locker · Aug – Oct 2025
`Raspberry Pi` `Python` `Flask` `Google Apps Script` `Google Sheets`
- Designed the workflow, built the hardware (Raspberry Pi, servo lock, OLED) and wrote all the hardware code.
- Built a non-blocking Flask REST API with multithreading and a busy state (HTTP 202) so concurrent requests cannot trigger duplicate lock commands.
- Integrated Apps Script and Google Sheets for remote unlock and logging, with a CSV backup every 30 s.

### 🌐 IoT Department Website · Dec 2025 – Mar 2026
`Vue.js` `Nuxt` `Figma`
- Co-designed the UI/UX in Figma with the team.
- Built the responsive About page in Vue.js/Nuxt using reusable components and modular sections.

---

## 🎓 Education & Certifications

- **KMITL**: B.Eng. in IoT System and Information Engineering (expected May 2028)
- **AWS Academy Graduate**: Cloud Foundations · Machine Learning Foundations (Oct 2026)
