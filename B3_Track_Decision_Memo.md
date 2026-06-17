# Track Decision Memo - Day 15 (Bộ Câu Hỏi 6)

Bản ghi nhớ này tổng hợp quyết định định hướng chuyên sâu trong Phase 2 của chương trình học, dựa trên kết quả nghiên cứu thị trường công nghệ và đối chiếu năng lực thực tế của bản thân.

---

```text
TRACK DECISION MEMO - Day 15
Họ tên: NGÔ ĐẮC LÂM                 MSSV: 2A202600655
Pathway: A (Tìm / chuyển việc)
```

### 1. ĐỊNH HƯỚNG
Vài job/role hướng tới và kỹ năng mỗi job đòi hỏi (từ JD thật và báo cáo thị trường):
*   **Job 1: Kỹ Sư Ứng Dụng AI (AI Application Engineer)** tại các tập đoàn lớn (FPT, Viettel, VNG)
    *   *Kỹ năng cần*: Thành thạo Python, LangChain/LlamaIndex, phát triển RAG, kết nối Vector DB (Milvus, Pinecone), tối ưu hóa prompt và API.
*   **Job 2: Kỹ Sư Agent (Agentic AI Developer)** tại các startup công nghệ đột phá
    *   *Kỹ năng cần*: Thiết kế cấu trúc agent phức tạp (CrewAI, LangGraph, AutoGen), tích hợp công cụ qua giao thức MCP, xử lý các trạng thái vòng lặp của agent.
*   **Job 3: LLM Integration Specialist / AI Solutions Engineer**
    *   *Kỹ năng cần*: Docker hóa ứng dụng AI, deploy API phục vụ mô hình (FastAPI, Ollama), cấu hình Guardrails an toàn bảo mật cho dữ liệu.

---

### 2. ĐỐI CHIẾU BẢN THÂN (từ Phase 1)
*   **Những việc mình đã làm được (liệt kê tự do, không giới hạn)**:
    *   Xây dựng thành công RAG pipeline hoàn chỉnh truy xuất thông tin từ tài liệu nội bộ, giảm thiểu ảo giác của mô hình.
    *   Lập trình hệ thống Multi-Agent (Supervisor-Worker) để tự động hóa quy trình phân tích dữ liệu phức tạp.
    *   Sử dụng giao thức MCP để kết nối các Agent với hệ thống dữ liệu cục bộ và các công cụ dòng lệnh (CLI).
    *   Thực hành kỹ thuật gọi công cụ (Tool Calling) thông minh và Prompt Engineering tối ưu ngữ cảnh.
    *   Xây dựng và giám sát data pipeline cơ bản phục vụ huấn luyện/truy xuất dữ liệu (Day 10).
*   **Loại công việc cho mình năng lượng, muốn làm tiếp**:
    *   Thiết kế cấu trúc logic của hệ thống (System Architecture).
    *   Lập trình luồng hoạt động thông minh của Agent, tối ưu hóa quá trình ra quyết định của LLM (Reasoning).
    *   Tích hợp các công cụ mới và tối ưu hóa hệ thống để chạy nhanh hơn, tốn ít chi phí token hơn.

---

### 3. KỸ NĂNG MÌNH ĐỊNH PHÁT TRIỂN TỚI
*   **Danh sách kỹ năng**: Multi-Agent Orchestration (phối hợp nhiều tác tử phức tạp), GraphRAG (truy xuất thông tin trên đồ thị kiến thức), LLM Fine-tuning (tinh chỉnh mô hình bằng LoRA/QLoRA).
*   **Gap lớn nhất + thứ mình sẽ build để cho thấy tiến bộ**:
    *   *Gap lớn nhất*: Kinh nghiệm tối ưu hóa chi phí (FinOps) và hiệu năng (latency/throughput) cho mô hình AI trong môi trường sản xuất quy mô lớn.
    *   *Thứ sẽ build*: Một dự án cuối khóa (Capstone Project) hoàn chỉnh: Ứng dụng trợ lý ảo phân tích tài chính/học thuật tự động chạy trên kiến trúc Multi-Agent + GraphRAG + kết nối MCP, được triển khai qua Docker và giám sát bằng một dashboard đo lường độ chính xác (Ragas) và lượng tiêu thụ token theo thời gian thực.

---

### 4. QUYẾT ĐỊNH TRACK
*   **Track chọn**: **T3 - AI Engineering**
    *   *Vì*: Track này hoàn toàn tương thích với thế mạnh lập trình và niềm đam mê thiết kế luồng tư duy cho AI của tôi. Các bài lab trước (RAG, Multi-Agent, MCP) đã cho thấy tôi học rất nhanh và cảm thấy hứng thú nhất khi xử lý các vấn đề logic phần mềm kết hợp AI.
*   **Track cân nhắc nhưng KHÔNG chọn + lý do mạnh nhất cho nó**: **T2 - Data & Infrastructure**
    *   *Lý do*: Mặc dù tôi nhận thức rõ tầm quan trọng của cơ sở hạ tầng dữ liệu và deploy ở Day 10/12, nhưng tôi thích tập trung vào việc kiến tạo ra các Agent thông minh và giải quyết các bài toán logic ứng dụng hơn là việc tập trung phần lớn thời gian quản trị hệ thống Cloud, cấu hình mạng Kubernetes hoặc quản trị chi phí phần cứng.
*   **Dấu hiệu sẽ khiến mình xem lại lựa chọn**:
    *   Nếu trong 6 tháng tới, các nền tảng AI no-code/low-code phát triển mạnh đến mức việc lập trình agent và RAG trở nên bão hòa, trong khi nhu cầu tuyển dụng đòi hỏi kỹ năng hạ tầng tự vận hành (T2) hoặc quản trị sản phẩm AI (T1) tăng gấp nhiều lần so với T3.

---

### 5. ĐỊNH HƯỚNG & CHUẨN BỊ (ghi mở - có gì ghi nấy)
*   **Định hướng tiếp theo**: Tập trung nghiên cứu sâu về LangGraph và CrewAI để xây dựng agent có bộ nhớ và trạng thái ổn định.
*   **Những thứ cần chuẩn bị**:
    *   Củng cố thêm kỹ năng Python nâng cao (Asynchronous Programming, Pydantic).
    *   Đăng ký và làm quen với các nền tảng cloud hỗ trợ GPU miễn phí/giá rẻ phục vụ thử nghiệm Fine-tuning.
    *   Xây dựng một portfolio GitHub chuyên nghiệp hiển thị rõ ràng sơ đồ thiết kế hệ thống và mã nguồn sạch sẽ.
*   **Plan nếu có**: Dành ra 2 tiếng mỗi ngày để nghiên cứu các bài báo khoa học (Arxiv) về RAG nâng cao và Agentic AI để cập nhật kiến thức liên tục.
*   **Câu hỏi còn mở**: Làm cách nào để tối ưu hóa việc phân chia nhiệm vụ của các Agent một cách tự động khi danh sách công cụ đầu vào (MCP servers) thay đổi liên tục theo thời gian thực?
