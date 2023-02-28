# Masha

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
  <div class="container">
    <div class="logo"> 
      <div class="logo-left"> 
        <div class="logo-left__up">
          <a class="logo_1" href="#"> <img src="/logo-1.png" alt="logo"/></a>
          <div class="text">
            <img src="/R.png" alt="R">
            <h1 class="logo-header">ракурс</h1>
            <p class="logo-text-1">ясность цели</p>
          </div>
        </div>
        <p class="logo-text-2">ООО "Ракурс", 198095, РФ, Санкт-Петербург, Химический пер. 1, к. 2</p>
      </div>
      <div class="info-user">
        <h2 class="info-user__name">ЕРОШЕНКО СЕРГЕЙ</h2>
        <p class="info-user__post">Старший менеджер по продажам</p>
        <ul class="info-user_list">
          <li class="info-user_item">+7 (812) 655-07-68, доб. 130</li>
          <li class="info-user_item">eroshenko@rakurs.com</li>
          <li class="info-user_item">www.rakurs.su</li>
        </ul>
      </div>
    </div>
  
    <div class="footer">
      <ul class="footer-list">
        <li class="footer-item"><a class="logo_2" href="https://www.rakurs.su/producers/invt/?clear_cache=Y"> <img src="/logo-2.webp" alt="logo"/></a></li>
        <li class="footer-item"><a class="logo_3" href="https://www.rakurs.su/producers/schneiderelectric/?clear_cache=Y"> <img src="/logo-3.gif" alt="logo"/></a></li>
        <li class="footer-item"><a class="logo_4" href="https://www.rakurs.su/producers/omron/?clear_cache=Y"> <img src="/logo-4.webp" alt="logo"/></a></li>
        <li class="footer-item"><a class="logo_5" href="https://www.rakurs.su/producers/hikrobot/?clear_cache=Y"> <img src="/logo-5.webp" alt="logo"/></a></li>
        <li class="footer-item"><a class="logo_6" href="https://www.hcfa.com.cn/"> <img src="/logo-6.png" alt="logo"/></a></li>
        <li class="footer-item"><a class="logo_7" href="https://www.rakurs.su/producers/akusense/"> <img src="/logo-7.png" alt="logo"/></a></li>
      </ul>
    </div>

  </div>
  
  
  
  
  
  
  
  * {
    -webkit-box-sizing: border-box;
            box-sizing: border-box;
  }
  
  html {
    font-family: "Montserrat", sans-serif;
  }
  
  body {
    background-color: #FFFFFF;
    max-width: 680px;
    max-height: 270px;
  }
  
  a {
    text-decoration: none;
  }
  
  ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  img {
    max-width: 100%;
  }

.container {
    padding: 20px;
}

.logo {
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid rgba(31, 32, 65, 0.25);
}

.logo-left {
    display: flex;
    flex-direction: column;
    max-width: 350px;
}

.logo-left__up {
    display: flex;
    flex-direction: row;
}

.logo_1 {
    max-width: 70px;
}

.text {
    margin-left: 20px;
}

.logo-header {
  margin-top: 0;
  margin-bottom: 15px;
  font-size: 60px;
  font-weight: 500;
  line-height: 50px;
  color: #4a4848;
}

.logo-text-1 {
  margin: 0;
  font-size: 20px;
  font-weight: 400;
  color: #626262;
}

.logo-text-2 {
    margin-top: 10px;
    font-size: 14px;
    font-weight: 400;
    color: #626262;
}

.footer-list {
    display: flex;
    justify-content: flex-start;
}

.footer-item {
    max-width: 70px;
}

.info-user__name {
    margin-top: 32px;
    margin-bottom: 0;
    font-size: 19px;
    font-weight: 800;
    color: #0b7bd1;
}

.info-user__post {
    margin-top: 10px;
}

.footer {
    margin-top: 20px;
}

.footer-list {
    display: flex;
    justify-content: space-between;
}
  
