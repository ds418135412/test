<template>
	<div class="main">
		<div class="foote_1">
			<img src="../assets/1.gif" />
		</div>
		<div class="set_1">
			<span>中国大陆</span>
		</div>
		<div class="set_2">
			<span>其他地区</span>
		</div>
		<div class="qc"></div>
		<div class="set_3">
			<span>---手机号码登入---</span>
		</div>
		<from >
	<!--	<input class="hed_1"  v-model="password " placeholder=
		"请输入手机号(中国大陆 )"  />
		<img class="hed_2" src="../assets/2.gif" />-->
		<div class="hed">
			<div class="hed_1">
				<img src="../assets/2.gif" />
				<input class="hed_2" v-model="passname"  
				placeholder="请输入手机号(中国大陆)"/>
			</div>
		</div>
		</from>
		<from>
			<div class="hed_3">
				<img src="../assets/3.gif" />
				<div class="hed_4">
					<input class="hed_5" v-model="password" 
						placeholder="请输入验证码获取验证码"/>
				</div>
			</div>
		</from>
		<div class="ds">
			<span>登入</span>
		</div>
	</div>
</template>

<script>
</script>
<style>
	
	.foote_1>img{
		width: 100%;
	}
	.set_1>span{
		float: left;we,                                                                                                                                                                                                                                                                                                                                              
		color: "#a3a3a3";
		font-size: 40px;
		margin-top: 15px;
		margin-left: 15px;
		
	}
		.set_2>span{
		float: right;
		color: gray;
		font-size: 40px;
	    margin-top: 15px;
	    margin-right: 15px;
	}
	.qc{
		clear: both;
	}
	.set_3>span{
		float: left;
		color:gray;
		font-size: 40px;
		margin-top: 40px;
		margin-left: 200px;
	}
	/*.hed_1{
	  float: left;
	  height: 59px;
	  width: 550px;
	  border:solid  1px white;
	  border-bottom:1px solid black ;
	 font-size: 40px;
	  margin-top: 70px;
	  margin-left: 130px;
	 }
     .hed_2{
     	float: left;
     	margin-left: -610px;
     	margin-top: 60px;
     }*/
    .hed_1>img{
    	float: left;
    	margin-left: -437px;
    	margin-top: 130px;
    	border-bottom: solid 1px black;
    }
    .hed_2{
    	float:left;
    	 height: 59px;
    	 font-size: 40px;
    	 border:solid 1px white ;
    	 border-bottom:solid 1px black ;
    	 margin-top: 35px;
    }
    .hed_3>img{
    	float: left;
    	border-bottom:solid 1px black;
    	margin-left: -539px;
    	margin-top: 160px;
    }
    .hed_5{
    	float: left;
    	height: 59px;
    	font-size: 40px;
    	border:solid 1px white;
    	border-bottom: solid 1px black;
    	margin-top: 62px;
    	margin-left: -5px;
    }
    .ds{
    	float: left;
    	border: solid 1px white;
    	border-radius:45px ;
    	margin-top: 200px;
    	margin-left: -520px;
    	background-color:#bebebe;
    	height: 65px;
    	width: 507px;
    }
    .ds>span{
    	float: left;
    	color: white;
    	font-size: 20px;
    	margin-left: 220px;
    	margin-top:16px;
    	font-size: 28px;
    	font-weight: bold;
    	/*cursor:pointer */
    }
</style>