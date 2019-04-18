# payment-portal
<html>
	<head>
		<style>
			.a{
				margin: auto;
				height: 700px;
				width:  450px;
				background-color:#CBE36D;
				border-radius: 5px;
			}
			.x{
				margin: auto;
				height: 660px;
				width: 400px;
				background-color:#CBE36D;
			}
			.b{
				background-color: #D2E87B;
				margin: 4px;
				padding: 4px;
				border-radius: 2px;
			}
			.c{
				background-color: #7AE61C;
				height: 50px;
				width: 75px;
				margin-top: 4px;
			}
			.y{
				background-color: #D2E87B;
				height:60px;
				margin: 4px;
				padding: 4px;
				border-radius: 2px;
			}
		</style>
	</head>
	<body>
		
		<div class="a">
		<div class="x">
			<h2>Step1:Enter Your Details</h2>
			<div class="b">
					Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" placeholder="First and Last Name">
			</div>
			<div class="b">
					Email&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="Email "placeholder="eg. abc@xyz.com">
			</div>
			<div class="b">
					Phone no.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="Phone" placeholder="eg. 9801601216">
			</div>
			<h2>Step2:Delivery Address</h2>
			<div class="b">
					Address&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<textarea>      

										</textarea>
			</div>
			<div class="b">
					Postcode&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="postcode">
			</div>
			<div class="b">
					Country&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="country">
			</div>
			<h2>Step3:Card Details</h2>
			<div class="y">
				Card type<br><br>
				<input type="radio" name="s1" value="visa">VISA
				<input type="radio" name="s2" value="Amex">AMEX
				<input type="radio" name="s3" value="Master Card">Master Card
			</div>
			<div class="b">
					Card Number&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="card">
			</div>
			<div class="b">
					Seccurity Code&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="security">
			</div>
			<div class="b">
					Name on Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="s2" placeholder="Exact Name on the card">
			</div>
			<center><input type="submit" value="Pay" class="c"></center>
		</div>
		</div>
		
	</body>
</html>
