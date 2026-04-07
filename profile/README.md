<div align="center">

# 🗼 SentryBeacon
### Traffic Vision System

*"Smart Vision for Safer Roads – Drive with care, someone is waiting for you."* 🛡️

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Focus](https://img.shields.io/badge/Focus-Computer%20Vision-orange.svg)

</div>

---

## 📝 Giới thiệu

**SentryBeacon** là hệ thống giám sát giao thông thông minh ứng dụng **Computer Vision** để tự động nhận diện, phân loại phương tiện và hỗ trợ giám sát an toàn đường bộ — giảm thiểu sai sót do yếu tố con người.

---

## 🚀 Tính năng chính

| Tính năng | Mô tả |
|---|---|
| 🚗 **Vehicle Detection** | Nhận diện ô tô, xe máy, xe tải, xe buýt theo thời gian thực |
| 🔤 **License Plate Recognition** | Tách vùng biển số và OCR ký tự độ chính xác cao |
| 📊 **Traffic Flow Analysis** | Đếm phương tiện, phân tích mật độ theo làn đường |
| ⚠️ **Safety Alerts** | Cảnh báo vi phạm và khu vực có nguy cơ mất an toàn |

---

## 🧠 Khái niệm cốt lõi

**1. Object Detection** — Dùng mô hình **YOLO** để xác định vị trí (bounding box) phương tiện trong từng khung hình.

**2. Character Segmentation** — Tách từng ký tự trên biển số, loại nhiễu và căn chỉnh trước khi nhận diện.

**3. IoU & Overlap Removal** — Chỉ số **Intersection over Union** loại bỏ vùng nhận diện trùng lặp, giữ lại kết quả tin cậy nhất.

**4. OCR** — Chuyển đổi ảnh ký tự thành chuỗi văn bản để lưu vào cơ sở dữ liệu.

---

## 🛠️ Tech Stack

```
Ngôn ngữ   : Python · C++
Thư viện   : OpenCV · PyTorch / TensorFlow · Flask
Công cụ    : Jupyter Notebook · Git LFS · YOLO
```

---

## 🔗 Tài nguyên hệ thống 

> 🌐 **[tài liệu](https://your-link-here.com)**

---

<div align="center">

*Chúng tôi tin rằng công nghệ có thể làm cho con đường về nhà của mỗi người trở nên an toàn hơn.*
*Hãy giữ vững tay lái và tuân thủ luật lệ giao thông.* ❤️

<br/>

© 2026 **SentryBeacon Team** · Developed by [Nguyen Duc Manh](https://github.com/ducmanh-jr)

</div>
