\# RUN\_INDEX\_VANBAN



\## 🎯 MỤC TIÊU

Xử lý văn bản pháp luật thành hệ thống logic + phục vụ triển khai thực tế.



\---



\## 📥 INPUT

\- Văn bản pháp luật (PDF hoặc text)

\- Tên văn bản (ví dụ: ND\_94\_2026)



\---



\## ⚙️ PHƯƠNG PHÁP THỰC HIỆN



\### STEP 1 – CHUNKING

\- Tách văn bản thành các phần hợp lý

\- Mỗi chunk chứa 3–5 Điều

\- Giữ cấu trúc theo Chương

\- Mỗi chunk phải độc lập logic



\---



\### STEP 2 – EXTRACT LOGIC

Với mỗi chunk, trích xuất:



\- Licensing → điều kiện cấp phép

\- Compliance → nghĩa vụ tuân thủ

\- Operational → quy định vận hành

\- Revocation → thu hồi / xử phạt

\- Data → dữ liệu / báo cáo



\---



\### STEP 3 – MERGE SYSTEM

\- Gộp tất cả chunk

\- Loại bỏ trùng lặp

\- Xây dựng hệ thống:



&#x20; - Core principles

&#x20; - Licensing framework

&#x20; - Compliance system

&#x20; - Operational model

&#x20; - Enforcement \& revocation

&#x20; - Data \& reporting



\---



\### STEP 4 – IMPLEMENTATION LAYER



\#### Forms (Biểu mẫu)

Xác định các loại:

\- Hồ sơ cấp phép

\- Đơn / biểu mẫu

\- Báo cáo

\- Danh sách / checklist



\---



\#### Process (Quy trình)

Xây dựng:

\- Quy trình cấp phép

\- Quy trình vận hành

\- Quy trình kiểm tra / thu hồi



\---



\#### Risk \& Control

Xác định:

\- Điểm rủi ro chính

\- Điểm kiểm soát nội bộ



\---



\## 📤 OUTPUT FORMAT (BẮT BUỘC)



Output MUST follow this structure exactly.



\---



\# {LAW\_NAME} – REGULATORY SYSTEM



\---



\## 1. OVERVIEW

\- Document:

\- Scope:

\- Effective Date:

\- Authority:



\---



\## 2. CORE PRINCIPLES

\- ...



\---



\## 3. LICENSING FRAMEWORK



\### 3.1 Entities

\- ...



\### 3.2 Licensing Requirements

\- ...



\### 3.3 Licensing Process

1\. ...

2\. ...

3\. ...



\---



\## 4. COMPLIANCE SYSTEM



\### 4.1 Ongoing Obligations

\- ...



\### 4.2 Reporting \& Data

\- ...



\---



\## 5. OPERATIONAL MODEL



\### 5.1 Training / Operation

\- ...



\### 5.2 Execution

\- ...



\---



\## 6. ENFORCEMENT \& REVOCATION



\### 6.1 Triggers

\- ...



\### 6.2 Penalties

\- ...



\---



\## 7. IMPLEMENTATION LAYER



\### 7.1 Required Forms

\- ...



\### 7.2 Required Processes

\- ...



\### 7.3 Risk \& Control Points

\- ...



\---



\## 8. NOTES

\- ...



\---



\## 📁 FILE OUTPUT



Save result as:



/output/{LAW\_NAME}\_system.md



\---



\## ⚠️ RULES



\- Use bullet points (no long paragraphs)

\- Keep concise, system-level logic

\- Do NOT copy full legal text

\- Always structure in Markdown

\- Output must be ready to paste into GitHub

``

