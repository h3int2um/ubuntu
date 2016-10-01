# Gõ tiếng Việt trong Ubuntu 16.04

Sưu tầm: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 02 tháng 10 năm 2016

## Tài liệu tham khảo

[Hướng dẫn cài bộ gõ tiếng Việt trên Ubuntu 16.04 LTS - ibus-unikey](http://nguyenhuuhoang.com/huong-dan-cai-bo-go-tieng-viet-tren-ubuntu-16-04-lts-ibus-unikey/)

## Hướng dẫn thực hiện

* Bước 1: Cài đặt `ibus-unikey`.

		sudo apt-get install ibus-unikey
		
* Bước 2: Khởi động `ibus`.

		ibus restart
		
* Bước 3: Thực hiện cấu hình bàn phím.

	+ Trong thanh `Dash` nhập vào `Text Entry`. Click vào để mở `Text Entry`.
	
		![Text Entry](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-tutorials/images-ubuntu-tutorials/text-entry.png)
	
	+ Click vào dấu `+` trên hàng `Show current input source in the menubar`. Cửa sổ `Choose and input source` xuất hiện.
	
	+ Nhập vào `vietnamese` chọn `Vietnamese(Unikey)(IBus)` và click chọn `Add`.
	
		![Vietnamese(Unikey)(IBus)](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-tutorials/images-ubuntu-tutorials/vietnamese-ibus-unikey.png)
		
	+ Sau khi chọn `Add` được kết quả như hình dưới:
	
		![Add Vietnamese(Unikey)(Ibus)](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-tutorials/images-ubuntu-tutorials/add-vietnamese-ibus-unikey.png)
		
	+ Chọn phím tắt chuyển đổi giữa kiểu gõ tiếng Anh và tiếng Việt trong 2 khung `Switch to next source using` và 
	`Switch to previous source using`. *Ví dụ* chọn `Shift + Ctrl`  được như hình dưới:
	
		![Shift + Ctrl](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-tutorials/images-ubuntu-tutorials/shift-ctrl-en-to-vi.png)
		
	+ Đóng của sổ `Text Entry`.

* Sau này, mỗi khi bật hoặc tắt chế độ gõ tiếng Việt, nhấn tổ hợp phím `Shift + Ctrl`.
