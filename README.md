<!-- ABOUT STORE -->
<section class="store-about" id="about">
    <div class="container store-content">

        <div class="store-image">
            <img src="images/store.jpg"
                 alt="Không gian cửa hàng Model Kit Store">
        </div>

        <div class="store-text">

            <p class="subtitle">ABOUT OUR STORE</p>

            <h2>
                Không gian dành cho
                <span>người yêu mô hình</span>
            </h2>

            <p>
                Model Kit Store là cửa hàng dành cho
                những người yêu thích mô hình lắp ráp,
                Gundam, robot và các sản phẩm sưu tầm.
            </p>

            <p>
                Chúng tôi mong muốn mang đến một không gian
                trưng bày mô hình độc đáo, giúp khách hàng
                khám phá và lựa chọn những sản phẩm yêu thích.
            </p>

            <a href="#products" class="button">
                Khám phá sản phẩm
            </a>

        </div>

    </div>
</section>
/* STORE ABOUT */
.store-about {
    background-color: white;
    padding: 70px 0;
}

.store-content {
    display: flex;
    align-items: center;
    gap: 50px;
}

.store-image {
    flex: 1;
}

.store-image img {
    width: 100%;
    height: 400px;
    object-fit: cover;
    border-radius: 15px;
    box-shadow: 0 8px 25px #00000020;
}

.store-text {
    flex: 1;
}

.store-text h2 {
    font-size: 35px;
    line-height: 1.3;
    margin: 15px 0 20px;
}

.store-text h2 span {
    color: #f97316;
}

.store-text p {
    margin-bottom: 15px;
    color: #555;
}

/* STORE RESPONSIVE */
@media (max-width: 768px) {
    .store-content {
        flex-direction: column;
    }

    .store-image img {
        height: 280px;
    }

    .store-text h2 {
        font-size: 28px;
    }
}
.banner {
    background-image:
        linear-gradient(
            rgba(10, 15, 30, 0.35),
            rgba(10, 15, 30, 0.35)
        ),
        url("images/store.jpg");

    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
# XT Hobby store

## 1. Giới thiệu đề tài

XT Hobby store là website giới thiệu cửa hàng mô hình lắp ráp, tập trung
vào các sản phẩm Gundam, robot, model kit và đồ chơi sưu tầm.

Website được xây dựng nhằm giới thiệu cửa hàng, trưng bày sản phẩm, giới
thiệu không gian cửa hàng và cung cấp thông tin liên hệ cho khách hàng.

## 2. Mục tiêu của website

-   Xây dựng website giới thiệu cửa hàng XT Hobby store.
-   Thiết kế giao diện phù hợp với chủ đề mô hình lắp ráp.
-   Hiển thị hình ảnh và thông tin sản phẩm.
-   Giới thiệu không gian bên trong cửa hàng.
-   Cung cấp thông tin liên hệ.
-   Vận dụng kiến thức HTML5 và CSS3 đã học.

## 3. Công nghệ sử dụng

  Công nghệ / công cụ         Mục đích
  --------------------------- ------------------------------------------
  HTML5                       Xây dựng cấu trúc website
  CSS3                        Thiết kế giao diện, bố cục và responsive
  Visual Studio Code          Soạn thảo mã nguồn
  Google Chrome               Chạy và kiểm tra website
  Live Server (nếu sử dụng)   Xem website trong quá trình phát triển

Phiên bản hiện tại là website tĩnh, sử dụng HTML và CSS. Chưa triển khai
JavaScript, backend hoặc cơ sở dữ liệu.

## 4. Cấu trúc thư mục

``` text
web mô hình/
├── images/
│   ├── anh1.jpg
│   ├── anh2.jpg
│   ├── anh3.jpg
│   ├── anh4.jpg
│   └── anh5.jpg
├── AI_Log.md
├── index.html
├── README.md
└── style.css
```

## 5. Các thành phần của website

### Trang chủ

Giới thiệu XT Hobby store và chủ đề mô hình lắp ráp.

### Banner

Hiển thị hình ảnh cửa hàng và nội dung giới thiệu chính.

### Danh mục sản phẩm

Giới thiệu các nhóm sản phẩm như Gundam, robot và phụ kiện.

### Sản phẩm

Hiển thị hình ảnh, tên sản phẩm và giá tham khảo.

### Không gian cửa hàng

Giới thiệu hình ảnh mặt tiền và không gian bên trong XT Hobby store.

### Giới thiệu

Cung cấp thông tin về cửa hàng và định hướng hoạt động.

### Liên hệ

Hiển thị thông tin liên hệ của cửa hàng.

## 6. Hướng dẫn chạy website

1.  Mở thư mục project bằng Visual Studio Code.
2.  Kiểm tra file `index.html` và `style.css`.
3.  Kiểm tra các hình ảnh trong thư mục `images` có đúng tên và đường
    dẫn.
4.  Mở file `index.html` bằng Google Chrome.
5.  Có thể sử dụng Live Server để xem website trong quá trình chỉnh sửa.

## 7. Kiểm thử website

Sau khi hoàn thành website XT Hobby store, người thực hiện đã kiểm tra
các thành phần và giao diện trên trình duyệt.

Kết quả kiểm thử:
-   [x] Website mở được trên trình duyệt.
-   [x] Hình ảnh banner hiển thị đúng.
-   [x] Hình ảnh sản phẩm hiển thị đúng.
-   [x] Menu điều hướng hoạt động.
-   [x] Các liên kết đến danh mục hoạt động.
-   [x] Phần giới thiệu cửa hàng hiển thị đúng.
-   [x] Giao diện hiển thị trên máy tính.
-   [x] Giao diện hiển thị trên điện thoại.

Kết quả: Các nội dung kiểm thử trên đã được thực hiện và hoạt động đúng
theo yêu cầu của website.

## 8. Hạn chế của phiên bản hiện tại

Website hiện tại là website tĩnh, tập trung vào giới thiệu cửa hàng và
trưng bày sản phẩm.

Các chức năng chưa được triển khai:

-   Giỏ hàng tự động.
-   Tìm kiếm và lọc sản phẩm.
-   Đăng nhập và đăng ký tài khoản.
-   Thanh toán trực tuyến.
-   Quản lý sản phẩm bằng cơ sở dữ liệu.

## 9. Thông tin project

-   Tên đề tài: Website XT Hobby store
-   Người thực hiện: Tống Xuân Thành
-   Lớp: CNTT 20-02
-   Repository GitHub: \[https://github.com/Thanhtong-255/web-ban-mo-hinh.git\]
-   Website: \[https://thanhtong-255.github.io/web-ban-mo-hinh/\]

## 10. Kết luận

Thông qua đề tài XT Hobby store, người thực hiện đã vận dụng kiến thức
HTML5 và CSS3 để xây dựng website giới thiệu cửa hàng mô hình.

Quá trình thực hiện giúp củng cố kiến thức về cấu trúc HTML, thiết kế
giao diện CSS, bố trí hình ảnh, xây dựng liên kết điều hướng và kiểm tra
khả năng hiển thị trên các thiết bị.

Website là sản phẩm thực hành nhằm phát triển kỹ năng xây dựng giao diện
web cơ bản và làm nền tảng cho việc học các công nghệ web nâng cao trong
tương lai.
