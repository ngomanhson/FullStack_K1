# Sử dụng GIT cơ bản

-   Tạo tài khoản github.com
-   Cài đặt Git scm: https://git-scm.com/
-   Kiểm tra:

*   Mở terminal
*   Gõ: git -v

Các bước đẩy code lên git

Gõ lần các câu lệnh sau

git add .
git commit -m 'noi dung'
git push

Các bước lấy code từ repository về máy

Nếu lần đầu: git clone link_repo

# Ngôn ngữ HTML

## Viết comment

## Các thuộc tính định dạng văn bản

-   Màu sắc: tên màu tiếng anh, mã màu hexa, rgb(), hsl()
-   Các giá trị kế thừa trong CSS (Áp dụng với tất cả thuộc tính)

*   initial
*   inherit
*   unset

## Thuộc tính background

-   background-color
-   background-image
-   background-position
-   background-repeat
-   background-attachment
-   background-size

=> background: tổng hợp các thuộc tính trên

## Flex

## Flex Container

-   display : flex | inline-flex => Kích hoạt flex

-   flex-direction : Chọn hướng của flex

*   row : Nằm ngang (Mặc định)
*   row-reverse : Nằm ngang đảo ngược
*   column : Cột
*   column-reverse : Cột đảo ngược

-   flex-wrap :

*   nowrap
*   wrap
*   wrap-reverse

-   justify-content : Căn chỉnh item theo hướng song song với trục chính

*   flex-start
*   flex-end
*   center
*   space-around
*   space-between
*   space-evenly

-   align-items: Căn chỉnh item theo hướng vuông góc với trục chính

*   stretch
*   flex-start
*   flex-end
*   center
*   baseline

-   align-content

-   gap

## Flex Item

-   flex-grow

-   flew-shrink

-   flex-basis

*   Bị chặn bởi min-width và max-width nếu flex-direction = row
*   Bị chặn bởi min-height và max-height nếu flex-direction = column
