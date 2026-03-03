# MES Package Explorer

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/yourusername/mes-package-explorer)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yourusername/mes-package-explorer/pulls)

> **Công cụ tra cứu và quản lý Package trong hệ thống MES (Manufacturing Execution System) một cách thông minh và hiệu quả.**

![MES Package Explorer Dashboard](screenshot-dashboard.png)

## ✨ Tính năng nổi bật

### 📊 **Dashboard Thông Minh**
- **Tra cứu linh hoạt**: Tìm kiếm packages theo khoảng thời gian tùy chỉnh (từ/đến) với giới hạn 90 ngày
- **Đa dạng định dạng xuất**: JSON, CSV, Table View, Simple List
- **Filter nâng cao**: Lọc theo Package Group, Line Name, Buyer, Style Code, Status
- **Quick Copy**: Sao chép nhanh danh sách packages theo nhiều định dạng

### 🔐 **Quản lý Authentication**
- **Lưu cookie an toàn**: Mã hóa và lưu trữ cookie với thời hạn 30 ngày
- **Tự động validate**: Kiểm tra tính hợp lệ của cookie trước khi gọi API
- **Cảnh báo thông minh**: Thông báo khi cookie sắp hết hạn

### 📈 **Thống kê & Phân tích**
- **Real-time stats**: Cập nhật số lượng packages, tỷ lệ confirmed/pending
- **Trend indicators**: Hiển thị xu hướng tăng/giảm theo thời gian
- **Success rate**: Đo lường hiệu suất gọi API

### 🎯 **Tiện ích thông minh**
- **Quick Date Range**: 6 nút chọn nhanh (Today, Yesterday, ±7 days, ±30 days)
- **Copy formats đa dạng**: MxPackage, Line+MxPackage, JSON Array, CSV, Newline, Space
- **Export dữ liệu**: Tải về file với định dạng mong muốn
- **Active filters**: Hiển thị trực quan các bộ lọc đang áp dụng

## 🚀 Công nghệ sử dụng

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Inter)
- **Storage**: LocalStorage (mã hóa cookie)
- **API Integration**: Cloudflare Worker

## 📦 Cài đặt & Triển khai

### Yêu cầu hệ thống
- Trình duyệt web hiện đại (Chrome, Firefox, Edge, Safari)
- Kết nối Internet (để tải fonts và icons)

### Các bước triển khai

1. **Clone repository**
```bash
git clone https://github.com/yourusername/mes-package-explorer.git
cd mes-package-explorer
```


## 📚 Tài liệu tham khảo

- [MES System Documentation](http://mespk2.pungkookvn.com)
- [Cloudflare Workers Docs](https://developers.cloudflare.com/workers/)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

