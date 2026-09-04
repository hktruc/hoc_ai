# AI Agent Architecture — Giáo trình tự học

Website lưu giáo trình **28 bài / 7 chặng** về tư duy thiết kế AI Agent, hướng tới mục tiêu tự xây **agent chạy local + API + workflow chuyên biệt**.

## Bản V3 — học, nộp bài và lưu điểm

- Trang giới thiệu: `index.html`
- **Khóa học chi tiết:** `course.html`
- **Nộp bài & lưu kết quả:** `submit.html`
- Chặng 1: `stage-1.html` — Tư duy nền tảng
- Chặng 2: `stage-2.html` — Workflow Design
- Chặng 3: `stage-3.html` — Tools & MCP
- Chặng 4: `stage-4.html` — Context, State & Memory
- Chặng 5: `stage-5.html` — Agent Loop
- Chặng 6: `stage-6.html` — Reliability & Safety
- Chặng 7: `stage-7.html` — Framework, Multi-Agent & Capstone

Website: https://hktruc.github.io/hoc_ai/

**Giáo trình:** https://hktruc.github.io/hoc_ai/course.html

**Nộp bài:** https://hktruc.github.io/hoc_ai/submit.html

## Cách nộp bài đơn giản

Trang `submit.html` được thiết kế cho một người học duy nhất, không dùng backend, database hay API key:

1. Chọn bài 1–28.
2. Viết bài trực tiếp trên web; nháp được tự lưu bằng `localStorage`.
3. Bấm **Chuẩn bị bài nộp** để tạo và copy một grading packet gồm tên bài, yêu cầu, rubric và bài làm.
4. Bấm **Mở ChatGPT**, dán grading packet vào cuộc trò chuyện để được chấm và phản biện.
5. Quay lại website, nhập điểm và nhận xét để lưu lịch sử các lần nộp.

Mục tiêu chấm không chỉ là sản phẩm chạy được mà là chất lượng **tư duy thiết kế**: decomposition, ranh giới code/AI/human, assumption, overengineering, underengineering, failure modes và lập luận kiến trúc.

## Cấu trúc mỗi bài

Mỗi bài được khai triển theo format:

1. Câu hỏi thiết kế / mục tiêu học.
2. Bài giảng và mô hình tư duy.
3. Sơ đồ hoặc ví dụ thực tế.
4. Bài tập thực hành từng bước.
5. Deliverable / sản phẩm phải làm.
6. Tiêu chí tự đánh giá khi phù hợp.
7. **Nguồn gốc kiến thức gốc** với link trực tiếp tới tài liệu chính thức.

Các mô hình do giáo trình tự tổng hợp (ví dụ `Goal → Task → Subtask → Action → Tool`, ma trận `CODE / LLM / HUMAN`, GREEN/YELLOW/RED) được ghi rõ là **BIÊN SOẠN**, không gán nhầm cho nguồn bên ngoài.

## Nguồn chính

- Anthropic Engineering — Building Effective Agents; Context Engineering; Writing Effective Tools for Agents; Demystifying Evals for AI Agents; Effective Harnesses for Long-Running Agents.
- OpenAI Agents SDK — Agents, Tools, Guardrails, Sessions, Human-in-the-loop, Tracing.
- Model Context Protocol — Specification về Prompts, Resources, Tools.
- LangGraph / LangChain Docs — State, Persistence, Checkpoints, Interrupts, Human-in-the-loop.
- Google Agent Development Kit — agent development lifecycle, tools, sessions/state, evaluation và deployment ecosystem.

## Cách học đề xuất

- 8–10 tuần
- 3 buổi × 90 phút / tuần
- 30% đọc tài liệu
- 20% tư duy kiến trúc
- 50% làm project

Tiến độ, nháp bài, điểm và nhận xét được lưu trên trình duyệt bằng `localStorage`; không cần database hay đăng nhập.

## Nguyên tắc xuyên suốt

```text
BUSINESS PROBLEM
        ↓
WORK PROCESS
        ↓
TASK DECOMPOSITION
        ↓
DETERMINISTIC / AI
        ↓
WORKFLOW
        ↓
TOOLS
        ↓
CONTEXT
        ↓
STATE
        ↓
AGENT LOOP
        ↓
SAFETY
        ↓
EVALUATION
        ↓
FRAMEWORK
        ↓
MODEL
```

> Đích đến là có khả năng nhìn một quy trình công việc thực tế, phân rã nó, xác định phần nào dùng code — phần nào dùng AI — phần nào cần agent tự quyết định. Khi đó framework và model chỉ còn là linh kiện.
