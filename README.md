# 📚 Project - Java

Source Code Bài tâp lớn Kỹ thuật phần mềm về quản lí thư viện trường đại học Phenikaa

## Sử dụng: 

         - Java swing (Graphical User Interface) -> tạo giao diện người dùng 
         - Java AWT (Abstract Window Toolkit) -> tạo các giao diện đồ họa

## Nhóm 4:

                             |  Nguyễn Thị Hà  |  Hồ Thị Hương | Nguyễn Thị Ngọc Trâm|
                             |     21010988    |    21011200   |      21011418       |  
                             |   K15-CNTT-VJ1  |  K15-CNTT-VJ1 |    K15-CNTT-VJ1     |

## Hướng dẫn chạy code:

Clone code từ git

         git clone https://github.com/NgyanHa02072003/BTL_Cuoiky_KTPM.git

sau khi clone có folder:

        BTL_Cuoiky_KTPM/
            LMP/
                idea/
                out/
                src/
            LibraryJTP/

## How to Run

**Bước 1:** Cài IDE Intelij tại link

         https://www.jetbrains.com/idea/download/#section=windows 

**Bước 2:** Đăng ký tài khoản jetbrain để sử dụng IDE, sau khi mở Intelij chọn Open -> LMP -> OK kết quả như hình dưới:

![step2](Images/OpenProject.png)

**Bước 3** Chọn File -> Project Structure -> Modules -> Dependencies -> + -> JARs or Directories... -> tìm đường dẫn LibraryJPT.jar + mysql-connector

![step3](Images/JAR.png)

**Bước 4** Vào package Database 

    Mở mysql trên máy, chạy từng dòng trong LM.sql (trừ dòng drop database ...) để:
        - tạo database
        - tạo bảng
        - thêm nội dung vào trong bảng 

![step4](Images/mysql.png)

    Chọn DB đổi mật khẩu mysql (phần bôi đen)

![step4](Images/password.png)

**Bước 5:** Chạy file Main: Giao diện ra như hình dưới, chọn Admin Login để tạo tài khoản Libararian -> nhập tài khoản mật khẩu là:

        phenikaa
        k15cntt

![step5](Images/run.png)
