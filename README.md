<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Karma">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Karma", sans-serif}
.w3-bar-block .w3-bar-item {padding:20px}
</style>
</head>
<body>

<!-- Sidebar (hidden by default) -->
<nav class="w3-sidebar w3-bar-block w3-card w3-top w3-xlarge w3-animate-left" style="display:none;z-index:2;width:40%;min-width:300px" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()"
  class="w3-bar-item w3-button">Close Menu</a>
  <a href="#event" onclick="w3_close()" class="w3-bar-item w3-button">Event</a>
  <a href="#food" onclick="w3_close()" class="w3-bar-item w3-button">Food</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">About</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">Contact</a>
</nav>

<!-- Top menu -->
<div class="w3-top">
  <div class="w3-white w3-xlarge" style="max-width:1200px;margin:auto">
    <div class="w3-button w3-padding-16 w3-left" onclick="w3_open()">☰</div>
    <div class="w3-right w3-padding-16">Mail</div>
    <div class="w3-center w3-padding-16">My Food</div>
  </div>
</div>
  
<!-- !PAGE CONTENT! -->
<div class="w3-main w3-content w3-padding" style="max-width:1200px;margin-top:100px">

 <!-- Event Section -->
 <div class="w3-row w3-padding-64" id="event">
  <div class="w3-col l6 w3-padding-large">
    <img src="image/ngott.jpg" class="w3-round w3-image w3-opacity-min" alt="ngọt" style="width:200%">
  </div>
  <div class="w3-col l6 w3-padding-large">
    <h1 class="w3-center">Sự kiện của cửa hàng</h1><br>
    <h4>Baked Cheesecake</h4>
    <p class="w3-text-grey">Giảm 50% khi mua tại cửa hàng ngày 12/12</p><br>

    <h4>Peach Panna Cotta</h4>
    <p class="w3-text-grey">Mua 2 bánh tặng 1 bánh áp dụng chỉ ngày 8/3</p><br>
  
    <h4>Passion Cheeses</h4>
    <p class="w3-text-grey">Khuyến mại đơn hàng từ 150k trở lên tặng 1 bánh Passion Cheeses áp dụng chỉ tháng 1/2024</p><br>
</div>
<hr>
  <!-- First Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center" id="food">
    <div class="w3-quarter">
      <img src="image/cam.jpg" alt="Sandwich" style="width:100%">
      <h3>Baked Cheesecake</h3>
      <p>Cảm nhận ngay sự mềm mịn, ngọt ngào của lớp kẹo dẻo, và sự thanh mát của trái cây</p>
    </div>
    <div class="w3-quarter">
      <img src="image/vietquatsua.jpg" alt="Steak" style="width:100%">
      <h3>Peach Panna Cotta</h3>
      <p>Mùi vị thơm béo của caramen quyện cùng lớp trái cây ngọt ngào</p>
    </div>
    <div class="w3-quarter">
      <img src="image/caramen.jpg" alt="Cherries" style="width:100%">
      <h3>Passion Cheeses</h3>
      <p>Bánh mềm mịn và thơm mùi trứng </p>
    </div>
    <div class="w3-quarter">
      <img src="image/caramenvietquat.jpg" alt="Pasta and Wine" style="width:100%">
      <h3>Mango Panna Cotta</h3>
      <p>Thanh mát cùng những trái việt quất và vị bơ thơm ngon</p>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center">
    <div class="w3-quarter">
      <img src="image/dau.jpg" alt="Popsicle" style="width:100%">
      <h3>Strawberry Panna Cotta</h3>
      <p>Khiến cho người ăn không bao giờ thấy ngán, một khi ăn đảm bảo sẽ nghiền</p>
    </div>
    <div class="w3-quarter">
      <img src="image/hongdau.jpg" alt="Salmon" style="width:100%">
      <h3>Mouse Dâu Yogurt</h3>
      <p>Ẩn chứa sự ngọt ngào, đậm đà và tinh tế</div>
    <div class="w3-quarter">
      <img src="image/matcha.jpg" alt="Sandwich" style="width:100%">
      <h3>Mouse Matcha</h3>
      <p>Kết hợp hài hòa hương vị trà và hương dâu béo ngậy</p>
    </div>
    <div class="w3-quarter">
      <img src="image/socola.jpg" alt="Croissant" style="width:100%">
      <h3>Tiramisu</h3>
      <p>Béo ngậy với nhiều lớp cốt bánh chocolate</p>
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>
  
  <hr id="about">

  <!-- About Section -->
  <div class="w3-container w3-padding-32 w3-center">  
    <h3>About Me, The Food Girl</h3><br>
    <img src="image/trang.jpg" alt="Me" class="w3-image" style="display:block;margin:auto" width="400" height="333">
    <div class="w3-padding-32">
      <h4><b>Trần Huyền Trang</b></h4>
      <h6><i>Hương vị ngọt ngào cuộc sống</i></h6>
      <p>Mỗi loại bánh ra đời đều có một câu chuyện cũng như đằng sau nó. Sẽ thật bất ngờ khi bạn biết được ý nghĩa của chiếc bánh ngọt ngào xinh xắn mà bạn mê mẩn </p>
    </div>
  </div>
  <hr>
  <!--  Contact Section -->
  <div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
    <h2 class="w3-wide w3-center">CONTACT</h2>
    <p class="w3-opacity w3-center"><i>Liên hệ với chúng tôi</i></p>
    <div class="w3-row w3-padding-32">
      <div class="w3-col m6 w3-large w3-margin-bottom">
        <i class="fa fa-map-marker" style="width:30px"></i>40P.Phùng Hưng, Hàng Bông, Hoàn Kiếm, Hà Nội<br>
        <i class="fa fa-phone" style="width:30px"></i> Phone: 0357169024<br>
        <i class="fa fa-envelope" style="width:30px"> </i> Email: huyentrangtran585@gmail.com<br>
      </div>
      <div class="w3-col m6">
        <form action="/action_page.php" target="_blank">
          <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
            </div>
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
            </div>
          </div>
          <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
          <button class="w3-button w3-black w3-section w3-right" type="submit">SEND</button>
        </form>
      </div>
    </div>
  </div>
  
  <!-- Footer -->
  <footer class="w3-row-padding w3-padding-32">
    <div class="w3-third">
      <h3>FOOTER</h3>
      <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
      <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
    </div>
  
    <div class="w3-third">
      <h3>BLOG POSTS</h3>
      <ul class="w3-ul w3-hoverable">
        <li class="w3-padding-16">
          <img src="image/thoitrangg.jpg" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">Thời Trang</span><br>
          <span>Phụ nữ là phải đẹp</span>
        </li>
        <li class="w3-padding-16">
          <img src="image/nhahanggg.jpg" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">Nhà Hàng</span><br>
          <span>Vị ngon trên từng bữa ăn</span>
        </li> 
      </ul>
    </div>

    <div class="w3-third w3-serif">
      <h3>POPULAR TAGS</h3>
      <p>
        <span class="w3-tag w3-black w3-margin-bottom">Travel</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">New York</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dinner</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Salmon</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">France</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Drinks</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ideas</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Flavors</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Cuisine</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Chicken</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dressing</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fried</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fish</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Duck</span>
      </p>
    </div>
  </footer>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>
