# Web Development with WSL
<b>WSL (Windows Subsystem for Linux)</b> là một trong những nỗ lực mới nhất của Microsoft trong việc níu chân developer ở nền tảng Windows. Được giới thiệu chính thức ở bản Windows 10 Arniversary Update, từ việc chỉ hỗ trợ Ubuntu riêng lẻ, WSL giờ đã có thể chạy được mọi Linux distro một cách rất ổn định. Tut này cung cấp cái nhìn tổng quan về WSL và hướng dẫn setup môi trường Web Development nói chung.
# Changelog
<b>v1.2 (current)</b>: thêm hướng dẫn isolate WSL.
<b>v1.1</b>: thay MobaXterm bằng VcXsrv.
<b>v1.0</b>: initial version.
# Getting Started
Tut này sử dụng Ubuntu 18.04 làm core của WSL và thiết lập môi trường dev Magento 2 hoàn thiện. Như vậy các bước tiến hành bao gồm:
I. Tinh chỉnh Windows 10
II. Cài Ubuntu 18.04 WSL
1.	Enable WSL
2.	Download, launch and install Ubuntu 18.04
3.	Move WSL to another place
III. Sử dụng các tool linux trong WSL dưới dạng GUI
1.	Setting up VcXsrv to run Graphical Linux Apps
2.	Install Sublime Text
3.	Install VS Code
4.	Install PHPStorm
IV. Cài LEMP Stack
1.	Install NGINX
2.	Install MariaDB
3.	Install PHP 7.1-FPM
V. Cài Magento 2
1.	Download Magento 2
2.	Create Magento 2 Database
3.	Create NGINX VirtualHost
4.	Install Magento 2 via command line
5.	Optimize Magento 2 for development purpose
VI. Tips n’ Tricks
