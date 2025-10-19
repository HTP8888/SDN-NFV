# Project môn SDN & NFV (TEL1450) 👋

Chào mọi người!

Đây là kho lưu trữ của mình (Hoàng Trần Phong - B21DCVT339) cho môn học **SDN & NFV (TEL1450)** tại Học viện Công nghệ Bưu chính Viễn thông (PTIT).

Trong này là toàn bộ các bài báo cáo, tiểu luận và bài lab mình đã thực hiện trong suốt học kỳ dưới sự hướng dẫn của các giảng viên:
* Nguyễn Thanh Trà
* Phạm Anh Thư

---

## Trong Repo này có gì? 🧐

Mình đã sắp xếp các bài nộp chính một cách rõ ràng:

### 1. Bài tiểu luận: Ứng dụng SDN trong Lưới điện thông minh
* **File:** `BÀI TIỂU LUẬN [CLO1, CLO3].docx`
* **Nội dung:** Bài này tập trung vào phần lý thuyết (cover CLO1, CLO3), đi từ tổng quan về SDN, OpenFlow đến đề xuất một mô hình thiết kế hệ thống SDN/NFV cho Lưới điện thông minh (Smart Grid).

### 2. Báo cáo Giữa kỳ: "Mổ xẻ" Giao thức OpenFlow
* **File:** `BÀI GIỮA KỲ.pdf`
* **Nội dung:** Đây là phần thực hành (cover CLO2). Trong bài này, mình đã:
    * Dùng **Mininet** để dựng một topo mạng đơn giản (2 switch, 4 host).
    * Chạy controller **Pox** (sử dụng module `forwarding.l2_learning`) để giúp các host "thấy" nhau.
    * Dùng **Wireshark** để bắt và "soi" chi tiết các gói tin OpenFlow. Mình đã phân tích quá trình từ lúc switch kết nối với controller (`HELLO`) cho đến khi xử lý gói tin đầu tiên (`PACKET_IN`, `PACKET_OUT`, `FLOW_MOD`).

### 3. Báo cáo Lab 2: Làm quen với Mininet
* **File:** `Lab2_mininet.docx`
* **Nội dung:** Bài lab này là các bước đầu tiên làm quen với Mininet. Gồm các bước cài đặt môi trường (Ubuntu, Mininet, Xterm) và thực hành tạo 2 topo mạng cơ bản bằng cả **MiniEdit** (tool kéo thả) và **script Python**.
* *(Bài lab này mình làm cùng nhóm với: Nguyễn Việt Anh, Lương Xuân Huy, và Đào Tiến Hân)*

### 4. Đề bài
* **File:** `2025 Bài tiểu luận và giữa kỳ SDN.pdf`
* **Nội dung:** Đây là file PDF chứa đề bài và yêu cầu chi tiết cho các bài tiểu luận và báo cáo giữa kỳ.

---

## Tech Stack 🛠️

Các công cụ và công nghệ chính mình đã dùng trong môn này:

* **Mô phỏng mạng:** Mininet
* **SDN Controller:** Pox
* **Phân tích gói tin:** Wireshark
* **Môi trường:** Ubuntu (chạy trên máy ảo VMware)

Cảm ơn đã ghé qua repo của mình!
