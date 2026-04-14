
<div align="center">

<a href="https://github.com/TTPzZ">
  <img src="https://raw.githubusercontent.com/TTPzZ/TTPzZ/master/phuc_digital_realm_banner.gif" alt="Phuc's Digital Realm Banner" width="800" />
</a>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00F0FF&center=true&vCenter=true&width=600&lines=Full-stack+%26+IoT+Developer;Instructor+of+Robot,+Python,+Game+Maker;Architecting+Hermit-Home;Tinkering+with+Smart+Systems" alt="Typing SVG" />
</a>

<br/>
<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=nodejs,ts,flutter,mongodb,vercel,firebase,c,cpp,arduino,react,nextjs,nestjs,git,github,docker,figma&perline=8" alt="Tech Stack"/>
</a>

<br/>
<br/>

---

<br/>

<table border="0">
  <tr>
    <td align="center"><img src="https://github-readme-stats.shion.dev/api?username=TTPzZ&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats"/></td>
    <td align="center"><img src="https://github-readme-stats.shion.dev/api/top-langs/?username=TTPzZ&theme=radical&hide_border=true&layout=compact" alt="Top Langs"/></td>
  </tr>
</table>

<img src="https://streak-stats.demolab.com/?user=TTPzZ&theme=radical&hide_border=true" alt="Streak"/>

<br/>
<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TTPzZ/TTPzZ/output/github-contribution-grid-snake-dark.svg?color_snake=white&color_dots=#161b22,#4a1c40,#8c275f,#d93874,#f56296">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TTPzZ/TTPzZ/output/github-contribution-grid-snake.svg?color_snake=white&color_dots=#161b22,#4a1c40,#8c275f,#d93874,#f56296">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/TTPzZ/TTPzZ/output/github-contribution-grid-snake.svg">
</picture>

<br/>
<br/>

---

<p align="center">
  <a href="https://visitcount.itsvg.in"><img src="https://komarev.com/ghpvc/?username=TTPzZ&color=FF00FF&style=flat-square&label=Profile+views" alt="Visitor Count"/></a>
</p>

</div>



-----------------------------

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
