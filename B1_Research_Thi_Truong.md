# Báo Cáo Nghiên Cứu Thị Trường Việc Làm AI & Công Nghệ (Bộ Câu Hỏi 4)

Báo cáo này được thực hiện nhằm tổng hợp, phân tích các xu hướng việc làm, nhu cầu kỹ năng trong lĩnh vực Trí tuệ nhân tạo (AI) và Công nghệ thông tin từ các nguồn báo cáo uy tín toàn cầu và Việt Nam năm 2025 - 2026 (WEF, Microsoft, PwC, Stanford HAI, ITviec).

---

## 1. Những Nghề Nghiệp & Kỹ Năng Đang Tăng Nhanh

Dựa trên các báo cáo kinh tế và xu hướng tuyển dụng mới nhất, cơ cấu việc làm ngành công nghệ đang dịch chuyển mạnh mẽ từ việc phát triển phần mềm truyền thống sang các giải pháp tích hợp AI.

### Kỹ năng tăng trưởng mạnh nhất:
*   **Agentic AI & Multi-Agent Orchestration**: Khả năng thiết kế, xây dựng và kết nối các hệ thống tác tử (Agents) tự trị để thực hiện các luồng công việc phức tạp thay vì chỉ sử dụng các câu lệnh đơn lẻ.
*   **Advanced RAG & GraphRAG**: Kỹ thuật truy xuất thông tin nâng cao kết hợp đồ thị tri thức để cung cấp dữ liệu chính xác, giảm thiểu hiện tượng ảo giác (hallucination) của LLM.
*   **Tool Calling & Protocol Integration (MCP)**: Khả năng tích hợp mô hình ngôn ngữ với các hệ thống phần mềm, cơ sở dữ liệu, API bên ngoài thông qua các tiêu chuẩn như Model Context Protocol (MCP).
*   **Tối ưu hóa mô hình & Fine-tuning (LoRA, QLoRA)**: Khả năng tinh chỉnh các mô hình mã nguồn mở (như Llama, Qwen, Mistral) để đáp ứng nghiệp vụ cụ thể của doanh nghiệp nhằm tối ưu chi phí và tăng tính bảo mật.

### Nghề nghiệp phát triển nhanh nhất:
*   **AI Engineer (Kỹ sư ứng dụng AI)**: Vai trò cầu nối đưa mô hình ngôn ngữ lớn (LLM) vào sản phẩm thực tế thông qua code (Python/TypeScript) và các framework RAG/Agent.
*   **LLMOps / AI Infrastructure Engineer**: Chuyên viên vận hành, giám sát, triển khai và tối ưu hóa tài nguyên phần cứng (GPU) cho các mô hình AI trong môi trường sản xuất.
*   **Analytics Engineer / AI Data Engineer**: Kỹ sư chuẩn bị và làm sạch dữ liệu chuyên dụng, thiết lập cơ sở dữ liệu Vector để phục vụ cho các mô hình AI.

---

## 2. Những Nghề Nghiệp & Kỹ Năng Đang Khan Hiếm (Cầu Vượt Quá Cung)

Mặc dù có nhiều người học lập trình và AI, thị trường đang đối mặt với sự thiếu hụt nghiêm trọng nguồn nhân lực chất lượng cao có năng lực thực chiến trong các mảng sau:

| Kỹ năng / Vai trò khan hiếm | Lý do khan hiếm | Yêu cầu thực tế từ doanh nghiệp |
| :--- | :--- | :--- |
| **Senior AI Engineer / Architect** | Lĩnh vực Agentic AI và LLM còn quá mới (bùng nổ từ cuối 2023), chưa có nhiều chuyên gia tích lũy đủ kinh nghiệm thực chiến. | Khả năng thiết kế hệ thống multi-agent hoạt động ổn định, kiểm soát được chi phí API (FinOps) và xử lý lỗi hệ thống tốt. |
| **LLMOps & GPU Optimization** | Đòi hỏi sự kết hợp phức tạp giữa kiến thức phần cứng (GPU), mạng máy tính, ảo hóa (Docker/Kubernetes) và kiến thức về Deep Learning/LLM. | Tối ưu hóa latency (độ trễ), throughput, triển khai các kỹ thuật quantization (lượng tử hóa) và phục vụ mô hình hiệu năng cao (vLLM, Ollama). |
| **AI Evaluation & Guardrails** | Rất khó để đánh giá khách quan hiệu năng của AI khi dữ liệu đầu vào luôn biến động và tính chất ngôn ngữ tự nhiên phức tạp. | Thiết lập các hệ thống đánh giá tự động (Ragas, TruLens) và các bộ lọc bảo vệ (Guardrails) chống tấn công prompt injection, rò rỉ dữ liệu. |

---

## 3. Những Bất Ngờ & Năng Lực Đang Bị Định Giá Lại

Sự tiến hóa thần tốc của AI đã làm thay đổi nhanh chóng quan điểm đánh giá nhân lực của các nhà tuyển dụng:

### Điều gây bất ngờ nhất:
*   **Sự xuất hiện và chuẩn hóa của MCP (Model Context Protocol)**: Giao thức này đang cách mạng hóa cách các Agent tương tác với môi trường bên ngoài. Việc kết nối AI với các IDE, cơ sở dữ liệu hay API không còn là các giải pháp chắp vá mà đã được chuẩn hóa, giúp rút ngắn thời gian phát triển hệ thống Agent cực kỳ nhanh chóng.

### Năng lực đang bị định giá lại (Giảm giá trị):
*   **Prompt Engineering thuần túy (Basic Prompting)**: Khả năng viết các câu lệnh đơn giản (như viết bài viết, tóm tắt cơ bản) đang mất dần giá trị. Các mô hình LLM thế hệ mới (GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro) ngày càng thông minh hơn, có khả năng tự suy luận và tự tối ưu hóa prompt đầu vào.
*   **Lập trình viết code lặp đi lặp lại (boilerplate code)**: Việc viết code cơ bản, cấu trúc khung ứng dụng đơn giản đang được thay thế bằng các AI coding assistant (như Github Copilot, Cursor). Do đó, những lập trình viên chỉ biết viết code theo khuôn mẫu mà thiếu tư duy kiến trúc đang bị định giá lại thấp hơn.

### Năng lực được định giá cao hơn (Tăng giá trị):
*   **Tư duy hệ thống và Tích hợp công cụ (System Thinking & Integration)**: Năng lực hiểu sâu về luồng đi của dữ liệu, biết cách phân rã bài toán kinh doanh lớn thành các nhiệm vụ nhỏ cho các agent thực hiện và giám sát hiệu năng hệ thống.
*   **Kỹ năng giải quyết vấn đề bằng AI (AI Problem Solving)**: Khả năng nhận diện điểm nghẽn của doanh nghiệp và thiết kế giải pháp AI phù hợp (chọn RAG hay Agent, cấu hình Guardrails ra sao, tối ưu chi phí token thế nào).

---

## 4. Kết Luận Bằng Một Câu

> **"Thị trường tương lai sẽ ưu tiên và tưởng thưởng xứng đáng cho những nhân lực có tư duy hệ thống vững chắc, sở hữu năng lực thiết kế và vận hành các hệ thống AI tự động hóa (Agentic AI) có khả năng tự động giải quyết các bài toán thực tế phức tạp một cách độc lập, tin cậy và tối ưu chi phí (FinOps)."**
