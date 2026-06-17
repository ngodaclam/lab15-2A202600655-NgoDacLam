# Nghiên Cứu Vai Trò AI Engineer & Đối Chiếu Bản Thân (Bộ Câu Hỏi 5)

Báo cáo này nghiên cứu chi tiết vai trò mục tiêu **AI Engineer (Kỹ sư ứng dụng AI)** bằng việc phân tích các yêu cầu tuyển dụng thực tế trên thị trường, đồng thời tự đối chiếu với năng lực bản thân tích lũy được trong Phase 1.

---

## 1. Nghiên Cứu Yêu Cầu Từ Bên Ngoài (Job Descriptions Thực Tế)

Dưới đây là tổng hợp thông tin tuyển dụng từ 2 Job Description (JD) thực tế đối với vị trí AI Engineer tại Việt Nam.

### JD 1: Kỹ Sư Ứng Dụng AI (AI Application Engineer) - FPT Software
*   **Mức lương & Hình thức**: Thỏa thuận | Toàn thời gian.
*   **Yêu cầu kỹ năng chính**:
    *   Thành thạo lập trình **Python**, làm việc tốt với các LLM API (OpenAI, Anthropic, Gemini) và các mô hình mã nguồn mở.
    *   Có kinh nghiệm xây dựng hệ thống **RAG** (Retrieval-Augmented Generation) sử dụng **LangChain** hoặc **LlamaIndex**.
    *   Sử dụng thành thạo cơ sở dữ liệu Vector (như Pinecone, Milvus, ChromaDB, PGVector).
    *   Biết cách thiết lập cơ chế **Tool Calling** và kết nối API ngoài.
*   **Mức Seniority**: Junior - Middle (1 - 3 năm kinh nghiệm lập trình, tối thiểu 6 tháng làm việc trực tiếp với LLM/RAG).
*   **Kỳ vọng Portfolio**:
    *   GitHub repository chứa mã nguồn của một ứng dụng RAG chạy thực tế (ví dụ: Chatbot trả lời câu hỏi dựa trên tài liệu nội bộ).
    *   Có demo chứng minh khả năng tối ưu hóa truy xuất dữ liệu (Hybrid Search) và xử lý ảo giác (Anti-hallucination).

### JD 2: AI Engineer (Agent & Automation) - VNG Corporation
*   **Mức lương & Hình thức**: Thỏa thuận | Toàn thời gian.
*   **Yêu cầu kỹ năng chính**:
    *   Thiết kế luồng hoạt động tự động của Agent sử dụng các framework như **LangGraph** hoặc **CrewAI**.
    *   Khả năng tích hợp mô hình với hệ thống nghiệp vụ thông qua giao thức kết nối công cụ nâng cao (như **MCP - Model Context Protocol**).
    *   Kinh nghiệm về deploy mô hình và Docker hóa ứng dụng; có kiến thức cơ bản về CI/CD cho hệ thống AI.
    *   Ưu tiên ứng viên có kiến thức về tinh chỉnh mô hình (**Fine-tuning**) bằng kỹ thuật LoRA, QLoRA.
*   **Mức Seniority**: Middle (2+ năm kinh nghiệm trong phát triển sản phẩm công nghệ, hiểu sâu về kiến trúc Agent).
*   **Kỳ vọng Portfolio**:
    *   Các dự án thực tế về Multi-Agent (ví dụ: Hệ thống agent tự động phân tích thị trường, viết báo cáo tài chính).
    *   Minh chứng về việc giám sát và tối ưu hóa hệ thống agent (Observability), kiểm soát chi phí token đầu vào/đầu ra.

---

## 2. Đối Chiếu Năng Lực Bản Thân (Bên Trong)

Dưới đây là phần tự đánh giá năng lực của bản thân (**Ngô Đắc Lâm**) sau khi hoàn thành Phase 1 của chương trình:

### Kỹ năng đã chạm ở Phase 1 (kèm theo Artifact minh chứng):
1.  **Prompt Engineering & Tool Calling** (Đã thực hành tại Day 4):
    *   *Artifact minh chứng*: File lab Prompt Engineering và cấu hình gọi công cụ thông minh tùy thuộc ngữ cảnh của người dùng.
2.  **Xây dựng RAG Pipeline** (Đã thực hành tại Day 8):
    *   *Artifact minh chứng*: Dự án RAG hoàn chỉnh kết hợp cơ sở dữ liệu vector và cơ chế kiểm soát chất lượng câu trả lời.
3.  **Hệ thống Multi-Agent & Kết nối MCP** (Đã thực hành tại Day 9):
    *   *Artifact minh chứng*: Dự án xây dựng hệ thống multi-agent (Supervisor-Worker) sử dụng các MCP Server để đọc dữ liệu và vận hành công cụ cục bộ.
4.  **Data Pipeline & Observability** (Đã thực hành tại Day 10):
    *   *Artifact minh chứng*: Xây dựng hệ thống thu thập dữ liệu tự động và giám sát chất lượng luồng dữ liệu (Data Pipeline Monitoring).

### Kỹ năng cần đào sâu & Kỹ năng chưa có:
*   **Cần đào sâu**: Kỹ thuật xây dựng GraphRAG (truy xuất nâng cao dựa trên đồ thị kiến thức), tối ưu hóa cấu trúc agent phức tạp có vòng lặp (stateful agent loops) để tránh tình trạng agent bị lặp vô tận.
*   **Chưa có**: Kinh nghiệm Fine-tuning mô hình ngôn ngữ lớn thực tế (LoRA/QLoRA) và tối ưu hóa tài nguyên phần cứng chuyên dụng (GPU/FinOps) cho các mô hình tự triển khai.

### Khớp với loại công việc cho năng lượng:
*   **Rất khớp**: Tôi cảm thấy tràn đầy năng lượng nhất khi làm các công việc thiết kế logic hệ thống, lập trình luồng phối hợp giữa các Agent (Agentic Orchestration), và giải quyết các lỗi logic phát sinh khi Agent gọi công cụ. Những công việc này kích thích tư duy lập trình hệ thống và giải quyết vấn đề của tôi hơn là việc ngồi tinh chỉnh các giao diện người dùng đơn giản.

---

## 3. Kết Luận

> **"Vai trò AI Engineer hoàn toàn nghiêng về track T3 - AI Engineering, bởi vì nó tập trung sâu vào kỹ thuật lập trình Agent, thiết kế kiến trúc truy xuất RAG nâng cao, và tích hợp các LLM vào quy trình tự động hóa nghiệp vụ thực tế của doanh nghiệp."**
