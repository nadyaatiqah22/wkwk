<!DOCTYPE html>
<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Sono:wght@600&display=swap" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script><link href="https://feeldreams.github.io/thisyou/style.css" rel="stylesheet" type="text/css" />
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  
<head>
<title>For Fatih</title>
<link rel="icon" type="image/x-icon" href="https://www.palingit.com/favicon.ico">
<meta name="description" content="HTML Replit Coding">
</head>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="music.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1fYUJTGP_7VICM1ogQKKOLASmTGkRWfXM3g&s" id="wallpaper"/>
   </div>
   
   <div id='Content'>

     <div id="ftAwal">
       <img src="https://i.pinimg.com/originals/49/d7/fb/49d7fb42e18e2bf7eb62a3f477584638.gif" id="ftoAwal"/>
     </div>

     <div id="loveIn">
       <!-- Tombol LOVE --><label class='lovein'>😈</label>
     </div>
     <p id="ket">Halo Fatih</p>
     <p id="ket">Klik Emot Setan Ungunya</p>

     <!-- ---------------------- -->
     
     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://s3.getstickerpack.com/storage/uploads/sticker-pack/quby-pentol-gif/sticker_9.gif?afb050261cc5640e21ce2eb44043c17a" id="fotostiker"/>
         <img src="https://i.pinimg.com/originals/b7/53/65/b753658d551ec755d0dad8c66b86d24d.gif" id="fotostiker1"/>
         <img src="https://media1.tenor.com/m/Dp9JlqQDuHUAAAAd/pentol-stiker.gif" id="fotostiker2"/>
         <img src="https://i.pinimg.com/originals/12/ed/28/12ed284fdc02931de098213c2b2fd26f.gif" id="fotostiker3"/>
         <img src="https://i.pinimg.com/originals/4a/05/31/4a053115c867be62279b8c9bfe181c90.gif" id="fotostiker4"/>
         <img src="https://feeldreams.github.io/pandakuning.gif" id="fotostiker5"/>
     </div>
     
     <div><blockquote id='bq' data-text='🌈'>
       <p id="halo" class="halo"></p>
       <p id="kalimat">Semoga harimu enak dijalanin ya 🗿</p>
       
       
       <!-- Pesan -->
       <p id="pesan0">Hari ini ngajar kan, semoga lancar semuanya🗿</p>
       <p id="pesan1">Pasti capek, tapi semoga tetap enjoy ngejalaninnya</p>
       <p id="pesan2">Kalau sempet, istirahat bentar ya jangan dipaksain terus</p>
       <p id="pesan3">Pelan-pelan aja gapapa, yang penting tetap jalan</p>
       <p id="pesan4">Udah sejauh ini, tinggal lanjut dikit lagi, Semoga semua yang kamu jalanin hari ini dimudahin(klik 3 emot bomnya)</p>
       <div id="kolombaru">
         <li id="lv1">💣</li>
         <li id="lv2">🔫</li>
         <li id="lv3">🧨</li>
       </div>
       <p id="pesan5">lanjut gak???</p>
       <p id="pesan6">Udah ya, itu aja. Semangat hari ini 🙂😭 &gt;&lt;</p>
       <p id="pesan7" class="gaya2">dah gitu aja, Papay✨</p>

       <!-- Tombol Lanjut -->
       <p id="opsL">Klik untuk lanjut</p>
     </blockquote></div>

     <!-- Tombol Multifungsi -->
     <div id="Tombol">
       <a id="By">iyaa ...</a>
       <a id="Bn">ih ogah</a>
     </div>

     <!-- Pesan Ditolak -->
     <div id="pesanditolak">
       <img id="stikerditolak" src="https://feeldreams.github.io/peachsad1.gif"/>
       <p id="kataditolak">iya iya udah noh</p>
     </div>

   </div>

<!-- Jangan Edit Bagian Ini --><script>
  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2300, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); audio = new Audio('' + linkmp3.src); ftganti=0;fungsi=0;fungsiAwal=0;deffotostiker=fotostiker.src;function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-snowflake"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-snowflake"); if (heartArr.length > 100) {heartArr[0].remove()}},100);Content.style = "opacity:1;margin-top:16vh"; const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageHeight: 80,}); 
  
  async function inipesan(){
         vketikhalo="morning bro✨";
         mulainama();
  }

  async function menuju(){
    pesanwhatsapp = "wkwk";
    await swals.fire('OK!', 'Kirim jawabannya ke WhatsApp aku, ya!', 'success');
    window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;
  }
</script>
<script src="https://feeldreams.github.io/thisyou/script.js"></script>
<!-- Sampai Sini -->
</body>
</html>
