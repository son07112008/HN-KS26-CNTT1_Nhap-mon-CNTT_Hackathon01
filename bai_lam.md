# BÀI LÀM – HACKATHON 01

- **Mã đề:** 19
- **Họ tên:Hoàng Ngọc Sơn
- **Lớp:CNTT1
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):Windows** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

Get-Location
Get-ChildItem –Force
Move-Item lich_trinh.txt docs/
Move-Item logo* media/
Copy-Item media/logo* backup/
Remove-Item *.tmp
cd ./logs; Get-ChildItem -Force; cd ..

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng

Get-Location
Get-ChildItem –Force
Move-Item lich_trinh.txt docs/
Move-Item logo* media/
Copy-Item media/logo* backup/
Remove-Item *.tmp
cd ./logs; Get-ChildItem -Force; cd ..
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)
Mode                 LastWriteTime    Length
----                 -------------    ------
d-----        10/28/2026   8:05 AM
d-----        10/16/2026   8:25 AM
d-----        10/14/2026   8:37 AM
d-----        10/13/2026   2:20 PM
d-----         10/9/2026   8:38 AM
-a----        10/27/2026  12:59 AM    382874
-a-hs-          9/7/2026   1:05 AM       282
-a----        10/22/2026  10:41 AM      2250
-a----         9/22/2026   4:01 PM      2648
-a----         9/23/2026  11:59 AM      2042
-a----         10/7/2026   8:21 AM       572
-a----         10/4/2026  12:41 PM      2350
-a----         9/23/2026  12:07 PM      2667
-a----         9/22/2026   4:01 PM      2642
-a----         9/22/2026   4:01 PM      2656
-a----          9/6/2026  10:18 AM      2225
-a----        10/19/2026   6:50 PM      1933


    Directory: C:\Users\Admin\Desktop\Bài 1


Mode                 LastWriteTime    Length
----                 -------------    ------
-a----        10/27/2026   1:00 AM    382873
-a----        10/27/2026   1:00 AM     15580
-a-h--        10/27/2026   1:00 AM       165


    Directory: C:\Users\Admin\Desktop\bài 2


Mode                 LastWriteTime    Length
----                 -------------    ------
-a----        10/16/2026   8:32 AM      2451


    Directory:
    C:\Users\Admin\Desktop\session08


Mode                 LastWriteTime    Length
----                 -------------    ------
-a----        10/14/2026   8:37 AM        38
-a----        10/14/2026   8:37 AM        22


    Directory:
    C:\Users\Admin\Desktop\session7


Mode                 LastWriteTime    Length
----                 -------------    ------
d-----        10/13/2026   1:33 PM
d-----        10/13/2026   1:33 PM
d-----        10/13/2026   2:20 PM
-a----        10/13/2026   2:21 PM       253


    Directory:
    C:\Users\Admin\Desktop\terminal


Mode                 LastWriteTime    Length
----                 -------------    ------
d-----         10/7/2026   8:26 AM
d-----         9/28/2026   8:32 AM
d-----         10/9/2026   8:34 AM
d-----         10/9/2026   8:38 AM
d-----         10/7/2026   9:30 AM
d-----         10/7/2026   9:30 AM
d-----         10/7/2026   9:29 AM
d-----         10/7/2026   8:29 AM
d-----         10/7/2026   8:29 AM
d-----         10/7/2026   9:22 AM
d-----         10/7/2026   9:25 AM
-a----        10/13/2026   2:18 PM       230


    Directory:
    C:\Users\Admin\Desktop\terminal\cntt1
    NMCNTT


Mode                 LastWriteTime    Length
----                 -------------    ------
d-----         10/7/2026   8:26 AM


    Directory: C:\Users\Admin\Desktop\termin
    al\session01


Mode                 LastWriteTime    Length
----                 -------------    ------
-a----         9/28/2026   8:30 AM         0
-a----         9/28/2026   8:32 AM         0
```text


```

## 4.3. Lọc log thủ công

### Lệnh đã chạy
grep "ERROR" logs/travel.log > logs/daily_report.txt
head -n 2 logs/daily_report.txt
```shell
grep "ERROR" logs/travel.log > logs/daily_report.txt
head -n 2 logs/daily_report.txt
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dat_tour_thang_8.xlsx`, không cần ghi vào đây.

