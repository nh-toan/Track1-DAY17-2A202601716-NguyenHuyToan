# 01 — Interview Evidence Synthesis
## Case C — AI Support Radar

> Tổng hợp này gom evidence từ các interview/notes hiện có trong repo. Đây là synthesis để học từ dữ liệu, không phải tuyên bố problem đã validated.

---

# 1. Nguồn dữ liệu đã dùng

| Mã | Vai trò | File notes | Recording / transcript | Điểm chính |
|---|---|---|---|---|
| P01 | TA | `interview/notes_p01_ta.md` | `interview/transcript_p01_ta.md` | Học viên rụt rè, không chủ động giơ tay/request; TA phải quan sát và triage thủ công |
| P02 | TA | `interview/notes_p02_ta.md` | `interview/recording_p02_ta.m4a`, `interview/transcript_p02_ta.md` | Learner không reach out; TA dùng checkpoint, raise hand, Discord, quan sát màn hình |
| L01 | Learner | `interview/notes.md` | `interview/Monday at 12_05_03 pm_1.mp3` | Kẹt phần LoRA/VRAM, tự đọc lại, đổi quiz, hỏi ChatGPT, không hỏi Discord vì ngại |
| L02 | Learner | `interview/03_interview_runbook_01120_completed.md` | `interview/recording02017.mp3` | Gặp khái niệm mới, dùng Gemini Assistant, vẫn mất thời gian suy nghĩ/tìm thêm tài liệu |

---

# 2. Pattern chính sau khi gom evidence

## Pattern A — Silent struggle có xuất hiện ở cả phía TA và learner

Evidence từ TA:

- TA 1 thấy học viên có vẻ đang kẹt nhưng khi hỏi thì học viên nói đã xong hoặc không cần hỗ trợ.
- TA 2 nói có tình huống TA biết học viên đang gặp vấn đề nhưng các bạn không hỏi hoặc không reach out đến mentor.
- Cả hai TA đều phải dựa vào tín hiệu gián tiếp như giơ tay, request nhóm, checkpoint, Discord hoặc quan sát trực tiếp.

Evidence từ learner:

- L01 gặp khó với LoRA/VRAM nhưng không nhắn Discord vì ngại hỏi lúc muộn và sợ bị đánh giá.
- L02 gặp khái niệm mới và tự mở Gemini Assistant thay vì hỏi người ngay.

**Kết luận học được:** Giả thuyết "learner có thể bị kẹt nhưng chưa hỏi" được làm mạnh hơn. Tuy nhiên, cần phân biệt rõ hai dạng: không hỏi vì ngại và không hỏi vì đã có workaround nhanh như AI/search.

---

## Pattern B — Workaround tồn tại nhưng không phải lúc nào giải quyết đủ tốt

Workaround của learner:

- Đọc lại slide/tài liệu nhiều lần.
- Dừng lâu ở một phần.
- Đổi đáp án quiz theo trial-and-error.
- Hỏi ChatGPT/Gemini.
- Xem lại recording.
- Hỏi bạn xung quanh.
- Bỏ qua hoặc nộp bài khi chưa thật sự tự tin.

Evidence cụ thể:

- L01 mất khoảng 3 tiếng tổng cộng: loay hoay trong đêm, nộp bài chưa tự tin, rồi hôm sau xem lại recording.
- L01 dùng ChatGPT nhưng câu trả lời lệch bối cảnh bài lab.
- L02 dùng Gemini Assistant và thấy tiện, nhưng vẫn "phải mất thời gian", phải suy nghĩ hoặc tìm thêm tài liệu.

**Kết luận học được:** AI/search là workaround có thật, nhưng không tự động xóa pain. Pain mạnh hơn khi câu hỏi cần context cụ thể của bài lab, deadline, setup hoặc thông số khóa học.

---

## Pattern C — TA/instructor có visibility một phần, nhưng vẫn có gap

TA hiện đã có một số kênh phát hiện:

- Giơ tay.
- Request trên nhóm.
- Raise hand trong V-Lab.
- Discord ticket/message.
- Checkpoint trong V-Lab.
- Quan sát màn hình khi đi quanh lớp.
- Quiz/bài làm/tiến độ.

Nhưng gap vẫn tồn tại:

- Nhiều học viên không chủ động signal.
- Có học viên nói không cần hỗ trợ dù đang gặp vấn đề.
- TA phải đi hỏi từng bạn hoặc tự quan sát.
- Khi lớp đông hoặc nhiều bạn cần hỗ trợ, triage vẫn thủ công.

**Kết luận học được:** Problem không phải "TA hoàn toàn mù thông tin", mà là tín hiệu đang rời rạc, phụ thuộc vào learner chủ động, và cần TA tự rà/quan sát để phát hiện trường hợp đáng chú ý.

---

## Pattern D — Capacity/hạ tầng là competing bottleneck thật

Evidence:

- TA 1 nhắc case cài môi trường, tài nguyên/hạ tầng mạng giới hạn khiến không thể hỗ trợ kịp, ảnh hưởng tiến độ cả team.
- TA 2 nói trong thời lượng lab có nhiều bạn gặp vấn đề nên không thể tách ra hỗ trợ hết từng bạn.
- Khi nhiều bạn cùng gặp một vấn đề chung, TA thường giải thích chung qua mic/comment thay vì cá nhân hóa.

**Kết luận học được:** Nếu chỉ phát hiện sớm hơn mà TA không có capacity, intervention vẫn có thể chậm. Hypothesis nên giữ nhánh competing: bottleneck có thể là support capacity, không chỉ detection.

---

# 3. Evidence làm hypothesis mạnh hơn

- Learner thật sự có tình huống bị kẹt nhưng không hỏi ngay.
- Rào cản tâm lý xuất hiện rõ: ngại hỏi, sợ bị đánh giá, không muốn làm phiền, không biết hỏi thế nào.
- Learner có workaround nhưng vẫn mất thời gian hoặc còn không chắc mình hiểu đúng.
- TA phải dựa vào nhiều tín hiệu gián tiếp để phát hiện learner đang kẹt.
- Khi TA hỗ trợ, learner thường gỡ được lỗi hoặc tiếp tục bài lab tốt hơn.
- Proactive support có thể được learner chấp nhận: L01 nói nếu mentor chủ động hỏi lúc đang kẹt thì sẽ thấy nhẹ nhõm.

---

# 4. Evidence làm hypothesis yếu đi hoặc cần sửa

- Một số learner đã có workaround khá tiện như Gemini Assistant.
- Với lỗi/vấn đề chung, TA có thể giải thích một lượt cho cả lớp; không phải lúc nào cũng cần queue cá nhân.
- TA đã có một số tín hiệu hiện tại như checkpoint, raise hand, Discord, quan sát màn hình; solution không nên giả định hiện tại không có visibility nào.
- Bottleneck có thể là hạ tầng/capacity, không chỉ là phát hiện muộn.
- Các tín hiệu như dừng lâu, dùng AI hoặc checkpoint thấp cần được kiểm tra cẩn thận vì có thể nhiễu hoặc do nguyên nhân khác.

---

# 5. Problem Hypothesis sau khi học từ interview

## Bản nên dùng sau practice

> Khi learner đang học lab/online lesson và gặp một phần chưa hiểu hoặc lỗi kỹ thuật nhưng vẫn cần tiếp tục, họ có thể không chủ động hỏi TA/mentor ngay vì ngại, không chắc mình hỏi có đúng không, hoặc muốn tự xử lý trước bằng cách đọc lại, hỏi AI/search, hỏi bạn hoặc xem recording. Nếu workaround không giải quyết đúng bối cảnh bài học, learner mất thời gian, chậm tiến độ hoặc tiếp tục với mức hiểu chưa chắc. Trong khi đó, TA có một số tín hiệu như giơ tay, request, checkpoint, Discord và quan sát trực tiếp, nhưng các tín hiệu này rời rạc và phụ thuộc nhiều vào learner chủ động, khiến TA vẫn phải triage thủ công và có thể phát hiện muộn những learner rụt rè hoặc silent struggle.

## Competing hypothesis cần giữ

> Trong một số case, pain chính không nằm ở việc phát hiện learner đang gặp khó mà nằm ở capacity/hạ tầng: TA biết có nhiều learner cần hỗ trợ nhưng không đủ thời gian, nhân lực hoặc điều kiện kỹ thuật để can thiệp kịp.

---

# 6. Sửa Conversation Guide sau practice

Những câu nên thêm hoặc nhấn mạnh:

1. "Lần gần nhất bạn bị kẹt ở một khái niệm/lỗi cụ thể là khi nào?"
2. "Ngay sau khi bị kẹt, bạn làm gì đầu tiên?"
3. "Bạn có dùng AI/search/recording/bạn học không? Cách đó giúp đến đâu và còn thiếu gì?"
4. "Điều gì khiến bạn chưa hỏi TA/mentor ngay lúc đó?"
5. "Bạn mất khoảng bao lâu từ lúc kẹt đến lúc tiếp tục được?"
6. "Nếu TA/mentor biết bạn đang kẹt sớm hơn trong tình huống đó, điều gì thực tế có thể khác?"
7. Cho TA: "Bạn dựa vào tín hiệu cụ thể nào để biết learner đang kẹt nếu họ không tự hỏi?"
8. Cho TA: "Có lần nào bạn đã biết learner cần hỗ trợ nhưng vẫn không thể hỗ trợ kịp vì thiếu thời gian/tài nguyên không?"

Những câu nên tránh:

- "Bạn có muốn dùng V-Lab/AI Support Radar không?"
- "Nếu có app raise hand online thì có giải quyết được không?"
- "Bạn có thích được hệ thống phát hiện không?"

---

# 7. Kết luận thực hành

Evidence hiện tại đủ để nói hypothesis **đáng tiếp tục điều tra và nên được chỉnh sắc hơn**, nhưng chưa đủ để tuyên bố validated. Nhóm nên trình bày kết quả như sau:

> Practice interview cho thấy learner silent struggle và TA visibility/triage gap là vấn đề có dấu hiệu thật trong bối cảnh lab. Tuy nhiên, solution cần cẩn trọng với hai điểm: learner đã có một số workaround AI/search, và bottleneck có thể chuyển sang capacity/hạ tầng nếu TA đã biết vấn đề nhưng không đủ nguồn lực hỗ trợ.
