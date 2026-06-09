# 🦯 Smart Blind Stick - Hệ Thống Hỗ Trợ Người Khiếm Thị Phát Hiện Vật Cản

<p align="center">
  <b>Đồ án IoT - Hệ thống gậy thông minh hỗ trợ người khiếm thị phát hiện vật cản và cảnh báo nguy hiểm.</b>
</p>

---

# 📖 Giới thiệu

Người khiếm thị thường gặp nhiều khó khăn trong quá trình di chuyển do không thể quan sát được các vật cản phía trước.

Dự án **Smart Blind Stick** được xây dựng nhằm hỗ trợ người khiếm thị phát hiện vật cản bằng cảm biến siêu âm và đưa ra cảnh báo thông qua còi buzzer và đèn LED.

---

# 🎯 Mục tiêu dự án

- Phát hiện vật cản phía trước.
- Đo khoảng cách bằng cảm biến HC-SR04.
- Cảnh báo bằng âm thanh và ánh sáng.
- Hỗ trợ người khiếm thị di chuyển an toàn hơn.

---

# 🛠 Công nghệ sử dụng

| Thành phần | Chức năng |
|------------|-----------|
| Arduino Uno | Bộ điều khiển |
| HC-SR04 | Đo khoảng cách |
| Buzzer | Cảnh báo âm thanh |
| LED | Cảnh báo ánh sáng |
| Arduino IDE | Lập trình |
| C/C++ | Ngôn ngữ lập trình |

---

# 🔌 Sơ đồ kết nối

| Thiết bị | Arduino Uno |
|-----------|-----------|
| HC-SR04 TRIG | D9 |
| HC-SR04 ECHO | D10 |
| Buzzer | D11 |
| LED | D13 |
| VCC | 5V |
| GND | GND |

---

# ⚙️ Nguyên lý hoạt động

```text
HC-SR04 phát sóng
      ↓
Gặp vật cản
      ↓
Nhận tín hiệu phản xạ
      ↓
Tính khoảng cách
      ↓
Nếu khoảng cách ≤ ngưỡng
      ↓
Bật LED + Buzzer
```

---

# 📊 Kết quả đạt được

- Đo khoảng cách theo thời gian thực.
- Cảnh báo bằng còi và đèn LED.
- Chi phí thấp.
- Dễ triển khai.

---

# ⚠️ Hạn chế

- Chỉ phát hiện vật cản phía trước.
- Chưa phát hiện hố sâu.
- Chưa tích hợp IoT.

---

# 🔮 Hướng phát triển

- ESP32 / ESP8266.
- GPS định vị.
- Motor rung thay buzzer.
- ESP32-CAM nhận diện vật thể.
- AI và Blockchain lưu nhật ký cảnh báo.

---

# 👨‍💻 Tác giả

**Nguyễn Đức Đại**

Sinh viên ngành Công nghệ Thông tin.

---

# 📜 Giấy phép

Phục vụ mục đích học tập và nghiên cứu.
