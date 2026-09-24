# Đường tới TOEIC 700

Bộ luyện TOEIC Reading — **64 câu Part 5, 6 và 7**, giải thích bằng tiếng Việt,
theo dõi điểm yếu theo chủ điểm ngữ pháp.

Một file HTML duy nhất, không build, không phụ thuộc thư viện ngoài. Mở bằng
trình duyệt là chạy.

## Vì sao làm cái này

Tôi cần lên từ TOEIC 575 tới 700 cho một vị trí ứng tuyển. Các app luyện thi có
sẵn hoặc chỉ chấm điểm mà không nói vì sao sai, hoặc trộn lẫn mọi chủ điểm nên
không biết mình hổng chỗ nào. Cái này làm đúng hai việc đó.

## Nội dung

| Phần | Số câu | Chủ điểm |
|---|---|---|
| Part 5 — Incomplete Sentences | 43 | Dạng từ · thì & thể · giới từ · liên từ · đại từ & mệnh đề quan hệ · từ vựng · so sánh & thức giả định |
| Part 6 — Text Completion | 8 | Hai bài, gồm hai câu chèn câu |
| Part 7 — Reading Comprehension | 13 | Ba bài: email, thông báo, và **một bài kép** tin tuyển dụng + email ứng tuyển |

Câu hỏi tự soạn theo định dạng TOEIC. **Không phải đề ETS thật** — đề thật có
bản quyền.

## Hai thứ đáng dùng

**Bảng điểm yếu theo chủ điểm.** Chủ điểm dưới 70% hiện thanh đỏ và được đẩy lên
đầu danh sách. Lên điểm TOEIC không phải nhờ làm nhiều đề mà nhờ bịt đúng vài lỗ
hổng — bảng này chỉ ra chúng.

**Bài kép ở Part 7.** Có những câu không thể trả lời nếu chỉ đọc một bài:

> *Which requirement does Mr. Okonkwo exceed?*

Tin tuyển ghi `at least one year`, email ứng tuyển ghi `eighteen months`. Phải
ghép hai con số ở hai bài mới ra đáp án. Đây là dạng chiếm phần lớn điểm của bài
kép và bài ba trong đề thật.

Giải thích luôn nói vì sao **ba đáp án kia sai**, không chỉ chỉ ra đáp án đúng:

> `review` = xem lại. Bẫy: `overlook` nghĩa ngược hẳn — bỏ sót; `oversee` = giám sát.

## Hai chế độ

- **Luyện tập** — chọn xong hiện giải thích ngay.
- **Thi thử** — 40 phút, chấm ở cuối, không xem giải thích giữa chừng.

Bàn phím: `A` `B` `C` `D` chọn đáp án, `Enter` sang câu tiếp.

## Chạy

```bash
# mở thẳng
start index.html

# hoặc serve tại chỗ
python -m http.server 8000
```

Tiến độ lưu bằng `localStorage` của trình duyệt, không gửi đi đâu cả.

## Còn thiếu

Không có **Listening (Part 1–4)** — chiếm 495/990 điểm và cần file âm thanh.
Điểm ước lượng trong app chỉ để theo dõi tiến bộ, không thay thế điểm thi thật.
