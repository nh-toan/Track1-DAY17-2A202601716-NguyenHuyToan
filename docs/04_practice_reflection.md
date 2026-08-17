# 04 — Practice Reflection & Guide Revision
## Chặng 4 — Chỉnh guide và nộp bài

> Reflection này dựa trên các notes/recording trong `interview/` và bản tổng hợp `evidence/01_interview_synthesis.md`. Đây là practice evidence, chưa đủ để tuyên bố problem đã validated.

---

# 1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?

**Câu hỏi hiệu quả nhất với learner:**

> "Kể mình nghe về lần gần nhất trong một buổi học/lab bạn gặp một phần mà lúc đó bạn chưa hiểu rõ hoặc chưa biết làm tiếp thế nào?"

**Vì sao hiệu quả?**

- Với L01, câu hỏi này kéo learner về một episode cụ thể: tối thứ Sáu làm lab LoRA/VRAM, bị kẹt ở phần `target_modules` và tính VRAM.
- Sau đó thu được behavior rõ: đọc lại slide, dừng lâu ở Slide 15, đổi đáp án quiz, hỏi ChatGPT, không nhắn Discord, nộp bài khi chưa tự tin, hôm sau xem lại recording.
- Có consequence cụ thể: mất khoảng 3 tiếng, nộp bài trễ hơn mốc tự đặt, sang bài sau về Deploy LoRA Adapter vẫn lúng túng với OOM.

**Câu hỏi hiệu quả nhất với TA:**

> "Lần gần nhất bạn phát hiện một learner đang gặp khó trong hoặc sau một buổi lab là khi nào?"

**Vì sao hiệu quả?**

- Câu hỏi này giúp TA kể về cách phát hiện learner qua giơ tay, request, checkpoint, Discord và quan sát màn hình.
- Nó cũng mở ra insight quan trọng: có learner đang gặp vấn đề nhưng không hỏi hoặc nói không cần hỗ trợ vì ngại.

---

# 2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?

- Một số câu hỏi vẫn còn hơi rộng, khiến interviewee trả lời theo thói quen chung thay vì một episode cụ thể. Ví dụ L02 trả lời "trong mọi buổi học" trước khi được kéo về buổi sáng cùng ngày.
- Có lúc interviewer nhắc tới V-Lab/raise hand/checkpoint quá sớm. Lần sau nên để TA tự kể công cụ/tín hiệu họ đang dùng, rồi mới đào sâu.
- Chưa đào đủ timeline trong một số interview: cần hỏi rõ learner bị kẹt lúc mấy giờ, kẹt ở phần nào, mất bao lâu, ai biết, support diễn ra lúc nào và kết quả ra sao.
- Với các workaround AI như ChatGPT/Gemini, cần hỏi thêm: câu trả lời AI giúp đến đâu, còn thiếu context gì, learner dựa vào đâu để biết câu trả lời đúng với bài lab.
- Với TA, cần hỏi kỹ hơn về capacity: nếu đã biết learner cần hỗ trợ nhưng không đủ thời gian/tài nguyên, TA thực tế làm gì và consequence là gì.

Lần sau mình sẽ hỏi ngắn hơn và neo mạnh hơn vào một sự kiện:

> "Bạn đưa mình về đúng lần đó được không: lúc ấy bạn đang làm bài nào, mắc ở bước nào, và hành động đầu tiên bạn làm là gì?"

---

# 3. Sau khi luyện, mình đã sửa Conversation Guide ở đâu và vì sao?

| Trước practice | Vấn đề nhận ra | Sau practice | Vì sao sửa |
|---|---|---|---|
| "Bạn gặp phần chưa hiểu trong buổi học/lab khi nào?" | Còn rộng, dễ ra câu trả lời chung chung | "Lần gần nhất bạn bị mắc lại ở một khái niệm hoặc lỗi cụ thể là khi nào?" | L02 ban đầu nói chung về "mọi buổi học"; cần kéo về một episode |
| "Bạn đã làm gì để xử lý?" | Chưa đào đủ workaround AI/search | "Bạn có dùng AI/search/recording/bạn học không? Cách đó giúp đến đâu và còn thiếu gì?" | L01 dùng ChatGPT nhưng bị lệch context; L02 dùng Gemini nhưng vẫn mất thời gian |
| "Vì sao bạn không hỏi người hỗ trợ?" | Đúng nhưng cần cụ thể hơn | "Điều gì khiến bạn chưa hỏi TA/mentor ngay lúc đó: thời điểm, cảm giác ngại, không biết hỏi sao hay nghĩ tự xử lý nhanh hơn?" | L01 không hỏi Discord vì đêm muộn và sợ bị đánh giá |
| "TA phát hiện learner đang gặp khó bằng cách nào?" | Cần hỏi tín hiệu cụ thể hơn | "Bạn dựa vào tín hiệu cụ thể nào để biết learner đang kẹt nếu họ không tự hỏi?" | P02 dùng checkpoint, raise hand, Discord và quan sát màn hình |
| Chưa hỏi rõ capacity | Có thể nhầm detection là bottleneck duy nhất | "Có lần nào bạn đã biết learner cần hỗ trợ nhưng vẫn không thể hỗ trợ kịp vì thiếu thời gian/tài nguyên không?" | P01/P02 đều nhắc giới hạn nhân lực, thời lượng lab, hạ tầng/cài môi trường |

---

# 4. Evidence làm hypothesis mạnh hơn

- Learner có thể bị kẹt nhưng không hỏi ngay vì ngại, sợ bị đánh giá hoặc không biết hỏi thế nào.
- TA cũng quan sát thấy learner không chủ động signal, thậm chí nói không cần hỗ trợ dù đang gặp trục trặc.
- Workaround tự xử lý có thật: đọc lại slide, đổi quiz, hỏi AI, xem recording, hỏi bạn.
- Workaround không luôn đủ tốt: ChatGPT trả lời lệch bối cảnh lab; Gemini tiện nhưng learner vẫn mất thời gian.
- TA có visibility gap: phải dựa vào giơ tay, request, checkpoint, Discord, quan sát màn hình và đi hỏi từng bạn.
- Khi TA/mentor hỗ trợ, learner thường gỡ được lỗi hoặc tiếp tục bài lab.

---

# 5. Evidence làm hypothesis yếu đi / trái giả thuyết

- Một số learner đã có AI workaround khá tiện, như Gemini Assistant mở cạnh tài liệu.
- TA đã có một số tín hiệu hiện tại như checkpoint, raise hand và Discord; không thể nói instructor hoàn toàn không có visibility.
- Với lỗi chung, TA có thể giải thích một lượt cho cả lớp; không phải vấn đề nào cũng cần phát hiện/cá nhân hóa từng learner.
- Bottleneck có thể là capacity/hạ tầng: TA biết learner gặp vấn đề nhưng vẫn không đủ thời gian/tài nguyên để hỗ trợ kịp.

---

# 6. Hypothesis có cần sửa không?

- [ ] Giữ nguyên
- [x] Thu hẹp
- [ ] Đổi actor
- [x] Đổi situation/job
- [x] Đổi pain
- [x] Chuyển trọng tâm sang competing hypothesis như một nhánh cần kiểm tra

**Lý do:**

- Hypothesis ban đầu đúng hướng nhưng hơi rộng. Sau interview, cần thu hẹp vào bối cảnh **lab/online learning có task cụ thể**, nơi learner bị kẹt ở khái niệm/lỗi kỹ thuật nhưng chưa signal rõ.
- Pain không chỉ là "không hiểu", mà là tổ hợp: rào cản hỏi người, workaround AI/search chưa đủ context, tín hiệu rời rạc và support capacity có hạn.
- Instructor/TA không hoàn toàn thiếu visibility; họ có vài tín hiệu nhưng phải tự ghép và triage thủ công.

**Problem Hypothesis sau practice:**

> Khi learner đang học lab/online lesson và gặp một phần chưa hiểu hoặc lỗi kỹ thuật nhưng vẫn cần tiếp tục, họ có thể không chủ động hỏi TA/mentor ngay vì ngại, không chắc mình hỏi có đúng không, hoặc muốn tự xử lý trước bằng cách đọc lại, hỏi AI/search, hỏi bạn hoặc xem recording. Nếu workaround không giải quyết đúng bối cảnh bài học, learner mất thời gian, chậm tiến độ hoặc tiếp tục với mức hiểu chưa chắc. Trong khi đó, TA có một số tín hiệu như giơ tay, request, checkpoint, Discord và quan sát trực tiếp, nhưng các tín hiệu này rời rạc và phụ thuộc nhiều vào learner chủ động, khiến TA vẫn phải triage thủ công và có thể phát hiện muộn những learner rụt rè hoặc silent struggle.

---

# 7. Guide revision log

Sau reflection, cần cập nhật `docs/02_conversation_guide.md` theo ba hướng:

1. Neo story opener vào **khái niệm/lỗi cụ thể** thay vì "phần chưa hiểu" chung chung.
2. Thêm probe về **AI/search workaround**: giúp gì, thiếu gì, có đúng context bài lab không.
3. Thêm probe cho TA về **capacity/hạ tầng** để kiểm tra liệu detection có thật sự là bottleneck chính không.

---

# 8. Giới hạn

- Đây là practice interview và dữ liệu từ nhóm nhỏ, chưa đủ để tuyên bố problem đã validated.
- Một số nguồn là transcript/notes đã được làm sạch hoặc tổng hợp, cần tránh coi mọi câu là quote nguyên văn.
- Vòng này có cả learner-side và TA-side evidence, nhưng chưa đủ để định lượng tần suất hoặc mức độ false positive của các tín hiệu hành vi.
