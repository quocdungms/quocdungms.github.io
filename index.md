﻿<!DOCTYPE html>
<html lang="vi">
<head>
  <title>Product Finder</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src="jquery/jquery.min.js"></script>
  <script src="js/bootstrap.min.js"></script>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>

  <nav class="navbar navbar-inverse navbar-fixed-top">
    <div class="container">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>                        
        </button>
        <a class="navbar-brand" style="font-size: 2em" href="index.html">Product Finder</a>
      </div>

      <form class="navbar-form navbar-left">
        <div class="input-group">
          <input type="text" class="form-control" placeholder="Nhập tên sản phẩm...">
          <div class="input-group-btn">
            <button class="btn btn-default" type="submit">
              <i class="glyphicon glyphicon-search"></i>
            </button>
          </div>
        </div>
      </form>
      
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="index.html">Home</a></li>
          <li class="dropdown">
			<a class="dropdown-toggle" data-toggle="dropdown" href="#">Top Products</a>
			<ul class="dropdown-menu">
				<li>
					<a style="color:#000" href="mp.html">
						<span><i style="font-size:20px" class="fa">&#xf21e;</i></span>
						<span> Mỹ phẩm</span>
					</a>
				</li>
				<li>
					<a style="color:#000" href="#">
						<span><i style="font-size:20px" class="fa">&#xf072;</i></span>
						<span> Giải trí</span>
					</a>
				</li>
				<li>
					<a style="color:#000" href="#">
						<span><i style="font-size:20px" class="fa">&#xf25b;</i></span>
						<span> Hàng gia dụng</span>
					</a>
				</li>  
				<li>
					<a style="color:#000" href="#">
						<span><i style="font-size:20px" class="fa">&#xf021;</i></span>
						<span> Du lịch</span>
					</a>
				</li>  					
			</ul>
		  </li>
          <li><a href="aboutUs.html">About us</a></li>
		  <li><a href="signIn.html">Sign In | Sign Up</a></li>
        </ul>  
      </div>
    </div>
  </nav>
  
  <div class="container" style="margin-top:50px;width:100%;padding:0px">
  <div id="myCarousel" class="carousel slide" data-ride="carousel">

		<ol class="carousel-indicators">
			<li data-target="#myCarousel" data-slide-to="0" class="active"></li>
			<li data-target="#myCarousel" data-slide-to="1"></li>
			<li data-target="#myCarousel" data-slide-to="2"></li>
			<li data-target="#myCarousel" data-slide-to="3"></li>
		</ol>


		<div class="carousel-inner">
			<div class="item active">
				<img src="images/landmark.jpg" alt="Los Angeles" style="width:100%;height:400px">
			</div>

			<div class="item">
					<img src="images/8.jpg" alt="Chicago" style="width:100%;height:400px">
			</div>
    
			<div class="item">
				<img src="images/9.jpg" alt="New york" style="width:100%;height:400px">
			</div>
			<div class="item">
				<img src="images/10.jpg" alt="New york" style="width:100%;height:400px">
			</div>
		</div>

 
		<a class="left carousel-control" href="#myCarousel" data-slide="prev">
			<span class="glyphicon glyphicon-chevron-left"></span>
			<span class="sr-only">Previous</span>
		</a>
		<a class="right carousel-control" href="#myCarousel" data-slide="next">
			<span class="glyphicon glyphicon-chevron-right"></span>
			<span class="sr-only">Next</span>
		</a>
	</div>
	</div>
	<div class="container">
      <div class="col-sm-12">
        <h3>GỢI Ý</h3>
		<div class="row">
        <div class="col-sm-4">
			<div class="thumbnail pd-box">
				<a href="redirect.html">
					<img src="images/aonu.jpg" class="imgf" alt="ao-nu" title="Áo thun nữ">
				</a>
				<a class="pd-name" href="redirect.html">Áo thun nữ</a>
				<p class="describe">Giá sốc 150k 
					<span class="price">250k</span>
					<span class="saleoff"> -40%</span>
				</p>
				<p>
					<img src="images/tiki.png" class="source" alt="tiki">
					<a href="https://tiki.vn">Tiki.vn</a>
				</p>
				<div style="text-align:center">
					<p class="btn btn-info" data-toggle="collapse" data-target="#demo1">Xem thêm...</p>
				</div>
				<div id="demo1" class="collapse">
					<ul>
						<li>Chất liệu vải thun mềm và thoáng mát.</li>
						<li>Đường may tinh tế, tỉ mỉ.
						<li>Thích hợp đi làm, đi chơi, dạo phố, du lịch.</li>
						<li>Kết hợp cùng quần jeans dài, quần âu,...</li>
					</ul>
				</div>
			</div>
        </div>
        <div class="col-sm-4">
        	<div class="thumbnail pd-box">
				<a href="https://tiki.vn/">
					<img src="images/usbnamecard.jpg" class="imgf" alt="usb-namecard" title="USB Namecard 2GB">
				</a>
        		<a class="pd-name" href="https://tiki.vn">USB Namecard 2GB</a>
        		<p class="describe">Giá sốc 100k
					<span class="price">150k</span>
					<span class="saleoff"> -33%</span>
				</p>
				<p>
					<img src="images/tiki.png" class="source" alt="tiki">
					<a href="https://tiki.vn" >Tiki.vn</a>
				</p>
				<div style="text-align:center">
					<p class="btn btn-info" data-toggle="collapse" data-target="#demo2">Xem thêm...</p>
				</div>
				<div id="demo2" class="collapse">
					<ul>
						<li>Dung lượng: 2GB</li>
						<li>Giao tiếp: USB 2.0, 3.0</li>
						<li>Tốc độ đọc lớn nhất: 40Mb/s</li>
						<li>Tốc độ ghi lớn nhất: 10Mb/s</li>
					</ul>
				</div>
        	</div>
        </div>
        <div class="col-sm-4">
        	<div class="thumbnail pd-box">
				<a href="https://shopdongho.com">
					<img src="images/donghonam.jpeg" class="imgf" alt="dong-ho-nam" title="Đồng hồ nam Tissot">
				</a>
        		<a class="pd-name" href="https://shopdongho.com">Đồng hồ nam Tissot</a>
        		<p class="describe">Giá sốc 2000k
					<span class="price">3500k</span>
					<span class="saleoff"> -43%</span>
				</p>
				<p>
					<img src="images/logo-shopdongho.jpg" class="source" alt="shopdongho">
					<a href="https://shopdongho.com">Shopdongho.com</a>
				</p>
				<div style="text-align:center">
					<p class="btn btn-info" data-toggle="collapse" data-target="#demo3">Xem thêm...</p>
				</div>
				<div id="demo3" class="collapse">
					<ul>
						<li>Xuất xứ: Thụy Sĩ</li>
						<li>Kính: Sapphire(chống trầy)</li>
						<li>Chống nước: 5ATM</li>
						<li>Chức năng: Lịch ngày...</li>
					</ul>
				</div>
        	</div>
        </div>
		</div>
		<div class="row">
        <div class="col-sm-4">
        	<div class="thumbnail pd-box">
				<a href="https://shopee.com">
					<img src="images/giayvans.jpg" class="imgf" alt="giay-vans" title="Giày Vans chính hãng">
				</a>
        		<a class="pd-name" href="https://shopee.com">Giày Vans chính hãng</a>
        		<p class="describe">Giá sốc 1800k
					<span class="price">2500k</span>
					<span class="saleoff"> -28%</span>
				</p>
				<p>
					<img src="images/shopee.png" class="source" alt="shopee">
					<a href="https://shopee.com" >Shopee.com</a>
				</p>
				<div style="text-align:center">
					<p class="btn btn-info" data-toggle="collapse" data-target="#demo4">Xem thêm...</p>
				</div>
				<div id="demo4" class="collapse">
					<ul>
						<li>Thương hiệu: Vans</li>
						<li>Size: 42</li>
						<li>Đế cao su độ bám tốt cùng thiết kế tối ưu cho môn trượt ván, BMX và các môn thể thao mạo hiểm khác</li>
						
					</ul>
				</div>
        	</div>
        </div>
        <div class="col-sm-4">
        	<div class="thumbnail pd-box">
				<a href="https://lazada.vn">
					<img src="images/maysinhto.jpg" class="imgf" alt="may-sinh-to" title="Máy xay sinh tố">
				</a>
        		<a class="pd-name" href="https://lazada.vn">Máy xay sinh tố</a>
        		<p class="describe">Giá sốc 450k
					<span class="price">800k</span>
					<span class="saleoff"> -44%</span>
				</p>
				<p>
					<img src="images/lazada.png" class="source" alt="lazada">
					<a href="https://lazada.vn">Lazada.com</a>
				</p>
				<div style="text-align:center">
					<p class="btn btn-info" data-toggle="collapse" data-target="#demo5">Xem thêm...</p>
				</div>
				<div id="demo5" class="collapse">
					<ul>
						<li>Công suất: 300W</li>
						<li>Lưỡi dao: Inox</li>
						<li>Thiết bị chống quá tải nhiệt</li>
						<li>Hai tốc độ, có chức năng nhồi</li>
					</ul>
				</div>
        	</div>
        </div>
        <div class="col-sm-4">
        	<div class="thumbnail pd-box">
				<a href="https://tiki.vn">
					<img src="images/spa.jpg" class="imgf" alt="spa" title="Voucher spa tại TPHCM">
				</a>
        		<a class="pd-name" href="https://tiki.vn">Voucher spa tại TPHCM</a>
        		<p class="describe">Giá sốc 250k
					<span class="price">400k</span>
					<span class="saleoff"> -38%</span>
				</p>
				<p>
					<img src="images/tiki.png" class="source" alt="tiki">
					<a href="https://tiki.vn" >Tiki.vn</a>
				</p>
				<div style="text-align:center">
					<p class="btn btn-info" data-toggle="collapse" data-target="#demo6">Xem thêm...</p>
				</div>
				<div id="demo6" class="collapse">
					<ul>
						<li>Thanh Thanh Spa sở hữu không gian tươi mới, sang trọng mang đến cho bạn cảm giác thư thái nhất khi đến đây</li>
						<li>Dịch vụ đa dạng, đáp ứng được mọi nhu cầu của bạn, bao gồm: Xông hơi, chăm sóc da mặt, massage, điều trị mụn,
						tắm dưỡng da toàn thân, waxing…</li>
						<li> Spa có hệ thống phòng ốc hiện đại, sử dụng sản phẩm chăm sóc sắc đẹp có thương hiệu, tốt cho sức khỏe</li>
						<li>Công nghệ kĩ thuật tiên tiến, hiện đại, cập nhật thường xuyên</li>
					</ul>
				</div>
        	</div>
        </div>
		</div>
	</div>
	<div style="text-align:right;margin-right:15px;">
		<ul class="pagination">
			<li><a href="index.html">1</a></li>
			<li><a href="#">2</a></li>
			<li><a href="#">3</a></li>
			<li><a href="#">4</a></li>
			<li><a href="#">5</a></li>
		</ul>
	</div>
	</div>
  </div>
  
  <div class="container-fluid">
    <div class="row">
     <div class="col-sm-12 footer">
		<div class="ft">
			<div style="float:left;margin-top:10px;">
				<a style="color:#d30f30" href="aboutUs.html">Về Product Finder</a><br>
				<div>
					<i style="font-size:15px;color:#d30f30;float:left" class="fa">&#xf2a0;</i>
					<p style="margin-left:5px;color:#d30c30;font-weight:bold;font-size:16px;float:left">LIÊN HỆ<p>
				</div>
				<div style="clear:both"></div>
				<div>
					<ul>
						<li>Mr Dũng: 18271827812</li>
						<li>Mr Cường: 12989128982</li>
						<li>Mr Huy: 10920192909</li>
					</ul>
					<p>Địa chỉ: 605H6, ĐHBK, TP.HCM<p>
				</div>
			</div>
			<div class="b">
				<i style="font-size:15px;color:#d30f30;float:left" class="fa">&#xf14c;</i>
				<p style="margin-left:5px;color:#d30c30;font-weight:bold;font-size:16px;float:left">LIÊN KẾT<p>
				<i style="font-size:24px;color:#4267b2" class="fa">&#xf082;</i><a style="color:#58595b;text-decoration:none" href="https://facebook.com">  Facebook</a><br>
				<i style="font-size:24px;color:#1da1f2" class="fa">&#xf081;</i><a style="color:#58595b;text-decoration:none" href="https://twitter.com">  Twitter</a><br>
				<i style="font-size:24px;color:#cd486b" class="fa">&#xf16d;</i><a style="color:#58595b;text-decoration:none" href="https://instagram.com">  Instagram</a>	
			</div>
			<div class="a">
				<h3>Product Finder</h3>
			</div>
		</div>
     </div>
	</div>
 </div>
</body>
</html>
