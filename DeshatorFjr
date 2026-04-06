<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jasa Desainer Editor</title>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: linear-gradient(135deg,#1e293b,#0f172a);
  color: white;
}

.animasi {
  opacity: 0;
  transform: translateX(-60px);
  transition: all 0.5s ease;
}

.animasi.show {
  opacity: 1;
  transform: translateX(0);
}

.container { padding: 20px; }

h2 { text-align: center; }

.card {
  background: #1e293b;
  padding: 15px;
  border-radius: 12px;
  margin-bottom: 20px;
}

.item {
  display: flex;
  justify-content: space-between;
  margin: 5px 0;
}

input[type="text"] {
  width: 120px;
  border-radius: 6px;
  border: none;
  padding: 6px;
}

button {
  width: 100%;
  padding: 12px;
  margin-top: 10px;
  border: none;
  border-radius: 10px;
  background: #22c55e;
  color: white;
  font-weight: bold;
}

.admin-box {
  display: none;
  background: #020617;
  padding: 20px;
  border-radius: 12px;
}

.log-item {
  background: #334155;
  padding: 10px;
  border-radius: 8px;
  margin: 10px 0;
  text-align: left;
  white-space: pre-line;
}

.delete-btn {
  background: red;
  margin-top: 5px;
}

.total-box {
  margin-top: 15px;
  padding: 10px;
  background: #1e293b;
  border-radius: 8px;
}
</style>
</head>

<body>
    
<div id="loading" style="
position:fixed;
top:0;left:0;
width:100%;height:100%;
background:#020617;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
color:white;
z-index:9999;
overflow:hidden;
font-family:monospace;
">

<!-- teks jatuh -->
<div id="teks" style="
font-size:18px;
position:relative;
top:-100px;
opacity:0;
transition: all 1s ease;
text-align:center;
margin-bottom:20px;
">
Sedang Loading Yeahhh...<br>di Web vip fjr mth
</div>

<!-- bola mantul -->
<div style="position:relative;width:100%;height:80px;margin-bottom:20px;">
<div style="position:absolute;top:0;width:100%;height:2px;background:white;"></div>

<div class="bola" style="left:20%;"></div>
<div class="bola" style="left:50%;"></div>
<div class="bola" style="left:80%;"></div>
</div>

<!-- petasan kiri -->
<div class="petasan kiri"></div>

<!-- petasan kanan -->
<div class="petasan kanan"></div>

<!-- tulisan dari ledakan -->
<div id="loveText">Love You Mutee</div>

<!-- area game -->
<div style="position:relative;width:90%;height:100px;overflow:hidden;">
<div style="position:absolute;bottom:0;width:100%;height:3px;background:white;"></div>

<div id="dino" style="
position:absolute;
bottom:3px;
left:10px;
width:4px;
height:4px;
background:white;
box-shadow:
4px 0 white, 8px 0 white, 12px 0 white,
0 -4px white, 4px -4px white, 8px -4px white, 12px -4px white, 16px -4px white,
0 -8px white, 4px -8px white, 8px -8px white, 12px -8px white, 16px -8px white,
4px -12px white, 8px -12px white, 12px -12px white,
8px -16px white, 12px -16px white,
12px -20px white;
"></div>

<div id="kaktus" style="
position:absolute;
bottom:3px;
right:-20px;
width:6px;
height:20px;
background:white;
"></div>
</div>

<style>
/* bola */
.bola{
  position:absolute;
  top:0;
  width:12px;
  height:12px;
  background:white;
  border-radius:50%;
  animation: jatuh 1s ease-in-out infinite;
}
.bola:nth-child(2){ animation-delay:0s;}
.bola:nth-child(3){ animation-delay:0.2s;}
.bola:nth-child(4){ animation-delay:0.4s;}

@keyframes jatuh{
  0%{top:0;}
  50%{top:60px; box-shadow:0 10px 10px rgba(255,255,255,0.3);}
  100%{top:0;}
}

/* petasan */
.petasan{
  position:absolute;
  bottom:0;
  width:4px;
  height:5px; 
  background:red;
}
.kiri{ left:20%; animation: naik 2s linear forwards;}
.kanan{ right:20%; animation: naik 2s linear forwards;}

@keyframes naik{
  0%{ bottom:0;}
  100%{ bottom:77%;}
}

/* ledakan */
.petasan::after{
  content:"";
  position:absolute;
  top:-10px;
  left:-10px;
  width:6px;
  height:6px;
  background:yellow;
  box-shadow:
  0 0 red,
  10px 0 orange,
  -10px 0 yellow,
  0 10px pink,
  0 -10px red,
  8px 8px orange,
  -8px -8px yellow,
  8px -8px pink,
  -8px 8px red;
  opacity:0;
  animation: ledak 0.4s ease 2s forwards;
}

@keyframes ledak{
  to{ opacity:1; transform:scale(2);}
}

/* tulisan love */
#loveText{
  position:absolute;
  top:10%;
  opacity:0;
  font-size:22px;
  color:pink;
  text-shadow:0 0 10px pink;
  animation: muncul 1s ease 2.5s forwards;
}

@keyframes muncul{
  to{ opacity:1; transform:scale(1.2);}
}
</style>

<script>
setTimeout(()=>{
  // teks jatuh
  let teks = document.getElementById("teks");
  teks.style.top = "0";
  teks.style.opacity = "1";

  // kaktus jalan
  let kaktus = document.getElementById("kaktus");
  kaktus.style.transition = "right 5s linear";
  kaktus.style.right = "100%";
},100);
</script>

</div>

<div class="container">

<h2>🎨 Deshator VIP.FJR.MTH</h2>

<div class="card">
  <b>💀Nama Customer:</b><br>
  <input type="text" id="namaCustomer" placeholder="Masukkan nama">
</div>

<div class="card" id="menu"></div>

<button onclick="kirimWA()">📩 Kirim ke WhatsApp</button>

<hr>

<button onclick="loginAdmin()">🔐 Admin</button>

<div class="admin-box" id="adminBox">

<h3>💰 Input Harga (Di wajibkan untuk admin)</h3>
<div id="adminMenu"></div>

<div class="total-box">
  💵 Jasa Desain/Editing:<br>
  <input type="text" id="hargaTambahan">
</div>

<!-- Tombol di HTML -->
<button onclick="simpanHarga()">💾 Simpan + Hitung</button>
<button onclick="kirimWAAdmin()">📲 Kirim WA Admin</button>

<script>
// Function kirim WA Admin
function kirimWAAdmin(){
  let data = localStorage.getItem("logPesanan");
  if(!data){
    alert("Belum ada log!");
    return;
  }

  let div = document.createElement("div");
  div.innerHTML = data;

  let teks = "📋 DATA PESANAN\n\n" + div.innerText;

  let nomor = "6283838497601"; // ganti nomor admin jika perlu
  let url = "https://wa.me/" + nomor + "?text=" + encodeURIComponent(teks);

  window.open(url, "_blank");
}
</script>

<h3>📋 Log</h3>
<div id="logData"></div>

<button onclick="printLog()">🖨️ Cetak</button>

</div>

</div>

<script>

/* ===========================
   🔥 EDIT MENU DI SINI SAJA
   =========================== */

const menuKategori = {
  "✏️Jasa Desainer": [
    "Desain gambar untuk kaos",
    "Desain grafis",
    "Desain custom",
    "Desain vector",
    "Desain banner",
    "Desain logo",
    "Desain sticker berwarna",
    "Desain sticker non warna"
  ],

  "🖌️Jasa Editing": [
    "Editing foto",
    "Editing Restorasi foto",
    "Editing Hapus background",
    "Editing jas non/berwarna",
    "Editing efek foto",
    "Editing Hapus object",
    "Editing Tambah object"
  ],

  "💻Jasa Coding": [
    "Coding website",
    "Coding game (belum tersedia)"
  ]
};

/* ===========================
   🔧 AUTO GENERATE MENU
   =========================== */

const menuDiv = document.getElementById("menu");
const adminMenu = document.getElementById("adminMenu");

let index = 0;

for (let kategori in menuKategori) {
  menuDiv.innerHTML += `<h3>${kategori}</h3>`;
  adminMenu.innerHTML += `<h4>${kategori}</h4>`;

  menuKategori[kategori].forEach(item => {

    menuDiv.innerHTML += `
      <div class="item">
        <label><input type="checkbox" value="${item}"> ${item}</label>
        <span>Rp-</span>
      </div>
    `;

    adminMenu.innerHTML += `
      <div class="item">
        ${item}
        <input type="text" id="harga_${index}">
      </div>
    `;

    index++;
  });
}

/* ===========================
   🔧 FUNCTION
   =========================== */

function parseHarga(text){
  if(!text) return 0;
  text = text.toLowerCase().replace(/\./g,"");
  if(text.includes("k")) return parseInt(text)*1000;
  return parseInt(text)||0;
}

function formatRupiah(angka){
  return angka.toString().replace(/\B(?=(\d{3})+(?!\d))/g,".");
}

function kirimWA(){
  let nama = document.getElementById("namaCustomer").value.trim();

  if(!nama){
    alert("Isi nama dulu!");
    return;
  }

  let pilih = [];
  document.querySelectorAll("input[type=checkbox]:checked")
    .forEach(cb=>pilih.push(cb.value));

  if(pilih.length===0){
    alert("Pilih menu dulu!");
    return;
  }

  let teks = "Nama: " + nama + "\n\nPesanan:\n" + pilih.join("\n");

  window.open("https://wa.me/6283838497601?text="+encodeURIComponent(teks));

  let log = localStorage.getItem("logPesanan") || "";
  localStorage.setItem("logPesanan", log + "<div class='log-item'>"+teks+"</div>");

  tampilkanLog();
}

function loginAdmin(){
  let pass = prompt("Password:");
  if(pass==="03FAJARTIA"){
    document.getElementById("adminBox").style.display="block";
    tampilkanLog();
  } else alert("Salah!");
}

function simpanHarga(){
  let total = 0;
  let log = "";
  let inputs = document.querySelectorAll("#adminMenu input");

  inputs.forEach((inp,i)=>{
    let val = inp.value.trim();
    if(val){
      let angka = parseHarga(val);
      total += angka;

      let nama = inp.parentElement.firstChild.textContent.trim();
      let spasi = 25 - nama.length; // atur lebar
if(spasi < 1) spasi = 1;

log += nama + " ".repeat(spasi) + "Rp " + formatRupiah(angka) + "\n";
    }
  });

  let tambahan = document.getElementById("hargaTambahan").value.trim();
  if(tambahan){
    let t = parseHarga(tambahan);
    total += t;
    log += "Jasa Desain/Editing " + formatRupiah(t) + "\n";
  }

  log += "\n====================";
log += "\nTotal keseluruhan : Rp " + formatRupiah(total);
log += "\n====================";
log += "\nVip.Fjr.Mth Mengucapkan Terimakasi sudah memesan jasa di kami kak 🙏";

  let old = localStorage.getItem("logPesanan") || "";
  localStorage.setItem("logPesanan", old + "<div class='log-item'>"+log+"</div>");

  tampilkanLog();
  alert("Tersimpan!");
}
function tampilkanLog(){
  let data = localStorage.getItem("logPesanan") || "";
  let container = document.getElementById("logData");
  container.innerHTML = data;

  let items = container.querySelectorAll(".log-item");

  items.forEach(div=>{
    let btn = document.createElement("button");
    btn.textContent = "Hapus";
    btn.className = "delete-btn";

    btn.onclick = function(){
      div.remove();
      simpanUlangLog(); // 🔥 update storage setelah hapus
    };

    div.appendChild(btn);
  });
}


function simpanUlangLog(){
  let semua = document.querySelectorAll("#logData .log-item");
  let hasil = "";

  semua.forEach(div=>{
    let clone = div.cloneNode(true);

    // hapus tombol sebelum disimpan
    let btn = clone.querySelector("button");
    if(btn) btn.remove();

    hasil += "<div class='log-item'>" + clone.innerHTML + "</div>";
  });

  if(hasil.trim() === ""){
    localStorage.removeItem("logPesanan"); // 🔥 biar benar-benar kosong
  } else {
    localStorage.setItem("logPesanan", hasil);
  }
}


function printLog(){
  let clone = document.getElementById("logData").cloneNode(true);

  // hapus semua tombol sebelum print
  clone.querySelectorAll("button").forEach(btn => btn.remove());

  let isi = clone.innerHTML;

  let w = window.open('', '', 'width=400,height=600');

  w.document.write(`
    <html>
    <body style="font-family:monospace;padding:10px;color:black;white-space:pre-line;">
    <h3 style="text-align:center;">NOTA</h3>
    ${isi}
    </body>
    </html>
  `);

  w.document.close();
  w.print();
}


// otomatis tampilkan saat buka halaman
window.onload = function(){

  // 🔥 loading delay
  setTimeout(()=>{
    let loading = document.getElementById("loading");
    if(loading) loading.style.display = "none";

    // tampilkan log
    tampilkanLog();

    // animasi masuk
    let semua = document.body.querySelectorAll("*");

    semua.forEach((el, i)=>{
      if(el.tagName !== "SCRIPT" && el.tagName !== "STYLE"){
        el.classList.add("animasi");

        setTimeout(()=>{
          el.classList.add("show");
        }, i * 20);
      }
    });

  }, 5000);

};

</script>
