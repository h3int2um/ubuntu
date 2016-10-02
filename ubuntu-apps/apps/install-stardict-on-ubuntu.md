# Cài đặt bộ từ điển Anh - Việt cho StarDict trên Ubuntu 16.04

Thực hiện: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 02 tháng 10 năm 2016

## Hướng dẫn cài đặt

* Bước 1: Cài đặt bộ từ điển `StarDict` trên Ubuntu:

		$ sudo apt-get install stardict stardict-plugin
		
	Đợi quá trình cài đặt hoàn thành.

* Bước 2: Kiểm tra phiên bản `StarDict` được cài đặt:

		$ stardict --version
		
		GNOME stardict 3.0.1
	
* Bước 3: Cài đặt từ điển `Anh - Việt` cho `StarDict`:

	+ Tải bộ từ điển `Anh - Việt` về máy: [Download](https://drive.google.com/drive/folders/0B6_x_4VdySxqZFp0ZzZXTFN2ZjA). 
	Chọn tải về 3 file `dictd_anh-viet.dict.dz`, `dictd_anh-viet.idx` và `dictd_anh-viet.ifo`.
	
	+ Ví dụ: thư mục tải về (của 3 file trên) là thư mục `Downloads`.
	
	+ Di chuyển các file của bộ từ điển `Anh - Việt` vào thư mục `/usr/share/stardict/dic`:
	
			$ cd ~
			
			$ sudo mv Downloads/dictd_anh-viet.* /usr/share/stardict/dic

## Hướng dẫn sử dụng

* Mở `StarDict`, có 2 cách:

	+ Cách 1: Trong thanh `Dash` gõ tên ứng dụng `stardict`.
	
	+ Cách 2: Mở ứng dụng `StarDict` từ Terminal:
	
			$ stardict
			
	+ Ứng dụng `StarDict`:
	
		![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/stardict-on-ubuntu.png)
		
* Sử dụng ứng dụng `StarDict`:

	+ Cách 1: Nhập trực tiếp từ cần tra vào khung bên cạnh nút `Clear`.
	
		![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/using-stardict-on-ubuntu.png)
	
	+ Cách 2: Bôi đen từ cần tra, ứng dụng sẽ tự động dịch nghĩa của từ đó.
	
* Thoát ứng dụng:

	+ Cách 1: Click vào biểu tượng `x` để thoát.
	
	+ Cách 2: Nhấn tổ hợp phím `Ctrl + Q` để thoát.
	
## Cài đặt các bộ từ điển khác

Thực hiện cài đặt các bộ từ điển: `Nga - Việt`, `Pháp - Việt`, `Việt - Anh` và `Việt - Pháp` hoàn toàn tương tự như trên.
