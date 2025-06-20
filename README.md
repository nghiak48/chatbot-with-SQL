# chatbot with SQL

🤖 Chatbot AI Biết SQL – Truy Vấn SQLite Bằng LangChain + GGUF + LlamaCpp

Chatbot thông minh có khả năng hiểu tiếng Việt tự nhiên, tự sinh câu lệnh SQL, và truy vấn trực tiếp cơ sở dữ liệu SQLite.

📌 Điểm đặc biệt:
💡 Không cần OpenAI API, không tốn tiền, không cần GPU mạnh – vì sử dụng mô hình GGUF chạy bằng LlamaCpp.
🔥 Chạy hoàn toàn offline, cực nhẹ, phù hợp cả khi dùng trên Google Colab, laptop cá nhân, hoặc môi trường không có internet.

📂 File duy nhất cần dùng

Tên file	Mô tả
Chatbot_sql-2.ipynb	Notebook chính – tích hợp LlamaCpp, LangChain và giao diện Gradio để trò chuyện
🧠 Công nghệ sử dụng

LangChain – Xây dựng logic truy vấn và SQL Agent
LlamaCpp + GGUF – Chạy mô hình ngôn ngữ hoàn toàn offline
SQLite – Cơ sở dữ liệu gọn nhẹ, không cần cài đặt thêm
Gradio – Giao diện trò chuyện đơn giản, dễ dùng
✅ Tính năng nổi bật

✔️ Hiểu tiếng Việt tự nhiên
✔️ Sinh câu lệnh SQL thông minh và chính xác
✔️ Không cần kết nối internet hay tài khoản API
✔️ Sử dụng mô hình GGUF siêu nhẹ, tiết kiệm tài nguyên
✔️ Chạy tốt cả trên CPU (không cần GPU)
✔️ Giao diện Gradio trực quan – chỉ cần nhập câu hỏi tiếng Việt
💬 Ví dụ truy vấn chatbot

"Liệt kê các sản phẩm giá dưới 300k"
"Danh mục Thời Trang Nam có những gì?"
"Có bao nhiêu danh mục sản phẩm?"
🚀 Cách chạy (rất đơn giản)

✅ Trên Google Colab hoặc máy cá nhân:
Mở file Chatbot_sql-2.ipynb
Tải mô hình .gguf (xem bên dưới) và chỉ định đúng đường dẫn
Chạy lần lượt các cell
Giao diện Gradio sẽ xuất hiện để bạn trò chuyện trực tiếp