# Xem thông tin hệ điều hành Ubuntu bằng dòng lệnh với NeoFetch

Tìm hiểu: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 01 tháng 12 năm 2016

## Tài liệu tham khảo

[NeoFetch — See System Information from the Command Line on Linux](http://www.omgubuntu.co.uk/2016/11/neofetch-terminal-system-info-app).

## Mục đích cài đặt NeoFetch

Xem thông tin của hệ điều hành  bằng dòng lệnh trên Ubuntu, Linux,...

![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/install-neofetch-guide-ubuntu.png)

## Hướng dẫn cài đặt

* Bước 1: Thêm `neofetch` vào `repository` bằng `PPA`:

		$ sudo add-apt-repository ppa:dawidd0811/neofetch

	![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/install-neofetch-add-repository-ppa-ubuntu.png)
	
* Bước 2: Cập nhật lại `repository` và cài đặt `NeoFetch`:

		$ sudo apt update && sudo apt install neofetch
		
	![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/install-neofetch-ubuntu.png)

## Hướng dẫn sử dụng

* Để xem thông tin của hệ điều hành, dùng lệnh:

		$ neofetch
		
	![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/install-neofetch-guide-ubuntu.png)
	
* Để biết cách sử dụng đầy đủ các tham số của lệnh `neofetch`, dùng lệnh:

		$ neofetch --help
		
	![](https://raw.githubusercontent.com/h3int2um/ubuntu/master/ubuntu-apps/images-ubuntu-apps/install-neofetch-help-ubuntu.png)
