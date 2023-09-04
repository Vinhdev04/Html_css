                                 Chương 1 : HTML CƠ BẢN

BÀI 1 : THIẾT LẬP VSCODE

+ Extension cần dùng :
- VSCode
- auto Rename tag            ==>> giúp sửa đồng thời
- prettier                   ==>> giúp format code khi lưu
- html snippets              ==>> hỗ trợ các thẻ html
- live serve                 ==>> lưu lại sau khi code không ccanf reload
- matterial icon theme       ==>> hiển thị file, folder với các icon
- highlight matching tag     ==>> giúp nhận biết các cặp tag đang được chọn
- bracket pair colorizer     ==>> các ngoặc
- html to scc autocompletion ==>> gợi ý code
- scss intellisense          ==>> code Sass
- htmltagwap                 ==> ráp các tag lại

Bài 2 : CẤU TRÚC CƠ BẢN CỦA 1 FILE HTML

+ Tạo nhanh : SHIFT + !

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    .............. NỘI DUNG CODE................
</body>
</html>

- <!DOCTYPE html> ==>> kiểu văn bản html
- <html lang="en"> ==>> thuộc tính "lang" ,kiểu english
- <head> ==>> thẻ head
- <meta charset="UTF-8"> ==>> định dạng ngôn ngữ
- <meta name="viewport" content="width=device-width, initial-scale=1.0"> ==>> hiển thị responsive
- <title>Document</title> ==>> hiển thị trên trang web
- <body>.. <body>  ==>> nội dung
- </html> ==>> thẻ đóng lại chương trình

Bài 3 : Các thẻ HTML CẦN  BIẾT P1

+  <h1></h1>
+  <h2></h2>
+  <h3></h3>
+  <h4></h4>
+  <h5></h5>
+  <h6></h6>
==>> thẻ tiêu đề 
==>> thẻ <h1> lớn nhất
==>> chỉ sử dụng được duy nhất 1 thẻ <h1>

+ <div></div>
+ <section></section>
==>> đặt một  ,chia 1 khối khối dữ liệu lớn
==>> bên trong thẻ div có thể có thẻ div

+  <img src="link" alt="image">
==>> gán link dẫn tới ảnh 
==>> src = source : đường dẫn
==>> đường dẫn đúng -> hiện hình ảnh

+ <a href="link" target="_blank" rel="noopener noreferrer">link</a>
==>>dùng để them link liên kết 
==>> href = attributes : thuộc tính
==>> rel="noopener noreferrer" làm tăng tính bảo mật
==>> target_blank mở liên kết sang táp mới

+   <ol>
        <li>1</li>
        <li>2</li>
    </ol>
==>> thẻ danh sách
==>> ordered list :có thứ tự
==>> dùng làm mục lục

+    <ul>
        <li>1</li>
        <li>2</li>
    </ul>
==>> thẻ danh sách
==>> unordered list không cần thứ tự
==>> dùng làm Menu

+  <p>
 văn bản
   <p>
==>> dùng để note văn bản

Bài 3 : Các thẻ HTML CẦN  BIẾT P2

+  <header>  </header> ==>> thẻ hiện thị ở phía trên
+  <footer> </footer>  ==>> thẻ hiển thị phía dưới
+   <aside> </aside>   ==>> thẻ hiện thị bên trái ,phải
+   <nav>   </nav>     ==>> dùng làm Menu
+   <main>  </main>    ==>> chính giữa cảu web
+   <article> </article> ==>> tượng trưng cho bài viết
+   <iframe src="" frameborder="0"></iframe>...link nhúng ==>>đưa link nhúng vào trang web
+    <strong> hi</strong>  ==>> thẻ in đậm
+    <em> hi</em>          ==>> thẻ in nghiêng
+    <b> hi</b>            ==>> in đậm
+    <i> hi</i>            ==>> in nghiêng
https://htmlreference.io/  ==>> TRANG WEB GIÚP TÌM HIỂU VÀ PHÂN BIỆT CÁC LOẠI THẺ : INLINE, BLOCK,....