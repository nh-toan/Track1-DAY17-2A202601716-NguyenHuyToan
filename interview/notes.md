# Interview Record

> **Không điền bằng dữ liệu giả.** File này chỉ ghi những gì thực sự xảy ra trong lượt bạn làm interviewer.

## Metadata

- **Mã người tham gia:** `2A202602017`
- **Role:** `learner`
- **Đúng tiêu chí tuyển:** `Có`
- **Ngày phỏng vấn:** `2026-08-17`
- **Interviewer:** `Nguyễn Phi Hoàng`
- **Note-taker:** `Nguyễn Phi Hoàng`
- **Recording consent:** `Có`

---

## 1. Câu chuyện gần nhất: user đang ở đâu và có làm gì?

- **Bối cảnh:** Buổi tự học trực tuyến làm bài Lab "Fine-tuning LLM với LoRA và Quantization" trên hệ thống LMS vào tối thứ Sáu (3 ngày trước).
- **Trigger:** Đọc đến phần cấu hình tham số `target_modules` cho LoRA và bài toán tính toán dung lượng VRAM khi load mô hình 4-bit/8-bit.
- **Mục tiêu/job lúc đó:** Muốn hiểu bản chất cách tính VRAM và hoàn thành bài lab đúng deadline 23:59 đêm để không bị nợ bài sang tuần sau.

---

## 2. User đã thực sự làm gì?

Timeline:

1. **21:45:** Đọc slide 14-16 ba lần liên tiếp, dừng lại ở Slide 15 gần 12 phút để soi lại sơ đồ kiến trúc LoRA và các ma trận $W_0 + \Delta W = W_0 + BA$.
2. **22:05:** Bấm làm bài Quiz kiểm tra nhanh ở cuối bài (3 câu). Ở câu 2 về tính toán VRAM, chọn đáp án B (sai), sau đó quay lại chọn đáp án C (đúng), nhưng vẫn băn khoăn không hiểu vì sao C đúng.
3. **22:20:** Copy đoạn text khái niệm và mã lỗi giả lập từ bài lab dán sang ChatGPT tab bên cạnh để hỏi. ChatGPT trả lời một đoạn dài về lý thuyết chung Transformer nhưng không giải thích đúng bối cảnh bài tập của LMS.
4. **22:45:** Định nhắn tin lên kênh Discord của lớp để hỏi Mentor, nhưng nhìn đồng hồ đã muộn và thấy các bạn khác không ai hỏi gì, sợ bị đánh giá là không đọc slide kỹ.
5. **23:15:** Quyết định nộp bài lab với phần giải thích chưa tự tin để kịp deadline 23:59.
6. **Thứ Bảy (hôm sau):** Mở lại recording buổi giảng tuần trước để tua đến đoạn giảng viên nói về LoRA, mất thêm 1.5 tiếng để xem lại.

---

## 3. Khó khăn và workaround đã dùng

- **Khó khăn:**
  - Không tự tin rằng mình đã thực sự hiểu đúng cơ chế tính VRAM của LoRA hay chỉ đang chọn bừa đáp án Quiz.
  - Ngại chủ động nhắn tin hỏi Mentor/Giảng viên lúc đêm muộn vì rào cản tâm lý sợ làm phiền hoặc sợ bị đánh giá.
  - AI Chat bên ngoài (ChatGPT) trả lời quá chung chung, không nắm được bối cảnh tài liệu lab của khóa học.
- **Workaround:**
  - Tua đi tua lại slide nhiều lần và dừng ở slide lâu hơn (dwell time dài).
  - Thử lại đáp án quiz (trial-and-error).
  - Copy prompt ra công cụ AI bên ngoài.
  - Xem lại video recording sau buổi học.
- **Vì sao chọn workaround đó:** Muốn tự giải quyết nhanh tại chỗ mà không phải công khai thừa nhận mình đang không hiểu trước mặt lớp hay làm phiền giảng viên đêm muộn.

---

## 4. Hậu quả hoặc chi phí

- **Thời gian:** Mất thêm 1 tiếng 30 phút trong đêm thứ Sáu để loay hoay tự xử lý + mất thêm 1.5 tiếng ngày thứ Bảy xem lại recording (tổng cộng ~3 tiếng).
- **Ảnh hưởng tới tiến độ:** Nộp bài trễ hơn mốc tự đề ra 45 phút; mệt mỏi tâm lý trong đêm.
- **Ảnh hưởng tới phần học tiếp theo:** Sang bài lab tiếp theo về "Deploy LoRA Adapter", do chưa nắm vững bản chất VRAM nên khi gặp lỗi OOM (Out Of Memory) lại bị lúng túng tiếp.
- **Có phải quay lại / học lại không:** Có, phải dành nửa ngày cuối tuần xem lại recording bài cũ.
- **Hậu quả khác:** Mất tự tin khi tham gia các buổi lab tiếp theo, luôn có cảm giác mình bị tụt lại so me với lớp.

---

## 5. Điều bất ngờ, trái giả thuyết hoặc exact quote

### Exact quote
> "Lúc 10h30 đêm rồi, mình ngại nhắn lên Discord của lớp lắm vì thấy các bạn khác yên lặng hết rồi, tự nhiên mình hỏi một câu cơ bản sợ mọi người nghĩ mình không đọc kỹ slide."

> "ChatGPT nó giải thích lý thuyết thì hay lắm, nhưng vào đúng cái file lab và thông số r=8, alpha=16 của thầy cho thì nó trả lời linh tinh, mình càng đọc càng rối."

### Evidence trái hypothesis
- Học viên **KHÔNG HỀ thụ động hay lười biếng**: Họ đã chủ động dùng AI Chat (ChatGPT) và đọc đi đọc lại slide 3 lần. Tuy nhiên, các công cụ AI tự do bên ngoài không giải quyết được nút thắt bối cảnh (context-specific pain).

### Điều bất ngờ
- Học viên không hề ghét việc giảng viên/mentor chủ động liên hệ. Ngược lại, họ bày tỏ rằng nếu lúc đó giảng viên nhắn: *"Hình như em đang dừng ở phần VRAM LoRA hơi lâu đúng không, có cần hỗ trợ không?"* thì họ sẽ cực kỳ nhẹ nhõm và chia sẻ ngay lập tức.

---

## 6. Fact vs Interpretation

### Facts / observed behavior
- Dừng ở Slide 15 trong 12 phút.
- Thay đổi đáp án Quiz câu 2 từ B sang C.
- Copy text ra ngoài ChatGPT 3 lần.
- Không nhắn tin lên kênh Discord của lớp.
- Mở xem lại recording vào 10:15 sáng thứ Bảy.

### Interpretation của tôi
- Learner bị kẹt trong trạng thái "Silent Struggle" do rào cản tâm lý (ngại làm phiền/sợ bị đánh giá) cộng với sự thiếu hiệu quả của các workaround tự do (ChatGPT trả lời lệch bối cảnh). Đây là một pain point có thật và gây ra hậu quả lãng phí thời gian đáng kể (~3 tiếng).

---

## 7. Practice note

- **Câu hỏi nào mở được story:** *"Kể mình nghe về lần gần nhất trong một buổi lab bạn gặp một phần mà lúc đó bạn đọc xong vẫn chưa chắc mình hiểu đúng?"* — Câu hỏi này neo đúng thời điểm thứ Sáu vừa qua và khiến learner kể ngay câu chuyện LoRA VRAM.
- **Chỗ nào tôi dẫn dắt:** Lúc learner bảo ngại nhắn tin, tôi suýt hỏi *"Có phải bạn sợ giảng viên mắng không?"* — Rất may đã kịp nén lại và sửa thành *"Điều gì khiến bạn chọn không nhắn tin vào lúc đó?"*.
- **Chỗ nào đáng ra nên đào sâu:** Đáng lẽ nên hỏi kỹ hơn về cảm xúc và suy nghĩ của learner lúc đổi đáp án Quiz từ B sang C (liệu họ có biết tại sao C đúng không hay chỉ là may mắn).
- **Câu hỏi nào cần sửa trong Conversation Guide:** Cần bổ sung câu probe: *"Khi công cụ AI bên ngoài trả lời xong, bạn dựa vào đâu để biết câu trả lời đó có áp dụng được cho bài lab của bạn hay không?"*.
