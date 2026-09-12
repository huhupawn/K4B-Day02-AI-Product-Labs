# 01 — Individual Problem Scan

## Thông tin cá nhân

- Họ và tên: Trần Quốc Toản
- Mã học viên: 2A202602984
- Vai trò / bối cảnh: Intern Design
- Công việc hằng tuần:
   - Tiếp nhận task thiết kế mới (feature/screen) từ mentor
   - Tìm hiểu tài liệu kỹ thuật (design system, component spec, accessibility guideline) trước khi bắt đầu task
   - Tìm reference/inspiration để định hình hướng thiết kế
   - Tham gia các buổi họp/sync với mentor và team (1-2 buổi/tuần), sau đó tổng hợp note
   - Thỉnh thoảng hỗ trợ chuẩn bị số liệu hoặc cập nhật tiến độ khi được yêu cầu

---

## Phase 1 — Scan 5+ problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Trước mỗi task mới, phải tìm tài liệu kỹ thuật (design system, component spec, accessibility guideline) ở nhiều nguồn khác nhau rồi mới có thể thiết kế | Design intern | Mất khoảng 2-3 ngày/task cho phần research ban đầu |
| 2 | Tốn thời gian | Tìm reference/inspiration thiết kế bằng cách xem qua nhiều nền tảng (Dribbble, Behance, Pinterest...) | Design intern | Khoảng 2 tiếng/task, dễ tìm quá lâu và mất tập trung |
| 3 | Tốn thời gian | Chuyển các ghi chú sau buổi sync với mentor/team thành meeting notes có cấu trúc | Design intern, team | Khoảng 1 tiếng/buổi, 1-2 buổi/tuần |
| 4 | Lặp lại | Tạo checklist accessibility cho từng task, trong đó mỗi lần lại phải tra cứu tiêu chuẩn từ đầu | Design intern | Phát sinh lặp lại ở phần lớn task mới |
| 5 | AI có thể tốt hơn | Chưa có kho tổng hợp các reference đã dùng trong những task trước nên thường phải tìm lại | Design intern | Công sức bị lặp giữa các task có bối cảnh tương tự |
| 6 | Pain từ người khác | Một số thiết kế phải chỉnh sửa sau review vì chưa bám sát design system/spec hiện có | Design intern, mentor | Phát sinh vòng sửa sau khi nhận feedback |

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính (Tốn thời gian, Lặp lại, AI có thể tốt hơn, Pain từ người khác)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem (copy từ bảng scan) | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Research tài liệu kỹ thuật đầu mỗi task (#1) | Có impact lớn nhất (2-3 ngày/task), workflow dễ xác định và bottleneck nằm rõ ở khâu tìm/đọc tài liệu phân tán | Chưa chắc bản tóm tắt từ AI về tài liệu nội bộ có đủ chính xác để sử dụng |
| 2 | Tìm reference/inspiration (#2) | Xảy ra ở mỗi task, mất khoảng 2h và có thể so sánh thời gian trước/sau khá rõ | Chưa biết reference do AI đề xuất có phù hợp với gu thẩm mỹ và brand hay không |
| 3 | Viết meeting notes (#3) | Diễn ra đều hằng tuần và có thể chuẩn hóa thành một workflow cụ thể | Họp chỉ 1-2 buổi/tuần nên tổng impact thấp hơn hai vấn đề trên |

---

#### Problem Card #1 — Research tài liệu kỹ thuật đầu task

```text
Problem 1 câu:
Mỗi lần nhận task thiết kế mới, intern thường cần khoảng 2-3 ngày để tìm hiểu tài liệu kỹ thuật
(design system, component spec, accessibility guideline) trước khi bắt đầu thiết kế, từ đó
ảnh hưởng đến tiến độ chung của task.

Actor:
Design intern nhận task mới từ mentor/PM.

Thời điểm / bối cảnh:
Đầu mỗi task/feature mới, trước khi bắt tay vào wireframe/mockup.

Current workflow 3-7 bước:
1. Nhận task/brief từ mentor
2. Tìm tài liệu design system hiện có (Figma library, Notion doc)
3. Tra cứu accessibility guideline liên quan đến task
4. Tìm component spec / pattern đã dùng ở các task trước
5. Tổng hợp lại thành checklist áp dụng riêng cho task này

Bottleneck:
Bước 2-4 — tài liệu nằm rải rác ở Figma, Notion và Slack nên phải tự tìm rồi đối chiếu,
đây là phần tiêu tốn nhiều thời gian nhất trong workflow.

Impact:
Trung bình mất 2-3 ngày/task cho việc research trước khi thiết kế, khiến deadline bị kéo dài
và mentor phải chờ lâu hơn mới có thể review bản thiết kế đầu tiên.

Success metric:
Đưa thời gian research xuống dưới 1 ngày/task, đồng thời sản phẩm vẫn tuân thủ design
system và accessibility guideline, không phải sửa vì sai chuẩn.

Non-AI alternative:
Xây dựng checklist/wiki nội bộ, tập hợp các tài liệu quan trọng theo từng loại task và được
team design cập nhật định kỳ.

AI hypothesis:
AI tóm tắt và kết nối các tài liệu liên quan (design system + accessibility) theo từng loại
task, sau đó intern đọc, kiểm tra lại và mới áp dụng.

Quick gut:
[x] Workflow
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 2-3 ngày

[1 Nhận brief: 10'] → [2 Tìm design system doc: 3h] → [3 Tra accessibility: 3h]
→ [4 Tìm pattern cũ: 3h] → [5 Tổng hợp checklist: 2h]  <-- bottleneck (bước 2-4)

FUTURE STATE — dưới 1 ngày

[1 Nhận brief: 10'] → [2 AI tổng hợp tài liệu liên quan (design system + accessibility): 15']
→ [3 Intern review + verify: 1-2h]  <-- human boundary
→ [4 Bắt tay thiết kế]

Fallback: nếu AI tóm tắt sai/thiếu → intern quay lại tra tài liệu gốc như cũ.
```

---

#### Problem Card #2 — Tìm reference/inspiration thiết kế

```text
Problem 1 câu:
Ở mỗi task mới, intern dành khoảng 2 tiếng xem nhiều nền tảng (Dribbble, Behance, Pinterest,
Mobbin) để chọn reference phù hợp, nhưng quá trình này dễ bị kéo dài và phân tán sự chú ý.

Actor:
Design intern.

Thời điểm / bối cảnh:
Giai đoạn đầu mỗi task, trước khi phác thảo ý tưởng thiết kế.

Current workflow 3-7 bước:
1. Xác định loại UI/feature cần tham khảo
2. Search trên nhiều nền tảng khác nhau
3. Lưu lại các ảnh/ý tưởng ưng ý
4. So sánh, chọn lọc hướng phù hợp với brand/context hiện tại
5. Tổng hợp thành moodboard

Bottleneck:
Bước 2 — việc tìm kiếm trên nhiều nguồn chưa được lọc theo ngữ cảnh phù hợp (ngành, loại UI,
phong cách), nên phải mất nhiều công sức sàng lọc bằng tay.

Impact:
Khoảng 2 tiếng/task; khi có nhiều task trong tuần, thời gian này cộng dồn đáng kể nhưng
vẫn chưa đảm bảo đã chọn được reference tốt nhất.

Success metric:
Rút thời gian tìm reference xuống dưới 45 phút/task, trong khi moodboard vẫn đủ tốt để
mentor duyệt hướng thiết kế ngay ở lần đầu.

Non-AI alternative:
Tạo một thư viện reference nội bộ đã được chọn lọc theo các loại UI thường sử dụng.

AI hypothesis:
AI đề xuất reference dựa trên mô tả ngữ cảnh (ngành, loại UI, phong cách mong muốn), qua đó
giảm thời gian phải tìm thủ công trên nhiều nền tảng.

Quick gut:
[x] Workflow
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 2h

[1 Xác định loại UI: 5'] → [2 Search nhiều nguồn: 1h30]  <-- bottleneck
→ [3 Lưu ý tưởng: 15'] → [4 Chọn lọc + moodboard: 30']

FUTURE STATE — 40-45 phút

[1 Xác định loại UI: 5'] → [2 AI gợi ý reference theo mô tả: 5']
→ [3 Intern chọn lọc + review: 25']  <-- human boundary
→ [4 Tổng hợp moodboard: 10']

Fallback: nếu AI gợi ý không sát gu/brand → quay lại search thủ công như cũ.
```

---

#### Problem Card #3 — Viết meeting notes sau buổi sync

```text
Problem 1 câu:
Sau mỗi buổi sync với mentor/team (1-2 buổi/tuần), intern thường mất khoảng 1 tiếng để
chuyển ghi chú thô thành note có cấu trúc, nên việc bắt đầu task tiếp theo bị chậm lại.

Actor:
Design intern.

Thời điểm / bối cảnh:
Ngay sau buổi họp/sync với mentor hoặc team.

Current workflow 3-7 bước:
1. Tham gia họp, ghi chú rời rạc
2. Nhớ lại / nghe lại nội dung chính
3. Viết lại thành note có cấu trúc (quyết định, action item)
4. Gửi note cho team xác nhận

Bottleneck:
Bước 3 — sắp xếp ghi chú rời rạc thành note có cấu trúc, với nguy cơ bỏ quên action item.

Impact:
Khoảng 1 tiếng/buổi x 1-2 buổi/tuần = 1-2 tiếng/tuần, ảnh hưởng đến thời gian quay lại
task chính.

Success metric:
Rút thời gian hoàn thiện note xuống dưới 20 phút/buổi, vẫn đủ action item và không khiến
team phải hỏi lại "hôm đó đã quyết định gì".

Non-AI alternative:
Sử dụng template cố định (agenda / quyết định / action item) và điền ngay trong cuộc họp.

AI hypothesis:
AI chuyển ghi chú thô thành note có cấu trúc (quyết định + action item), intern chỉ cần
kiểm tra lại rồi gửi cho team.

Quick gut:
[x] Workflow
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 1h

[1 Ghi chú rời rạc trong họp: 0'] → [2 Nhớ/nghe lại: 20'] → [3 Viết note cấu trúc: 30']  <-- bottleneck
→ [4 Gửi team: 10']

FUTURE STATE — 15-20 phút

[1 Ghi chú rời rạc trong họp: 0'] → [2 AI tóm tắt thành note cấu trúc: 3']
→ [3 Intern review + sửa: 10']  <-- human boundary
→ [4 Gửi team: 2']

Fallback: nếu AI tóm tắt thiếu ý quan trọng → intern bổ sung thủ công từ ghi chú gốc.
```

---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Research tài liệu kỹ thuật đầu task
```

**Vì sao (2-3 câu):**

```text
Đây là workflow tốn nhiều thời gian nhất (2-3 ngày/task) trong công việc của intern. Nút
thắt nằm rõ ở việc tìm và đọc tài liệu từ nhiều nguồn, còn impact có thể đo trực tiếp qua
số ngày bị chậm trước khi bắt đầu thiết kế thực tế.
```

**Câu hỏi tôi muốn nhóm challenge:**

```text
1. Bản tổng hợp tài liệu nội bộ (Figma/Notion) do AI tạo ra có đủ chính xác để dùng ngay không,
   hay intern vẫn phải kiểm tra toàn bộ trước khi áp dụng?
2. Khi tài liệu design system thay đổi thường xuyên, nguồn dữ liệu của AI có cần được cập nhật
   liên tục không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Metric "giảm xuống dưới 1 ngày" chưa được đối chiếu với baseline của nhiều task, nên chưa thể khẳng định 2-3 ngày là mức ổn định mà mới dựa trên cảm nhận cá nhân.
- Tôi sửa gì: Tôi sẽ theo dõi thêm 2-3 task tiếp theo để thu được baseline thực tế trước khi chốt số liệu cuối.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge