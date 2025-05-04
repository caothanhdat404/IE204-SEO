# 📘 HƯỚNG DẪN CÀI ĐẶT VÀ SỬ DỤNG CÁC CÔNG CỤ HỖ TRỢ SEO


## 🧰 Plugin sử dụng

- **Asset CleanUp: Page Speed Booster**
- **Async JavaScript**
- **Autoptimize**
- **Easy Table of Contents**
- **EWWW Image Optimizer**
- **GTranslate**
- **kk Star Ratings**
- **Rank Math SEO PRO**

## 🔧 Các công cụ SEO hỗ trợ ngoài WordPress

- **Google Search Console**
- **Google Analytics**
- **Ahrefs**
- **Moz Keyword Explorer**
- **Mangools**
- **PageSpeed Insights**
- **Keyword Density Checker**
- **Sprout Social**
- **Google Search**

---

## 🛠️ Hướng dẫn cài đặt các plugin
- Đăng nhập vào **WordPress Admin Panel**.
- Truy cập **Plugins → Thêm Plugin**.
- Tìm kiếm và cài từng plugin trong danh sách trên (nếu không có trong thư viện, có thể cài bằng file `.zip`).
- Kích hoạt tất cả các plugin sau khi cài đặt.

---

## 📋 Cấu hình các plugin (cơ bản)

### 🔹 Asset CleanUp: Page Speed Booster
- Vào **Settings → Asset CleanUp**.
- Bật **Test Mode** nếu muốn kiểm tra trước khi áp dụng.
- Tắt các file **CSS/JS** không cần thiết ở từng trang.

### 🔹 Async JavaScript
- Truy cập **Settings → Async JavaScript**.
- Bật **Enable Async JavaScript**.
- Chọn **Async** hoặc **Defer** cho JS.

🧪 **Ghi chú:** Sau khi cấu hình chế độ async/defer, hãy kiểm tra lại toàn bộ trang để đảm bảo không có lỗi JavaScript và các chức năng giao diện vẫn hoạt động bình thường. Nếu phát sinh lỗi, hãy điều chỉnh lại chế độ tải tương ứng hoặc loại trừ script đó.

### 🔹 Autoptimize
- Vào **Settings → Autoptimize**.
- Bật:
  - **Optimize JavaScript Code**
  - **Optimize CSS Code**
  - **Optimize HTML Code**

🧠 **Mẹo nâng cao cho Autoptimize:**

Ngoài các tùy chọn cơ bản, bạn có thể cân nhắc bật thêm các mục sau để tối ưu sâu hơn:

- Aggregate JS/CSS files để gộp file, giảm request.
- Inline and defer CSS để cải thiện điểm PageSpeed.
- Remove Google Fonts nếu không dùng.
- Remove emojis để loại bỏ JS không cần thiết.

⚠️ **Lưu ý:** Mỗi thay đổi cần được kiểm tra để đảm bảo không gây lỗi hiển thị hay ảnh hưởng đến chức năng.

### 🔹 Easy Table of Contents
- Truy cập **Settings → Table of Contents**.
- Bật **Auto Insert** cho **Article**.
- Tùy chỉnh độ sâu tiêu đề và vị trí hiển thị.

### 🔹 EWWW Image Optimizer
- Vào **Settings → EWWW Image Optimizer**.
- Bật **Remove metadata** để giảm dung lượng ảnh.
- Có thể bật **Lazy Load** (tải ảnh khi cuộn đến) nếu chưa dùng plugin khác hỗ trợ
- Chọn mức nén ảnh và bật **WebP Conversion** để tạo phiên bản WebP.
- Bật **JS WebP Rewriting** hoặc **Picture WebP Rewriting**  (tùy vào cách muốn trình duyệt hiển thị ảnh WebP)

### 🔹 GTranslate
- Vào **Settings → GTranslate**.
- Cấu hình hiển thị widget ở **Widget look**.
- Chọn các ngôn ngữ hiển thị

### 🔹 kk Star Ratings
- Truy cập **kk Star Ratings**.
- Tại tab **Overview**:
    - Chọn **Active** cho **Status**
    - Chọn các vị trí xuất hiện ở **Location**
- Tại tab **Interface**:
    - Sửa lời chào ở ô **Greeting** và các tùy chỉnh khác


### 🔹 Rank Math SEO PRO
- Vào **Rank Math → Dashboard**.
- Kích hoạt các module cần thiết: **Schema (Structured Data)**, **Sitemap**, **SEO Analyzer**...
- Tối ưu SEO từng bài viết.

---

## 📊 Hướng dẫn sử dụng các công cụ SEO

### 🔸 Google Search Console
- Truy cập: [https://search.google.com/search-console](https://search.google.com/search-console)
- Thêm trang web bằng Domain hoặc URL Prefix.
- Xác minh bằng DNS hoặc HTML file/meta tag.
- Gửi sitemap.xml (thường là `https://yourdomain.com/sitemap_index.xml` nếu dùng Rank Math).
- Kiểm tra:
    - Trang nào đã được index.
    - Hiệu suất từ khóa (số lần hiển thị, CTR, vị trí).
    - Các lỗi: trang bị chặn, không index, redirect lỗi,…

## 🔸 Google Analytics
- Truy cập: [https://analytics.google.com](https://analytics.google.com)
- Tạo Property mới, lấy mã Measurement ID (G-XXXXXXX).
- Tích hợp bằng plugin (như Rank Math, Site Kit) hoặc chèn trực tiếp vào `<head>`.
- Theo dõi:
    - Lượng người truy cập, thời gian trên trang, thiết bị.
    - Nguồn truy cập: Google, Facebook, Direct…
    - Sự kiện như click, scroll, hoặc form submission.

## 🔸 Ahrefs / Moz / Mangools
- Truy cập nền tảng tương ứng.
- Dán URL website để phân tích:
  - Backlink profile: số lượng, chất lượng, domain trỏ về.
  - Organic keywords: từ khóa đang có thứ hạng.
  - Top pages: bài viết nào đang kéo traffic.
- Dùng Keyword Explorer để:
  - Tìm từ khóa có Search Volume cao, Keyword Difficulty thấp.
  - Xem SERP đối thủ để lên chiến lược nội dung.

## 🔸 PageSpeed Insights
- Truy cập: [https://pagespeed.web.dev](https://pagespeed.web.dev)
- Nhập URL để kiểm tra.
- Xem điểm hiệu suất (0–100) cho Mobile và Desktop.
- Tập trung cải thiện:
    - Largest Contentful Paint (LCP)
    - Total Blocking Time (TBT)
    - Cumulative Layout Shift (CLS)
- Làm theo gợi ý: lazy-load, dùng WebP, defer JS, preload font…

## 🔸 Keyword Density Checker
- Dán nội dung bài viết vào một công cụ như SEO Review Tools.
- Kiểm tra từ khóa chính và mật độ lặp lại.
- Giữ mật độ từ khóa chính trong khoảng 1–2.5%, tránh over-optimization (>3%).

## 🔸 Sprout Social (hoặc Buffer / Hootsuite)
- Kết nối các mạng xã hội như Facebook, Twitter, LinkedIn.
- Hẹn lịch đăng bài và theo dõi hiệu quả tương tác.
- Xem báo cáo chi tiết về lượt tương tác, nhấp chuột, lượt chia sẻ.

## 🔸 Google Search (phân tích đối thủ thủ công)
- Gõ từ khóa mục tiêu trên Google.
- Xem 10 kết quả đầu:
  - Họ dùng tiêu đề gì?
  - Meta description có CTA gì hấp dẫn?
