# Checklist CS9 · Kinh tế sản phẩm AI — DAY24 Track 1

Tổng hợp từ runbook 1–8 (`docs/1.md` … `docs/8.md`), `docs/slide-bai-hoc.pdf`, `docs/CS9_HuongDan_HocVien.pdf` và `docs/CS9_DeBai_GiaDinh.pdf`.
File làm bài: `DAY24_Track1_2A202602942_LuuManhHung.xlsx` · Sản phẩm đã chọn: **Đề bài 1 — SổSạch** (trợ lý đọc hoá đơn đầu vào cho văn phòng kế toán dịch vụ).

Ký hiệu: [x] đã xong trong file · [ ] học viên tự làm (ngoài file Excel)

## Quy tắc chung (áp dụng mọi sheet)
- [x] Chỉ điền ô **vàng**; không sửa ô xanh lá (công thức)
- [x] Sheet A dùng **triệu đồng**; sheet 1 trở đi dùng **đồng**; bảng độ nhạy sheet 5 dòng 56–68 hiển thị triệu đồng
- [x] Ô % nhập kèm `%`; tiền gõ liền, không dấu phân cách
- [x] Mỗi số có Nguồn / lý do — làm đề thì ghi `Đề bài 1`, không gắn nhãn [TỰ ĐO]/[NGÀNH] cho số của đề
- [x] Không chỉnh giả định cho đẹp số; cảnh báo đúng thì giữ và giải thích ở sheet 7

## Nhiệm vụ 0 — `0_Đầu vào` (runbook 1)
- [x] Chọn một sản phẩm cho cả buổi: Đề bài 1 — SổSạch
- [x] B5:B10 đánh dấu Có / Chưa (chỉ "Có" khi đầu vào tồn tại **và** được dùng) → cả 6 dòng "Chưa" vì dùng số của đề
- [x] E5:E10 ghi tài liệu thực dùng; E10 ghi tên đề

## Phần A — `A_Tài chính căn bản` (runbook 2)
- [x] Bài 1: G7:G17 phân loại 11 giao dịch (vào báo cáo kết quả? vì sao)
- [x] Bài 1: C21:E31 báo cáo kết quả kinh doanh theo kỳ; dòng 23–31 cột G và dòng 33 báo "Đạt" (lỗ 3 tháng = −174)
- [x] Bài 2: C37:C51 bảng cân đối cuối tháng 3, dòng 52–53 "Đạt" (tổng tài sản 1.341)
- [x] Bài 3: C57:C70 lưu chuyển tiền tệ, đúng dấu Cộng/Trừ dòng 58–61; dòng 71–72 "Đạt" (tiền cuối kỳ 921)
- [x] Câu 1–3 (C75:C77), mỗi câu 1–2 câu văn
- [x] Mở rộng: câu 4 (C78) và Bài 5 mua máy chủ hay thuê đám mây (C86:C89)

## Nhiệm vụ 1 — `1_Chi phí mỗi việc` (runbook 3)
- [x] B5 mô tả một việc (AI nhận gì → trả gì)
- [x] B6:B18 chép bảng Đề 1 · Trang 1 (2 lần gọi, 2.500/400 token, Haiku 4.5 1/5 USD, 26.170 đ/USD, 8% gọi lại, 120 đ hạ tầng, 20% × 1,5 phút × 50.000 đ/giờ, 50 đ đánh giá, 30 đ khác)
- [x] D5:D18 nguồn cho từng dòng
- [x] Không lẫn lương đội / thử sai / bán hàng (để ở sheet 3 dòng 10–12)
- [x] Đọc kết quả: chi phí mỗi việc ≈ 704 đ (AI 254 đ, người kiểm tra 250 đ), phần chìm 177% ≥ 30%, giá sàn ≈ 2.113 đ

## Nhiệm vụ 2 — `2_Định giá` (runbook 4)
- [x] B5:B8 + D5:D8: ngân sách nhân sự, gói kết hợp, lý do, neo lương 8 triệu
- [x] B9:B12: 1.990.000 đ / 1.000 hoá đơn / vượt 2.200 đ / không giới hạn 1.990.000 đ
- [x] B15:C16 + I15:I16: 70% × 800 hoá đơn; 30% × 4.000 hoá đơn (tổng tỷ trọng 100%)
- [x] B26:B27 + D26:D27: lương 8.000.000 đ; chia đối tác 0%
- [x] Ba phép thử: văn phòng nhỏ 24,9% lương (ổn); văn phòng lớn 107% lương (vượt 70% → giữ cảnh báo, ghi rủi ro ở sheet 7, không hạ phí vượt dưới giá sàn); biên sau chia 68,8%

## Nhiệm vụ 3 — `3_Giả định`, `4_Chỉ số mỗi khách`, `5_Dòng tiền & hiệu quả` (runbook 5)
- [x] Sheet 3 C7:C13 + F7:F13 theo Đề 1 · Trang 3 (12 khách, 5%, 3%, 9 triệu, 200 triệu, 900 triệu, 2,5 tỷ); hệ số 1/1, chiết khấu 15%
- [x] Kịch bản xấu đủ sốc: churn ×1,6, CAC ×1,5 → dòng 21–22 "Đạt"
- [x] Sheet 4: LTV ÷ CAC cơ sở 10,1; hoàn vốn CAC 3,3 tháng; biên gộp 68,8%
- [x] Sheet 5: NPV cơ sở +935 triệu; xấu −5,0 tỷ, hết tiền tháng 7; hoàn vốn dự án tháng 21
- [x] Độ nhạy B54 = 20%: biến nguy hiểm nhất = **doanh thu bình quân** (NPV −1.965 triệu); khách dùng nhiều bỏ đi → −3.827 triệu

## Nhiệm vụ 4 — `7_Quyết định` (runbook 6)
- [x] Soát dòng 5–12; giữ và giải thích "Cần kế hoạch cắt giảm" (xấu hết tiền tháng 7)
- [x] A15 quyết định: **Thử nghiệm nhỏ** + quy mô, thời hạn, điều kiện mở rộng + kế hoạch cắt giảm (ai, khi nào, cắt gì)
- [x] A18 giá bán + căn cứ khách chấp nhận (trả lời câu hỏi riêng 1–2 của đề)
- [x] A21 biến nguy hiểm nhất + ai theo dõi hằng tuần
- [x] A24 luật xử lý NẾU – TRONG – THÌ – KHÔNG THÌ có số
- [x] A27 mức tự tính sheet 5 dòng 72–77 + nhãn nguy / đáng lo + người theo dõi
- [x] Sheet 6 (nội bộ): **không áp dụng** — đề bán ra thị trường; đã ghi lý do ở F5

## Nộp bài (runbook 7)
- [x] Tên file đúng quy ước `DAY24_Track1_MSSV_HoVaTen.xlsx` → `DAY24_Track1_2A202602942_LuuManhHung.xlsx`
- [ ] Mở lại file, soát sheet 4–5 và năm câu ở sheet 7
- [ ] Đăng nhập VLearn bằng tài khoản cá nhân → bài **CS9 / Ngày 24 – Track 1** → đính kèm file → gửi
- [ ] Kiểm tra trạng thái "đã nộp" và đúng tên tệp đính kèm trước 12:00

## Nhiệm vụ 5 — Ba slide trình bày (runbook 8)
- [x] Nội dung ba slide soạn sẵn ở `SLIDES.md` (số lấy từ file Excel)
- [ ] Dựng ba slide trên công cụ trình chiếu, tập nói ≤ 3 phút
- [ ] Chuẩn bị trả lời phản biện: doanh thu −20%, churn lấy ở đâu, văn phòng lớn bỏ đi

## Kết buổi
- [ ] Ghi một giả định cần đo tiếp (gợi ý: số nhân viên nhập liệu văn phòng lớn đang dùng cho 4.000 hoá đơn/tháng)
