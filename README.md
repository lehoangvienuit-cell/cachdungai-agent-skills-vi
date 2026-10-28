# 10 AI Agent Skills tiếng Việt cho Blog và Fan Page

> Bộ workflow miễn phí do Blog AI biên soạn để giúp người làm nội dung đi từ hiểu độc giả đến viết, phân phối và cải thiện nội dung dựa trên dữ liệu.
>
> **Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)

## Bộ này dành cho ai?

Bộ skill phù hợp với blogger, người làm nội dung, quản trị fan page, giáo viên, sinh viên và người muốn dùng AI để hoàn thành một việc cụ thể. Các hướng dẫn ưu tiên tiếng Việt tự nhiên, ví dụ gần với người dùng Việt Nam và đầu ra có thể chỉnh sửa trước khi xuất bản.

Mười skill đi theo một quy trình thống nhất:

**Định vị thương hiệu → hiểu độc giả → chọn chủ đề → nghiên cứu → lập brief SEO → viết bài → chuyển thể → đăng fan page/video → xem số liệu → cải thiện.**

## 10 skill

| # | Tên | Giúp bạn làm gì? |
|---|---|---|
| 01 | [brand-voice-vi](skills/brand-voice-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/brand-voice-vi.zip) | Tạo hồ sơ thương hiệu, độc giả, giọng điệu và ranh giới nội dung để dùng nhất quán. |
| 02 | [audience-research-vi](skills/audience-research-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/audience-research-vi.zip) | Tìm nhu cầu, câu hỏi, nỗi vướng và cách độc giả thật sự diễn đạt vấn đề. |
| 03 | [content-strategy-vi](skills/content-strategy-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/content-strategy-vi.zip) | Lập trụ cột nội dung, cụm chủ đề và lịch xuất bản vừa với nguồn lực. |
| 04 | [content-research-vi](skills/content-research-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/content-research-vi.zip) | Nghiên cứu một chủ đề thành bộ ý chính có bằng chứng, nguồn và điểm còn chưa rõ. |
| 05 | [seo-content-brief-vi](skills/seo-content-brief-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/seo-content-brief-vi.zip) | Tạo brief SEO tiếng Việt có mục đích tìm kiếm, dàn ý và yêu cầu nội dung rõ ràng. |
| 06 | [vietnamese-blog-writer](skills/vietnamese-blog-writer/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/vietnamese-blog-writer.zip) | Viết bài hướng dẫn thực hành, dễ làm theo và có kiểm soát tính chính xác. |
| 07 | [blog-to-social-vi](skills/blog-to-social-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/blog-to-social-vi.zip) | Chuyển một bài dài thành nội dung riêng cho fan page và các định dạng mạng xã hội. |
| 08 | [facebook-page-content-vi](skills/facebook-page-content-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/facebook-page-content-vi.zip) | Soạn bài Facebook có hook, giá trị cụ thể, gợi ý hình ảnh và CTA phù hợp. |
| 09 | [short-video-script-vi](skills/short-video-script-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/short-video-script-vi.zip) | Viết kịch bản video dọc ngắn, có nhịp hình, lời thoại và chữ trên màn hình. |
| 10 | [content-performance-review-vi](skills/content-performance-review-vi/SKILL.md) · [Tải ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/content-performance-review-vi.zip) | Đọc số liệu nội dung, tách dữ kiện khỏi giả thuyết và đề xuất thử nghiệm tiếp theo. |

[Tải trọn bộ 10 skill dạng ZIP](https://github.com/lehoangvienuit-cell/cachdungai-agent-skills-vi/raw/refs/heads/main/downloads/cachdungai-agent-skills-vi.zip)

## Cài vào Claude

### Claude Code

Chép từng thư mục trong `skills/` vào thư mục skill của dự án:

- Dự án: `.claude/skills/<tên-skill>/SKILL.md`
- Cá nhân: `~/.claude/skills/<tên-skill>/SKILL.md`

Mở lại phiên Claude Code. Gọi skill bằng yêu cầu tự nhiên, ví dụ: “Dùng skill content-research-vi để nghiên cứu chủ đề này rồi tạo brief có nguồn.”

### Claude.ai

Nén **một thư mục skill** thành một tệp ZIP, trong ZIP giữ thư mục skill và file `SKILL.md`. Trong Claude, mở **Customize → Skills → Create skill → Upload a skill**, tải ZIP lên và bật skill. Tính năng skill tùy chỉnh phụ thuộc gói tài khoản và quyền chạy code/file.

## Cài vào ChatGPT và Codex

### ChatGPT có mục Skills

Trong **Plugins → Skills**, chọn **Create → Upload from your computer** và tải ZIP của skill lên. Giao diện Skills chỉ xuất hiện trên những tài khoản/workspace được bật tính năng. Nếu không thấy mục đó, bạn vẫn có thể mở file `SKILL.md`, sao chép hướng dẫn vào Project instructions hoặc dán vào cuộc trò chuyện để dùng như workflow thủ công.

### Codex

Chép thư mục skill vào `.agents/skills/<tên-skill>/SKILL.md` trong dự án. Yêu cầu Codex dùng skill theo tên hoặc mô tả công việc.

## Cách dùng để có kết quả tốt

1. Chọn một skill khớp với việc đang làm; không cần bật cả mười cùng lúc.
2. Cung cấp đầu vào thật: chủ đề, độc giả, mục tiêu, tài liệu gốc, giới hạn thời gian và giọng thương hiệu.
3. Nói rõ đầu ra muốn nhận: dàn ý, bài hoàn chỉnh, caption, kịch bản hay bảng phân tích.
4. Với thông tin có thể thay đổi như giá, tính năng, giao diện phần mềm và chính sách nền tảng, yêu cầu agent kiểm tra bằng nguồn hiện hành nếu có công cụ web.
5. Đọc lại dữ kiện và ví dụ trước khi đăng. Skill hỗ trợ quy trình; người dùng chịu trách nhiệm duyệt nội dung và quyết định xuất bản.

### Ví dụ

- “Dùng `audience-research-vi`. Đây là 40 bình luận của người đọc về việc làm video AI. Hãy nhóm câu hỏi và rào cản, giữ nguyên câu trích dẫn nhưng bỏ thông tin cá nhân.”
- “Dùng `seo-content-brief-vi` cho người mới ở Việt Nam đang muốn học cách viết prompt video. Tạo brief một bài hướng dẫn, không bịa lượng tìm kiếm.”
- “Dùng `blog-to-social-vi` chuyển bài dưới đây thành 3 góc đăng Facebook khác nhau, mỗi góc có CTA về bài gốc.”
- “Dùng `content-performance-review-vi`. Đây là số liệu 28 ngày trước và sau khi đổi tiêu đề; hãy nói rõ điều gì là dữ kiện và điều gì chỉ là giả thuyết.”

## Giới hạn và nguyên tắc

- Skill không thay thế dữ liệu, quyền truy cập, công cụ tìm kiếm hay công cụ đăng bài.
- Nếu không được cấp số liệu hoặc công cụ phù hợp, agent phải nói rõ phần nào chưa kiểm tra được.
- Không tự đăng bài, gửi tin nhắn, bình luận hoặc thay đổi website chỉ dựa trên một bản nháp.
- Không dùng thông tin bịa đặt, lời chứng thực giả, số liệu không kiểm chứng, bình luận giả hoặc spam nhóm để tăng tương tác.
- Watermark trong thư viện dùng để nhận diện bộ tài liệu. Không tự chèn watermark vào nội dung của người dùng trừ khi họ yêu cầu.

## Giấy phép

Bộ skill được phát hành theo MIT License. Khi chia sẻ lại hoặc chỉnh sửa, giữ file `LICENSE` và dòng nhận diện của Blog AI.

---

**Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)
