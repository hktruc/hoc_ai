# AI Agent Architecture — Giáo trình tự học

Website lưu giáo trình **28 bài / 7 chặng** về tư duy thiết kế AI Agent, hướng tới mục tiêu tự xây **agent chạy local + API + workflow chuyên biệt**.

## Bản V2 — giáo trình chi tiết

- Trang giới thiệu: `index.html`
- **Khóa học chi tiết:** `course.html`
- Chặng 1: `stage-1.html` — Tư duy nền tảng
- Chặng 2: `stage-2.html` — Workflow Design
- Chặng 3: `stage-3.html` — Tools & MCP
- Chặng 4: `stage-4.html` — Context, State & Memory
- Chặng 5: `stage-5.html` — Agent Loop
- Chặng 6: `stage-6.html` — Reliability & Safety
- Chặng 7: `stage-7.html` — Framework, Multi-Agent & Capstone

Website: https://hktruc.github.io/hoc_ai/

**Vào thẳng giáo trình chi tiết:** https://hktruc.github.io/hoc_ai/course.html

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

## Nội dung

- Tư duy nền tảng về Agent / Workflow / Automation
- Goal → Task → Action và Deterministic vs Probabilistic
- Workflow patterns: chaining, routing, parallelization, orchestrator-worker, evaluator-optimizer
- Function Calling, Tool Design, Tool Router, MCP
- Context Engineering, Context Window, State, Memory, Filesystem as Memory
- Agent Loop, Planning, Stopping Conditions, Error Recovery
- Guardrails, Human-in-the-loop, Sandboxing, Evaluation
- Framework Decision: raw API / OpenAI Agents SDK / LangGraph / Google ADK
- Multi-Agent design
- 4 mini projects
- Dự án cuối khóa: **Local AI Media Agent**

## Cách học đề xuất

- 8–10 tuần
- 3 buổi × 90 phút / tuần
- 30% đọc tài liệu
- 20% tư duy kiến trúc
- 50% làm project

Tiến độ 28 bài được lưu trên trình duyệt bằng `localStorage`; không cần database hay đăng nhập.

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
