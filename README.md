<div align="center">

# AI Evaluator 🤖

<a href="https://github.com/TTPzZ/AI-Evaluator">
  <img src="https://raw.githubusercontent.com/TTPzZ/TTPzZ/master/ai_evaluator_banner.gif" alt="AI Evaluator Banner" width="800" />
</a>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Extension-Chrome-pink.svg?style=flat-square&logo=google-chrome&logoColor=white" alt="Chrome Extension" />
  <img src="https://img.shields.io/badge/Automation-Teacher%20Tool-purple.svg?style=flat-square&logo=automation&logoColor=white" alt="Automation Tool" />
</p>

</div>

---

### 🎥 Demo

<p align="center">
  <img src="https://raw.githubusercontent.com/TTPzZ/AI-Evaluator/main/demo.gif" alt="AI Evaluator in Action" width="600" />
</p>

---

### 💡 Vấn đề & Giải pháp

Việc viết nhận xét chi tiết cho từng học sinh dựa trên các tiêu chí (rubric) mất quá nhiều thời gian. 

**AI Evaluator** là một Chrome Extension giúp tự động hóa quy trình này. Thầy cô chỉ cần click chọn các thẻ tiêu chí (ví dụ: 'Hoàn thành tốt', 'Cần cố gắng', 'Sáng tạo'), công cụ sẽ tự động tổng hợp và điền văn bản nhận xét hoàn chỉnh vào ô đánh giá.

---

### 🚀 Cách Cài Đặt (Dành cho Giáo viên)

Dự án hiện tại đang ở dạng mã nguồn (chưa đưa lên Chrome Web Store). Để sử dụng, thầy cô làm theo các bước sau:

1.  **Tải mã nguồn:** Bấm vào nút màu xanh **<> Code** ở trên cùng bên phải -> chọn **Download ZIP**. Giải nén file vừa tải về.
2.  **Mở trang Extension:** Mở trình duyệt Chrome, gõ `chrome://extensions` vào thanh địa chỉ và nhấn Enter.
3.  **Bật chế độ Developer:** Ở góc trên bên phải màn hình, gạt công tắc **Developer mode** sang ON.
4.  **Cài đặt extension:** Bấm vào nút **Load unpacked** ở góc trên bên trái. Chọn thư mục thầy cô vừa giải nén ở bước 1.
5.  **Hoàn tất:** Icon của AI Evaluator sẽ xuất hiện trên thanh công cụ. Thầy cô có thể ghim nó để sử dụng nhanh.

---

### 🛠️ Cấu hình dữ liệu

Để thay đổi hệ thống thẻ và văn bản nhận xét, thầy cô có thể can thiệp vào file cấu hình `config.js` (hoặc định dạng tương tự trong dự án này). Cấu trúc dữ liệu có dạng:

```javascript
const criteria = {
  'Tốt': ['Sáng tạo', 'Hiểu bài', 'Trình bày đẹp'],
  'Khá': ['Đầy đủ', 'Cần cẩn thận hơn'],
  'Cần cố gắng': ['Thiếu bài tập', 'Chưa tập trung'],
};
