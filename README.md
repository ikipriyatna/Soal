<html lang="in">
<head>
				<title>Judul halaman</title>
				<style>
								body{
				background-image:url(https://raw.githubusercontent.com/rifkipriyatna/SIMP/main/bintang.jpeg);
}



.awal{
				margin:auto;
				display:block;
				width:90%;
				margin-top:40%;
				displa:none;
}

.welcome{
				text-align:center;
				font-family:Cursive;
				color:white; font-size:15px;

				
}

.nama{
				margin:auto;
				display:block;
				border:none;
				text-decoration:none; width:50%;

				padding:10px;
				border-radius:3px;
				box-shadow: 0px 0px 9px grey; font-size:9px;
				
}

.mulai{
				margin:auto;
				display:block;
				border:none;
				text-decoration:none;
				width:30%;
				background-color:black;
				color:white;
				padding:5px;
				font-weight:bold;
				font-size:9px;
				box-shadow: 0px 0px 15px grey;
}

.nomor1{
				margin:auto;
				display:block;
				width:90%;
				margin-top:50%;
				border:none;
				text-decoration:none;
				bckground:grey;
				display:none;
				
}

.soal1{
			  text-align:center;
				font-family:Arial;
				color:white;
				padding:20px;
				
}

.pilihan1{
				margin-left:15%;		
						
}
.pilihan2{
				margin-left:10%;							
}

.pilihan3{
				margin-left:15%;							
}

.pilihan4{
				margin-left:12%;							
}


.pilihan5{
				margin-left:16%;							
}



.buttonA{
				border:none;
				text-decoration:none;
				width:80%;
				padding:5px;
				border-radius:4px;
				
				
}

.buttonB{
				border:none;
				text-decoration:none;
				width:80%;
				padding:5px;
				border-radius:4px;
				
}

.buttonC{
				border:none;
				text-decoration:none;
				width:80%;
				padding:5px;
				border-radius:4px;
		
}

.buttonD{
				border:none;
				text-decoration:none;
				width:80%;
				padding:5px;
				border-radius:4px;
				
}

.cinta{
				opacity:0;
				width:10%;
}

.selesai{
				background:black;
				color:white;
				font-weight:bold;
				font-size:9px;
				border:none;
				
}

.hasil{
				background:grey;
				
}

.aweh{
				background:grey;
				color:white;
}

.opacity{
				opacity:0;
				width:10px;
}

.cekhasil{
			
				margin-left:27%;
				display:non;
				border:none;
				text-decoration:none;
				width:30%;
				background-color:black;
				color:white;
				padding:10px;
				font-weight:bold;
				font-size:9px;
				box-shadow: 0px 0px 15px grey;
}

.akhir{
				
				margin:auto;
				display:block;
				font-family:Cursive;
				color:white;
				width:80%;
				display:none;
				margin-top:50%;
				text-align:center;
}

.dih{
			  margin-left:5%;
			 
				
				
				display:flex;
				
				
}

.wah{
			
				margin-left:5%;
				display:flex;
}

.em{
				width:80%;
				margin:auto;
				display:block;
				text-align:center;
}





				</style>
				<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
</head>
<body>
				
				<form name="form">
							<div id="awal" class="awal">
											<h3 class="welcome">Halo selamat datang di quiz PRYTNA CODE</h3>
						<input type="text" name="Nama" placeholder="Nama lengkap" class="nama" id="nama"><br>
						<button class="mulai" id="mulai">Mulai</button>
						<script>
										$(document).ready(function(){
  $("#mulai").click(function(){
    $("#awal").fadeOut(100);
    $("#nomor1").fadeIn(1000);
    
    
  });
});
						</script>
						</div>
						<div id="nomor1" class="nomor1">
<h3 class="soal1">Siapa ras terkuat di bumi	?																													</h3>
<div class="pilihan1">
<button type="button" onclick="a1()" id="satuA" class="buttonA">A. Wibu</button><br><br>
<button type="button" onclick="b1()" class="buttonB" id="satuB" >B. K-POP</button><br><br>
<button class="buttonC" type="button" onclick="c1()" id="satuC" >C. Ngabers </button><br><br>
<button class="buttonD" type="button" onclick="d1()" id="satuD" >D. Nak Tiktod</button><br>
<input class="opacity" type="text" name="No1" size="1">
</div>

<br>

<br>
<br>
<h3 id="tampil"></h3>
<script>
				var score = 0;
function a1(){
form.No1.value= "A";
score = score+ 25 ;
     document.getElementById("nilai").innerHTML=(score);
}
function b1(){
form.No1.value= "B";
}
function c1(){
form.No1.value= "C";
}
function d1(){
form.No1.value= "D";
}

$(document).ready(function(){
  $("#satuA").click(function(){
    $("#nomor1").fadeOut(100);
    $("#nomor2").fadeIn(1000);
    
    
  });
});

$(document).ready(function(){
  $("#satuB").click(function(){
    $("#nomor1").fadeOut(100);
    $("#nomor2").fadeIn(1000);
    
    
  });
});

$(document).ready(function(){
  $("#satuC").click(function(){
    $("#nomor1").fadeOut(100);
    $("#nomor2").fadeIn(1000);
    
    
  });
});

$(document).ready(function(){
  $("#satuD").click(function(){
    $("#nomor1").fadeOut(100);
    $("#nomor2").fadeIn(1000);
    
    
  });
});








				







</script>
</div>

				<div class="nomor1" id="nomor2">


<h2 class="soal1">Satuan polisi pramong praja singkatan dari...</h2>
<div class="pilihan1">

<button class="buttonA" type="button" onclick="a2()" id="duaA" >A. Satpol</button><br><br>

<button class="buttonB" type="button" onclick="b2()" id="duaB" >B. Saya Satpol</button><br><br>
<button class="buttonD" type="button" onclick="c2()" id="duaC" >C. Osis</button><br><br>
<button class="buttonD" type="button" onclick="d2()" id="duaD" >D. Pramuka</button><br><br>
</div>
<input class="opacity" type="text" name="No2" size="1">




<h3 id="hasil"></h3>
				 <script>
function a2(){
form.No2.value= "A";
}
function b2(){
form.No2.value= "B";
score = score+ 25 ;
     document.getElementById("nilai").innerHTML=(score);
}
function c2(){
form.No2.value= "C";
}
function d2(){
form.No2.value= "D";
}

$(document).ready(function(){
  $("#duaA").click(function(){
    $("#nomor2").fadeOut(100);
    $("#nomor3").fadeIn(1000);
    
    
  });
});

$(document).ready(function(){
  $("#duaB").click(function(){
    $("#nomor2").fadeOut(100);
    $("#nomor3").fadeIn(1000);
    
    
  });
});


$(document).ready(function(){
  $("#duaC").click(function(){
    $("#nomor2").fadeOut(100);
    $("#nomor3").fadeIn(1000);
    
    
  });
});

$(document).ready(function(){
  $("#duaD").click(function(){
    $("#nomor2").fadeOut(100);
    $("#nomor3").fadeIn(1000);
    
    
  });
});


</script>
</div>



				<div class="nomor1" id="nomor3">


<h2 class="soal1">Dia perempuan tetapi mempunyai batang, di sebut apakah itu</h2>
<div class="pilihan1">
<button class="buttonA" type="button" onclick="a3()" id="tigaA" >A. LAKIKK!!</button><br><br>

<button class="buttonB" type="button" onclick="b3()" id="tigaB" >B. Testis Jerapah</button><br><br>
<button class="buttonC" type="button" onclick="c3()" id="tigaC">C. Hode</button><br><br>
<button class="buttonD" type="button" onclick="d3()" id="tigaD" >D. Gonggo</button><br><br>
</div>

<input class="opacity" type="text" name="No3" size="1">



<h3 id="hasil3"></h3>
				 <script>
function a3(){
form.No3.value= "A";
}
function b3(){
form.No3.value= "B";
}
function c3(){
form.No3.value= "C";
score = score+ 25 ;
     document.getElementById("nilai").innerHTML=(score);
}
function d3(){
form.No3.value= "D";
}


$(document).ready(function(){
  $("#tigaA").click(function(){
    $("#nomor3").fadeOut(100);
    $("#nomor4").fadeIn(1000);
    
    
  });
});


$(document).ready(function(){
  $("#tigaB").click(function(){
    $("#nomor3").fadeOut(100);
    $("#nomor4").fadeIn(1000);
    
    
  });
});

$(document).ready(function(){
  $("#tigaC").click(function(){
    $("#nomor3").fadeOut(100);
    $("#nomor4").fadeIn(1000);
    
    
  });
});


$(document).ready(function(){
  $("#tigaD").click(function(){
    $("#nomor3").fadeOut(100);
    $("#nomor4").fadeIn(1000);
    
    
  });
});


</script>

</div>


<div id="nomor4" class="nomor1">
<h3 class="soal1">Kamu mau ga jadi pacar aku	?																													</h3>
<div class="pilihan1">
<button class="buttonA" type="button" onclick="a1()" id="empatA">Mauu </button><br><br>
<button  type="button" onclick="b1()" class="buttonB" id="empatB" >Enggak</button><br><br>
<button class="buttonC" type="button" onclick="c1()" id="empatC" >Tidak </button><br><br>
<button class="buttonD" type="button" onclick="d1()" id="empatD" >Ga lu jelek </button><br>

<br><br>
<button class="cekhasil" id="cek" type="submit" onclick="selesai()">Cek Hasil</button>

<input class="opacity" type="text" name="mau" size="1">
</div>

<br>

<br>
<br>
<h3 id="tampil"></h3>
<script>
				var score = 0;
function a1(){
form.mau.value= "mau";
score = score+ 25 ;
     document.getElementById("nilai").innerHTML=(score);
}
function b1(){
form.mau.value= "engga";
}
function c1(){
form.mau.value= "tidak";
}
function d1(){
form.mau.value= "g lu jelek";
}


$(document).ready(function(){
  $("#empatA").click(function(){
    $("#empatA").fadeOut(100);
    $("#empatB").fadeOut(100);
    $("#empatC").fadeOut(100);
    $("#empatD").fadeOut(100);
   
    
    
  });
});

$(document).ready(function(){
  $("#empatB").click(function(){
     $("#empatA").fadeOut(100);
    $("#empatB").fadeOut(100);
    $("#empatC").fadeOut(100);
    $("#empatD").fadeOut(100);
    
    
  });
});

$(document).ready(function(){
  $("#empatC").click(function(){
     $("#empatA").fadeOut(100);
    $("#empatB").fadeOut(100);
    $("#empatC").fadeOut(100);
    $("#empatD").fadeOut(100);
    
  });
});

$(document).ready(function(){
  $("#empatD").click(function(){
     $("#empatA").fadeOut(100);
    $("#empatB").fadeOut(100);
    $("#empatC").fadeOut(100);
    $("#empatD").fadeOut(100);
    
    
  });
});


$(document).ready(function(){
  $("#cek").click(function(){
     $("#nomor4").fadeOut(100);
    $("#akhir").fadeIn(1000);
    
    
    
  });
});



</script>
</div>

<div class=" akhir" id="akhir">
				<div class="dih">
<h3 class="anda">Nama :</h3>
<h3 class="hai" id="hai"></h3>
</div>
<div class="wah">
<h3 class="nilaianda">Nilai : </h3>
<h3 class="nilai" id="nilai"></h3>
</div>

<p class="em"><em>Apapun hasilnya kamu harus tetap semangat dan seburuk apapun hidup kamu jangan jadi beban keluarga</em></p>
<input class="opacity" type="text" name="Hasil" id="last" >
<script>
				
				function selesai(){
					document.getElementById("last").value = document.getElementById("nilai").innerHTML
     
				}
				
					$(document).ready(function() {
		$("#mulai").click(function(){
						var name = $("#nama").val()
						$("#hai").html(name)
						$("#nama").val("")
				});
				});
				
				
</script>












</div>
</form>
<script>
						const scriptURL = 'https://script.google.com/macros/s/AKfycbweEQmgVauLKEj1w6W_7NVhkADnTtTa7b0dwz6-42Mq3vzXlWJ8N8Z-vJXoLY9BuQJ81g/exec'
  const form = document.forms['form']

  form.addEventListener('submit', e => {
    e.preventDefault()
    fetch(scriptURL, { method: 'POST', body: new FormData(form)})
      .then(response => console.log('Success!', response))
      .catch(error => console.error('Error!', error.message))
  })
		</script>
</body>
</html>
