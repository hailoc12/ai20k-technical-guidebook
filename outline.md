# AI20K Technical Guidebook — Dàn ý chi tiết

## Thông tin sách
- **Tiêu đề:** Xây Dựng AI Agent Chuyên Nghiệp — Hướng dẫn thực hành từ A đến Z
- **Phụ đề:** Cho học viên VinUni AI20K Build Phase
- **Mục tiêu:** Đọc xong có thể build project đạt 35+/50 points
- **Target:** ~30,000 words, 80-100 trang

## Cấu trúc 10 chương

### Chương 1: Lời mở đầu — Tại sao bạn cần cuốn sách này (~2000 words)
- 1.1 AI Agent đang thay đổi thế giới như thế nào
- 1.2 Thực trạng Cohort 1 — bài học từ 12 đội
- 1.3 Đối tượng và cách sử dụng sách này
- 1.4 Cấu trúc sách và lộ trình 6 tuần

### Chương 2: Khởi tạo dự án từ Template (~3500 words)
- 2.1 Clone template và cấu trúc thư mục
- 2.2 Thiết lập môi trường phát triển
- 2.3 Cấu hình biến môi trường và API keys
- 2.4 Git workflow — branching và commit chuẩn
- 2.5 Verify setup — chạy server lần đầu tiên
- 2.6 Xóa nội dung mẫu và bắt đầu project của bạn

### Chương 3: Thiết kế kiến trúc hệ thống (~4000 words)
- 3.1 Tổng quan kiến trúc 3 tầng
- 3.2 Frontend — React/Next.js
- 3.3 Backend — FastAPI
- 3.4 AI Agent — LangGraph
- 3.5 Cơ sở dữ liệu và Vector Store
- 3.6 Vẽ Architecture Diagram bằng Mermaid
- 3.7 Ghi lại quyết định kiến trúc (ADR)
- Tóm tắt + Bài tập

### Chương 4: Xây dựng AI Agent với LangGraph (~5000 words) — CHƯƠNG TRỌNG TÂM
- 4.1 Agent là gì? Tại sao cần LangGraph?
- 4.2 State — Bộ nhớ của Agent
- 4.3 Nodes — Các bước xử lý
- 4.4 Edges — Điều hướng luồng
- 4.5 Tools — Mở rộng khả năng Agent
- 4.6 Pattern ReAct — Phân tích → Hành động → Quan sát
- 4.7 Xây dựng Graph hoàn chỉnh — ví dụ end-to-end
- 4.8 RAG — Kết hợp tìm kiếm kiến thức
- 4.9 Error handling trong Agent
- 4.10 Testing Agent
- Tóm tắt + Bài tập

### Chương 5: Phát triển API với FastAPI (~3500 words)
- 5.1 FastAPI — tại sao và bắt đầu thế nào
- 5.2 Định nghĩa routes và schemas
- 5.3 Validation với Pydantic
- 5.4 Error handling chuẩn
- 5.5 CORS và Middleware
- 5.6 Streaming response
- 5.7 Kết nối Agent với API
- Tóm tắt + Bài tập

### Chương 6: Giao diện người dùng (~3000 words)
- 6.1 Setup Next.js từ template
- 6.2 Thiết kế responsive
- 6.3 Dark mode và theming
- 6.4 Kết nối frontend với API
- 6.5 Hiển thị AI response
- Tóm tắt + Bài tập

### Chương 7: DevOps và Triển khai (~3500 words)
- 7.1 Docker — Container hóa ứng dụng
- 7.2 Multi-stage Dockerfile
- 7.3 Docker Compose — Chạy nhiều services
- 7.4 CI/CD với GitHub Actions
- 7.5 Deploy lên cloud (Vercel, Render)
- 7.6 Monitoring và Logging
- Tóm tắt + Bài tập

### Chương 8: Kiểm thử và Đánh giá (~3000 words)
- 8.1 Tại sao cần test?
- 8.2 Viết test cho API
- 8.3 Viết test cho Agent
- 8.4 Test coverage
- 8.5 Evaluation Evidence — Báo cáo đánh giá
- 8.6 RAGAS metrics
- Tóm tắt + Bài tập

### Chương 9: Nộp bài Demo Day (~2500 words)
- 9.1 10 deliverables BTC yêu cầu
- 9.2 Checklist chi tiết từng deliverable
- 9.3 Tiêu chí chấm điểm (5 tiêu chí, 10 points mỗi tiêu chí)
- 9.4 Phân tích lỗi Cohort 1 và cách tránh
- 9.5 Tips ghi điểm từ BTC
- 9.6 Pitch Deck structure (10 slides)
- Tóm tắt + Checklist

### Chương 10: Tài nguyên học tập (~2000 words)
- 10.1 Lộ trình học 6 tuần
- 10.2 Khóa học DeepLearning.AI (35 courses AI Agents)
- 10.3 Tài liệu LangGraph chính thức
- 10.4 BMAD Method — Quản lý dự án với AI
- 10.5 Reference teams từ Cohort 1
