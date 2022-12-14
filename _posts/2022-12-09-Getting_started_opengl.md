---
layout: post
title: Getting Started with OpenGL
categories: opengl
---

- **Opengl** thường được coi là 1 API(Application Programming Interface) cung cấp cho chúng ta một số lượng lớn các **HÀM** dùng để thao tác với
 đồ họa và hình ảnh. Tuy nhiên, bản thân OpenGl không phải là 1 API, nó chỉ là một chuẩn được phát triển và duy trì bởi tổ chức **Khronos Group**
- OpenGL chỉ định chính xác kết quả của mỗi function và cách thức hoạt động của nó. Sau đó, các nhà phát sẽ đưa ra giải pháp và cách thức hoạt động của function. Vì vậy, tiêu chuẩn OpenGL không cung cấp cho chúng ta chi tiết triển khai. Trên thực tế, các phiên bản OpenGL cho phép triển khai khác nhau, miễn là kết quả đầu ra là như nhau (tuân thủ tiêu chuẩn chung).
- Người phát triển Lib **Opengl** thường là các nhà sẳn xuất card đồ họa (nvidia, amd, apple, ...). Mỗi loại card sẽ hỗ trợ phiên bản cụ thể của Lib OpenGL. Ví dụ với các thiết bị Apple thì họ sẽ là người phát triển và bảo trì Lib trên card của họ. Vì vậy, khi vấn đề đồ họa trên thiết bị của chúng ta gặp lỗi, nó có thể được giải quyết bằng việc cập nhật phiên bản mới của card.
- **Khronos** lưu trữ tất cả các tài liệu chuẩn của các phiên bản OpenGL. 

## Core-profile vs Immediate mode
- Ngày xưa, việc sử dụng openGL để phát triển có nghĩa là **Immediate mode** cái mà rất dễ dàng sử dụng cho việc vẽ đồ họa. Nhưng các function của nó bị ẩn bên trong library. Vì vậy, các nhà phát triển không thể nào tùy biến việc triển khai của các hàm bên trong thư viện.
- Đến version 3.2, OpenGL loại bỏ chế độ **Immediate mode** và bắt đầu thù đẩy các nhà phát triển triển khai trong chế độ **Core-profile**. OpenGL loại bỏ các hàm không còn dùng tới nữa.

