# Bài 1: Khởi tạo Workflow chạy Unit Test tự động cho Java Spring Boot với Gradle

## Giới thiệu
Bài tập này yêu cầu cấu hình GitHub Actions Workflow tự động chạy Unit Test cho dự án Java Spring Boot sử dụng Gradle mỗi khi có sự kiện push lên nhánh `main`.

## Cấu hình
- Sử dụng môi trường `ubuntu-latest`.
- Cài đặt Java JDK 17 với phân phối Temurin.
- Sử dụng Gradle Wrapper để thực thi câu lệnh test (`./gradlew test`).

## Hướng dẫn
1. Đặt tệp kịch bản tại đường dẫn: `homework/session_11/ex1/.github/workflows/ci.yml` trong repository của bạn.
2. Đẩy mã nguồn lên nhánh `main` trên GitHub.
3. Truy cập tab **Actions** trên GitHub Repository để kiểm tra kết quả chạy Unit Test.

## Ảnh chụp màn hình kết quả thực nghiệm
![Kết quả thực nghiệm](git_verification_result.png)
