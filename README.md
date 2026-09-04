# AI Agent Architecture — Giáo trình tự học

Website lưu giáo trình 28 bài / 7 chặng về tư duy thiết kế AI Agent, hướng tới mục tiêu tự xây **agent chạy local + API + workflow chuyên biệt**.

## Nội dung

- Tư duy nền tảng về Agent / Workflow / Automation
- Workflow patterns
- Tool Calling, Tool Design, MCP
- Context Engineering, State, Memory
- Agent Loop, Planning, Error Recovery
- Guardrails, Human-in-the-loop, Sandboxing, Evaluation
- Framework & Multi-Agent
- 4 mini project
- Dự án cuối khóa: **Local AI Media Agent**

## Xem website

Trang web nằm ngay tại `index.html` và `styles.css`.

Để xuất bản bằng GitHub Pages:

1. Vào **Settings → Pages** của repository.
2. Ở **Build and deployment**, chọn **Deploy from a branch**.
3. Chọn branch **main** và thư mục **/(root)**.
4. Nhấn **Save**.

Sau khi GitHub Pages được bật, website thường có địa chỉ:

`https://hktruc.github.io/hoc_ai/`

## Cách học đề xuất

- 8–10 tuần
- 3 buổi × 90 phút / tuần
- 30% đọc tài liệu
- 20% tư duy kiến trúc
- 50% làm project

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
EVALUATION
        ↓
FRAMEWORK
        ↓
MODEL
```

> Học để có khả năng nhìn một quy trình công việc thực tế, phân rã nó, xác định phần nào dùng code — phần nào dùng AI — phần nào cần agent tự quyết định. Khi đó framework và model chỉ còn là linh kiện.
