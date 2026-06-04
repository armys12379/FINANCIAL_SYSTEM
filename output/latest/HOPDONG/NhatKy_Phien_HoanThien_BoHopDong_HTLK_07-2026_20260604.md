# NHẬT KÝ PHIÊN — Hoàn thiện bộ Hợp đồng HTLK 07/2026
**Ngày:** 04/06/2026 · **Phạm vi:** Nhánh hợp đồng (02_BIEU_MAU_HT/HOPDONG) — HĐ khung + PL A/B/C/D/E/F + PL CK
**Mục tiêu phiên:** Hoàn thiện toàn bộ HĐ khung tại thời điểm 07/2026 và các phụ lục; đề xuất & áp dụng phương án điều chỉnh do bổ sung văn bản pháp luật mới.

---

## A. VIỆC ĐÃ HOÀN THÀNH

### A.1. File đã tạo (outputs — chờ pass vào hệ thống)

| # | File | Phiên bản | Ghi chú |
|---|---|:---:|---|
| 1 | `HD_HTLK_HopNhat_07-2026.md` | hợp nhất 07/2026 | HĐ khung |
| 2 | `PLA_Hoa_Hong_Tuyen_Sinh_v2.2_07-2026.md` | 2.2 | Hoa hồng tuyển sinh — ĐTHH |
| 3 | `PLB_Khoan_Giang_Day_CaNhan_v2.1_07-2026.md` | 2.1 | Khoán giảng dạy — cá nhân không ĐKKD |
| 4 | `PLC_Khoan_Giang_Day_HKD_v2.1_07-2026.md` | 2.1 | Khoán giảng dạy — HKD/CNKD |
| 5 | `PLD_Khoan_DaoTao_CoPhuongTien_v2.1_07-2026.md` | 2.1 | Khoán đào tạo có phương tiện — VPTS |
| 6 | `PLE_Khoan_TronGoi_PhapNhan_v1.1_07-2026.md` | 1.1 | Khoán trọn gói — pháp nhân |
| 7 | `PLF_Cho_Thue_Xe_TapLai_v2.2_07-2026.md` | 2.2 | Cho thuê xe tập lái — ĐTCX |
| 8 | `HD_HTLK_PLCK_CamKet_Khoan_TheoKy_v1.1_07-2026.md` | 1.1 | Cam kết khoán theo kỳ |

> *Lưu ý tên file:* file #8 (PL CK) mang tiền tố `HD_HTLK_PLCK_` theo yêu cầu trước; các file #1–7 giữ tên cũ kiểu `PLxx_` để sắp xếp theo tên gom nhóm. Nếu muốn đồng bộ một kiểu tên, báo để đổi.

### A.2. Quyết định đã chốt trong phiên

- **Phạm vi:** chốt **Phương án II** — chuẩn hóa căn cứ pháp lý + tinh chỉnh nội dung theo VBPL mới (không chỉ sửa căn cứ).
- **Cách dẫn GTGT (2A):** dẫn chuỗi đầy đủ *"Luật GTGT 48/2024 (sửa bởi Luật 90/2025 và Luật 149/2025)"*.
- **Bản chất giao dịch (3A):** bổ sung nguyên tắc Điều 6 Luật QLT 108/2025 vào Điều 8 HĐ khung; các PL dẫn chiếu lại Điều 8.
- **NĐ 336/2025:** **không** đưa vào căn cứ HĐ — là Nghị định xử phạt VPHC đường bộ, không phải nền pháp lý của hợp đồng dịch vụ.
- **Đại diện Bên A:** để trống chức danh + họ tên trong template (điền khi ký) theo Quy định Format HĐ v1.2; điền sẵn MST 3400991745 + địa chỉ Bên A.
- **Ngưỡng doanh thu năm (chuẩn hóa toàn bộ):** **≤ 500tr / > 500tr–1 tỷ / > 1 tỷ** — bắt cả hai mốc 500tr (GTGT, Luật 149/2025) và 1 tỷ (NĐ 141/2026).
- **Xử lý thuế hoa hồng (PL A):** giữ **phương án tổng quát** (chưa nhúng bảng tỷ lệ chi tiết) để dễ chủ động.
- **B.1 — PL F, cá nhân không ĐKKD cho thuê xe > 500tr:** chốt **5% GTGT + 5% TNCN** (đúng bản chất *cho thuê tài sản*), Bên A khai thay/nộp thay hoặc cá nhân tự kê khai; **bỏ cơ chế "10% khấu trừ tại nguồn"** (mức 10% chỉ áp cho tiền công/dịch vụ). Đã xóa dòng 🔧.
- **Đầu ra:** `.md` để duyệt; xuất `.docx` về sau khi có chỉ đạo.

### A.3. Điều chỉnh chung đã áp cho toàn bộ bộ hợp đồng

1. **Căn cứ pháp lý:** Luật QLT **38/2019 → 108/2025** (toàn bộ); bổ sung **GTGT 48/2024 (sửa 90/2025 + 149/2025)** ở các văn bản có nghĩa vụ GTGT; bổ sung ngày ban hành NĐ 94/2026.
2. **MST = số định danh cá nhân (CCCD)** theo Điều 11 Luật 108 — thêm cho cá nhân/HKD/CNKD (không áp cho pháp nhân).
3. **HĐĐT từ 01/01/2026** theo Điều 26 Luật 108 — bổ sung cho HKD/CNKD khi vượt ngưỡng.
4. **Nguyên tắc bản chất giao dịch** (Điều 6 Luật 108) — dẫn chiếu thống nhất qua Điều 8 HĐ khung.
5. **Tách tài khoản & biểu mẫu nội bộ Bên A khỏi bản ký** (quy tắc mới): bỏ các mã `TK 641/622/141/112/33871/33872`, `BM-07`; giữ lại biểu mẫu hai bên cùng ký (biên bản nghiệm thu, bảng kiểm xe bàn giao, cam kết doanh thu năm, bảng kê thay hóa đơn, BB xác nhận DS học viên). Diễn đạt lại theo bản chất nghiệp vụ.
6. **Bổ sung thông tin các bên (Bên A + Bên B)** cho các phụ lục còn thiếu: **PL A, PL F, PL CK** (thêm Điều 1 "Thông tin các bên", dồn số điều, sửa dẫn chiếu chéo).
7. **Chuẩn hóa format:** header bảng 2 cột tên viết tắt; chuẩn ngưỡng DT; nâng phiên bản.

### A.4. Điểm riêng từng văn bản

- **HĐ khung:** Điều 8 đổi tên "Bản chất giao dịch và phân biệt với QHLĐ", thêm 8.2 (phân loại 3 nhóm chi: hoa hồng / khoán dịch vụ / thuê tài sản) + 8.3 (lưu hồ sơ giải trình); Điều 1.3 (MST=CCCD); Điều 7.2 (HĐĐT 01/01/2026).
- **PL A:** bỏ cột "(TK 641)" trong bảng hoa hồng; bỏ "TK 641/622" ở nguyên tắc bảo toàn tổng → diễn đạt theo "cơ cấu các khoản".
- **PL B:** bỏ "mẫu BM-07" và "(TK 141)"; giữ cơ chế khấu trừ TNCN 10% tại nguồn cho cá nhân không ĐKKD.
- **PL C/D:** thân vốn đã sạch mã nội bộ; chuẩn ngưỡng + căn cứ + Điều 26 HĐĐT.
- **PL E (pháp nhân):** không thêm MST=CCCD (pháp nhân có MST riêng); thêm tra cứu MST + hiệu lực GP đào tạo.
- **PL F:** chốt B.1 (5%+5%); xác nhận B.2 đã áp (nhãn bên cho thuê/bên thuê; Bên A thông báo tai nạn 24h; Bên A toàn quyền vận hành; Bên A chịu bảo dưỡng; không bắt buộc nhật ký xe); thêm CĂN CỨ + THÔNG TIN CHUNG + Bên A.
- **PL CK:** tách toàn bộ hạch toán nội bộ (đặt cọc/tạm ứng/chuyển đổi) khỏi bản ký; thêm Điều 1 Thông tin các bên.

---

## B. VIỆC CÒN TỒN — TIẾP TỤC LẦN SAU

| # | Việc | Trạng thái / Ghi chú |
|---|---|---|
| B.1 | **PL F — xác nhận lần cuối B.1:** đã áp **5% GTGT + 5% TNCN** cho cá nhân >500tr. Nếu CFO có lý do vận hành muốn giữ "10% khấu trừ tại nguồn" → báo để đổi lại | ⚠️ Chờ CFO xác nhận giữ |
| B.2 | **Tỷ lệ thuế chi tiết cho hoa hồng (PL A):** hiện để tổng quát. Nếu muốn nhúng bảng tỷ lệ (môi giới/hoa hồng HKD = 10% GTGT + 2% TNCN = 12% theo P4) → cần CFO chốt rồi bổ sung | Chờ quyết định |
| B.3 | **Đồng bộ ngưỡng 500tr/1 tỷ ra ngoài bộ HĐ:** cập nhật mẫu **Cam kết doanh thu năm (PL05)**, Bảng kê thay hóa đơn (PL06), và các P-doc (P3–P6) cho khớp ngưỡng mới | Chưa làm |
| B.4 | **Rà căn cứ Luật 38/2019 → 108/2025 trong các quy chế nội bộ** (P3, P4, P5, P6 — QCTC-KT) trước 01/07/2026 | Chưa làm (ngoài phạm vi phiên này) |
| B.5 | **Đọc sâu Luật 108 phần OCR mờ:** Chương III–V–VII; Điều 13 (khai thuế), 22 (kiểm tra), 37 (quyền-nghĩa vụ NNT), 44–50 (vi phạm/cưỡng chế) | Chưa làm — chờ Army chỉ nhóm Điều ưu tiên |
| B.6 | **Xác định số hiệu Thông tư đăng ký thuế kế thừa TT 86** (thay từ ~01/07/2025) để neo đúng ô "văn bản kế thừa" | Chưa làm |
| B.7 | **Đối chiếu phần tái lập:** khối KÝ KẾT / HỒ SƠ ĐÍNH KÈM của **PL B, PL E, PL F** được tái lập theo pattern (bản gốc không đủ đoạn cuối) — Army đối chiếu lại với bản gốc | Cần xác nhận |
| B.8 | **Pass 8 file .md vào hệ thống** (dán body Notion + cập nhật INDEX.md) | Bước thủ công của Army |
| B.9 | **Xuất .docx** bộ HĐ sau khi duyệt .md | Khi có chỉ đạo |

---

## C. ĐIỂM NEO ĐỂ TIẾP TỤC

- **Căn cứ chuẩn:** Luật QLT **108/2025** (hiệu lực toàn bộ 01/07/2026); GTGT **48/2024 sửa bởi 90/2025 + 149/2025** (ngưỡng HKD 500tr từ 01/01/2026); ngưỡng vận hành **500tr (cá nhân) / 1 tỷ (HKD)**.
- **Nguyên tắc nền:** bản chất giao dịch quyết định nghĩa vụ thuế (Điều 6 Luật 108) — chỗ dựa cho tái phân loại hoa hồng/khoán/thuê tài sản; **hợp đồng A–B không nhúng tài khoản/biểu mẫu nội bộ Bên A**, chỉ giữ biểu mẫu hai bên cùng ký.
- **Format:** đại diện Bên A để trống (điền khi ký); INDEX.md chỉ liệt kê file đã sync.
- **3 tiêu chí kiểm chứng** (logic hệ thống · tối ưu thuế hợp pháp · khả thi vận hành) đã đối chiếu đạt cho toàn bộ 8 văn bản.

---

*Nhật ký phiên · CTM · 04/06/2026 · Hoàn thiện bộ HĐ HTLK 07/2026 (HĐ khung + PL A–F + PL CK) theo Phương án II — chuẩn hóa căn cứ Luật 108/2025 & 149/2025, tách tài khoản/biểu mẫu nội bộ, chuẩn ngưỡng & thông tin các bên.*
