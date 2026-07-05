# 🔄 Quy trình làm việc — Từ nhận việc đến nộp bài

> Copy từ hệ thống thực tế, đơn giản hóa cho công việc hành chính.

---

## Sơ đồ tổng thể

```
📥 NHẬN VIỆC (Input)
       ↓
📋 XÁC NHẬN YÊU CẦU (PRD)
       ↓
⚙️ XỬ LÝ (Process)
       ↓
🤖 REVIEW AI (Antigravity)
       ↓
✅ NỘP BÀI (Output)
```

---

## Bước 1 — NHẬN VIỆC (Input)

**Làm gì:**
1. Nhận file/tài liệu → đặt vào thư mục `Inbox/`
2. Đặt tên file theo format: `YYYY-MM-DD Tên tài liệu`
   - Ví dụ: `2026-07-05 Công văn phòng nhân sự`
3. Tạo file ghi chú từ template `Templates/nhan-viec.md`

**Output của bước này:** File trong Inbox + ghi chú yêu cầu

---

## Bước 2 — XÁC NHẬN YÊU CẦU (PRD)

> PRD = xác nhận rõ: làm gì, cho ai, deadline bao giờ, nộp ở đâu

**Điền vào template `nhan-viec.md`:**

| Câu hỏi | Trả lời |
|---|---|
| Ai giao việc? | |
| Cần làm gì cụ thể? | |
| Deadline? | |
| Nộp cho ai / nộp ở đâu? | |
| File output là gì? (PDF / Word / in ra) | |

**Nguyên tắc:** Không rõ → hỏi ngay trước khi làm. Làm xong mới hỏi = mất công.

---

## Bước 3 — XỬ LÝ (Process)

**Move file sang `Đang làm/`**

Chọn checklist phù hợp:
- Sửa lỗi chính tả → `Templates/checklist-sua-van-ban.md`
- Review toàn bộ tài liệu → `Templates/review-tai-lieu.md`

**Quy trình xử lý chuẩn:**
1. Đọc lướt toàn bộ (đừng sửa ngay)
2. Đọc lại, đánh dấu chỗ cần sửa
3. Sửa từng lỗi theo thứ tự trong checklist
4. Đọc lại lần 3 sau khi sửa xong

---

## Bước 4 — REVIEW AI (Antigravity)

**Khi nào dùng:** Sau khi đã sửa thủ công xong

1. Mở Antigravity
2. Chọn prompt phù hợp trong `HUONG-DAN-ANTIGRAVITY.md`
3. Paste văn bản vào
4. Đọc kết quả → **tự quyết định** có áp dụng không
5. Sửa thêm nếu AI phát hiện lỗi còn sót

**Không bỏ qua bước tự đọc lại** — AI không thay thế được đọc bằng mắt.

---

## Bước 5 — NỘP BÀI (Output)

1. Lưu bản cuối → đặt tên rõ: `2026-07-05 Tên tài liệu FINAL`
2. Move sang thư mục `Xong/`
3. Nộp đúng format theo yêu cầu (PDF / in ra / email...)
4. Điền vào `Templates/output-nop-bai.md` để có bằng chứng đã nộp
5. Ghi 1 dòng vào `logs/YYYY-MM-DD.md`

---

## Mẹo nhỏ

- **Không xóa file gốc** — luôn giữ bản gốc, chỉ tạo thêm bản sửa
- **Đặt tên rõ ràng** — file tên mơ hồ = mất công tìm sau này
- **Inbox không phải thùng rác** — file nào xong thì move, đừng để đọng
