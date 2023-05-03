<template>
	<footer class="footer">
	  <div class="footer-content">
		<div class="footer-left">
			<a href="/" class="navbar-brand w-202">
				<img src="../assets/img/logo9pw.png" class="img-logo-text" alt="">
			</a>
			<a href="/" class="navbar-brand">
			</a>
		  <div class="footer-address">
			<a href="https://www.google.com/maps/@21.0506866,105.8047464,19z?hl=vi"><i class="fa fa-map" aria-hidden="true"></i>  123 Đường 14, Ninh KIều, Cần Thơ</a><br>
			<a href="tel: 0939235461"><i class="fa fa-mobile" aria-hidden="true"></i>  Phone:0939235461</a><br>
			<a href="mailto:huyb2012210@student.ctu.edu.vn"><i class="fa fa-envelope" aria-hidden="true"></i>  Email: huyb2012210@student.ctu.edu.vn</a>
		  </div>
		</div>
		<ul class="description">
          <li>Chào mừng bạn đến với 9pw Library, 9pw Library là một nền tảng nội dung số trên internet, nơi thành viên có thể tự do xuất bản những nội dung tiếng Việt như: Tiểu thuyết, light novel, truyện ngắn hoặc thơ văn khác. Với những chức năng được cải tiến liên tục, 9pw Library sẽ mang lại cho Tác giả sáng tác truyện, Dịch giả đăng truyện và Người đọc truyện online những trải nghiệm tuyệt vời nhất. Đừng ngại đăng ký tài khoản tại 9pw Library, chỉ mất 30s và hoàn toàn miễn phí.</li>
        </ul>
	  </div>
	</footer>
  </template>
  <style>
  .footer {
  background-color: blue;
  padding: 40px 0;
  color: white;
}
.navbar {
		max-width: 1200px;
		margin: auto;
	}
	.navbar-expand {
		justify-content: space-between;
	}
	.pull-r {
		float: right;
		background-color: white;
	}
	.img-logo {
		width: 100px;
		filter: brightness(60%);
	}
	.img-logo-text {
		width: 100px;
	}
	.navbar-brand {
		font-size: 90px;
	}
	.w-202 {
		width: 202px;
	}
	a:hover {
		text-decoration: none;
		background-color: transparent;
		opacity: 0.8;
	}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}

.footer-left {
  display: flex;
  align-items: center;
}

.footer-logo {
  display: flex;
  align-items: center;
  width: 200%;
  color: white;
}

.footer-logo img {
  width: 100px;
  margin-right: 10px;
}

.footer-logo span {
  font-size: 24px;
  font-weight: bold;
  color: #f1f0f0;
}

.footer-address {
  margin-top: 10px;
}

.footer-right {
  display: flex;
  align-items: center;
}

.social-icons {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

.social-icons li {
  margin-right: 10px;
}


</style>
  