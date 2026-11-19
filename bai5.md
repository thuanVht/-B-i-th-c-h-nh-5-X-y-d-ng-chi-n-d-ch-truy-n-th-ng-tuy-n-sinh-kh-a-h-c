# **BÀI TẬP THỰC HÀNH: XÂY DỰNG CHIẾN DỊCH TRUYỀN THÔNG BẰNG PROMPT CHAINING**

## **1. Sơ đồ mô tả chuỗi Prompt Chaining**

Sử dụng 5 prompt liên tiếp để xây dựng chiến dịch truyền thông tuyển sinh khóa học Python cơ bản.

**Prompt 1: Phân tích khách hàng mục tiêu**

Xác định nhu cầu, khó khăn, hành vi và sở thích

**Prompt 2: Xây dựng thông điệp truyền thông**

Dựa trên chân dung khách hàng từ Prompt 1

**Prompt 3: Lập kế hoạch nội dung 7 ngày**

Dựa trên khách hàng và thông điệp từ Prompt 1, 2

**Prompt 4: Viết nội dung quảng cáo**

Tạo 2 bài Facebook và 2 kịch bản TikTok

**Prompt 5: Kiểm tra tính nhất quán**

Đối chiếu toàn bộ nội dung với mục tiêu ban đầu

## **2. Xây dựng chuỗi Prompt**

### **Prompt 1: Phân tích chân dung khách hàng mục tiêu**

**Nội dung Prompt:**

```
Bạn là chuyên gia Marketing trong lĩnh vực giáo dục.

Hãy phân tích khách hàng mục tiêu cho chiến dịch
tuyển sinh khóa học Python cơ bản.

Thông tin:
- Đối tượng: Sinh viên năm nhất.
- Độ tuổi: 18–20.
- Thời lượng khóa học: 8 tuần.
- Mục tiêu: 100 lượt đăng ký tư vấn.
- Kênh truyền thông: Facebook và TikTok.

Hãy phân tích:
1. Nhu cầu học tập.
2. Khó khăn và nỗi lo.
3. Sở thích và hành vi sử dụng mạng xã hội.
4. Động lực đăng ký khóa học.
5. Những yếu tố ảnh hưởng đến quyết định đăng ký.

Trình bày ngắn gọn, rõ ràng.
Không tự ý thay đổi thông tin khóa học.

Đầu ra sẽ được sử dụng cho Prompt 2.
```

**Kết quả Prompt 1: Chân dung khách hàng mục tiêu**

- Đối tượng: Sinh viên năm nhất, từ 18–20 tuổi.
- Nhu cầu: Muốn học lập trình Python từ cơ bản.
- Khó khăn: Chưa có kiến thức lập trình, sợ học khó và không biết bắt đầu từ đâu.
- Sở thích: Xem video ngắn, nội dung công nghệ và chia sẻ kinh nghiệm học tập.
- Hành vi: Thường sử dụng Facebook và TikTok để tìm kiếm thông tin.
- Động lực: Muốn có kiến thức lập trình phục vụ học tập và phát triển nghề nghiệp.

### **Prompt 2: Xác định thông điệp truyền thông**

**Nội dung Prompt:**

```
Bạn là chuyên gia xây dựng thương hiệu giáo dục.

Dựa trên chân dung khách hàng mục tiêu từ Prompt 1,
hãy xây dựng thông điệp truyền thông cho khóa học Python.

Yêu cầu:
1. Đưa ra 3 thông điệp truyền thông đề xuất.
2. Chọn 1 thông điệp phù hợp nhất.
3. Giải thích lý do lựa chọn.
4. Xác định lời kêu gọi hành động (CTA).

Thông tin khóa học:
- Đối tượng: Sinh viên năm nhất, 18–20 tuổi.
- Thời lượng: 8 tuần.
- Mục tiêu: 100 lượt đăng ký tư vấn.

Thông điệp phải gần gũi, dễ nhớ, phù hợp với
người chưa có kiến thức lập trình.

Không thay đổi thông tin khóa học.

Đầu ra sẽ được sử dụng cho Prompt 3.
```

**Kết quả Prompt 2:**

Ba thông điệp đề xuất:

1. Bắt đầu học lập trình Python ngay cả khi bạn chưa biết gì.
2. 8 tuần làm quen với thế giới lập trình Python.
3. Sinh viên năm nhất – bắt đầu hành trình lập trình từ hôm nay.

Thông điệp được lựa chọn

**"Chưa biết lập trình? Bắt đầu với Python từ con số 0!"**

- Lý do: Ngắn gọn, dễ nhớ, đánh đúng tâm lý người mới bắt đầu.
- CTA: Đăng ký tư vấn ngay hôm nay để tìm hiểu khóa học Python cơ bản.

### **Prompt 3: Xây dựng kế hoạch nội dung 7 ngày**

**Nội dung Prompt:**

```
Bạn là chuyên gia lập kế hoạch Content Marketing.

Dựa trên:
- Chân dung khách hàng từ Prompt 1.
- Thông điệp truyền thông từ Prompt 2.

Hãy xây dựng kế hoạch nội dung trong 7 ngày
cho chiến dịch tuyển sinh khóa học Python cơ bản.

Yêu cầu:
1. Lập kế hoạch từ ngày 1 đến ngày 7.
2. Mỗi ngày có chủ đề nội dung cụ thể.
3. Xác định kênh đăng Facebook hoặc TikTok.
4. Xác định mục tiêu của từng bài đăng.
5. Nội dung phải thống nhất với thông điệp chính.
6. Có lời kêu gọi đăng ký tư vấn.

Không thay đổi thông tin khóa học.
Đầu ra sẽ được sử dụng cho Prompt 4.
```

**Kết quả Prompt 3: Lịch đăng nội dung 7 ngày**

| Ngày | Chủ đề nội dung                     | Kênh     | Mục tiêu           |
| ---- | ----------------------------------- | -------- | ------------------ |
| 1    | Giới thiệu khóa học Python          | Facebook | Thu hút chú ý      |
| 2    | Python là gì?                       | TikTok   | Cung cấp kiến thức |
| 3    | Nỗi lo khi mới học lập trình        | Facebook | Tạo sự đồng cảm    |
| 4    | Giới thiệu lợi ích của Python       | TikTok   | Tăng quan tâm      |
| 5    | Lộ trình học Python trong 8 tuần    | Facebook | Giải đáp thắc mắc  |
| 6    | Người mới có học được Python không? | TikTok   | Tạo niềm tin       |
| 7    | Kêu gọi đăng ký tư vấn              | Facebook | Thu hút đăng ký    |

### **Prompt 4: Viết bài quảng cáo Facebook và kịch bản TikTok**

**Nội dung Prompt:**

```
Bạn là chuyên gia sáng tạo nội dung quảng cáo.

Dựa trên kết quả Prompt 1, Prompt 2 và Prompt 3,
hãy viết nội dung quảng cáo cho chiến dịch tuyển sinh.

Yêu cầu đầu ra:

PHẦN 1: FACEBOOK
- Viết 2 bài đăng quảng cáo.
- Tiêu đề thu hút.
- Nội dung ngắn gọn, gần gũi.
- Có lời kêu gọi đăng ký tư vấn.

PHẦN 2: TIKTOK
- Viết 2 kịch bản video.
- Thời lượng mỗi video từ 30–45 giây.
- Có lời thoại, hình ảnh và nội dung từng cảnh.
- Có câu mở đầu thu hút người xem.
- Có CTA ở cuối video.

Tất cả nội dung phải hướng đến sinh viên năm nhất
18–20 tuổi và thống nhất với thông điệp:

"Chưa biết lập trình? Bắt đầu với Python từ con số 0!"

Không tự ý thay đổi thời lượng khóa học 8 tuần
và các thông tin đã cung cấp.
```

**Kết quả Prompt 4: Hai bài đăng Facebook**

### BÀI ĐĂNG FACEBOOK 1: GIỚI THIỆU KHÓA HỌC

**CHƯA BIẾT LẬP TRÌNH? ĐỪNG LO, HÃY BẮT ĐẦU VỚI PYTHON!**

Bạn là sinh viên năm nhất và muốn tìm hiểu về lập trình nhưng chưa biết bắt đầu từ đâu?

Python là một lựa chọn phù hợp để bạn làm quen với thế giới lập trình.

Trung tâm tổ chức khóa học Python cơ bản dành cho người mới bắt đầu với thời lượng **8 tuần**.

Đừng để nỗi sợ lập trình cản trở hành trình học tập của bạn!

**Đăng ký tư vấn ngay hôm nay để tìm hiểu khóa học Python cơ bản nhé!**

### BÀI ĐĂNG FACEBOOK 2: KÊU GỌI ĐĂNG KÝ

**SINH VIÊN NĂM NHẤT – BẠN ĐÃ SẴN SÀNG KHÁM PHÁ PYTHON?**

Bạn muốn học lập trình nhưng chưa có kiến thức nền tảng?

Bạn lo lắng vì không biết viết dòng code đầu tiên như thế nào?

Đừng lo! Khóa học Python cơ bản dành cho người mới bắt đầu sẽ giúp bạn làm quen với lập trình trong thời lượng **8 tuần**.

Hãy bắt đầu hành trình học lập trình ngay từ hôm nay!

**Đăng ký tư vấn để tìm hiểu thêm về khóa học Python cơ bản!**

**Kết quả Prompt 4: Hai kịch bản TikTok**

**Video TikTok 1: Người mới có học được Python không?**

Thời lượng: 30–45 giây

| Thời gian | Hình ảnh                         | Lời thoại                                                                       |
| --------- | -------------------------------- | ------------------------------------------------------------------------------- |
| 0–5s      | Sinh viên nhìn màn hình máy tính | "Bạn muốn học lập trình nhưng chưa biết bắt đầu từ đâu?"                        |
| 5–15s     | Hiển thị dòng code Python        | "Đừng lo! Python là một lựa chọn để bạn bắt đầu làm quen với lập trình."        |
| 15–30s    | Hình ảnh học tập                 | "Khóa học Python cơ bản dành cho người mới bắt đầu có thời lượng 8 tuần."       |
| 30–45s    | Hiện thông tin đăng ký           | "Chưa biết lập trình? Bắt đầu với Python từ con số 0! Đăng ký tư vấn ngay nhé!" |

**Video TikTok 2: Sinh viên năm nhất nên học Python?**

Thời lượng: 30–45 giây

| Thời gian | Hình ảnh                    | Lời thoại                                                                     |
| --------- | --------------------------- | ----------------------------------------------------------------------------- |
| 0–5s      | Sinh viên ngồi trước laptop | "Năm nhất rồi, bạn đã thử học lập trình chưa?"                                |
| 5–15s     | Hiển thị giao diện Python   | "Nếu chưa biết bắt đầu từ đâu, hãy thử tìm hiểu Python cơ bản."               |
| 15–30s    | Hình ảnh sinh viên học tập  | "Khóa học dành cho người mới bắt đầu với thời lượng 8 tuần."                  |
| 30–45s    | Hiện thông điệp và CTA      | "Đừng ngại bắt đầu từ con số 0. Đăng ký tư vấn khóa học Python ngay hôm nay!" |

### **Prompt 5: Kiểm tra tính nhất quán toàn bộ chiến dịch**

**Nội dung Prompt:**

```
Bạn là chuyên gia kiểm định chiến dịch Marketing.

Hãy kiểm tra toàn bộ kết quả từ Prompt 1 đến Prompt 4.

Các tiêu chí kiểm tra:
1. Nội dung có đúng đối tượng sinh viên năm nhất
   từ 18–20 tuổi không?
2. Có thống nhất thông điệp truyền thông chính không?
3. Lịch nội dung 7 ngày có phù hợp với mục tiêu không?
4. Hai bài Facebook có phù hợp với khách hàng mục tiêu không?
5. Hai video TikTok có thời lượng 30–45 giây không?
6. Có sử dụng đúng thông tin khóa học 8 tuần không?
7. Có lời kêu gọi đăng ký tư vấn không?

Nếu phát hiện lỗi, hãy chỉ rõ lỗi và đề xuất chỉnh sửa.

Không tự ý thay đổi thông tin khóa học.

Cuối cùng, đưa ra báo cáo đánh giá tính nhất quán.
```

## **3. Báo cáo kiểm tra tính nhất quán**

| Tiêu chí                  | Kết quả                | Đánh giá |
| ------------------------- | ---------------------- | -------- |
| Đúng đối tượng 18–20 tuổi | Sinh viên năm nhất     | Đạt      |
| Đúng thông điệp chính     | Python từ con số 0     | Đạt      |
| Kế hoạch 7 ngày           | Có đủ 7 ngày           | Đạt      |
| Hai bài Facebook          | Đúng chủ đề tuyển sinh | Đạt      |
| Hai video TikTok          | Có kịch bản 30–45 giây | Đạt      |
| Thời lượng khóa học       | 8 tuần                 | Đạt      |
| CTA đăng ký tư vấn        | Có trong nội dung      | Đạt      |
