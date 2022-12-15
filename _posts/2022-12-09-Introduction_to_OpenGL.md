---
layout: post
title: Giới thiệu về OpenGL
categories: opengl
---

## **Tổng Quan**
*Bài viết này tham khảo từ blog [VIBLO](https://viblo.asia/p/tim-hieu-ve-opengl-13-ZjleallxGqJ)*

OpenGL là viết tắt cho "Open Graphics Library". Nó là nơi gần nhất giữa CPU và CPU nên cần có sự hỗ trợ bởi các nhà sản xuất đồ họa (vd: NVidia) và được cài đặt bởi các đối tác phát triển hệ điều hành (vd: Apple, Microsoft). OpenGL cung cấp cho chúng ta một API (Application programming interface) miễn phí, thống nhất để làm việc.

### **Lịch Sử**
- Khoảng 20 năm trước có một người tên là **Silicon Graphics (SGI)** tạo ra một loại thiết bị nhỏ. Thiết bị này có thể nhận ra các ảo ảnh rất thực tế. Với ảnh 2D, thiết bị đó hiển thị được các ảnh kiểu 3D, mô phỏng cái nhìn và chiều sâu theo mắt của con người. Thiết bị đó được gọi là **IrisGL**.
- Đó chính là thiết bị đồ họa đầu tiên của chúng ta. Nhưng nó chết quá nhanh vì để làm được như thế cần điều khiển quá nhiều thứ như card đồ họa, hệ điều hành, các ngôn ngữ lập trình, giao diện tương tác người dùng,... Quá nhiều thứ khiến cho 1 công ty quản lý còn khó chưa nói tới 1 người. Vì vậy, **SGI** bắt đầu chuyển sang một thứ giống như "thẻ tạo đồ họa", "hệ thống quản lý cửa sổ", "tạo giao diện người dùng" cho các cty khác và tập trung vào phần quan trọng nhất của thư viện đồ họa. Năm 1992 đã ra đời OpenGL thế hệ đầu tiên.
- Vào năm 1995, Microsoft giới thiệu **Direct3D**, đối thủ cạnh tranh đáng gờm với **OpenGL**. Tới năm  1997, OpenGL 1.1 được tung ra. Năm 2004, OpenGL 2.0 ra mắt với Shaders, lập trình pipeline. Năm 2007, OpenGL ES 2.0 đã mang sức mạnh của Shader và Programmable pipeline.

