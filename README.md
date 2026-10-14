# 👋 Hi, I'm Hoàng Sơn (Dev Basic)

<p align="center">
  🎓 Sinh viên Công nghệ thông tin – Trường Đại học Thủ Dầu Một<br>
  💻 Software Development | Artificial Intelligence |<br>
  🛰️ NASA Space Apps Challenge 2026
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-IoT%20%7C%20AI%20%7C%20Cybersecurity-0B3D91?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Building%20Projects-2EA44F?style=for-the-badge" />
</p>

---

## 🌐 Socials

[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://www.facebook.com/sonzz.nss)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://www.instagram.com/nguyenson3144)
[![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://www.tiktok.com/@haison100999)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/DevSon1009)

---

## 🚀 Featured Project: Radar-YOLO Smart Intrusion Detection System

**Hệ thống Radar IoT phát hiện người và cảnh báo xâm nhập tích hợp YOLO**

Xây dựng hệ thống an ninh thông minh kết hợp cảm biến radar, vi điều khiển IoT và thị giác máy tính nhằm phát hiện sự hiện diện, nhận diện người và các đối tượng trong khu vực giám sát, đồng thời gửi cảnh báo đến thiết bị người dùng.

### 🎯 Key Features

- 📡 **Radar Presence Detection:** Sử dụng cảm biến LD2410C kết hợp ESP32-S3 để phát hiện sự hiện diện của người.
- 🤖 **YOLO Object Detection:** Tích hợp mô hình YOLO để nhận diện người và các lớp vật thể được mô hình hỗ trợ từ hình ảnh/video.
- 🎯 **Object Tracking:** Theo dõi đối tượng qua các khung hình để hỗ trợ giám sát liên tục.
- 🚨 **Real-time Intrusion Alerts:** Xử lý sự kiện và kích hoạt cảnh báo khi điều kiện xâm nhập được thỏa mãn.
- 💡 **Hardware Alarm:** Điều khiển relay, đèn cảnh báo và buzzer thông qua bộ điều khiển IoT.
- ☁️ **Backend & Event Management:** Tiếp nhận dữ liệu thiết bị và sự kiện AI, quản lý trạng thái, lịch sử cảnh báo và logic xử lý.
- 📱 **Remote Monitoring & Notifications:** Web App/PWA hỗ trợ theo dõi trạng thái, xem lịch sử và nhận thông báo trên thiết bị người dùng theo cơ chế thông báo được triển khai.
- 🖥️ **Web Admin Dashboard:** Hỗ trợ quản lý thiết bị, theo dõi trạng thái online/offline và giám sát sự kiện.
- 📲 **Responsive Interface:** Giao diện hướng đến khả năng sử dụng trên cả máy tính và điện thoại.

### 🏗️ System Architecture

```text
LD2410C Radar
     │
     ▼
 ESP32-S3 ───────────────► Relay / Warning Light / Buzzer
     │
     ▼
  MQTT / HTTPS
     │
     ▼
    Backend ◄──────── AI Service
     │                     ▲
     │                 Camera / Video
     │                     │
     │                 YOLO + Tracking
     │
     ├── Event & Alert Management
     ├── Device Monitoring
     ├── Event History
     │
     ├── Web Admin Dashboard
     │
     └── Web App / PWA
                │
                ▼
       User's Phone / Computer
       Remote Monitoring & Alerts
```

### 🛠️ Technologies

![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-008080?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-6A5ACD?style=flat-square)

### 🔍 Project Highlights

- Kết hợp hai nguồn dữ liệu: radar phát hiện hiện diện và camera phân tích hình ảnh bằng YOLO.
- Phân tách firmware, backend, dịch vụ AI và giao diện web để dễ bảo trì, mở rộng.
- Hướng đến giám sát từ xa, quản lý lịch sử sự kiện và cảnh báo đa thiết bị.
- Hỗ trợ phát triển thêm các luật cảnh báo theo vùng giám sát và trạng thái hệ thống.

> **Project goal:** Xây dựng hệ thống AIoT hỗ trợ phát hiện xâm nhập, kết hợp cảm biến vật lý, Computer Vision và giám sát từ xa. Hiệu năng và độ chính xác cần được đánh giá bằng thử nghiệm thực tế trước khi công bố các chỉ số định lượng.

🔗 **Repository:** [Radar-YOLO](https://github.com/DevSon1009/Radar-YOLO-)

---

## 🛰️ NASA Space Apps Challenge 2026

<p align="center">
  <img src="assets/nasa-dancing-with-sars.png" alt="NASA Space Apps Challenge 2026 — Dancing with the SARs" width="100%" />
</p>

![NASA](https://img.shields.io/badge/NASA-Space%20Apps%202026-0B3D91?style=for-the-badge&logo=nasa&logoColor=white)
![Status](https://img.shields.io/badge/Status-Preparing-orange?style=for-the-badge)
![Subject](https://img.shields.io/badge/Subject-Earth%20Science-3B4CC0?style=for-the-badge)

### Challenge: *Dancing with the SARs*

**Sự kiện:** NASA Space Apps Challenge 2026  
**Chủ đề:** Earth Science (Khoa học Trái Đất)  
**Độ khó hiển thị:** Intermediate / Advanced

Bề mặt Trái Đất luôn thay đổi bởi các quá trình tự nhiên và hoạt động của con người. Thử thách *Dancing with the SARs* hướng đến việc xây dựng một ứng dụng tương tác sử dụng dữ liệu viễn thám radar từ sứ mệnh NASA–ISRO Synthetic Aperture Radar (NISAR), nhằm theo dõi và trực quan hóa một hoặc nhiều dạng biến đổi bề mặt tại các địa điểm trên thế giới.

**Hướng tiếp cận dự kiến:**

- 📡 Tìm hiểu dữ liệu SAR và sứ mệnh NASA–ISRO NISAR.
- 🗺️ Xây dựng web app tương tác để hiển thị dữ liệu và trực quan hóa biến đổi bề mặt.
- 🤖 Nghiên cứu khả năng áp dụng Machine Learning để hỗ trợ phát hiện thay đổi.
- 🌍 Tập trung vào một dạng biến đổi phù hợp, chẳng hạn vùng ngập nước, thay đổi thảm thực vật hoặc biến động bề mặt.
- ☁️ Triển khai ứng dụng web để người dùng có thể khám phá kết quả trực quan.

> **Project status:** Đang ở giai đoạn chuẩn bị và nghiên cứu hướng triển khai; các tính năng trên là kế hoạch dự kiến, không phải kết quả đã hoàn thành.

---

## 🔬 Scientific Research | NCKH 2025–2026

<p align="center">
  <img src="https://img.shields.io/badge/Research%20Score-8.8%2F10-2E8B57?style=for-the-badge" alt="Research score 8.8 out of 10" />
  <img src="https://img.shields.io/badge/Classification-%C4%90%E1%BA%A1t%20lo%E1%BA%A1i%20T%E1%BB%91t-0B3D91?style=for-the-badge" alt="Research classification: Good" />
</p>

**Thành tích:** Đạt **8.8/10 – xếp loại Tốt** với đề tài nghiên cứu khoa học sinh viên năm học 2025–2026 tại Trường Đại học Thủ Dầu Một.

### Malware Detection Web System Using Static Analysis and Machine Learning

**Đề tài:** Xây dựng hệ thống hỗ trợ phân tích và phát hiện mã độc dựa trên đặc trưng tĩnh và kỹ thuật học máy trên nền tảng website.

*Trường Đại học Thủ Dầu Một – Khoa Công nghệ Thông tin*

Phát triển website hỗ trợ phân tích file PE (Portable Executable), kết hợp mô hình Machine Learning với phương pháp giải thích kết quả dự đoán.

| Metric | Reported Result |
|---|---:|
| Dataset | EMBER 2018 |
| Labeled samples | 600,000 |
| Static features | 2,381 |
| Best model | XGBoost |
| F1-score | 0.9682 |
| AUC | 0.9938 |
| F1 standard deviation | 0.00023 across 8 random seeds |
| False Positive Rate | 3.59% → 2.05% |

### Key Contributions

1. 🎚️ Tối ưu ngưỡng phân loại bằng Youden's J Statistic.
2. 🧾 Kết hợp Evidence Aggregation Framework và SHAP để giải thích kết quả dự đoán.
3. 🧩 Phân loại API theo 8 danh mục MITRE ATT&CK trong Import Pattern Engine.

### Technologies

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-2980B9?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainable%20AI-8A2BE2?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-E31937?style=flat-square)

> Research metrics are based on the reported experimental results of the project. Static analysis has limitations against some fileless and dynamically loaded threats.

---

## 🏆 Achievements & Activities

- 🔬 Đề tài nghiên cứu khoa học sinh viên năm học 2025–2026 đạt **8.8/10 – xếp loại Tốt**.
- 🛰️ Chuẩn bị tham gia NASA Space Apps Challenge 2026.
- 🤖 Phát triển dự án Radar-YOLO tích hợp IoT, Computer Vision và cảnh báo từ xa.
- 💻 Thực hành phát triển ứng dụng web, backend API và hệ thống nhúng.

---

## 💻 Tech Stack

### Programming Languages
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![C#](https://img.shields.io/badge/C%23-239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C.svg?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0.svg?style=for-the-badge&logo=python&logoColor=white)

### Web & Backend
![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000.svg?style=for-the-badge&logo=flask&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-6DA55F.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

### AI, Data & IoT
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

### Tools & Design
![Git](https://img.shields.io/badge/Git-F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black.svg?style=for-the-badge&logo=three.js&logoColor=white)

---

## 🎯 Areas of Interest

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-red?style=for-the-badge&logo=hackthebox&logoColor=white)
![Malware Analysis](https://img.shields.io/badge/Malware%20Analysis-darkred?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-orange?style=for-the-badge)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-6A5ACD?style=for-the-badge)
![IoT](https://img.shields.io/badge/IoT-008080?style=for-the-badge)
![Explainable AI](https://img.shields.io/badge/Explainable%20AI-8A2BE2?style=for-the-badge)
![Remote Sensing](https://img.shields.io/badge/Remote%20Sensing-0B3D91?style=for-the-badge&logo=nasa&logoColor=white)

---

## 📊 GitHub Stats

![](https://github-readme-stats.shion.dev/api?username=DevSon1009&theme=dark&hide_border=false&include_all_commits=true&count_private=false)

![](https://streak-stats.demolab.com/?user=DevSon1009&theme=dark&hide_border=false)

![](https://github-readme-stats.shion.dev/api/top-langs/?username=DevSon1009&theme=dark&hide_border=false&layout=compact)

### ✍️ Random Dev Quote

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---

[![](https://komarev.com/ghpvc/?username=DevSon1009&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Profile README -->
