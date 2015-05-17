Cuốn sách này là những kiến thức cơ bản nhất trong HTML và css. Cuốn sách này gồm nhiều chương và được tôi chia làm **2** phần là ==***HTML***== và ==***CSS***== giúp các bạn dễ theo dõi hơn.

### ==Phần 1. HTML==
#### <ins>Chương 1. Cấu trúc một trang web</ins>
* HTML sử dụng các thẻ để mô tả cấu trúc của một trang web: 
  * Nội dung nằm trong một cặp thẻ mở và 1 thẻ đóng.
* Trang HTML là một văn bản text.
* HTML sử dụng các thẻ để mô tả thông tin của các văn bản text.
* Các thẻ được gọi là một elements.
* Các thẻ luôn được bắt đầu bằng một ký tự nhỏ hơn và kết thúc bằng một kí tự lớn hơn.
* Trong các thẻ mở có thể chứa một attributes.
* Attributes bắt buộc phải có một tên và một giá trị.
* Học HTML thì cần biết các thẻ, nó được dùng như thế nào và dùng ở đâu.

#### Chương 2. Văn bản hay còn gọi là TEXT
> 
Headings and paragraphs
Bold, italic, emphasis
Structural and semantic markup

* Headings bao gồm các thẻ từ h1 đến h6
* Paragraphs là thẻ `<p>` nội dung của từng đoạn văn bản.
* In đậm là thẻ `<b>`, in nghiên là thẻ `<i>`.
* Superscript & Subscript là chỉ số trên và chỉ số dưới.
* chỉ số trên thì sử dụng thẻ `<sup>`, chỉ số trên thì sử dụng thẻ `<sub>`.
* không khoảng trống.
*  Xuống dòng dùng `<br />`, gạch một dòng dùng `<hr />`.
* Thẻ `<strong>` = `<b>` và `<em>` = `<i>`.
* thẻ `<blockquote>` và thẻ `<q>` : <q> đây là thẻ  `<q>`.</q>
*  Thẻ `<abbr>`.
* Thẻ `<cite>` : <cite>the cite</cite> = `<i>`.
*  Thẻ `<dfn>` : <dfn> co gi dau ma </dfn> = `<i>`.
* Thẻ `<address>` : <address> Toi o thai binh , emai cua toi la: <a href="mailto:nguyenvannam0411@gmail.com">nguyenvannam0411@gmail.com</a> </address>
* Thay đổi nội dung: 
  * Thẻ `<del>` = <del>Đây là thẻ del</del>.
  * Thẻ `<ins>` = <ins> Đây là thẻ ins </ins>.
  * Thẻ `<s>` = <p> Mot ngay <del>nao</del> <s>do</s> toi se co viec.</p>
 
##### # Demo
![](/content/images/2015/05/demo-text.png)
#### Chương 3. Danh sách - LIST.
> 
Danh sách có thứ tự.
Danh sách không có thứ tự.
Danh sách tự định nghĩa.

`<ol>`: Đây là danh sách có thứ tự: 
<ol> 
<li>Thứ tự 1.</li> 
<li>Thứ tự 2.</li> 
<li>Thứ tự 3.</li> 
</ol>
`<ul>`: Đây là danh sách không có thứ tự: 
<ul> 
<li>Thứ tự 1.</li> 
<li>Thứ tự 2.</li> 
<li>Thứ tự 3.</li> 
</ul>
`<dl> > <dt> & <dd>`:
<dl> 
<dt> Day la dt </dt>
<dd> Nhieu dd </dd>
<dd> Nhieu dd </dd>
<dd> Nhieu dd </dd>
</dl>

* Danh sách nhiều cấp:
  * cấp 2
      * cấp 3
         * cấp ...

##### Demo
![](/content/images/2015/05/demo-list.png)
----
#### Chương 4. Địa chỉ liên kết - LINKS
> 
Tạo link ở trong trang. 
tạo link ngoài trang.
Tạo email link.

*  Link từ một website tới website khác.
![Link](/content/images/2015/05/link.png)
*  Link của các trang trong một website.
![](/content/images/2015/05/linktopage.png)
![](/content/images/2015/05/relative_link.png)
* Link của từng phần trong một trang web.
   * Link href="#selector" 
   * view div#selector 
* Link mở ra một cửa sổ trình duyệt mới.
   * target="_blank"
* Link tới email.
   * `<a href="mailto: your email"> Email </a>`
   * <a href="mailto: your email"> Email </a>

##### # Demo:
![](/content/images/2015/05/demo-link.png)
#### Chương 5. Hình ảnh - Images
* Thêm ảnh vào website quả thẻ `<img>` với các attributes:
    * src: đường dẫn đến hình ảnh.
    * alt: tên hình ảnh.
    * width & height: độ rộng và chiều cao cho hình ảnh.
* Chỉnh vị trí hình ảnh: text-align trong css.

###### # 3 quy tắc khi tạo một ảnh cho trang web:
*  Lưu ảnh dưới một định dạng có dung lượng tốt nhất để trang web load nhanh hơn.
* Lưu ảnh dưới một kích cỡ mà bạn đã thiết kế sẵn.
* Sử dụng 1 công cụ chỉnh sửa ảnh, chỉnh độ phân giải tốt nhất là 72 px/inch cho ảnh.

* Thẻ `<figure>` và `<figcaption>` trong html5
    * `<figure>`: chứa thẻ `<img>`.
    * `<figcaption>`: chú thích cho hình ảnh.

###### # Demo:
![image.html](/content/images/2015/05/demo-image.png)

#### Chương 6. Bảng - Table
> 
Làm sao để tạo ra một bảng.
Bảng để làm gì.
biểu diễn dữ liệu trên bảng.

* `<table>`: là bảng, `<tr>`: dòng, `<td>`: cột, `<th>`: ô.
    * `<th scope="col">`.
    * `<th scope = "row">`.
*  Gộp cột, gộp dòng:
   * `<td colspan = "3">` : gộp 3 cột.
   * `<td rowspan = "4">` : gộp 4 dòng.

*  Bảng dài:
   * `<thead>`: phần tên các cột của bảng.
   * `<tbody>`: phần nột dung của bảng.
   * `<tfoot>`: phần footer.
*  Độ rộng và khoảng cách giữa các giá trị trong bảng:
   * width = "200" : độ rộng của bảng là 200px;
   * cellpadding = '10' : khoảng cách lề phải của 1 ô trong bảng.
   * cellspacing = '5': khoảng cách lề trái của 1 ô trong bảng.
* `border` and `=background`
   * border = '3' : viền bao quanh có độ rộng = 3px.
   * bgcolor = '#333' : màu nền có giá trị là #333.

##### # Demo
![table](/content/images/2015/05/demo-table.png)

#### Chương 7. Forms
> 
làm thế nào để lấy thông tin từ người truy cập.
sự khác biệt của các điều khiển trong form.
các điều khiển mới trong html5.

*  Tại sao phải dùng form.
    * forms được sử dụng: khi người dùng muốn tìm kiếm, khi người dùng muốn đăng ký, đăng nhập, cập nhật sản phẩm, ... 
*  Một vài điều khiển trong forms:
   * Thêm văn bản:
     * Input text: chèn một văn bản đơn giản.
     * Input password: chèn một văn bản được ẩn bằng các ký tự.
     * textare: chèn đoạn văn nhiều dòng.
   * Chọn giá trị:
     * select: chọn một danh sách các giá trị thả xuống.
     * Radio button: chỉ được chọn 1 giá trị.
     * Checkboxs: có thể chọn hoặc bỏ chọn một hoặc nhiều giá trị.
   * Điều khiển submit forms.
     * Submit Button
     * image button
   * Upload tệp:
     * Input file: upload một tệp lên.
*  Cách mà forms làm việc:
![](/content/images/2015/05/form-work.png)
* Cấu trúc forms
   * Thẻ `<form>`
   * attributes action: xử lý thông tin gửi lên server.
   * method: post và get; mặc định là post.
   * Text Input & password input: 
     * type = "text" : input text.
     * type = "password" : input password.
     * size = 5
     * maxlength = '4' : dài nhất 4 ký tự.
     * name = "name input" : tên của input.
   * Textarea
     * cols = '10' : 10 cột.
     * rows = '5' : 5 dòng.
   * radio và checkbox button:
     * name = "name".
     * value = "gia tri hiện thị".
     * checked : mặc định là đã chọn.
   * Dropdown list box:
     * name
     * option value selected
     * mutiple = mutiple
   * file input
     * text = 'file'
   * summit button:
     * text = 'summit'
   * image button
     * text = 'image' src = 'path/url/image'
   * button và điều khiển hidden
     * button
     * text = 'hidden'
   * label
     * label: nhãn, for = 'name'
   * group form:
     * `<fieldset>`
     * `<legend>` : tên form
   * kiểm tra dữ liệu nhập vào trong form HTML5
     * required: không được để trống.
     * input type = 'date'
     * input type = 'email'
     * input type = 'url'
     * input type = 'search'
     * attributes placeholder.
##### # Demo

#### Chương 8.
> 
Sự khác biệt giữa các phiên bản HTML
id and class attributes.
Chú thích, thẻ meta và iframe.

*  Chú thích trong HTML
    * Được đặt trong kí tự `<!-- nội dung chú thích -->`
*  id atts: chỉ dùng cho 1 thẻ.
* class atts: có thể dùng lại cho nhiều thẻ.
* block element: hiện thị trên 1 dòng.
* inline element: hiện thị cùng 1 dòng.
* Thẻ `<iframe>`: chèn 1 trang web khác vào
* Thẻ meta ghi thông tin trang web, có tác dụng với seo
   * `<meta name='description' content='max 155 kí tự'>`
   * `<meta name='keywords' content='không được dài quá, là từ khóa chính của trang'>`
   * `<meta name='robots' content='nofollow hoặc follow'>`
   * `<meta http-equiz='author' content='tac gia,'>`
   * `<meta http-equiv="pragma" content="no-cache hay cache" />`
   * `<meta http-equiv="expires" content="Thoi gian, ngay thang nam..." />`

* escape character
![](/content/images/2015/05/escape.png)

##### Demo 
![](/content/images/2015/05/demo-8.png)

#### Chương 9. Flash, video & audio
> 
Chèn flash, video, audio vào trang web.
Tìm hiểu về thẻ `<video>` và `<audio>` trong HTML5.

##### Sự thay đổi giữa các nền tảng.
![](/content/images/2015/05/4.png)
![](/content/images/2015/05/timeline-flash.png)

* Sử dụng swfobject.js để chèn flash 
* sử dụng tag HTML5:
   * `<video>`
      * src="đường dẫn file video"
      * poster = "path\images" hiện thị hình ảnh khi video chưa play.
      * width & height: đô rộng và chiều cao của video tính theo giá trị pixcel.
      * controls: hiện thị các điều khiển trên video.
      * autoplay: tự động play khi mở trang.
      * loop: cho phép lặp lại.
      * preload: load lại video khi tải lại trang.
      * none: chưa tải video khi chưa nhấn play.
   * Multiple video với thẻ `<source>`:
      * type = 'video/mp4;codecs="avc1.42E01E, mp4a.40.2"'
      * src = "path\video".

*  Thêm audio vào trang web
   * cần 1 web host lưu trữ file audio:
     * SoundCloud.com hoặc MySpace.com.
   * Sử dụng flash hoặc HTML5 thẻ `<audio> `
   * 2 định dạng là .ogg và .mp3
      * MP3: Safari 5+, Chrome 6+, IE9
      * Ogg Vorbis: Firefox 3.6, Chome 6, Opera 1.5, IE9.

### ==Phần 2. CSS==
Trong phần này ta sẽ trả lời được cái câu hỏi sau:
> 
css là gì?
sử dụng css thế nào?
các quy tắc, thuộc tính, giá trị trong css ?.

#### Chương 1. Giới thiệu bé css - thành phần không thể thiếu trong trang web.
*  quy tắc css:
   * gồm có 2 phần: phần selector: phần mô tả;
![](/content/images/2015/05/selector.png)
   * phần mô tả gồm nhiều properties. mỗi thuộc tính có một value.
![](/content/images/2015/05/properties.png)

*  Khai báo sử dụng css
   * Ta sử dụng thẻ `<link href='đường dẫn file.css' type="text/css" ref="stylesheet">`
      * đặt thẻ link ở trong thẻ mở head và trước thẻ `</head>`.
      * Giúp web load nhanh hơn.

   * Sử dụng css trực tiếp:
      * khai báo css trong thẻ `<style type="text/css"></style>`.
      * hoặc có thể khai báo trực tiếp trên một thẻ `<p style="color: red;">haha</p>` sẽ cho kết quả: <p style="color: red;">haha</p>

*  Css selector:
![Css selector](/content/images/2015/05/css-selector.png)

* Sự khác nhau giữa các phiên bản css và trình duyệt.

*CSS 1 ra đời đi năm 1996, phiên bản CSS 2 ra đời sau đó 2 năm, css3 cũng bắt đầu từ đây. Hiện nay đã ra thêm css 4.*

#### Chương 2. Màu - color.

*  Có 3 kiểu màu hay dùng:
   * Kiểu RGB = red, green, blue
   * Kiểu HEX = #333.
   * Kiểu name = DarkCyan.
* Foreground Color
  * Sử dụng thuộc tính color
* Background Color
  * Sử dụng thuộc tính backgroud-color.
* Cơ bản về màu:
Mỗi một màu hiện thị trên màn hình máy tính là sự trộn của 3 màu chính: đỏ, xanh và xanh da trời.    
![](/content/images/2015/05/color-rea.png)

*  Thuộc tính opacity và RGBA
   * Giảm giá trị màu sắc bao nhiu %.

#### Chương 3. Text

* kiểu font
  * font serif
  * font sans-serif
  * font monospace
* font-face
* font-size
* font-weight
* font-style
* text-transform
* text-decoration
* line-height
* letter-spacing khoảng cách giữa các ký tự
* word-spacing khoảng cách giữa các từ
* text-align: 
  * left
  * right
  * center
  * Justify
* vertical-align
  * baseline
  * sub
  * super
  * top
  * text-top
  * middle
  * bottom
  * text-bottom
* Text-indent left or right
* text-shadow left, top, opacity, color
* :first-letter: Ký tự đầu tiên
* :first-line: dòng đầu tiên
* Styling link:
  * :link & :visited
  * :hover, :active,:focus.

###### seclector attributes
![](/content/images/2015/05/selector-atts.png)

#### Chương 4. Boxes
Trong chương này bạn sẽ học được
> 
Điều chỉnh kích cỡ của một khung làm việc
borders, margin and padding in boxs
Hiển thị và ẩn boxes

* Độ rộng và chiều cao của box:
  * width
  * height
*  Giới hạn độ rộng
  * min-width & max-width
* Cuộn nội dung
  * cho phép cuộn : overflow: scroll; 
  * không cuộn : hidden
* Borders, margin và padding
  * Borders: viền bao quanh.
  * margin: khoảng cách bên ngoài từ viền borders
  * padding: khoảng cách so với bên trong.
* Độ rộng của borders
  * Thuộc tính border-width: 
  * các giá trị mặc định:
     * thin
     * medium
     * thick
  * border-width: top, right, bottom, left px;
*  Định dạng borders
   * Thuộc tính: border-style
   * Giá trị: 
        * solid: nết liền.
        * dotted: nét chấm chấm
        * dashed: nét đứt
        * double: 2 nét liền
        * groove: appears to be carved into the page
        * ridge: appears to stick out from the page
        * inset appears embedded into the page
        * outset looks like it is coming out of the screen
        * hidden / none no border is shown.
   * Thuộc tính khác:
        * border-top-style
        * border-left-style
        * border-right-style
        * border-bottom-style
* Màu border
   * Thuộc tính: border-color
   * Giá trị: 
        * border-top-color
        * border-right-color
        * border-bottom-color
        * border-left-color
* border: border-width border-style border-color;
* Thuộc tính: display
   * inline: trên một dòng
   * inline-block: chỉ block 1 level dc chọn
   * none: ẩn box đó
   * block
*  Thuộc tính visibility:
   * hidden
   * visible
* Thuộc tính css3 Border-images
  * border-image: url("path/image") 11 11 11 11 border-style
  * border-style: 
        * stretch stretches the image
        * repeat repeats the image
        * round like repeat but if the tiles do not fit exactly, scales
* Thuộc tính box-shadow:
![](/content/images/2015/05/box-shadow.png)
* Border-radius: top right bottom left
* border-top-left-radius: width height;

#### Chương 5. Lists, table and forms
> 
Các kiểu dịnh dạng cho danh sách có thứ tự ol.
Định dạng tables.
>
Điều khiển forms.

* Thuộc tính list-style-type
  * none: ko định dạng.
  * disc: kí tự chấm đen.
  * circle: kí tự chấm trắng.
  * square: ô vuông đen.
  * decimal: 1 2 3
  * decimal-leading-zero: 01 02 03
  * lower-alpha: a b c
  * upper-alpha: A B C
  * lower-roman: i. ii. iii.
  * upper-roman: I II III
* Thuộc tính list-style-image
  * url('path/image')
* Thuộc tính list-style-position
  * inside: chỉ dòng đầu tiên cách lề trái
  * outside: tất cả cách lề trái
* Thuộc tính list-stype rút gọn
  * list-stype: position type;
* Thuộc tính table
  * width: độ rộng cho bảng.
  * padding: khoảng cách của ô bên trong bảng
  * text-transform: chuyển kiểu chữ cho tiêu đề bảng .
  * letter-spacing: khoảng cách giữa các ký tự.
  * font-size: cỡ văn bản
  * border-top, border-bottom: đường viền trên và dưới.
  * background: màu nề.
  * :hover: khi ng dùng đi chụt vào.
  * Border cho những ô không có giá trị:
      * Thuộc tính empty-cells:
      * show: cho phép hiện thị border của ô không có giá trị
      * hide: ẩn
      * inherit: tự động.
* Khoảng cách giữa từng ô
  * border-spacing: row px , col px;
  * border-collapse: collapse;
*  Định dạng form
   * style text input
   * style submit
   * style fieldset và legend.
   * Căn lề cho các điều khiển trong form.
* Định dạng con chuột
  * Thuộc tính cursor với các giá trị:
     * auto
     * crosshair
     * default
     * pointer
     * move
     * text
     * wait
     * help
     * url("cursor.gif");
* Một số công vụ phát riển web:
  * debug.
  * chorme, fifox, .. developer
  * webdevelop addon fifox, chorme

#### Chương 6. Layout
> 
Chỉnh vị trị hiển thị.
Tạo một màn hình hiển thị cho web
Thiết kế các kích cỡ màn hình khác nhau

* Thuộc tính position
  * relative: định vị trí tương đối. đi với top left bottom right. chỉ cho với vị tri hiện tại mà nó đang đứng
  * absolute: định vị trí tuyệt đối. so với body.
  * z-index: đè lên.
  * fixed.  fix cứng khi cuộn trag web.
  * static. Bình thường. mặc định là kiểu này
  * floaf: left, right
* css framework layour
  * 960.GS Grid
  * bootstrap
  * foun

#### Chương 7 Images
> 
Điều chỉnh kích cỡ
> 
Căn lề
>
Thay background

*  Có thể điều chỉnh kích cỡ, căn vị trí, thay đổi hình nền cho hình ảnh trong css

#### Chương 8. HTML 5 Layout
> 
Header, footer
> 
Nav
> 
aside
> 
article
> 
figure

 Hỗ trợ html5 trên những trình duyệt cũ
 [http://html5shiv.googlecode.com/svn/trunk/html5.js"](http://html5shiv.googlecode.com/svn/trunk/html.js")

#### Chương 9 Xử lý và thiết kế bộ cục trước
#### Chương 10 seo và Thực hành.
