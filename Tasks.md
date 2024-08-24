### 1. Liệt kê số lượng tham số đầu vào và giải thích ý nghĩa từng giá trị (Word & Powerpoint)

> Người thực hiện: @

Đọc trong [`data_description.txt`](./data/data_description.txt) (có tất 80 trường)

#### Ví dụ:

```plaintext
MSSubClass: Identifies the type of dwelling involved in the sale.	

        20	1-STORY 1946 & NEWER ALL STYLES
        30	1-STORY 1945 & OLDER
        40	1-STORY W/FINISHED ATTIC ALL AGES
        45	1-1/2 STORY - UNFINISHED ALL AGES
        50	1-1/2 STORY FINISHED ALL AGES
        60	2-STORY 1946 & NEWER
        70	2-STORY 1945 & OLDER
        75	2-1/2 STORY ALL AGES
        80	SPLIT OR MULTI-LEVEL
        85	SPLIT FOYER
        90	DUPLEX - ALL STYLES AND AGES
       120	1-STORY PUD (Planned Unit Development) - 1946 & NEWER
       150	1-1/2 STORY PUD - ALL AGES
       160	2-STORY PUD - 1946 & NEWER
       180	PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
       190	2 FAMILY CONVERSION - ALL STYLES AND AGES
```

#### Kết quả mong muốn

MSSubClass: dùng để xác định loại hình nhà ở liên quan đến giao dịch mua bán

- 20: Nhà một tầng, xây từ năm 1946 trở về sau, tất cả các kiểu dáng.
- 30: Nhà một tầng, xây từ năm 1945 trở về trước.
- 40: Nhà một tầng có tầng áp mái hoàn thiện, không phụ thuộc vào năm xây dựng.
- 45: Nhà một tầng rưỡi, tầng áp mái chưa hoàn thiện, không phụ thuộc vào năm xây dựng.
- 50: Nhà một tầng rưỡi, tầng áp mái đã hoàn thiện, không phụ thuộc vào năm xây dựng.
- 60: Nhà hai tầng, xây từ năm 1946 trở về sau.
- 70: Nhà hai tầng, xây từ năm 1945 trở về trước.
- 75: Nhà hai tầng rưỡi, không phụ thuộc vào năm xây dựng.
- 80: Nhà chia tầng hoặc nhiều tầng.
- 85: Nhà có tầng foyer (tầng thấp hơn một nửa so với tầng chính).
- 90: Nhà duplex (nhà có hai căn hộ riêng biệt) - tất cả các kiểu dáng và thời kỳ xây dựng.
- 120: Nhà một tầng trong khu phát triển quy hoạch (PUD), xây từ năm 1946 trở về sau.
- 150: Nhà một tầng rưỡi trong khu phát triển quy hoạch, không phụ thuộc vào năm xây dựng.
- 160: Nhà hai tầng trong khu phát triển quy hoạch, xây từ năm 1946 trở về sau.
- 180: Nhà nhiều tầng trong khu phát triển quy hoạch, bao gồm nhà chia tầng hoặc có tầng foyer.
- 190: Nhà chuyển đổi thành nhà hai hộ gia đình, không phụ thuộc vào kiểu dáng và thời kỳ xây dựng.


### 2. 