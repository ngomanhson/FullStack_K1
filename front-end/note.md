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

-   align-self

*   Bị chặn bởi min-width và max-width nếu flex-direction = row
*   Bị chặn bởi min-height và max-height nếu flex-direction = column

## Variables

-   Biếm trong Css

*   Biến toàn cục: Sử dụng khắp mọi nơi (Tính từ chỗ khai báo)
*   Biến cục bộ: Chỉ sử dụng bên trong Selector đã khai báo (Áp dụng với tất cả selector con)

## Transition

-   transition-properties: all | tên thuộc tính (Mỗi thuộc tính cách nhau bởi dấu ,)

-   transition-duration: ms, s

-   transition-timing-function:

*   linear: tốc độ đều
*   ease
*   ease-in
*   ease-out
*   ease-in-out

-   transition-delay

## Transform

-   transform: giá trị

## Xoay

-   rotate(angle)
-   rotateX(angle)
-   rotateY(angle)
-   rotateZ(angle)

## Phóng to - Thu nhỏ

-   scale(x, y)
-   scaleX(x)
-   scaleY(y)

## Nghiêng

-   skew(x, y)
-   skewX(x)
-   skewY(y)

## Di chuyển

-   translate(x, y)
-   translateX(x)
-   translateY(y)

## Responsive

# Breakpoint

-   Điểm dừng mà tại đó giao diện sẽ thay đổi
-   Không có breakpoint cố định cho cách dự án
-   Không khai báo tất cả các breakpoint khi làm dự án (Tùy dự án)
-   Một số breakpoint phổ biến

*   576px
*   768px
*   992px
*   1200px
*   1400px

# Viewport

-   Khung nội dung người dùng thấy trên website
-   Để xây dựng website responsive => Cần có thẻ meta viewport
    => Cross Browser Testing

# Media Query

## Desktop First

    CSS giao diện 1400px trở lên

    @media screen and (max-width: 1200px) {
        Giao diện màn hình <= 1400px
    }

    @media screen and (max-width: 992px) {
        Giao diện màn hình <= 1200px
    }

    @media screen and (max-width: 768px) {
        Giao diện màn hình <= 992px
    }

    @media screen and (max-width: 768px) {
        Giao diện màn hình <= 768px
    }

    @media screen and (max-width: 576px) {
        Giao diện màn hình <= 576px
    }

## Mobile First

    @media screen and (min-width: 576px) {

    }

    @media screen and (min-width: 768px) {

    }

    @media screen and (min-width: 992px) {

    }

    @media screen and (min-width: 1200px) {

    }

    @media screen and (min-width: 1400px) {

    }

-   all => Tất cả giao diện web và giao diện trang in
-   screen => Chỉ hoạt động ở giao diện web
-   print => Chỉ hoạt động ở giao diện trang in

*   Lưu ý: Chỉ viết media query theo 1 chiều (max-width hoặc min-width)

-   max-width => Desktop First
-   min-width => Mobile First
