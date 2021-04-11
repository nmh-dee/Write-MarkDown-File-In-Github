# Cách sử dụng ngôn ngữ Markdown
# 1.Thẻ tiêu đề
Ví dụ:
```
# 1. Tiêu đề cấp 1
```
*Kết quả:*
# 1. Tiêu đề cấp 1
```
## 2.Tiêu đề cấp 2
````

*Kết quả:*
## 2.Tiêu đề cấp 2

# 2. Chèn link, chèn ảnh
Để chèn hyperlink chỉ cần paste luôn link vào file.md
```
https://github.com
```
*Kết quả:*
https://github.com

Hoặc sử dụng cú pháp để thu ngắn đường link:
```
[Github](https://github.com)
```
*Kết quả:*
[Github](https://github.com)

Để chèn ảnh thì sử dụng cú pháp sau:
```
<img src="link_anh_cua_ban">
```
#3. Ký tự in đậm, in nghiêng:
Để in đậm:
```
**từ cần in đậm**
```
Để in nghiêng:
```
*từ cần in nghiêng*
```
# 4. Trích dẫn, bo chữ
Để bo chữ:
```
'đoạn cần bo'
```
*Kết quả:*
'đoạn cần bo'

Để làm nổi bật 1 đoạn, chẳng hạn như một đoạn shell hay file cấu hình bạn có thể sử dụng cú pháp như sau:

    ```sh
    auto eth0
    iface eth0 inet static
    ipaddress 10.10.10.10
	netmask 255.255.255.0
	gateway 10.10.10.1
	dns-nameservers 8.8.8.8
    ```
*Kết quả:*
```sh
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```
#5. Gạch đầu dòng
Để sử dụng gạch đầu dong, sử dụng cú pháp:
```
- Gạch dầu dòng thứ nhất
  -  Thụt với đầu dòng 1
  -  Thụt với đầu dòng 1
- Gạch đầu dòng thứ hai
  -  Thụt với đầu dòng 2
  -  Thụt với đầu dòng 2
```

*Kết quả:*
- Gạch dầu dòng thứ nhất
  -  Thụt với đầu dòng 1
  -  Thụt với đầu dòng 1
- Gạch đầu dòng thứ hai
  -  Thụt với đầu dòng 2
  -  Thụt với đầu dòng 2
#6. Tạo bảng
```
| Cột 1  | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
```
*Kết quả:*
| Cột 1  | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
