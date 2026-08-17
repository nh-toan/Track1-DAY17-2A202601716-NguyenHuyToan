# Track 1 — Day 17: Finding and Validating Pain Points

## Case C — AI Support Radar

> **Đổi tên repo trước khi nộp:** `Track1_Day17_MHV_HoVaTen`

Repo cá nhân này dùng để lưu toàn bộ kết quả bài lab theo 4 chặng:

1. Problem Hypothesis
2. Conversation Guide
3. Interview Practice
4. Reflection & Revision

**Lưu ý quan trọng:** Chặng 3 yêu cầu evidence từ cuộc phỏng vấn thật. Không tự tạo quote, transcript, recording hoặc kết luận “validated”.

---

# 1. Thông tin cá nhân và nhóm

- **Mã học viên (MHV):** `2A202601716`
- **Họ và tên:** `Nguyễn Huy Toàn`
- **Tên nhóm:** `<điền tên nhóm>`
- **Thành viên nhóm:** `Hoàng Bảo Huy - 2A202601440, Nguyễn Phi Hoàng - 2A202601818, Nguyễn Hải Yến - 2A202601604`
- **Case đã chọn:** **Case C — AI Support Radar**

---

# 2. Problem Hypothesis — kết quả Chặng 1

## Solution capability trung tính

> Tổng hợp các dấu hiệu học tập rời rạc sau một phiên học để giúp con người nhận biết và ưu tiên các nhu cầu hỗ trợ có thể đang bị bỏ sót.

## Problem Hypothesis chính

> Khi learner đang học một phiên online/self-paced và gặp một phần chưa hiểu nhưng vẫn cần tiếp tục, họ có thể không yêu cầu hỗ trợ ngay mà thử tự xử lý bằng cách xem lại, chuyển qua lại, sửa đáp án, ghi chú, hỏi AI hoặc bỏ qua tạm thời. Nếu phần vướng không được giải quyết, learner mất thời gian và có thể mang lỗ hổng sang bước tiếp theo; trong khi instructor thường chỉ biết khi learner chủ động hỏi hoặc khi đã xuất hiện kết quả muộn.

## Competing Hypothesis

> Pain chính có thể nằm ở instructor: sau một phiên học có nhiều learner, instructor thiếu visibility để biết ai đang gặp khó khăn nhưng chưa chủ động hỏi và họ đang vướng ở phần nào, dẫn đến triage thủ công, bỏ sót hoặc hỗ trợ muộn.

Chi tiết: [`docs/01_problem_hypothesis.md`](docs/01_problem_hypothesis.md)

---

# 3. Conversation Guide — phiên bản cuối

- Bản chuẩn bị cho Chặng 2: [`docs/02_conversation_guide.md`](docs/02_conversation_guide.md)
- Sau Chặng 3, phải cập nhật file trên thành **phiên bản đã chỉnh sau luyện phỏng vấn**.
- Không pitch hoặc cho interviewee xem solution directive.
- Tập trung vào hành vi đã xảy ra trong quá khứ.

---

# 4. Practice Reflection — Chặng 4

Reflection sau vòng luyện đã được tổng hợp tại [`docs/04_practice_reflection.md`](docs/04_practice_reflection.md).

Evidence synthesis từ 4 interview hiện có nằm tại [`evidence/01_interview_synthesis.md`](evidence/01_interview_synthesis.md).

---

# 5. AI Support Log

| Hạng mục | AI đã hỗ trợ gì? | Điểm AI có thể sai / hời hợt | Tôi đã kiểm tra / chỉnh gì? |
|---|---|---|---|
| Nạp yêu cầu bài lab | Hỗ trợ đọc và tóm tắt yêu cầu Day 17, các chặng làm bài, ba case và tiêu chí nộp repo | AI có thể hiểu thiếu nếu chỉ dựa vào ảnh chụp màn hình | Tôi cung cấp đủ ảnh yêu cầu bài và xác nhận chọn Case C |
| Problem framing | Hỗ trợ reverse-engineer Case C theo chuỗi `Solution → Change → Actor → Situation & Job → Pain → Evidence` | AI chỉ tạo hypothesis, chưa có evidence thật từ user | Tôi và team dùng interview với TA/learner để kiểm chứng |
| Conversation Guide | Hỗ trợ chuyển Evidence Map thành câu hỏi phỏng vấn quá khứ, tránh hỏi ý kiến về solution | Một số câu có thể vẫn dẫn dắt hoặc vô tình nhắc V-Lab/feature | Tôi rà lại sau practice và sửa câu hỏi để neo vào episode cụ thể |
| Transcript cleanup | Hỗ trợ làm sạch transcript TA 2, dựng lại transcript TA 1 từ trí nhớ theo format hội thoại | AI có thể làm câu chữ mượt hơn thực tế hoặc tạo cảm giác là quote nguyên văn | Tôi ghi rõ nguồn: TA 1 là reconstructed transcript, TA 2 là transcript được làm sạch; không dùng TA 1 như exact quote |
| Interview synthesis | Hỗ trợ gom 4 nguồn interview thành pattern, evidence ủng hộ, evidence phản biện và competing hypothesis | AI có thể diễn giải quá tay hoặc biến practice evidence thành kết luận validated | Tôi giữ wording là “evidence làm hypothesis mạnh/yếu hơn”, không tuyên bố validated |
| Reflection & revision | Hỗ trợ viết reflection Chặng 4 và đề xuất sửa Conversation Guide sau practice | AI không thể thay trải nghiệm thật của interviewer | Reflection dựa trên notes/recording/transcript trong `interview/` và synthesis trong `evidence/` |
| Repo organization | Hỗ trợ chuẩn hóa tên file, index interview, README và checklist | AI có thể sắp xếp file không đúng yêu cầu lớp nếu thiếu context | Tôi kiểm tra lại cấu trúc repo, recording, notes và các mục còn thiếu trước khi nộp |

---

# Repo structure

```text
Track1_Day17_MHV_HoVaTen/
├── README.md
├── .gitignore
├── docs/
│   ├── 01_problem_hypothesis.md
│   ├── 02_conversation_guide.md
│   ├── 03_interview_runbook.md
│   ├── 04_practice_reflection.md
│   └── 05_submission_checklist.md
├── interview/
│   ├── README.md
│   ├── notes_p01_ta.md
│   ├── transcript_p01_ta.md
│   ├── notes_p02_ta.md
│   ├── transcript_p02_ta.md
│   ├── recording_p02_ta.m4a
│   ├── notes.md
│   ├── Monday at 12_05_03 pm_1.mp3
│   ├── 03_interview_runbook_01120_completed.md
│   └── recording02017.mp3
└── evidence/
    ├── README.md
    └── 01_interview_synthesis.md
```

## Recording

Nếu có file ghi âm cục bộ, đặt một trong các file sau vào `interview/`:

```text
recording.m4a
recording.mp3
recording.mp4
```

Nếu file nằm trên Drive/nền tảng nội bộ, điền link vào:

[`interview/recording_link.md`](interview/recording_link.md)

Link phải mở được với giảng viên/TA theo yêu cầu của lớp và không cần để công khai toàn Internet.

---

# Trạng thái

- [X] Chặng 1 — Problem Hypothesis
- [X] Chặng 2 — Conversation Guide bản chuẩn bị
- [X] Chặng 3 — Interview Practice thực tế
- [X] Chặng 4 — Reflection & Revision
- [ ] Thay placeholder MHV / Họ tên / Nhóm
- [X] Thêm recording hoặc recording link
- [X] Chỉnh Conversation Guide sau practice
- [ ] Kiểm tra checklist trước khi nộp
