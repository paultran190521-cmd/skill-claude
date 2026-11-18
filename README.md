# KHO TỔNG HỢP SKILL CLAUDE & HỆ THỐNG AI AGENTS MÃ NGUỒN MỞ

> **Repository:** [skill-claude](https://github.com/paultran190521-cmd/skill-claude)  
> **Cập nhật:** Tháng 11/2026  
> **Mục tiêu:** Cẩm nang tra cứu và thư viện tổng hợp các Kỹ năng (Skills) cho Claude Code, trợ lý lập trình mã nguồn mở, hệ thống tự động hóa video, tối ưu token ngữ cảnh và kiến trúc đa tác tử (Multi-Agent).

---

## 📑 MỤC LỤC TRA CỨU NHANH (INDEX)

1. [Dựng Video Tự Động & Lập Trình Video](#1-hệ-thống-dựng-video-tự-động--lập-trình-video)
2. [Coding Agents & Trợ Lý Lập Trình](#2-coding-agents--trợ-lý-lập-trình)
3. [Tối Ưu Hóa Token & Đồ Thị Tri Thức Codebase](#3-tối-ưu-hóa-token--đồ-thị-tri-thức-codebase)
4. [Tự Động Hóa Trình Duyệt & Hệ Thống Đa Tác Tử](#4-tự-động-hóa-trình-duyệt--hệ-thống-đa-tác-tử)
5. [Mô Hình Mã Nguồn Mở & Hạ Tầng Local Offline](#5-mô-hình-mã-nguồn-mở--hạ-tầng-local-offline)
6. [Kỹ Năng Thiết Kế UI Chống Mùi AI (Anti-AI-Slop)](#6-kỹ-năng-thiết-kế-ui-chống-mùi-ai-anti-ai-slop)
7. [Phân Tích Dữ Liệu & Reverse Engineering](#7-phân-tích-dữ-liệu--reverse-engineering)
8. [Ứng Dụng Tự Host & Doanh Nghiệp Bảo Mật](#8-ứng-dụng-tự-host--doanh-nghiệp-bảo-mật)
9. [Bộ Kỹ Năng Đóng Gói (Skills) Chuyên Ngành](#9-bộ-kỹ-năng-đóng-gói-skills-chuyên-ngành)
10. [Hướng dẫn cài đặt Skill vào Claude Code & Cursor](#10-hướng-dẫn-cài-đặt-skill-vào-claude-code--cursor)

---

## 1. HỆ THỐNG DỰNG VIDEO TỰ ĐỘNG & LẬP TRÌNH VIDEO

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Remotion** | [remotion-dev/remotion](https://github.com/remotion-dev/remotion) | ~70K ⭐ | Dựng video có thể lập trình hoàn toàn bằng React, CSS và Canvas. Thay đổi file JSON để render hàng loạt video biến thể tự động. |
| **OpenMontage** | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | Nổi bật | Hệ thống điều phối AI Agent sản xuất video ngắn/Reels từ kịch bản, gom 12 quy trình và có trạm duyệt chi phí trước khi render. |
| **MoneyPrinterTurbo** | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | ~25K+ ⭐ | Tự động hóa sản xuất video ngắn: 1 câu lệnh $\rightarrow$ AI tự viết script, tải b-roll stock, đọc giọng AI tiếng Việt và chèn phụ đề. |
| **ShortGPT** | [RayVentura/ShortGPT](https://github.com/RayVentura/ShortGPT) | ~11K ⭐ | Framework tự động hóa video ngắn (Shorts/TikTok/Reels), căn phụ đề và render video dọc tự động. |
| **video-shotcraft** | [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | ~18.9K ⭐ | Skill cho Claude Code / Codex dựng video quảng cáo sản phẩm bằng Remotion kèm 124 shot recipes & 150 motion presets. |
| **HyperFrames** | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | Trending | Viết mã HTML/CSS và Canvas động để AI Agent tự render thành video MP4 chất lượng cao. |
| **Three.js** | [mrdoob/three.js](https://github.com/mrdoob/three.js) | ~105K ⭐ | Thư viện 3D JavaScript mạnh nhất, dùng tạo không gian và hiệu ứng 3D cho video lập trình. |
| **GSAP** | [greensock/GSAP](https://github.com/greensock/GSAP) | ~20K ⭐ | Thư viện tạo hiệu ứng chuyển động siêu mượt cho chữ, hình ảnh và đồ họa. |
| **Manim** | [3b1b/manim](https://github.com/3b1b/manim) | ~75K ⭐ | Công cụ chuyên vẽ đồ họa và hoạt họa toán học/khoa học/biểu đồ do Grant Sanderson (3Blue1Brown) sáng lập. |
| **Blender MCP** | [ahujasid/mcp-for-blender](https://github.com/ahujasid/mcp-for-blender) | Nổi bật | Kết nối AI Coding Agent trực tiếp vào phần mềm 3D Blender qua giao thức MCP để AI tự tạo cảnh và render 3D. |
| **FFmpeg** | [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg) | ~55K ⭐ | Bộ công cụ dòng lệnh đa năng xử lý cắt ghép video, nén âm thanh, gán phụ đề. |

---

## 2. CODING AGENTS & TRỢ LÝ LẬP TRÌNH

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Cline** | [cline/cline](https://github.com/cline/cline) | ~71.5K ⭐ | Autonomous coding agent trong VS Code / JetBrains, chạy lệnh terminal, sửa file, test giao diện qua MCP, chế độ Plan/Act. |
| **Aider** | [Aider-AI/aider](https://github.com/Aider-AI/aider) | ~50.1K ⭐ | AI pair-programming chạy trực tiếp trong terminal, tự động commit Git sạch sẽ theo từng bước, có Repository Map thông minh. |
| **Claude Code** | [anthropics/claude-code](https://github.com/anthropics/claude-code) | Chính thức | Agent dòng lệnh chính thức của Anthropic, tự điều tra dự án, chỉnh sửa code đa file, chạy test và tự sửa lỗi theo `CLAUDE.md`. |
| **Everything Claude Code (ECC)** | [affinda/everything-claude-code](https://github.com/affinda/everything-claude-code) | Nổi bật | Kho tổng hợp các cấu hình `CLAUDE.md`, mẹo prompt và kiến trúc mở rộng tối ưu cho Claude Code. |
| **Devika** | [stitionai/devika](https://github.com/stitionai/devika) | ~22K ⭐ | Kỹ sư phần mềm AI mã nguồn mở tự bóc tách yêu cầu, sửa lỗi code và chạy kiểm thử tự động. |
| **PydanticAI** | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | ~10K+ ⭐ | Framework xây dựng AI agent hướng dữ liệu nghiêm ngặt bằng Python, hỗ trợ chạy sub-agents song song. |
| **DSH Go** | [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | ~15K ⭐ | App Android điều khiển DeepSeek Harness trên máy tính ở nhà từ xa qua SSH / DSH Remote an toàn. |

---

## 3. TỐI ƯU HÓA TOKEN & ĐỒ THỊ TRI THỨC CODEBASE

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Graphify** | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | Nổi bật | Phân tích repo thành Đồ thị tri thức (Knowledge Graph) bằng `tree-sitter` cục bộ. Giúp AI chỉ đọc đúng hàm/file cần sửa, giảm đến **80% chi phí token**. |
| **Agent Reach** | [agentreach/agentreach](https://github.com/agentreach/agentreach) | Trending | Duy trì bộ nhớ dài hạn cho AI Agent xuyên suốt nhiều phiên làm việc mà không làm phình Context Window. |

---

## 4. TỰ ĐỘNG HÓA TRÌNH DUYỆT & HỆ THỐNG ĐA TÁC TỬ

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Browser-Use** | [browser-use/browser-use](https://github.com/browser-use/browser-use) | ~40K+ ⭐ | Điều khiển trình duyệt bằng Vision LLM: tự động click, điền form, cào dữ liệu, giải quyết tác vụ nhiều bước trên web. |
| **CrewAI** | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | ~30K+ ⭐ | Thiết lập nhóm AI agent phối hợp đa tác vụ: Researcher tìm kiếm $\rightarrow$ Writer soạn thảo $\rightarrow$ QA duyệt bài. |
| **AutoGen** | [microsoft/autogen](https://github.com/microsoft/autogen) | ~40K+ ⭐ | Framework của Microsoft hỗ trợ nhiều agent hội thoại qua lại để giải quyết bài toán phức tạp. |
| **AutoGPT** | [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ~170K ⭐ | Dự án agent độc lập tự chia nhỏ mục tiêu lớn thành chuỗi tác vụ con và thực thi tự động. |
| **Anthropic Computer Use** | [anthropics/anthropic-quickstarts](https://github.com/anthropics/anthropic-quickstarts) | Chính thức | Mã nguồn mẫu cho Claude điều khiển chuột, bàn phím và màn hình máy tính như người thật. |
| **TheAgentCompany** | [TheAgentCompany/TheAgentCompany](https://github.com/TheAgentCompany/TheAgentCompany) | Đột phá | Môi trường mô phỏng doanh nghiệp để thử nghiệm và đo lường khả năng giải quyết tác vụ văn phòng của agent. |

---

## 5. MÔ HÌNH MÃ NGUỒN MỞ & HẠ TẦNG LOCAL OFFLINE

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Qwen 2.5 Coder** | [QwenLM/Qwen2.5-Coder](https://github.com/QwenLM/Qwen2.5-Coder) | Hàng đầu | Mô hình chuyên lập trình mã nguồn mở của Alibaba, ngang ngửa Claude 3.5 Sonnet / GPT-4o, có thể tải về chạy offline. |
| **Ollama** | [ollama/ollama](https://github.com/ollama/ollama) | ~120K ⭐ | Công cụ chuẩn hóa việc chạy các mô hình ngôn ngữ lớn (Llama 3, DeepSeek, Qwen) cục bộ trên máy tính chỉ với 1 dòng lệnh. |
| **llama.cpp** | [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | ~80K ⭐ | Engine suy luận LLM bằng C/C++ thuần túy, tối ưu hóa lượng tử GGUF để chạy mượt trên CPU/GPU cá nhân. |

---

## 6. KỸ NĂNG THIẾT KẾ UI CHỐNG MÙI AI (ANTI-AI-SLOP)

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Taste Skill** | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | ~115K ⭐ | Kỹ năng định hướng thẩm mỹ cho coding agent: dạy AI dựng trang web có gu thực tế, loại bỏ gradient tím neon sáo rỗng. |
| **Hallmark** | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | ~54.5K ⭐ | Bộ quy chuẩn của Together AI: tích hợp 50 phong cách thiết kế hiện đại và bộ soát lỗi tự động phát hiện "dấu hiệu lộ là AI làm". |

---

## 7. PHÂN TÍCH DỮ LIỆU & REVERSE ENGINEERING

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Data Analysis Agent** | [Zafer-Liu/Data-Analysis-Agent](https://github.com/Zafer-Liu/Data-Analysis-Agent) | ~2.6K ⭐ | Tác tử AI phân tích số liệu: Đọc file Excel/CSV, nối SQL, tự viết truy vấn, vẽ 41 dạng biểu đồ và xuất file PPT/Word/Excel. |
| **Reverse API Engineer (rae)** | [kalil0321/reverse-api-engineer](https://github.com/kalil0321/reverse-api-engineer) | ~3.6K ⭐ | Bắt gói tin ngầm của website và tự sinh mã Client SDK trên 10 ngôn ngữ lập trình. |
| **Craft Anything** | [storytold/craft-anything](https://github.com/storytold/craft-anything) | ~20K ⭐ | Dựng lại logic trang web và game theo phương pháp "phòng sạch" bằng Rust + Claude Code. |

---

## 8. ỨNG DỤNG TỰ HOST & DOANH NGHIỆP BẢO MẬT

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Upscayl** | [upscayl/upscayl](https://github.com/upscayl/upscayl) | ~52.5K ⭐ | Phóng to & làm nét ảnh bằng AI miễn phí gấp 4 lần, xử lý offline trên GPU qua Vulkan, không gửi ảnh lên mạng. |
| **Resume Matcher** | [srbhr/Resume-Matcher](https://github.com/srbhr/Resume-Matcher) | ~29.3K ⭐ | Khớp CV với JD chấm điểm theo thang 100 để vượt qua hệ thống lọc ATS, chạy offline với Ollama. |
| **Sure** *(Maybe fork)* | [we-promise/sure](https://github.com/we-promise/sure) | ~15K ⭐ | Quản lý tài chính cá nhân tự host mã nguồn mở kế thừa Maybe Finance, theo dõi dòng tiền, tài sản ròng qua Docker. |
| **Securo** | [securo-finance/securo](https://github.com/securo-finance/securo) | ~4.5K ⭐ | Lập ngân sách và chi tiêu cá nhân tự host bảo mật, tự động phân loại giao dịch từ sao kê CSV/OFX/QIF. |
| **Twenty CRM** | [twentyhq/twenty](https://github.com/twentyhq/twenty) | ~30K+ ⭐ | CRM mã nguồn mở hiện đại thay thế Salesforce / HubSpot, giao diện đẹp mắt, tự quản lý dữ liệu trên máy chủ riêng. |
| **AnythingLLM** | [mintplex-labs/anything-llm](https://github.com/mintplex-labs/anything-llm) | ~35K+ ⭐ | Dựng ChatGPT riêng tư cho doanh nghiệp (RAG), phân quyền theo phòng ban, kết nối PDF/Docx/Notion. |
| **FeedLog** | [linkcraftstudio/feedlog](https://github.com/linkcraftstudio/feedlog) | Nổi bật | Hệ thống AI chăm sóc khách hàng tự động theo tài liệu nội bộ và quản lý lộ trình sản phẩm công khai. |

---

## 9. BỘ KỸ NĂNG ĐÓNG GÓI (SKILLS) CHUYÊN NGÀNH

| Tên công cụ / Repo | Link GitHub | Lượt sao (Stars) | Công dụng & Tính năng chính |
|:---|:---|:---:|:---|
| **Earshot MCP** | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | ~4.5K ⭐ | Gắn "tai nghe" cho Claude Code để phân tích âm thanh, tìm đoạn nhạc khớp với video và lập trình hiệu ứng âm thanh. |
| **Marketing Skills** | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | ~57.6K ⭐ | 53 kỹ năng marketing chuyên nghiệp đóng gói cho Claude Code / Cursor (copywriting, SEO, launch). |
| **Founder Skill** | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) | Nổi bật | 11 kỹ năng thẩm định dự án khởi nghiệp với hội đồng ảo và 100 khách hàng ảo mô phỏng. |
| **Podcastfy** | [souzatharsis/podcastfy](https://github.com/souzatharsis/podcastfy) | Trending | Tự động chuyển đổi tài liệu văn bản thành tập podcast đối thoại 2 người dẫn chuyện tự nhiên. |
| **GenOffice** | [genoffice/genoffice](https://github.com/genoffice/genoffice) | Nổi bật | Tự động sinh bài thuyết trình PowerPoint và tài liệu báo cáo văn phòng đẹp mắt từ kịch bản AI. |
| **Mika Handheld** | [mika-handheld/mika](https://github.com/mika-handheld/mika) | DIY AI | Bản thiết kế phần cứng và phần mềm mã nguồn mở để tự chế máy trợ lý ảo AI cầm tay. |

---

## 10. HƯỚNG DẪN CÀI ĐẶT SKILL VÀO CLAUDE CODE & CURSOR

### 1. Cấu hình tệp `CLAUDE.md` tại thư mục gốc dự án:
Tạo tệp `CLAUDE.md` để hướng dẫn ngữ cảnh, quy chuẩn code và phong cách làm việc cho Claude Code:

```markdown
# Quy chuẩn Dự án

- Framework: React / Next.js / TypeScript
- Thiết kế: Áp dụng quy tắc Taste Skill (không dùng gradient tím sáo rỗng, ưu tiên giao diện tinh tế thực tế)
- Tối ưu Token: Tra cứu cấu trúc file trước khi đọc toàn bộ nội dung
- Kiểm thử: Tự động chạy test sau mỗi lần sửa mã
```

### 2. Đóng gói kỹ năng theo chuẩn `SKILL.md`:
Đặt các kỹ năng chuyên biệt trong thư mục `.claude/skills/<ten-skill>/SKILL.md`:
```yaml
---
name: ten-skill
description: Mô tả khi nào Claude nên kích hoạt skill này
---
# Hướng dẫn chi tiết từng bước cho Agent...
```

---

*Tài liệu được tổng hợp và duy trì bởi cộng đồng yêu thích AI và tự động hóa.*
