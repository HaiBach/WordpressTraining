# WORDPRESS CƠ BẢN

WordPress là một phần mềm nguồn mở (Open Source Software) được viết bằng ngôn ngữ lập trình website PHP và sử dụng hệ quản trị cơ sở dữ liệu MySQL.
WordPress được ra mắt lần đầu tiên vào năm 2003 bởi tác giả Matt Mullenweg và Mike Little.
Hiện nay WordPress được sở hữu và phát triển bởi công ty Automattic có trụ sở tại Hoa Kỳ.

WordPress là một mã nguồn mở bằng ngôn ngữ PHP để hỗ trợ tạo blog cá nhân, và nó được rất nhiều người sử dụng ủng hộ về tính dễ sử dụng, nhiều tính năng hữu ích. Qua thời gian, số lượng người sử dụng tăng lên, các cộng tác viên là những lập trình viên cũng tham gia đông đảo để phát triển mã nguồn WordPress có thêm những tính năng tuyệt vời. Và cho đến thời điểm hiện tại WordPress đã được xem như là một hệ quản trị nội dung (CMS – Content Management System) vượt trội để hỗ trợ người dùng tạo ra nhiều thể loại website khác nhau như blog, website tin tức/tạp chí, giới thiệu doanh nghiệp, bán hàng – thương mại điện tử, thậm chí với các loại website có độ phức tạp cao như đặt phòng khách sạn, thuê xe, đăng dự án bất động sản,…vâng…vâng…Hầu như mọi hình thức website với quy mô nhỏ và vừa đều có thể triển khai trên nền tảng WordPress.

Nhưng như thế không có nghĩa là WordPress chỉ thích hợp với các dự án nhỏ, mà hiện nay có tới khoảng 25% website trong danh sách 100 website lớn nhất thế giới sử dụng mã nguồn WordPress. Ví dụ như trang tạp chí TechCrunch, Mashable, CNN, BBC America, Variety, Sony Music, MTV News, Bata, Quartz..



## 1. VIẾT BÀI POST ĐẦU TIÊN

Truy cập vào menu Posts > Add New để viết bài viết mới. 

![Bài viết đầu tiên](/assets/img/wordpress_co_ban/post_new.png)

Các phần chính trong bài viết:
- Tiêu đề
- Nội dung bài viết
- Hình ảnh đại diện
- Categories vả tags

Hãy điền thông tin vào các mục cần thiết và click vào button **Preview** để xem trước nội dung.
Sau khi kiểm tra mọi thứ, click vào button **Publish** để xuất bản hiển thị bài viết trên trang web.

Đây là những thành phần cơ bản nhất của bài viết Post.
Trong thực tế cần phải cài đặt thêm các thành phần khác như SEO, các custom field... tuỳ theo từng dự án.



## 2. VIẾT PAGE ĐẦU TIÊN

Truy cập vào menu Pages > Add New để tạo trang mới trong Wordpress

Giống như bài viết Post, trong màn hình tạo trang mới cũng có các thành phần chính:
+ Tiêu đề
+ Nội dung trang
+ HÌnh ảnh đại diện
+ Thuộc tính trang

Hãy điền thông tin vào các mục cần thiết và click vào button **Preview** để xem trước nội dung.
Sau khi kiểm tra mọi thứ, click vào button **Publish** để xuất bản hiển thị trang mới trên web.

Đây là những thành phần cơ bản nhất của bài viết Page.
Trong thực tế cần phải cài đặt thêm các thành phần khác như SEO, các custom field... tuỳ theo từng dự án.



## 3. KHÁC NHAU GIỮA POST VÀ PAGE

❖ Trong Wordpress có 2 kiểu Post Type chính:
+ **Post** (Post Type: 'post')
+ **Page** (Post Type: 'page')

Ngoài ra còn có các kiểu Post Type chính khác:
+ **Attachment** (Post Type: 'attachment')
+ **Revision** (Post Type: 'revision')
+ **Navigation menu** (Post Type: 'nav_menu_item')
+ **Block templates** (Post Type: 'wp_template')
+ **Template parts** (Post Type: 'wp_template_part')


**✱ Post Type: Post**

Post sử dụng để viết các bài viết có nội dung blog, sự kiện, tin tức... được phân loại băfng category và tags.
Post thường được chú trọng bằng nội dung và SEO.
+ Được phân loại theo taxonomies - mặc định là categories và tags trong bài viết.
+ Hỗ trợ lưu time stamp, có nghĩa hỗ trợ hiển thị bài viết theo permalink date và time stamp.
+ Hiển thị ra template home (trang blog) theo thứ tự ngược theo thời gian, bài post mới nhất hiển thị ra trước.
+ Được sư dụng để tạo các feeds.


**✱ Post Type: Page**

Page được sử dụng để tạo các trang có nội dung cố định, có yếu tố chung chung, ít thay đổi.
Page được phân loại theo cấu trúc phân cấp cha/con (hierarchical structure) và thứ tự để sắp xếp vị trí của các trang.
+ Được phân loại theo cấu trúc phân cấp cha/con và thứ tự.
+ Không hỗ trợ tổ chức bằng taxonomies - cụ thể là categories hoặc tags. 
+ Không phụ thuộc vào time stamp.
+ Hỗ trợ áp dụng **Page Template**.



## 4. TAXONOMY - CATEGORY - TAG

❖ Trong Wordpress, taxonomy là cách thức để nhóm nội dung lại với nhau. Nó cho phép tạo một nhóm có cùng tính chất nào đó. Ví dụ: nhóm các bộ phim theo cùng một thể loại như tình cảm, hành động.

❖ Taxonomy mặc định có sẵn trong Wordpress là **Category** và **Tag**. Chúng đều thuộc một nhánh của Taxonomy.
Mặc định có 3 taxonomies thường hay sử dụng trong Wordpress: **Category**, **Tag** và **Post format**.


**✱ Category**

Taxonomy Category giúp nhóm các bài viết theo một thể loại nhất định.
Category là một hierarchical taxonomy - taxonomy có phân cấp.
Để quản lý các categories, trong khu vực Admin, vào menu: **Posts » Categories**.


**✱ Tag**

Tag tương tự như category, nhóm các bài viết lại với.
Tag không phải là hierarchical taxonomy - không phải là taxonomy phân cấp.
Một tag chỉ có một tham số duy nhất giúp nhóm các bài viết tương tự lại với, tập trung vào việc phân loại nội dung chi tiết.
Để quản lý các tags, trong khu vực Admin, vào menu: Posts » Tags


**✱ Post format**

Post format giúp phân loại nội dung dựa theo định dạng của nó.
Các định post format thường thấy trong panel bênh cạnh ở trình biên soạn nội dung bài viết:
+ Standard
+ Aside
+ Image
+ Video
+ Quote
+ Link
+ Gallery
+ Audio



## 5. UPLOAD HÌNH ẢNH VÀO THƯ VIỆN MEDIA

Để upload hình ảnh vào Wordpress, vào menu **Media > Add New**.
Lúc này sẽ xuất hình khu vực kéo thả, hãy kéo thả hình ảnh vào để upload hình ảnh vào thư viện Wordpress.
Hoặc có thể chọn file bằng button Select files để upload hình ảnh.

![Thư viện media](/assets/img/wordpress_co_ban/media_addnew.png)



## 6. THIẾT LẬP CHUNG

Để thiết lập phần logo, tagline, site icon... hãy vào menu **Appearance > Customize > Site Identify**
+ Logo
+ Site Title
+ Tagline
+ Site Icon (favicon)

![Thiết lập chung](/assets/img/wordpress_co_ban/customize.png)



## 7. SỬ DỤNG VÀ THIẾT LẬP MENU

Menu thường dùng để hiển thị các liên kết các trang trên web. Tuỳ theo trang web mà có cấu trúc và liên kết của menu khác nhau.
Thuật ngữ Menu trong Wordpress:

+ Menu: mỗi menu bao gồm các liên kết khác nhau. Trong WP, ta có thể tạo bao nhiêu menu cũng được.
+ Menu location: Vị trí chứa menu, mỗi menu location chỉ chứa 1 menu. Nhưng ta cũng có thể đặt nhiều menu location ở các vị trí khác nhau tuỳ ý trong theme. Menu location được thiết lập trong các file template của theme.

Để sử dụng và thiết lập menu, ta vào menu **Appearance > Menus**

![Thiết lập Menu](/assets/img/wordpress_co_ban/menus.png)

Menus trong Wordpress được thiết lập và tổ chức một cách trực quan và dễ dàng cho người sử dụng.



## 8. THIẾT LẬP VÀ SỬ DỤNG WIDGET

Widgets tập hợp nhiều chức năng. Mỗi widget là một chức năng nhỏ, thực hiện 1 nhiệm vụ nhất định trong trang.
Ví dụ như hiển thị các bài Posts xem nhiều nhất, hiển thị khu vực tìm kiếm, các tags thông dụng nhất...
Widgets trong phiên bản Wordpress mới giờ đây hỗ trợ thao tác như trình soạn thảo Gutenberg của Wordpress, nên thao tác thân thiện và dễ sử dụng.

+ Widget: thực hiện 1 chức năng nhất định trên trang site
+ Widget area: là nơi chứa các widget, được tạo mới và thiết lập vị trí trong theme.

Để thiết lập và quản lý các widgets, vào menu: **Appearance > Widgets**.
Trong các theme sẽ hỗ trợ chỉnh sửa widget trực quan hơn ở menu: **Appearance > Customize >Widgets**

![Sử dụng Widget](/assets/img/wordpress_co_ban/widgets.png)



## 9. THIẾT LẬP PERMALINK [※](#wordpress-cơ-bản)

Permalink trong Wordpress được định nghĩa là những đường dẫn có cấu trúc dễ nhớ, thân thiện với người sử dụng,
thay cho các đường dẫn không thân thiện bằng ID

Thiết lập permalink ở menu: **Settings > Permalinks**

Các thiết lập permalink:
+ **Plain**: thiết lập mặc định, sử dụng ID trong cấu trúc permalink.
+ **Day and name**: sử dụng cấu trúc theo ngày-tháng-năm và tên bài viết trong permalink.
+ **Month and name**: sử dụng cấu trúc theo tháng-năm và tên bài viết trong permalink.
+ **Numeric**: sử dụng cấu trúc hiển thị ID bài viết trên permalink.
+ **Post name**: sử dụng cấu trúc tên bài viết trong permalink.
+ **Custom structure**: tuỳ chỉnh cấu trúc permalink tuỳ ý.

![Permalink](/assets/img/wordpress_co_ban/permalink.png)

**Lưu ý:**
+ Thiết lập permalink ngay từ đầu dự án.
+ Tránh thay đổi permalink để tránh trường hợp 404 hoặc link không tồn tại.