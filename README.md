# 🇻🇳 ViNO — Vietnam New Outlook (v4.5)
> **Giải Pháp Di Sản Số & Thử Đồ Việt Phục Ảo Dành Cho Thế Hệ Trẻ Bằng Google Gemini AI**

[![AI Arena Vietnam 2026]([suspicious link removed])](https://ai-arena-vietnam.vnu.edu.vn/)
[![Google Gemini API]([suspicious link removed])]([suspicious link removed])
[![React]([suspicious link removed])]([suspicious link removed])
[![Tailwind CSS]([suspicious link removed])]([suspicious link removed])
[![License]([suspicious link removed])](LICENSE)

---

## 📌 MỤC LỤC
1. [Giới Thiệu Dự Án](#-giới-thiệu-dự-án)
2. [Những Nỗi Đau Giải Quyết (Problem Statement)](#-những-nỗi-đau-giải-quyết-problem-statement)
3. [Các Tính Năng Cốt Lõi (Key Features)](#-các-tính-năng-cốt-lõi-key-features)
4. [Kiến Trúc Hệ Thống & Công Nghệ (Tech Stack)](#-kiến-trúc-hệ-thống--công-nghệ-tech-stack)
5. [Chiến Lược AI & Prompt Engineering](#-chiến-lược-ai--prompt-engineering)
6. [Hướng Dẫn Cài Đặt & Chạy Trực Tiếp (Getting Started)](#-hướng-dẫn-cài-đặt--chạy-trực-tiếp-getting-started)
7. [Cấu Trúc Thư Mục Dự Án (Project Structure)](#-cấu-trúc-thư-mục-dự-án-project-structure)
8. [Đội Ngũ Phát Triển (Team Members)](#-đội-ngũ-phát-triển-team-members)

---

## 📖 GIỚI THIỆU DỰ ÁN

**ViNO (Vietnam New Outlook)** là nền tảng di sản số ứng dụng **Trí tuệ nhân tạo (Google Gemini API)** giúp thế hệ trẻ (Gen Z) dễ dàng tìm hiểu, sáng tạo và trải nghiệm cổ phục truyền thống Việt Nam (*Áo Giao Lĩnh, Áo Nhật Bình, Áo Ngũ Thân Nam/Nữ, Áo Tứ Thân, Áo Dài Tân Thời*).

Giải pháp kết hợp giữa **màng lọc bảo tồn văn hóa (Cultural Guardian)**, **mô hình thử đồ AI đa phương thức** và **hệ thống kết nối nhà may ngoài đời thực**, biến tình yêu di sản thành hành động thực tế.

* 🎬 **Demo Video Link:** [Xem Video Audition trên YouTube/Drive](#)
* 🌐 **Live Web Application:** [Trải nghiệm ViNO Live WebApp]([suspicious link removed])

---

## 💡 NHỮNG NỖI ĐẠU GIẢI QUYẾT (PROBLEM STATEMENT)

* **Rào cản tri thức:** Gen Z rất yêu thích Việt phục nhưng e ngại khi mặc/phối đồ do thiếu nguồn tra cứu chuẩn xác, lo sợ vi phạm quy chuẩn văn hóa lịch sử.
* **Chi phí & Trải nghiệm thực tế:** Việc thuê/may một bộ cổ phục có chi phí đắt đỏ và tốn thời gian. Người dùng thiếu một công cụ "thử đồ ảo" cá nhân hóa trước khi quyết định may/thuê.
* **Nguy cơ mai một di sản:** Các tri thức may mặc thủ công truyền thống cần được số hóa theo hướng tương tác trực quan để tiếp cận thế hệ trẻ trong kỷ nguyên AI.

---

## ✨ CÁC TÍNH NĂNG CẤU THÀNH (KEY FEATURES)

### 1. 📜 Thẻ Văn Hóa & Bảo Tàng 3D Cổ Phục (Heritage Discovery & 3D Museum)
* Tra cứu bộ dữ liệu chuẩn hóa về 5 loại Việt phục cốt lõi: *Niên đại, tiến trình lịch sử, triết lý - ý nghĩa, chất liệu và kho phụ kiện đi kèm*.
* **Bảo tàng 3D (360° Interactive):** Tích hợp mô hình 3D xoay/phóng to giúp quan sát đường may sống áo trung phùng, nếp khăn đống và hoa văn thêu tay tỉ mỉ.

### 2. 👗 Phòng Thử Đồ Ảo AI (Virtual Fitting Room - VDR)
* Tải ảnh đại diện cá nhân, chọn loại trang phục, biến thể phụ kiện, dáng pose, phong cách tranh vẽ (Chân thực, Hoạt hình, Bán chân thực) và bối cảnh di sản (*Thăng Long, Huế, Hội An...*).
* Tích hợp **Gemini Image Engine (`gemini-3.1-flash-image`)** render ảnh thử đồ 3:4 chất lượng cao.

### 3. 🛡️ Màng Lọc Bảo Vệ Văn Hóa (Cultural Guardian Guardrail)
* Lớp kiểm duyệt thông minh tự động phát hiện và bật Pop-up cảnh báo giáo dục khi phát hiện người dùng phối đồ sai lệch lịch sử nghiêm trọng (ví dụ: *Áo Nhật Bình Hoàng tộc đi cùng Nón Quai Thao dân gian*).

### 4. 🎮 Mini-Game "Việt Phục Remix" & Giám Khảo AI
* Phối đồ tự do theo chủ đề (*Mùa Lễ Hội, Phong Thái Hoàng Gia, Đường Phố Remix*).
* **Giám khảo Gemini AI (`gemini-2.5-flash`)** chấm điểm tự động theo 3 tiêu chí JSON: *FitScore (Phù hợp)*, *CreativeScore (Sáng tạo)*, *DiversityScore (Đa dạng)* và cấp Huy hiệu **"Sứ Giả Văn Hóa"**.

### 5. 🤖 Trợ Lý Di Sản AI — ViVi (Heritage Chatbot)
* Trợ lý ảo tích hợp `gemini-3.1-flash-lite` tư vấn lịch sử, hướng dẫn phối đồ và giải đáp thắc mắc người dùng 24/7 với giọng văn thân thiện, gần gũi Gen Z.

### 6. 📍 Mạng Lưới Tiệm May & Cửa Hàng (Local Tailor Network)
* Định vị các tiệm may cổ phục, studio cho thuê uy tín trong bán kính 15km, hiển thị bảng giá và SĐT liên hệ trực tiếp.

### 7. 🛡️ Thuật Toán Smart Drive Backup Matcher (Cơ Chế Chịu Lỗi)
* Khi gặp sự cố gián đoạn API hoặc nghẽn mạng, thuật toán tự động đối soát độ tương đồng thuộc tính với kho 60+ ảnh mẫu trên Google Drive để trả về ảnh khớp nhất, đảm bảo ứng dụng **100% không văng lỗi khi demo**.

---

## 🛠️ KIẾN TRÚC HỆ THỐNG & CÔNG NGHỆ (TECH STACK)

### Frontend & UI
* **React 18** (Functional Components, Hooks)
* **Tailwind CSS CDN** (Custom Heritage Palette: Crimson `#8B0000`, Sungold `#D4AF37`, Navy `#1A191D`, Cream `#FFF8DC`)
* **Lucide Icons & Sketchfab 3D Embed**

### AI Engine (Google AI Studio & Gemini API)
* **`gemini-3.1-flash-image`**: Render hình ảnh thử đồ 3:4 đa phương thức.
* **`gemini-2.5-flash`**: Giám khảo Mini-game chấm điểm JSON & Màng lọc Cultural Guardian.
* **`gemini-3.1-flash-lite`**: Động cơ hội thoại cho Trợ lý ViVi.

### Resilience & API Management
* **`fetchWithRetry`**: Cơ chế Exponential Backoff (thử lại 3 lần với khoảng chờ 1s -> 2s -> 4s khi gặp mã lỗi 429/500).
* **Structured Output (JSON Schema)**: Ép kiểu dữ liệu phản hồi từ AI.

---

## 🧠 CHIẾN LƯỢC AI & PROMPTING

1. **Role-Based Persona:** Định danh System Instruction chuyên biệt cho từng mô hình AI (Chuyên gia di sản ViVi, Giám khảo Remix, Cultural Guardian).
2. **Context Injection:** Đưa toàn bộ kho dữ liệu `COSTUME_DATA` và quy chuẩn phụ kiện vào Prompt để kiểm soát hiện tượng "ảo giác" (hallucination).
3. **Structured Response Schema:** Ràng buộc chặt chẽ định dạng Output theo chuẩn JSON Schema:
   ```json
   {
     "fitScore": "NUMBER (0-100)",
     "creativeScore": "NUMBER (0-100)",
     "diversityScore": "NUMBER (0-100)",
     "feedback": "STRING (Nhận xét chuyên môn)"
   }
