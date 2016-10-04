# Cài đặt font Consolas trên Ubuntu 16.04

Sưu tầm: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 04 tháng 10 năm 2016

## Tài liệu tham khảo

[Consolas Font On Ubuntu](http://www.rushis.com/consolas-font-on-ubuntu/)

## Hướng dẫn thực hiện

* Bước 1: Cài đặt gói lệnh

		$ sudo apt-get install font-manager
		
		$ suod apt-get install cabextract

* Bước 2: Tạo một sheel script với nội dung như bên dưới:

	+ Tạo file `consolas.sh`:
	
			$ nano consolas.sh
			
	+ Thêm vào file `consolas.sh` với nội dung như bên dưới:
	
			#!/bin/sh
			
			set -e
			
			set -x
			
			mkdir temp

			cd temp
			
			wget http://download.microsoft.com/download/E/6/7/E675FFFC-2A6D-4AB0-B3EB-27C9F8C8F696/PowerPointViewer.exe
			
			cabextract -L -F ppviewer.cab PowerPointViewer.exe
			
			cabextract ppviewer.cab

	+ Nhấn `Ctrl + X + Y` để lưu nội dung và thoát.
	
	+ Địa chỉ tải script `consolas.sh`: [Download](https://github.com/h3int2um/ubuntu/blob/master/ubuntu-tutorials/code-tutorials/consolas.sh)
	
* Bước 3: Thực thi script vừa tạo

		$ chmod +x consolas.sh
		
		$ ./consolas.sh
		
* Bước 4: Cài đặt font `Consolas`:

		$ cd  temp/
		
		$ font-manager
		
	+ Giao diện như sau:
	
		![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-tutorials/images-ubuntu-tutorials/gui-font-manager-on-ubuntu.png)
		
	+ Chọn biểu tượng setting `Manage fonts` (dãy biểu tượng dưới cùng, gần nút `save`), chọn `Install fonts`.
	
	+ Chỉ đến đường dẫn thư mục `temp` chọn font `CONSOLA.TTF` để cài đặt font `Consolas`.
	
	+ Sau khi cài đặt chọn `Reload Latter` hoặc `Reload Now`.
	
* Cách xóa thư mục chứa font tải về và script `consolas.sh`:

		$ sudo rm -R temp
		
		$ sudo rm consolas.sh
