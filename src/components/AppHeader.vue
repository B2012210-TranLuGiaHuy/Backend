<template>
	<div class="nav-wrap bg-darkblue">
		<nav class="navbar navbar-expand navbar-dark ">
			<a href="/" class="navbar-brand w-202">
				<img src="../assets/img/logo9pw.png" class="img-logo-text" alt="">

				9pw Library
			</a>
			<a href="/" class="navbar-brand">
			</a>
			
				<div class=" navbar-nav">
	
				<li  @click="goToAddUser()" class="nav-item  w-202">
					<button  class="nav-link btn-add-user  pull-r">
						Thêm thành viên
						<img src="../assets/img/logo9pw.png" class="img-logo" alt="">
					</button>
				</li>
			</div>
		</nav>
	</div>
</template>
<script>
import UserService from "@/services/user.service";

export default {
	components: {
		UserService
	},
	methods: {
		goToAddUser() {
			this.$router.push({ name: "user.add" });
		},
	}
}
</script>
<style scoped>
.pull-r {
  background-color: blue;
  color: black;
  border-color: black;
  border: none;
  color: white;
  border-radius: 5px;
  padding: 10px 20px;
  cursor: pointer;
  font-weight: 600;
  transition: background-color 0.2s ease-in-out;
  float: right;
}

.pull-r:hover {
  background-color: black;
}

	.navbar {
		max-width: 1200px;
		margin: auto;
	}
	.navbar-expand {
		justify-content: space-between;
	}
	
	.img-logo {
		width: 40px;
		filter: brightness(60%);
	}
	.img-logo-text {
		width: 40px;
	}
	.navbar-brand {
		font-size: 32px;
	}
	.w-202 {
		width: 202px;
	}
	a:hover {
		text-decoration: none;
		background-color: transparent;
		opacity: 0.8;
	}
	.bg-darkblue {
		background-color: blue;
	}
	
	
</style>