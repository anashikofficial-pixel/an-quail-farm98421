<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#138a43">

<title>AN Quail Farm & Hatchery</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
  font-family:Arial,"Noto Sans Bengali",sans-serif;
}

body{
  background:#f2f7f3;
  color:#222;
  line-height:1.7;
}

header{
  background:linear-gradient(135deg,#075b2b,#20a957);
  color:white;
  text-align:center;
  padding:25px 15px;
}

.logo{
  width:80px;
  height:80px;
  border-radius:50%;
  background:white;
  margin:auto;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:43px;
  box-shadow:0 4px 15px #0003;
}

header h1{
  margin-top:10px;
  font-size:27px;
}

header p{
  font-size:14px;
}

nav{
  position:sticky;
  top:0;
  z-index:20;
  background:white;
  display:flex;
  justify-content:center;
  flex-wrap:wrap;
  gap:5px;
  padding:9px;
  box-shadow:0 2px 8px #0002;
}

nav a{
  color:#075b2b;
  text-decoration:none;
  padding:7px 10px;
  border-radius:20px;
  font-weight:bold;
  font-size:14px;
}

nav a:hover{
  background:#075b2b;
  color:white;
}

.container{
  max-width:1050px;
  margin:auto;
  padding:15px;
}

.hero,
.card{
  background:white;
  border-radius:18px;
  padding:20px;
  box-shadow:0 3px 12px #0001;
}

.hero{
  text-align:center;
  margin-top:15px;
}

.hero h2,
section h2{
  color:#075b2b;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(210px,1fr));
  gap:15px;
  margin-top:15px;
}

section{
  margin-top:28px;
}

section > h2{
  text-align:center;
  margin-bottom:12px;
}

.card h3{
  color:#138a43;
  margin-bottom:6px;
}

.price-card{
  text-align:center;
  border-top:5px solid #20a957;
}

.price-icon{
  font-size:38px;
}

.price{
  font-size:24px;
  font-weight:bold;
  color:#075b2b;
  margin:5px 0;
}

.price-note{
  color:#777;
  font-size:12px;
}

.info{
  background:#e8f7ed;
  border-left:5px solid #20a957;
  padding:14px;
  border-radius:10px;
  margin-top:12px;
}

.badge{
  display:inline-block;
  background:#e7f6ec;
  color:#075b2b;
  padding:5px 10px;
  margin:4px;
  border-radius:20px;
  font-weight:bold;
}

.share-area{
  margin-top:18px;
  display:flex;
  justify-content:center;
  flex-wrap:wrap;
  gap:10px;
}

button,
.btn{
  border:0;
  cursor:pointer;
  background:#138a43;
  color:white;
  padding:11px 17px;
  border-radius:25px;
  font-size:15px;
  font-weight:bold;
  text-decoration:none;
  display:inline-block;
}

button:hover,
.btn:hover{
  opacity:.9;
}

.copy{
  background:#555;
}

.contact{
  background:linear-gradient(135deg,#075b2b,#20a957);
  color:white;
  border-radius:18px;
  padding:25px 18px;
}

.contact h2{
  color:white;
}

.contact-box{
  background:#ffffff1c;
  padding:13px;
  margin:8px 0;
  border-radius:10px;
}

.contact a{
  color:white;
  font-weight:bold;
  text-decoration:none;
}

.admin-box{
  background:#fff;
  border-radius:18px;
  padding:20px;
  box-shadow:0 3px 12px #0001;
}

input{
  width:100%;
  padding:12px;
  margin:6px 0;
  border:1px solid #ccc;
  border-radius:10px;
  font-size:16px;
}

#adminPanel{
  display:none;
}

.admin-edit{
  background:#f7faf8;
  padding:15px;
  border-radius:12px;
  margin-top:15px;
}

footer{
  margin-top:30px;
  background:#08351d;
  color:white;
  text-align:center;
  padding:22px 10px;
  font-size:14px;
}

.notice{
  text-align:center;
  color:#666;
  font-size:13px;
  margin-top:10px;
}
</style>
</head>

<body>

<header>

<div class="logo">🐦</div>

<h1>AN Quail Farm & Hatchery</h1>

<p>কোয়েল পাখি • ডিম • বাচ্চা • হ্যাচারি • পালন গাইড</p>

<div class="share-area">

<button onclick="shareApp()">
📤 অ্যাপ শেয়ার করুন
</button>

<button class="copy" onclick="copyLink()">
🔗 লিংক কপি করুন
</button>

</div>

</header>


<nav>

<a href="#home">হোম</a>
<a href="#prices">দাম</a>
<a href="#quail">কোয়েল</a>
<a href="#egg">ডিম</a>
<a href="#hatchery">হ্যাচারি</a>
<a href="#guide">গাইড</a>
<a href="#contact">যোগাযোগ</a>
<a href="#admin">প্রোফাইল</a>

</nav>


<div class="container">


<!-- HOME -->

<section id="home" class="hero">

<h2>🐦 AN Quail Farm & Hatchery</h2>

<p>
কোয়েল পাখি, ডিম, বাচ্চা, হ্যাচারি এবং কোয়েল পালন
সম্পর্কিত প্রয়োজনীয় তথ্য এখানে সহজভাবে দেখা যাবে।
</p>

<div style="margin-top:12px;">

<span class="badge">🐦 কোয়েল পালন</span>
<span class="badge">🥚 ডিম</span>
<span class="badge">🐣 বাচ্চা</span>
<span class="badge">🌡️ ইনকিউবেটর</span>
<span class="badge">📚 গাইড</span>

</div>

</section>


<!-- PRICE SECTION -->

<section id="prices">

<h2>💰 আজকের দাম</h2>

<p style="text-align:center;color:#666;">
এলাকাভেদে ও সময়ভেদে দাম পরিবর্তন হতে পারে।
</p>


<div class="grid">


<div class="card price-card">

<div class="price-icon">🥚</div>

<h3>কোয়েলের ডিম</h3>

<div class="price" id="eggPrice">
৳ 0
</div>

<div class="price-note">
প্রতি পিস
</div>

</div>


<div class="card price-card">

<div class="price-icon">🐦</div>

<h3>কোয়েল পাখি</h3>

<div class="price" id="birdPrice">
৳ 0
</div>

<div class="price-note">
প্রতি পাখি
</div>

</div>


<div class="card price-card">

<div class="price-icon">🐣</div>

<h3>কোয়েল বাচ্চা</h3>

<div class="price" id="chickPrice">
৳ 0
</div>

<div class="price-note">
প্রতি বাচ্চা
</div>

</div>


<div class="card price-card">

<div class="price-icon">🌡️</div>

<h3>ইনকিউবেটর</h3>

<div class="price" id="incubatorPrice">
৳ 0
</div>

<div class="price-note">
মডেল/ক্ষমতা অনুযায়ী
</div>

</div>


</div>


<div class="info">

<b>📌 নোট:</b>

<br>

এখানে শুধু তথ্য ও দাম দেখানো হচ্ছে।
কোনো অনলাইন অর্ডার বা অনলাইন বিক্রির ব্যবস্থা নেই।

</div>

</section>


<!-- QUAIL -->

<section id="quail">

<h2>🐦 কোয়েল পাখি সম্পর্কে</h2>

<div class="grid">


<div class="card">

<h3>কোয়েল কী?</h3>

<p>
কোয়েল ছোট আকারের পাখি। সঠিক পরিবেশ,
খাবার ও পরিচর্যার মাধ্যমে কোয়েল পালন করা যায়।
</p>

</div>


<div class="card">

<h3>🏠 বাসস্থান</h3>

<p>
খাঁচা বা শেড পরিষ্কার, শুকনো এবং পর্যাপ্ত
বাতাস চলাচলযোগ্য রাখা গুরুত্বপূর্ণ।
</p>

</div>


<div class="card">

<h3>🍚 খাবার</h3>

<p>
বয়স অনুযায়ী সুষম খাবার এবং সবসময় পরিষ্কার
পানির ব্যবস্থা রাখা প্রয়োজন।
</p>

</div>


<div class="card">

<h3>🧹 পরিচ্ছন্নতা</h3>

<p>
খাঁচা, খাবারের পাত্র ও পানির পাত্র নিয়মিত
পরিষ্কার রাখুন।
</p>

</div>


</div>

</section>


<!-- EGG -->

<section id="egg">

<h2>🥚 কোয়েলের ডিম</h2>

<div class="card">

<h3>ডিম সংগ্রহ</h3>

<p>
ডিম নিয়মিত সংগ্রহ করে পরিষ্কার ও উপযুক্ত
পরিবেশে সংরক্ষণ করতে হবে।
</p>

<div class="info">

<b>📌 মনে রাখবেন:</b>

<br>

ডিমের উৎপাদন পাখির বয়স, খাবার, আলো,
পরিবেশ ও স্বাস্থ্যের ওপর নির্ভর করতে পারে।

</div>

</div>

</section>


<!-- HATCHERY -->

<section id="hatchery">

<h2>🐣 হ্যাচারি ও ইনকিউবেশন</h2>

<div class="grid">


<div class="card">

<h3>🥚 ডিম নির্বাচন</h3>

<p>
ইনকিউবেশনের জন্য উপযুক্ত, স্বাভাবিক আকৃতির
ও ভালো মানের ডিম নির্বাচন করা গুরুত্বপূর্ণ।
</p>

</div>


<div class="card">

<h3>🌡️ তাপমাত্রা</h3>

<p>
ইনকিউবেটর প্রস্তুতকারকের নির্দেশনা অনুযায়ী
তাপমাত্রা নিয়ন্ত্রণ করুন।
</p>

</div>


<div class="card">

<h3>💧 আর্দ্রতা</h3>

<p>
ইনকিউবেশনের বিভিন্ন সময়ে প্রয়োজন অনুযায়ী
আর্দ্রতা নিয়ন্ত্রণ করতে হয়।
</p>

</div>


<div class="card">

<h3>🐣 বাচ্চা</h3>

<p>
বাচ্চা ফোটার পর উষ্ণতা, পরিষ্কার পানি,
উপযুক্ত খাবার ও পরিষ্কার পরিবেশ নিশ্চিত করুন।
</p>

</div>


</div>

</section>


<!-- GUIDE -->

<section id="guide">

<h2>📚 কোয়েল পালন গাইড</h2>

<div class="grid">


<div class="card">

<h3>১️⃣ খামার প্রস্তুতি</h3>

<p>
খামার পরিষ্কার রাখুন এবং পাখির জন্য পর্যাপ্ত
জায়গা ও বাতাস চলাচলের ব্যবস্থা করুন।
</p>

</div>


<div class="card">

<h3>২️⃣ পানি ও খাবার</h3>

<p>
পরিষ্কার পানি এবং বয়স অনুযায়ী উপযুক্ত
খাবার নিয়মিত দিন।
</p>

</div>


<div class="card">

<h3>৩️⃣ স্বাস্থ্য</h3>

<p>
পাখির খাবার গ্রহণ, আচরণ ও স্বাভাবিক অবস্থার
পরিবর্তন নিয়মিত পর্যবেক্ষণ করুন।
</p>

</div>


<div class="card">

<h3>৪️⃣ রোগ প্রতিরোধ</h3>

<p>
পরিষ্কার-পরিচ্ছন্নতা বজায় রাখুন।
অসুস্থ পাখি দেখা দিলে যোগ্য প্রাণিসম্পদ
কর্মকর্তা বা পশু চিকিৎসকের পরামর্শ নিন।
</p>

</div>


</div>

</section>


<!-- ABOUT -->

<section>

<h2>ℹ️ আমাদের সম্পর্কে</h2>

<div class="card">

<p>

<b>AN Quail Farm & Hatchery</b>
কোয়েল পাখি, ডিম, বাচ্চা, হ্যাচারি এবং
কোয়েল পালন সম্পর্কিত তথ্য মানুষের কাছে
সহজভাবে পৌঁছে দেওয়ার জন্য তৈরি।

</p>

<p style="margin-top:10px;">

সবাই পাসওয়ার্ড ছাড়াই অ্যাপের তথ্য দেখতে পারবে।
শুধু অ্যাডমিন প্রোফাইল সুরক্ষিত থাকবে।

</p>

</div>

</section>


<!-- CONTACT -->

<section id="contact">

<div class="contact">

<h2>📞 যোগাযোগ করুন</h2>


<div class="contact-box">

📱

<a href="tel:01731198421">

01731198421

</a>

</div>


<div class="contact-box">

📱

<a href="tel:01845167291">

01845167291

</a>

</div>


<div class="contact-box">

📍 আনোয়ার কাসাইবাড়ী,
নাটুয়া, রাজারহাট, কুড়িগ্রাম

</div>


<div class="share-area">

<a class="btn" href="tel:01731198421">
📞 কল করুন
</a>

<a class="btn" href="tel:01845167291">
📞 কল করুন
</a>

</div>

</div>

</section>


<!-- ADMIN -->

<section id="admin">

<h2>🔐 অ্যাডমিন প্রোফাইল</h2>

<div class="admin-box">

<p>
সাধারণ দর্শকদের কোনো পাসওয়ার্ড প্রয়োজন নেই।
এই অংশটি শুধু অ্যাডমিন ব্যবহারের জন্য।
</p>


<input
type="text"
id="username"
placeholder="Admin Username"
>


<input
type="password"
id="password"
placeholder="Admin Password"
>


<button onclick="adminLogin()">
🔐 লগইন
</button>


<p id="loginMessage" style="margin-top:10px;"></p>


<div id="adminPanel">

<hr style="margin:18px 0">


<h3>✅ Admin Panel</h3>


<div class="admin-edit">

<h3>💰 দাম পরিবর্তন</h3>

<p style="font-size:13px;color:#666;">
নিচে নতুন দাম লিখে Save Price চাপুন।
</p>


<input
type="number"
id="newEggPrice"
placeholder="ডিমের দাম"
>


<input
type="number"
id="newBirdPrice"
placeholder="পাখির দাম"
>


<input
type="number"
id="newChickPrice"
placeholder="বাচ্চার দাম"
>


<input
type="number"
id="newIncubatorPrice"
placeholder="ইনকিউবেটরের দাম"
>


<button onclick="savePrices()">
💾 দাম Save করুন
</button>

</div>


<div class="info">

<b>যোগাযোগ:</b>

<br>

📱 01731198421

<br>

📱 01845167291

<br>

📍 আনোয়ার কাসাইবাড়ী, নাটুয়া,
রাজারহাট, কুড়িগ্রাম

</div>


<button
onclick="adminLogout()"
style="margin-top:12px;"
>

🚪 Logout

</button>


</div>

</div>

</section>


<p class="notice">

এই ওয়েব অ্যাপের তথ্য শিক্ষামূলক উদ্দেশ্যে দেওয়া হয়েছে।

</p>


</div>


<footer>

<b>AN Quail Farm & Hatchery</b>

<br>

🐦 কোয়েল পাখি • 🥚 ডিম • 🐣 হ্যাচারি

<br><br>

📞 01731198421 | 01845167291

<br><br>

© 2026 All Rights Reserved

</footer>



<script>

/* ==========================
   DEFAULT PRICE
========================== */

let prices = {

  egg: "0",
  bird: "0",
  chick: "0",
  incubator: "0"

};


/* ==========================
   LOAD SAVED PRICE
========================== */

function loadPrices(){

  const saved =
    localStorage.getItem("quailPrices");

  if(saved){

    prices = JSON.parse(saved);

  }

  document.getElementById("eggPrice").innerText =
    "৳ " + prices.egg;

  document.getElementById("birdPrice").innerText =
    "৳ " + prices.bird;

  document.getElementById("chickPrice").innerText =
    "৳ " + prices.chick;

  document.getElementById("incubatorPrice").innerText =
    "৳ " + prices.incubator;

}


/* ==========================
   SAVE PRICE
========================== */

function savePrices(){

  prices.egg =
    document.getElementById("newEggPrice").value || "0";

  prices.bird =
    document.getElementById("newBirdPrice").value || "0";

  prices.chick =
    document.getElementById("newChickPrice").value || "0";

  prices.incubator =
    document.getElementById("newIncubatorPrice").value || "0";


  localStorage.setItem(
    "quailPrices",
    JSON.stringify(prices)
  );


  loadPrices();

  alert("✅ দাম সফলভাবে Save হয়েছে!");

}


/* ==========================
   SHARE APP
========================== */

function shareApp(){

  const shareData = {

    title:
      "AN Quail Farm & Hatchery",

    text:
      "AN Quail Farm & Hatchery — কোয়েল পাখি, ডিম, হ্যাচারি ও পালন গাইড দেখুন।",

    url:
      window.location.href

  };


  if(navigator.share){

    navigator.share(shareData)
      .catch(function(){});

  }else{

    copyLink();

    alert(
      "অ্যাপের লিংক কপি হয়েছে। এখন WhatsApp, Messenger বা Telegram-এ পাঠাতে পারবেন।"
    );

  }

}


/* ==========================
   COPY LINK
========================== */

function copyLink(){

  const link =
    window.location.href;


  if(navigator.clipboard){

    navigator.clipboard.writeText(link)

    .then(function(){

      alert("✅ অ্যাপের লিংক কপি হয়েছে!");

    })

    .catch(function(){

      fallbackCopy(link);

    });

  }else{

    fallbackCopy(link);

  }

}


function fallbackCopy(text){

  const temp =
    document.createElement("textarea");

  temp.value = text;

  document.body.appendChild(temp);

  temp.select();

  document.execCommand("copy");

  document.body.removeChild(temp);

  alert("✅ অ্যাপের লিংক কপি হয়েছে!");

}


/* ==========================
   ADMIN LOGIN
========================== */

function adminLogin(){

  const user =
    document.getElementById("username").value;

  const pass =
    document.getElementById("password").value;


  if(
    user === "anashik" &&
    pass === "2009@#AN"
  ){

    document.getElementById(
      "adminPanel"
    ).style.display = "block";


    document.getElementById(
      "loginMessage"
    ).innerHTML =
      "✅ Admin Login সফল হয়েছে।";


    document.getElementById(
      "loginMessage"
    ).style.color = "green";


  }else{

    document.getElementById(
      "loginMessage"
    ).innerHTML =
      "❌ Username অথবা Password ভুল।";


    document.getElementById(
      "loginMessage"
    ).style.color = "red";


    document.getElementById(
      "adminPanel"
    ).style.display = "none";

  }

}


/* ==========================
   ADMIN LOGOUT
========================== */

function adminLogout(){

  document.getElementById(
    "adminPanel"
  ).style.display = "none";


  document.getElementById(
    "username"
  ).value = "";


  document.getElementById(
    "password"
  ).value = "";


  document.getElementById(
    "loginMessage"
  ).innerHTML =
    "আপনি Logout করেছেন।";

}


/* ==========================
   START
========================== */

loadPrices();

</script>

</body>
</html>
