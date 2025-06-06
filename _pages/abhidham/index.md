<!DOCTYPE html>
<html lang="th">
<head>
  
  <!-- Favicon -->
  <link rel="icon" href="https://raw.githubusercontent.com/dhamsutta/tripitaka/refs/heads/main/images/fav3.png" type="image/png" />

  <!-- OG Image สำหรับแชร์ -->
  <meta property="og:image" content="https://dhamsutta.github.io/tripitaka/images/dhamma
                                     
                                     " />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://dhamsutta.github.io/tripitaka/images/dhammalogo.png" />

  <!-- Structured Data (Breadcrumb for SEO) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "BreadcrumbList",
    "itemListElement": [
      {
        "@type": "ListItem",
        "position": 1,
        "name": "หน้าแรก",
        "item": "https://dhamsutta.github.io/tripitaka/"
      },
    
      {
        "@type": "ListItem",
        "position": 2,
        "name": "พระอภิธรรม",
        "item": "https://dhamsutta.github.io/tripitaka/abhidhamma/"
      },
      {
        "@type": "ListItem",
        "position": 3,
        "name": "จิต",
        "item": "https://dhamsutta.github.io/tripitaka/abhidhamma/citta.html"
      }
    ]
  }
  </script>

  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ธรรมสุตตะ | อภิธรรมเบื้องต้น</title>
  <meta name="description" content="เริ่มต้นศึกษาพระอภิธรรมเบื้องต้น ใช้ภาษาที่อ่านเข้าใจง่าย สามารถเรียนรู้ได้ด้วยตัวเอง" />
  <meta name="keywords" content="ธรรมะ, พระไตรปิฎก, พระอภิธรรม,รูป, จิต, เจตสิก, นิพพาน, วิปัสสนา" />

  <!-- Font และสไตล์ -->
  <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree&display=swap" rel="stylesheet">

  <style>
    html {
      scroll-behavior: smooth;
    }

:target {
  animation: highlight 2s ease-out;
}

@keyframes highlight {
  0%   { background-color: #fffcb0; }
  50%  { background-color: #fffcb0; }
  100% { background-color: transparent; }
}

a.readmore-button:hover {
  background-color: #333;
}

.sidebar ul {
  font-size: 16px;
  line-height: 1.4;
  padding-left: 0;
  list-style: none;
}

a.readmore-button:hover {
  background-color: #d1ae3d;
}
    

    body {
      font-family: 'Bai Jamjuree', sans-serif;
      font-size: 18px;
      line-height: 1.7;
      color: #222;
      background: #f9f9f9;
      margin: 0;
      padding: 0;
    }

    .sidebar {
      position: fixed;
      top: 0;
      left: 0;
      width: 240px;
      height: 100vh;
      background: rgba(255, 255, 255, 0.6);
      backdrop-filter: blur(4px);
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0,0,0,0.1);
      overflow-y: auto;
      z-index: 1000;
      transition: transform 0.3s ease;
    }

    .sidebar.hidden {
      transform: translateX(-100%);
    }

    .menu-toggle {
      position: fixed;
      top: 10px;
      left: 10px;
      background: #fff;
      border: 1px solid #ccc;
      padding: 10px 15px;
      font-size: 18px;
      cursor: pointer;
      z-index: 1100;
      border-radius: 6px;
      box-shadow: 1px 1px 4px rgba(0,0,0,0.1);
    }

    .content {
      max-width: 900px;
      margin: 30px auto;
      background: #fff;
      padding: 30px 40px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      border-radius: 8px;
      margin-left: 260px;
      flex-grow: 1;
      transition: margin-left 0.3s ease;
    }

    .sidebar.hidden ~ .content {
      margin-left: 30px;
    }

    h1, h2, h3 {
      color: #222;
      scroll-margin-top: 100px;
    }

    .tooltip-term[title] {
      border-bottom: 1px dotted #888;
      cursor: help;
    }

    a {
      color: #0645ad;
      text-decoration: underline;
    }

    a:hover {
      color: #0b0080;
    }

    hr {
      margin: 2em 0;
      border: none;
      border-top: 1px solid #ccc;
    }

    #backToTopBtn {
      position: fixed;
      bottom: 30px;
      right: 30px;
      z-index: 999;
      font-size: 22px;
      padding: 10px 14px;
      border: none;
      border-radius: 50%;
      background-color: #0645ad;
      color: white;
      cursor: pointer;
      display: none;
      box-shadow: 0 2px 6px rgba(0,0,0,0.3);
      transition: opacity 0.3s ease;
    }

    #backToTopBtn:hover {
      background-color: #0b0080;
    }

  @media (max-width: 768px) {
  .content {
    margin: 20px 10px;
    padding: 20px 16px;
  }
}

  </style>
</head>
<body>



  
  <button class="menu-toggle" onclick="toggleSidebar()">☰ เมนู</button>

  <div class="sidebar" id="sidebar">
    <a href="/" style="display: block; text-align: center; margin-bottom: 20px;">
      <img src="https://github.com/dhamsutta/tripitaka/blob/main/images/logo.png?raw=true"
           alt="โลโก้เว็บไซต์"
           style="max-width: 100px; height: auto;">
    </a>
    <h2></h2>
    <ul>
      <li><a href="#intro">เริ่มต้น</a></li>
      <li><a href="#section01">หมวดที่ ๐๑ พระอภิธรรมคืออะไร</a></li>
      <li><a href="#section02">หมวดที่ ๐๒ ชีวิต</a></li>
      <li><a href="#section03">หมวดที่ ๐๓ จิต</a></li>
      <li><a href="#section04">หมวดที่ ๐๔ เจตสิก </a></li>
      <li><a href="#section05">หมวดที่ ๐๕ รูปปรมัตถ์</a></li>
      <li><a href="#section06">หมวดที่ ๐๖ ภพภูมิ</a></li>
      <li><a href="#section07">หมวดที่ ๐๗ กฎแห่งกรรม</a></li>
       <li><a href="##section08">หมวดที่ ๐๘ สมุจจยสังคหะ</a></li>
      <li><a href="#section09">หมวดที่ ๐๙ สมถกรรมฐาน</a></li>
<li><a href="#section10">หมวดที่ ๑๐ วิปัสสนากรรมฐาน</a></li>
    </ul>

 <hr />
 <!-- ✅ กล่องค้นหา ใส่ตรงนี้ -->
  <h4 style="margin-top: 1.5rem;">📚 ค้นหาศัพท์บาลี</h4>
  <input type="text" id="dictSearch" placeholder="พิมพ์คำบาลี..." style="width: 100%; padding: 6px; border-radius: 6px; border: 1px solid #ccc;" />
  <div id="dictResults" style="margin-top: 0.5rem; font-size: 0.85rem; color: #444; max-height: 300px; overflow-y: auto;"></div>



    
  </div>

  <div class="content">

    <!-- ✅ Breadcrumb แสดงที่เดียว -->
   

    <!-- ✅ Google Search -->
    <script async src="https://cse.google.com/cse.js?cx=51c4343b3eeb842d6"></script>
    <div class="gcse-search"></div>
 <nav id="breadcrumb" style="font-size: 14px; margin-bottom: 20px;"></nav>
    <h1 id="intro">🕯️พระอภิธรรมเบื้องต้น</h1>
  <!--  <p>
      ตัวอย่างการใช้ <span class="tooltip-term" title="คำอธิบายคำศัพท์หรือคำเฉพาะที่ต้องการขยายความ">Tooltip</span> สำหรับคำเฉพาะ หรือศัพท์บาลี
    </p>


<a href="citta.html" class="readmore-button" style="
  display: inline-block;
  background-color: #e0c35a;
  color: #222;
  padding: 10px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-size: 16px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  transition: background-color 0.3s ease;
">
  📖 อ่านต่อ...
</a>



    
    -->
<img 
  src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiRcAqEU9I8BzRfA47pyFTsWUz85A-ESChJIGUxoMq9nQ1UF3jhwQk2csDQwpcvsAIsRURe3VtSb8YBBHJSKym4_C8ndPWEqXFGGVgxI8bZ0lb-kiKnnKgBo0cWzJB7wnmXi27ANmywd3qHWOy0UNNuDoK5dJwwwe3FJRLIYdy96UbMrgcCYxABXe_loczV/s1200/corpse-meditation.jpg" 
alt="ภาพจากบทความ"
style="float: right; width: 40%; margin-left: 1em; margin-bottom: 1em;"
/>
 <strong>พระอภิธรรม</strong>เปรียบเสมือน<strong>แก่นแท้ของพระพุทธศาสนา</strong> มีเนื้อหาสุขุมล้ำลึกอันนำไปสู่ความรู้ความเข้าใจในเรื่องธรรมชาติของชีวิต เรื่องของกรรมและการส่งผลของกรรม เรื่องภพภูมิต่างๆ เรื่องของการเวียนว่ายตายเกิดและ<strong><font size="" color="">เรื่องของการปฏิบัติเพื่อให้พ้นจากการเวียนว่ายตายเกิด</font></strong> ซึ่งเป็นจุดหมายอันสูงสุดในพระพุทธศาสนา ในที่นี้เป็นการปูพื้นฐานเพื่อให้เกิดความรู้และความเข้าใจในเบื้องต้นเกี่ยวกับประวัติความเป็นมาและเนื้อหาของพระอภิธรรม อันจะนำไปสู่การศึกษาที่ละเอียดลึกซึ้งต่อไป  
 <hr/>
<h2 id="section01">หมวดที่ ๐๑ พระอภิธรรมคืออะไร</h2>
๑. ประวัติพระอภิธรรม<br>
๒. ประโยชน์จากพระอภิธรรม<br>
 ๓. ปรมัตถและบัญญัติ<br>
๔. พระอภิธัมมัตถสังคหะ<br>
การศึกษาพระอภิธรรม ก็คือ<strong>การศึกษาธรรมชาติการทำงานของกายและใจ</strong> คื<font size="" color="red">อ รูปธรร</font>ม (กาย) และ<font size="" color="red"> นามธรร</font>ม (ใจ) ที่ประกอบกันเป็นชีวิต ซึ่งเป็นธรรมชาติที่มีอยู่ในตัวเราและสัตว์ทั้งหลาย เพื่อให้เกิดความรู้ความเข้าใจเกี่ยวกับเรื่อง จิต (วิญญาณ - ธรรมชาติที่รู้อารมณ์ เป็นประธานในธรรมทั้งปวง), เรื่อง เจตสิก (ธรรมชาติที่ประกอบกับจิต เกิดพร้อมจิต ดับพร้อมจิต รู้อารมณ์เดียวกับจิต), เรื่องอำนาจจิต, เรื่อง วีถีจิต (กระบวนการทำงานของจิตในการรับรู้อารมณ์ทางทวารต่างๆ), เรื่อง กรรม (การกระทำโดยเจตนา ทั้งทางกาย วาจา ใจ) และการส่งผลของกรรม (วิบาก - ผลของกรรม), เรื่องการเวียนว่ายตายเกิด (สังสารวัฏ - การเกิดดับสืบต่อในภพภูมิต่างๆ)<br>
<a href="https://dhamma-sutta.com/abhidhamma/chapter1.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;
">
  📖 อ่านต่อ...พระอภิธรรมคืออะไร
</a>

 <hr />

<h2 id="section02">หมวดที่ ๐๒ ชีวิต</h2>
๑. ชีวิตคืออะไร<br>
๒. จิตคืออะไร<br>
๓. ที่เกิดและอำนาจของจิต<br>
๔. บุญบาปเกิดขึ้นได้อย่างไร<br>
๕. ลักษณะของจิต<br>
ส่วนต่างๆ ที่ประกอบขึ้นมาเป็นร่างกายเรานั้นทางธรรมะเรียกว่า “<font size="" color="red">รูปธรรม</font>” หรือเรียกสั้นๆ ว่า <strong>รูป</strong> เป็นธรรมชาติที่<strong>ไม่มีความรู้สึกนึกคิดใดๆ</strong> เปรียบได้ดั่งท่อนไม้ ส่วน จิต และ เจตสิก นั้นเป็น “<font size="" color="red">นามธรรม</font>” หรือเรียกสั้นๆ ว่า <strong>นาม</strong> เป็น<strong>ธรรมชาติที่รับรู้สิ่งต่างๆ </strong>และสามารถคิดนึกเรื่องราวต่างๆได้ ดังนั้นตัวเรา หรือสัตว์ทั้งหลายจึงมีส่วนประกอบอยู่ ๓ ส่วน ได้แก่ กาย จิต และเจตสิก หรือเรียกว่า รูป กับ นาม<br>

<a href="https://dhamma-sutta.com/abhidhamma/chapter2.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">
📖 อ่านต่อ...ชีวิตในความหมาย รูป กับ นาม
</a>
<hr />

<h2 id="section03">หมวดที่ ๐๓ จิต</h2>
๑. ประเภทของจิต<br>
๒. กามาวจรจิต ๕๔ ดวง<br>
๓. รูปาวจรจิต ๑๕ ดวง<br>
๔. อรูปาวจรจิต ๑๒ ดวง<br>
๕. โลกุตตรจิต ๘ ดวง<br><strong>จิตมีสภาพรู้อารมณ์เป็นลักษณะ</strong> หรือเป็นธาตุรู้เท่านั้น ตามสภาวะแล้วจิตจะเกิดโดยลำพังไม่ได้จะต้องมี เจตสิก (ธรรมชาติที่ประกอบกับจิต) เกิดร่วมอยู่ด้วยเสมอ กล่าวคือเมื่อจิตเกิดเจตสิกก็เกิดร่วมด้วย เมื่อจิตดับเจตสิกก็ดับพร้อมกับจิตด้วย เจตสิกธรรม ธรรมชาติที่ประกอบกับจิต แบ่งออกเป็น ๓ ฝ่าย ดังนี้คือ..<br>
  <a href="https://dhamma-sutta.com/abhidhamma/chapter3.html" class="readmore-button" style="
  display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">

  📖 อ่านต่อ...ประเภทของจิต

</a>

<hr />

<h2 id="section04">หมวดที่ ๐๔ เจตสิก </h2>
๑. เจตสิก ๕๒ ดวง<br>
๒. เจตสิกกลุ่มที่ ๑<br>
๓. เจตสิกกลุ่มที่ ๒<br>
๔. เจตสิกกลุ่มที่ ๓<br>

<strong>จิตและเจตสิก</strong> ต่างก็เป็นนามธรรมด้วยกัน จึงประกอบเข้ากันได้สนิทโดยที่จิตนั้นเป็นธรรมชาติรู้อารมณ์ 
และ<font size="" color="red">เจตสิกเป็นธรรมชาติที่ปรุงแต่งจิตให้รู้อารมณ์เป็นไปต่างๆ</font>  ตามลักษณะของเจตสิก แม้เจตสิกจะเป็นธรรมชาติที่ปรุงแต่งจิตก็ตาม
 แต่ก็ต้องนับว่า จิตเป็นใหญ่หรือเป็นประธานเพื่อให้เจตสิกได้ปรุงแต่ง หรือเพื่อให้เจตสิกอิงอาศัยจิตเกิด จิตและเจตสิกที่ประกอบเข้าด้วยกันนี้ เรียกว่า "<strong>สัมปยุตตธรรม</strong>"<br>
<a href="https://dhamma-sutta.com/abhidhamma/chapter4.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">

  📖 อ่านต่อ...เจตสิกคืออะไร

</a>

<hr />

<h2 id="section05">หมวดที่ ๐๕ รูปปรมัตถ์ </h2>
นัยที่ ๑ รูปสมุทเทสนัย<br>
นัยที่ ๒ รูปวิภาคนัย<br>
นัยที่ ๓ รูปสมุฏฐานนัย<br>
นัยที่ ๔ รูปกลาปนัย<br>
นัยที่ ๕ รูปปวัตติกมนัย<br>

ปรมัตถ์ธรรมมี ๔ คือ จิต เจตสิก รูป และนิพพาน ผู้ศึกษาได้ศึกษาจิตและเจตสิกผ่านไปแล้ว เรื่องรูปปรมัตถ์นี้จะต่างจากจิตและเจตสิก เพราะ<font size="" color="red">จิตและเจตสิกนั้นเป็นนามธรรมเป็นธรรมที่รู้อารมณ์ ส่วนรูปนั้นเป็นธรรมที่ไม่รู้อารมณ์</font> <strong>รูปปรมัตถ์มี ๒๘ อย่าง</strong> โดยจำแนกเป็นรูปภายในและรูปภายนอก รูปที่ต้องอาศัย และรูปที่ไม่ต้องอาศัยเป็นต้น<br>

<a href="https://dhamma-sutta.com/abhidhamma/chapter5.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">

  📖 อ่านต่อ...รูปปรมัตถ์

</a>

<hr />

<h2 id="section06">หมวดที่ ๐๖ ภพภูมิ</h2>
๑. ความเป็นไปในสังสารวัฏ<br>
๒. ภพภูมิทั้ง ๓๑ ภูมิ<br>
๓. นรกภูมิ<br>
๔. ดิรัจฉานภูมิ<br>
๕. เปรตภูมิ<br>
๖. อสุรกายภูมิ<br>
๗. มนุษยภูมิ<br>
๘. เทวภูมิ<br>
๙. รูปาวจรภูมิ<br>
๑๐. อรูปาวจรภูมิ<br>
๑๑. อายุของสัตว์ในภูมิทั้ง ๓๑<br>
การศึกษาเรื่องภพภูมิ จะทำให้เข้าใจถึงชีวิต<strong>การเวียนว่ายตายเกิด</strong>ในภพภูมิอย่างไม่มีที่สิ้นสุดนั้นเป็นอย่างไร ทำไมจึงเป็นเช่นนั้นได้ และเพราะเหตุใด หรือมีผู้สร้างมีผู้กำหนดให้เป็นไปเช่นนั้นหรือไม่ จะมีอะไรมา<font size="" color="red"><strong>หยุดการเวียนว่ายตายเกิด</strong></font>อย่างไม่มีที่สิ้นสุดนั้นได้หรือไม่ คำตอบเรื่องเหล่านี้ มีอยู่ในคำสอนทางพระพุทธศาสนา<br>

<a href="https://dhamma-sutta.com/abhidhamma/chapter6.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">

  📖 อ่านต่อ...สังสารวัฎทั้ง ๓๑ ภพ

</a>

  
<hr />
<h2 id="section07">หมวดที่ ๐๗ กฎแห่งกรรม</h2>
๑. ความรู้เบื้องต้นของกรรม<br>
๒. ประเภทของกรรม<br>
     - ชนกกรรม<br>
     - อุปัตถัมภกกรรม<br>
     - อุปปีฬกกรรม<br>
     - อุปฆาตกกรรม<br>
๓. ความหนักเบาของกรรม<br>
     - ครุกกรรม<br>
     - อาสันนกรรม<br>
     - อาจิณณกรรม<br>
     - กฏัตตากรรม<br>
๔. ผลของกรรมกับการให้ผล<br>
     - ทิฏฐธัมมเวทนียกรรม<br>
     - อุปปัชชเวทนียกรรม<br>
     - อปราปริยเวทนียกรรม<br>
     - อโหสิกรรม<br>
๕. กรรมชั่ว กรรมดี<br>
     - อกุศลกรรม<br>
     - กายทุจริต ๓<br>
     - วจีทุจริต ๔<br>
     - มโนทุจริต ๓<br>
     - กามาวจรกุศลกรรม<br>
     - บุญกิริยาวัตถุ ๑๐<br>
     - รูปาวจรกุศลกรรม<br>
     - อรูปาวจรกุศลกรรม<br>
อะไรคือสิ่งที่เรียกว่ากรรม? สิ่งที่พระพุทธเจ้าตรัสเรียกว่ากรรมนั้น ตรัสหมายถึง<strong>เจตนา </strong>
    ฉะนั้นสิ่งที่เรียกว่ากรรมจึงมุ่งหมายถึงเจตนาที่กระทำ ทำดีก็เรียกว่า <strong>กุศลเจตนา</strong>
    เจตนาที่กระทำชั่ว เรียกว่า <strong>อกุศลเจตนา</strong> ซึ่งเมื่อสำเร็จเป็นกรรมแล้ว ก็เรียกว่า กุศลกรรม 
    อกุศลกรรม การกระทำต้องอาศัยเจตนาที่เกิดขึ้นภายในจิตเป็นเหตุ และเมื่อกระทำกรรมอันใดไว้ ก็จะมีผลของกรรมหรือวิบากตามมา<br>
  <<a href="https://dhamma-sutta.com/abhidhamma/chapter7.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">

  📖 อ่านต่อ...เรื่องกรรมและผลของกรรม

</a>

<hr />

<h2 id="#section08">หมวดที่ ๐๘ สมุจจยสังคหะ</h2>
๑. อกุศลสังคหะ (ธรรมที่เป็นบาปล้วนๆ)<br>
๒. มิสสกสังคหะ (ธรรมที่เป็นเหตุของการทำบุญ, ทำบาป, อพยากตะ)<br>
๓. โพธิปักขิยสังคหะ (ธรรมที่จะทําให้เข้าถึงมรรคผล)<br>
๔. สัพพสังคหะ (ธรรมที่สงเคราะห์จิต เจตสิก รูป นิพพาน)</p>เป็นการแสดงปรมัตถธรรมทั้ง ๔ คือ 
    จิต เจตสิก รูป และนิพพาน โดยจัดให้เป็นหมวดหมู่ <font size="" color="red">ธรรมใดที่เข้ากันได้ก็จัดไว้เป็นหมวดหมู่เดียวกัน</font>
    ซ<strong>ึ่งมีสภาวะธรรมทั้งหมด ๗๒ ประกา</strong>ร ต่อไปจะศึกษาหมวดธรรมใหญ่ ๔ หมวดนี้<br>
    
<<a href="https://dhamma-sutta.com/abhidhamma/chapter8.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">


  📖 อ่านต่อ...ธรรมที่เป็นปัจจัยแก่กัน

</a>

<hr />

<h2 id="section09"> หมวดที่ ๐๙ สมถกรรมฐาน</h2>
๑. ความรู้เบื้องต้นของกรรมฐาน<br>
๒. รูปฌาน อรูปฌาน<br>
๓. ประโยชน์ของสมาธิ<br>
๔. กสิณ ๑๐<br>
๕. อสุภะ ๑๐<br>
๖. อนุสสติ ๑๐<br>
๗. อัปปมัญญา ๔<br>
๘. อาหาเรปฏิกูลสัญญา ๑<br>
๙. จตุธาตุววัฏฐาน ๑<br>
๑๐. อรูปกรรมฐาน ๔<br>คำว่า<strong>กรรมฐาน</strong> หมายรวมถึงสมถะและวิปัสสนาได้ทั้ง ๒ อย่าง 
แต่ถ้าหากจะเจาะจงลงไปอย่างใดอย่างหนึ่งก็ต้องระบุให้ชัดลงไปว่า “<font size="" color="red">เจริญสมถกรรมฐาน</font>
 หรือ <font size="" color="red">เจริญวิปัสสนากรรมฐาน”</font> ถ้าบอกเพียงว่าปฏิบัติกรรมฐาน ความหมายก็จะคลุมทั้งสมถะและวิปัสสนา
 ในบทนี้ จะกล่าวถึงการเจริญสมถกรรมฐาน คือ การปฏิบัติเพื่อให้เข้าถึงซึ่งความสงบ 
พระพุทธเจ้าได้วางวิธีการฝึกกรรมฐานเพื่อให้เข้าถึงความสงบของจิตไว้อย่างแท้จริงถึง ๔๐ กรรมฐาน <br>
<<a href="https://dhamma-sutta.com/abhidhamma/chapter9.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">

  📖 อ่านต่อ...การเจริญสมถกรรมฐาน

</a>

<hr />
<h2 id="section10">หมวดที่ ๑๐ วิปัสสนากรรมฐาน</h2>
<p>๑. สติปัฏฐาน<br>
     - กายานุปัสสนาสติปัฏฐาน<br>
     - เวทนานุปัสสนาสติปัฏฐาน<br>
     - จิตตานุปัสสนาสติปัฏฐาน<br>
     - ธัมมานุปัสสนาสติปัฏฐาน<br>
๒. วิสุทธิ ๗<br>
๓. ลักษณะ ๓<br>
๔. อนุปัสสนา<br>
๕. ญาณ ๑๖<br>
ในบทสุดท้ายจะกล่าวถึงทางสายเอกที่จะทำให้บุคคลข้ามโคตรจากปุถุชนเป็นอริยะบุตตลก็ด้วยทางสายนี้ 
คือ<strong>การเจริญสติปัฏฐาน ๔ </strong>ซึ่งเป็น<font size="" color="">ข้อปฏิบัติเพื่อละสุภวิปัลลาส สุขวิปัลลาส นิจจวิปัลลาส วิปัสนาเพื่อเข้าถึงความบริสุทธิ์</font> 
ข้ามพ้นโสกะปริเทวะ ดับทุกข์ โทมนัส บรรลุเญยยธรรม แจ่มแจ้งในพระนิพพานก็ด้วยประการนี้<br>
<<a href="https://dhamma-sutta.com/abhidhamma/chapter10.html" class="readmore-button" style="
display: inline-block;
background-color: #e0c35a;
color: #222;
padding: 10px 20px;
border-radius: 8px;
text-decoration: none;
font-size: 16px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
transition: background-color 0.3s ease;

">
  📖 อ่านต่อ...การเจริญวิปัสสนากรรมฐาน

</a>
    
  </div>

  <button onclick="scrollToTop()" id="backToTopBtn" title="กลับด้านบน">⬆️</button>

  <footer style="width: 100%; text-align: center; font-size: 14px; color: #888; margin-top: 60px; padding: 20px 0;">
     <nav id="breadcrumb" style="font-size: 14px; margin-bottom: 20px;"></nav>
    จัดทำโดย <a href="https://github.com/dhamsutta/tripitaka" target="_blank">ธรรมสุตตะ</a> |
    <a href="/">หน้าแรก</a>
  </footer>

<script>
  function toggleSidebar() {
    document.getElementById('sidebar').classList.toggle('hidden');
  }

  // หด sidebar เมื่อคลิกเนื้อหาหลัก
  document.addEventListener('DOMContentLoaded', function () {
    const content = document.querySelector('.content');
    const sidebar = document.getElementById('sidebar');

    content.addEventListener('click', function () {
      if (!sidebar.classList.contains('hidden') && window.innerWidth <= 768) {
        sidebar.classList.add('hidden');
      }
    });
  });
</script>

<script>
    window.onscroll = function () {
      const btn = document.getElementById("backToTopBtn");
      btn.style.display = (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300)
        ? "block" : "none";
    };

    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    // ✅ Breadcrumb อัตโนมัติ

    const labels = {
      'tripitaka': 'หน้าแรก',
      'vinaya': 'พระวินัย',
      'sutta': 'พระสูตร',
      'abhidhamma': 'พระอภิธรรม',
      'atthakatha': 'อรรถกถา',
      'visuddhimagga': 'วิสุทธิมรรค',
      'nettippakarana': 'เนตติปกรณ์',
      'buddhadhamma': 'พุทธธรรม',
      'milindapanha': 'มิลินทปัญหา',
      'dictionary': 'คำอภิธานศัพท์',
      'pali-thai': 'พจนานุกรม บาลี-ไทย',
      'thai-eng': 'ไทย-อังกฤษ',
      'eng-thai': 'อังกฤษ-ไทย',
      'pakinnaka': 'ปกิณกะ',
      'audio': 'ฟังธรรมะออนไลน์',
      'asubha': 'ห้องปลงอสุภะ',
      'search': 'ค้นหาหัวข้อธรรมะ'
    };

    const path = location.pathname.split('/').filter(p => p && p !== 'index.html');
  let breadcrumbHTML = `<a href="/">หน้าแรก</a>`;
  let url = '';
  path.forEach((segment) => {
    const segmentKey = segment.replace('.html', '');
    url += '/' + segment;
    const label = labels[segmentKey] || decodeURIComponent(segmentKey);
    breadcrumbHTML += ' › ' + `<a href="${url}">${label}</a>`;
  });

  document.getElementById("breadcrumb").innerHTML = breadcrumbHTML;
</script>


<script>
  let dictionary = [];

  fetch('/dictionary/pali-thai.json') // ✅ อ้างจาก root
    .then(response => response.json())
    .then(data => {
      dictionary = data;
      showRandomSuggestions();
    })
    .catch(err => console.error("โหลดพจนานุกรมไม่สำเร็จ:", err));

  const searchInput = document.getElementById('dictSearch');
  const resultBox = document.getElementById('dictResults');

  searchInput.addEventListener('input', function () {
    const query = this.value.trim().toLowerCase();

    if (query.length === 0) {
      showRandomSuggestions();
      return;
    }

    const matches = dictionary.filter(entry =>
      entry.headword.toLowerCase().includes(query)
    );

    if (matches.length === 0) {
      resultBox.innerHTML = `ไม่พบคำว่า "<strong>${query}</strong>"`;
      return;
    }

    resultBox.innerHTML = matches.slice(0, 10).map(entry => {
      const link = `/tripitaka/abhidhamma/${entry.headword}.html`; // ปรับตาม path จริง
      return `<div style="margin-bottom: 0.3rem;">
                <a href="${link}" target="_blank" style="font-weight: bold; color: #0645ad; text-decoration: none;">
                  ${entry.headword}
                </a>: ${entry.content}
              </div>`;
    }).join('');
  });

  function showRandomSuggestions() {
    if (!dictionary.length) return;

    const randomSuggestions = dictionary
      .sort(() => 0.5 - Math.random())
      .slice(0, 3);

    resultBox.innerHTML = `<div style="color:#888; margin-bottom: 0.25rem;">🔎 ตัวอย่างคำศัพท์:</div>` +
      randomSuggestions.map(entry => {
        const link = `/tripitaka/abhidhamma/${entry.headword}.html`;
        return `<div style="margin-bottom: 0.3rem;">
                  <a href="${link}" target="_blank" style="font-weight: bold; color: #0645ad; text-decoration: none;">
                    ${entry.headword}
                  </a>: ${entry.content}
                </div>`;
      }).join('');
  }
</script>







  
  
</body>
</html>
