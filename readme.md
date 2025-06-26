# Bài Tập Giữa Kì: ỨNG DỤNG THƯƠNG MẠI ĐIỆN TỬ SPORTX - BÁN HÀNG THỂ THAO
# Họ và tên: Lê Văn Hiếu  
# Mã Sinh Viên : 22010034
## 1. Giới Thiệu


Mục tiêu:
SportX là một ứng dụng thương mại điện tử chuyên bán các sản phẩm thể thao, bao gồm giày, quần áo, phụ kiện và dụng cụ tập luyện. Website giúp người dùng dễ dàng tìm kiếm sản phẩm phù hợp, cung cấp đầy đủ thông tin chi tiết và mang đến trải nghiệm mua sắm tiện lợi, nhanh chóng.

Phạm vi:
Người dùng:
Truy cập trang chủ, xem danh sách sản phẩm, xem chi tiết sản phẩm, tìm kiếm sản phẩm, thêm sản phẩm vào giỏ hàng và đặt hàng.
Quản trị viên:
Quản lý sản phẩm, danh mục sản phẩm, đơn hàng và theo dõi thống kê thông qua dashboard quản trị.


Công Nghệ sử dụng: Laravel 11, Framework PHP mạnh mẽ cho phát triển ứng dụng web.
## 2. Tính Năng Chính
Trang Chủ: Giới thiệu ứng dụng và hiển thị sản phẩm nổi bật.
Danh Sách & Chi Tiết Sản Phẩm: Xem danh sách sản phẩm và chi tiết từng sản phẩm.
Tìm Kiếm Sản Phẩm: Cho phép tìm kiếm theo tên, danh mục hoặc thương hiệu.
Giỏ Hàng & Đặt Hàng: Thêm sản phẩm vào giỏ, cập nhật số lượng và thanh toán đơn hàng.
Xác Thực Người Dùng: Đăng ký, đăng nhập và quản lý tài khoản cá nhân.
Quản Lý Admin:
Dashboard quản trị để quản lý sản phẩm, danh mục, đơn hàng và theo dõi doanh số bán hàng.
## 3. Sơ Đồ Cấu Trúc & Chức Năng
Hình ảnh minh họa sơ đồ cấu trúc và chức năng của ứng dụng, bao gồm:
![mermaid-ai-diagram-2025-03-06-051454](https://github.com/user-attachments/assets/4d7979ec-4758-448b-b16e-4c825f1f28b7)
![mermaid-ai-diagram-2025-03-06-051201](https://github.com/user-attachments/assets/142794c5-dd52-4483-b6c3-54fae24dbc14)
![mermaid-ai-diagram-2025-03-06-051827](https://github.com/user-attachments/assets/238f1dfd-97d4-4998-a2c0-4d90d1cd1ed2)
## 4. Sơ Đồ Thuật Toán / Sơ Đồ Tuần Tự
![mermaid-ai-diagram-2025-03-06-044056](https://github.com/user-attachments/assets/b24af279-b82a-471d-b852-a65aaf45640d)
## 5. Class Diagram
![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459178521-a3b08b22-479c-4857-8d36-81dabb2b586a.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T024834Z&X-Amz-Expires=300&X-Amz-Signature=69822bc30c7b05c126f2a27efb081e8b37fc3648ab08675eeeda99ef97b53603&X-Amz-SignedHeaders=host)

## 6. Các chức năng chính của dự án
1. Trang đăng ký
   ![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459181850-9fb82e20-ca98-4fac-be16-40bb17863cb3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T024858Z&X-Amz-Expires=300&X-Amz-Signature=6d63e66b020411709baa325f6a821a377f29e6fa06add8cbb80d7b199e7b3731&X-Amz-SignedHeaders=host)
2. Trang đăng nhập
   ![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459182541-9f9e7c9c-9ede-431c-a88c-9d3bab71cce6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T024914Z&X-Amz-Expires=300&X-Amz-Signature=24058e04e954fe2c93cc0cf27d2ffbaed963bf45adb68f09ae1df2791418de2f&X-Amz-SignedHeaders=host)
3. Trang chủ
   ![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459182731-7a0de2c5-cc7f-464c-a42e-58e2f88a7817.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T024935Z&X-Amz-Expires=300&X-Amz-Signature=dc143b7b8cc14c93e816df4e07cc23e6ca41f06da3578e4097860d6f5048be77&X-Amz-SignedHeaders=host)
4. Trang quản lý sản phẩm
   ![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459183035-ac3a417e-dd08-4816-9c63-be53cdfb24a5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T024956Z&X-Amz-Expires=300&X-Amz-Signature=2b1c9af004623cd3768549307eaea6733222242d6a67f8d260fb113b7e40d948&X-Amz-SignedHeaders=host)
5. Trang tạo sản phẩm
   ![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459183404-377681fd-6577-4473-999d-d5f4d83d0e31.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T025011Z&X-Amz-Expires=300&X-Amz-Signature=562c8c2320764cc5b4fd06157efdab0b8c95daa4b59aceabe601022d2842230e&X-Amz-SignedHeaders=host)
6. Trang chỉnh sửa sản phẩm
![Image](https://github-production-user-asset-6210df.s3.amazonaws.com/213212927/459183555-b91f564e-319d-48df-9e25-ce31bffb10ac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250626%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250626T025024Z&X-Amz-Expires=300&X-Amz-Signature=f1a03536506bbb2767cfc72301d62c2629db88b8536462824623085f0bfa12e2&X-Amz-SignedHeaders=host)


## Code minh Hoạ 

## Link Repo 

https://github.com/VanHieu-dev/Laravel




