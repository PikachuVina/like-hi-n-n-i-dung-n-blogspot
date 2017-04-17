Đầu tiên thì hãy chèn đoạn code sau lên trên thẻ </head>

<script src='https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js' type='text/javascript'></script>
<link href='https://cdn.rawgit.com/tuan2308/social/master/css.css' rel='stylesheet'/>
<script src='https://cdn.rawgit.com/tuan2308/social/master/script.js' type='text/javascript'/>
<script type='text/javascript'>
//<![CDATA[
jQuery(document).ready(function ($) {
$('#default-usage .to-lock').sociallocker({
buttons: {order:["facebook-like","twitter-tweet","google-plus"]},
twitter: {url:"http://twitter.com/bmn2312"},
facebook: {url:"https://www.facebook.com/ConfigCSVN.BlogSpot.c0m"},
google: {url:"http://www.configcsvn.blogspot.com"},
text: {
header: "Nội Dung Đã Được Khóa",
message: "Hãy like - theo dõi - +1 để xem nội dung khóa."
},
locker: {close: false, timer: 0,},
theme: "secrets"
});
});
//]]>
</script>

Bây giờ sau khi chèn xong thì khi đăng bài viết mới, bạn chuyển sang soạn thảo bằng HTML và dán đoạn mã sau vào vị trí của nội dung bạn muốn ẩn để bắt người dùng Like, +1, Tweet.
<article id="default-usage">
<div class="to-lock" style="display:none;">
- NỘI DUNG CẦN ẨN -
</div>
</article>

Tùy chỉnh

ĐỂ THAY ĐỔI VỊ TRÍ CÁC NÚT LIKE G+1,... ĐƠN GIẢN CÁC BẠN CHỈ CẦN THAY ĐỔI VỊ TRÍ SAU.
" facebook-like "
" facebook-share "
" google-plus "
" google-share "
" twitter-tweet "
" twitter-follow "
" linkedin-share "

Thay đổi thời gian tự động hiện nội dung
timer: 0 Bạn có thể thay 0 1Bằng thời gian bạn muốn nó tự động hiện nội dung. Đơn vị là giây.
VD: timer: 60

Bước tiếp theo là thay đổi các giao diện của Content Social Locker có sẵn.

theme: "dandyish"

Các bạn có thể thay dandyish thành các theme sau :
"flat"
"glass"
"starter"
"secrets"
