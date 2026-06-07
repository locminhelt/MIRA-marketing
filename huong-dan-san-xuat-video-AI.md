# MIRA — Hướng dẫn sản xuất video bằng AI

> *just in flow* — Tài liệu nội bộ cho đội sản xuất content. Đi kèm `MIRA-content-plan.xlsx` và `content-brief.md`.
> Phiên bản 1.0 · 06/2026 · Ngân sách tham chiếu: trả phí hợp lý (~$10–30/tháng/công cụ).

---

## 00 · Nguyên tắc quan trọng nhất trước khi bắt đầu

**Phần lõi của video MIRA là DEMO TÍNH NĂNG THẬT — AI không thay thế được.**

Sản phẩm của MIRA bán bằng trải nghiệm: chú thích từ vựng hiện trên từ, giao diện thi CBT, định vị đáp án trong bài. Người xem phải thấy **màn hình thật** của app thì mới tin. Vì vậy:

- ❌ KHÔNG dùng AI để "vẽ ra" giao diện sản phẩm (sẽ sai, mất uy tín, và vi phạm sự thật sản phẩm trong brief).
- ✅ Quay màn hình thật (screen-record) tính năng → rồi dùng AI cho **mọi thứ bao quanh**: lồng tiếng, hook, b-roll cảm xúc, phụ đề, dựng, nhạc.

Hiểu đơn giản: **AI lo phần "kể chuyện", màn hình thật lo phần "bằng chứng".**

Và nhớ nguyên tắc nội dung đã chốt: **mở bằng nỗi đau/kết quả người học cảm nhận được, tính năng xuất hiện SAU.** Voiceover & hook AI phải bám đúng thứ tự này.

---

## 01 · Bốn khâu AI và công cụ đề xuất

| Khâu | Việc AI làm | Công cụ đề xuất (trả phí hợp lý) | Ghi chú |
|------|-------------|-----------------------------------|---------|
| **1. Voiceover (lồng tiếng)** | Đọc thuyết minh tiếng Việt tự nhiên | **ElevenLabs** (giọng Việt tốt nhất hiện nay) · CapCut AI voice (rẻ/free) | Chọn 1 giọng cố định làm "giọng MIRA" cho nhất quán |
| **2. Avatar / người dẫn AI** | Nhân vật nói trước camera | **HeyGen** (hỗ trợ tiếng Việt) · Synthesia | Chỉ dùng cho reel kể chuyện (#4); KHÔNG dùng khi cần demo màn hình |
| **3. B-roll / cảnh minh hoạ** | Cảnh cảm xúc, chuyển cảnh, animation | **Runway** · Pika · Kling | Dùng cho cảnh "mở sách rồi đóng lại", "ngồi nản" — KHÔNG dùng cho giao diện app |
| **4. Phụ đề + dựng tự động** | Cắt, phụ đề động, nhạc, caption | **CapCut** (free, mạnh, có sẵn template reel) · Opus Clip | Khâu cuối, ghép tất cả lại |

**Bộ công cụ tối thiểu khuyến nghị:** ElevenLabs (voiceover) + CapCut (dựng + phụ đề) + Runway/Pika (b-roll khi cần) + HeyGen (chỉ khi làm avatar). Tổng ~$20–40/tháng nếu dùng cả 4; có thể bắt đầu chỉ với ElevenLabs + CapCut.

---

## 02 · Quy trình chuẩn 6 bước (áp dụng cho mọi video)

1. **Lấy script từ Excel** — cột *Hook/Mở đầu* + *Outline* + *Mô tả video/demo feature* của content đó đã là kịch bản sẵn.
2. **Quay màn hình thật** phần demo tính năng (xem mục 04). Đây là tài sản không thể thiếu.
3. **Tạo voiceover** bằng ElevenLabs theo script — giọng MIRA cố định, đọc đúng thứ tự "nỗi đau trước, tính năng sau".
4. **Tạo b-roll cảm xúc** (nếu cần) bằng Runway/Pika cho đoạn mở đầu nỗi đau.
5. **Dựng trong CapCut**: ghép b-roll mở → screen-record demo → kết CTA; thêm phụ đề động, nhạc nền nhẹ, caption hook ở giây đầu.
6. **Soi Approval Checklist** (mục 11 brief) trước khi đăng: tính năng có thật? giọng đời thường? kết bằng 1 CTA?

---

## 03 · Hướng dẫn theo từng content cần video

Trong plan có **6 content cần video** (#2, #3, #4, #8, #15, #17) và **1 tùy chọn** (#5). Dưới đây là công thức AI cho từng loại.

### Nhóm A — Demo tính năng (screen-record là chính)

**#2 · "Đọc Cambridge 10 phút, hết 6 phút chỉ để tra từ"** (Short 15–20s)
- **Screen-record (bắt buộc):** màn hình app — cảnh đọc bị ngắt quãng (chuyển tab tra từ) → chuyển sang MIRA chạm vào từ, tooltip nghĩa theo ngữ cảnh + bản dịch hiện ra.
- **AI voiceover:** ElevenLabs đọc hook nỗi đau ở giây 0–5, tính năng nói sau giây 8.
- **AI b-roll (tùy chọn):** 2–3s cảnh người đọc mệt mỏi/chuyển tab liên tục (Runway) để mở đầu.
- **CapCut:** phụ đề động nhấn cụm "đọc không bị ngắt quãng"; nhạc nhẹ; tốc độ thật.

**#3 · "Nghe đề Listening 1 lần trôi hết? Nghe lại có phụ đề"** (Reel 20–30s)
- **Screen-record (bắt buộc):** video phụ đề đề Listening của MIRA — audio chạy, phụ đề Anh–Việt đồng bộ, chạm 1 từ trên phụ đề → tooltip nghĩa; cho thấy nút tua lại.
- **AI voiceover:** ElevenLabs đọc theo cấu trúc AIDA trong Excel.
- **CapCut:** đối lập nhanh "file nghe + transcript tĩnh" (b-roll text) ↔ màn MIRA.

**#8 · "Làm xong biết đúng/sai — nhưng vì sao sai thì chịu"** (Clip / carousel demo)
- **Screen-record (bắt buộc):** màn kết quả → bấm 1 câu sai → app highlight đoạn/dòng chứa đáp án. Đây là *proof*, phải quay rõ thao tác bấm → highlight.
- **AI voiceover:** đọc theo PPP (Problem–Promise–Proof).
- **B-roll:** không cần; để màn hình thật tự nói.

### Nhóm B — Kể chuyện / cảm xúc (AI làm nhiều hơn)

**#4 · "Lần đầu thi máy mình luống cuống cái đồng hồ"** (Reel kể chuyện 30s)
- **Lựa chọn 1 — Avatar AI:** HeyGen tạo nhân vật kể chuyện ngôi thứ nhất; chèn screen-record giao diện CBT (đồng hồ đếm ngược, palette câu hỏi) làm cảnh minh hoạ.
- **Lựa chọn 2 (khuyến nghị) — Voiceover + b-roll:** ElevenLabs kể chuyện + Runway tạo cảnh "ngồi phòng thi căng thẳng" + screen-record giao diện CBT thật. Tự nhiên hơn avatar.
- **CapCut:** nhấn cảnh đồng hồ đang chạy; giọng trấn an ở cuối.

**#15 · "Mở Cambridge ra rồi… đóng lại"** (Reel 20–30s)
- **AI b-roll (mở đầu):** Runway/Pika cảnh do dự — mở sách/đề nhìn 5 giây rồi đóng lại, gương mặt nản. Đây là đoạn cảm xúc AI làm tốt.
- **Screen-record (kết):** mở app MIRA → màn hình gợi ý "việc tiếp theo của bạn" hiện ngay.
- **AI voiceover:** giọng đồng cảm, không phán xét (theo cột Tone).

**#17 · "Bỏ một tuần không học, quay lại thấy mất gốc"** (Reel / carousel — video tùy chọn)
- **AI b-roll:** cảnh gián đoạn, ngại quay lại (Runway).
- **Screen-record:** màn /history cho thấy chỗ dừng + gợi ý bài quay lại.
- **AI voiceover:** giọng khích lệ, kết bằng 1 bước nhỏ dễ làm.

### Tùy chọn

**#5 · Chiến thuật chia thời gian 60 phút Reading** — chủ yếu carousel; nếu làm video ngắn: screen-record đồng hồ + palette câu hỏi đang chạy, AI voiceover đọc 4 mốc thời gian.

---

## 04 · Mẹo quay màn hình (screen-record) chuẩn

- Quay trên màn ≥13" (brief lưu CBT tốt nhất trên màn lớn), tỷ lệ phù hợp nền tảng: **9:16 dọc** cho reel/TikTok, **1:1** cho carousel video.
- Công cụ quay: QuickTime (Mac), CapCut Screen Recorder, hoặc OBS (free). Quay **mượt, không cắt giật**; di chuột chậm để tooltip kịp hiện.
- Dùng tài khoản demo có dữ liệu đẹp sẵn (lịch sử điểm, bài đã làm) để dashboard trông thuyết phục.
- Che thông tin nhạy cảm nếu quay tài khoản thật.

---

## 05 · Giữ nhất quán thương hiệu khi dựng

- **Giọng MIRA:** chọn 1 giọng ElevenLabs duy nhất, đời thường ngang hàng (persona "Linh"), dùng cho mọi video.
- **Màu & chữ:** caption dùng bảng màu thương hiệu — Flow gradient (sky→navy) cho khung CTA, Amber chỉ nhấn 1 điểm. Font Be Vietnam Pro cho chữ trên video.
- **Tagline:** "just in flow" luôn lowercase, in nghiêng, màu blue.
- **Phụ đề:** luôn có (đa số xem không bật tiếng); tiếng Việt rõ, ngắn, đúng nhịp đọc.
- **Kết video:** đúng 1 CTA theo cột CTA trong Excel — không chồng nhiều lời kêu gọi.

---

## 06 · Cảnh báo & giới hạn

- **Không để AI tạo giao diện/tính năng giả.** Mọi cảnh app phải là screen-record thật.
- **Không hứa band cụ thể trong thời gian ngắn** (voiceover dễ "lỡ miệng" — kiểm lại script).
- **Kiểm tra giọng AI đọc đúng** tên riêng, con số, thuật ngữ (vd "CBT", "Cambridge"); ElevenLabs đôi khi đọc sai số tiếng Việt.
- **Bản quyền nhạc:** dùng nhạc free-license trong CapCut hoặc thư viện được phép, tránh nhạc trending dính bản quyền khi chạy quảng cáo.
- **Con số giá/giảm giá** (nếu xuất hiện trong video chốt sales #18/#19 — vốn là ảnh, nhưng nếu chuyển thành video): kèm chữ "khoảng", nêu rõ chu kỳ, kiểm tra trang giá trước khi đăng.

---

## 07 · Tóm tắt nhanh — "Làm video này thì dùng gì?"

| Content | Screen-record? | Voiceover AI | Avatar AI | B-roll AI | Dựng |
|---------|:---:|:---:|:---:|:---:|:---:|
| #2 Tra từ đứt mạch | ✅ Bắt buộc | ✅ | — | Tùy chọn | CapCut |
| #3 Phụ đề Listening | ✅ Bắt buộc | ✅ | — | — | CapCut |
| #4 Luống cuống thi máy | ✅ (minh hoạ) | ✅ | Tùy chọn | ✅ | CapCut |
| #8 Định vị đáp án | ✅ Bắt buộc | ✅ | — | — | CapCut |
| #15 Mở sách rồi đóng | ✅ (kết) | ✅ | — | ✅ Mở đầu | CapCut |
| #17 Bỏ 1 tuần | ✅ (kết) | ✅ | — | ✅ | CapCut |
| #5 Chia thời gian (tùy chọn) | ✅ | ✅ | — | — | CapCut |

---

*MIRA — "Học trọng tâm, band xứng tầm." · AI lo phần kể chuyện, màn hình thật lo phần bằng chứng.*
