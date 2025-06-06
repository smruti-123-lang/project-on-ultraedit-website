# project-on-ultraedit-website
I created a responsive front-end clone of the UltraEdit website using HTML, CSS, and JavaScript. This project replicates the layout, design, and core sections of the official UltraEdit homepage, including the navigation bar, download section, product highlights, and footer.


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <fav class="container">
        <li class="image"><img src="Background-2 (1).png" style="height: 57px ;"></li>
        <li class="item item1">Products

        </li>
        <li class="item">For Business</li>
        <li class="item">Resources</li>
        <li class="item">Academic Licensing</li>
        <li class="item">Our Company</li>
        <li class="item">English</li>
    </fav>

    <div class="mainbox">
        <p> Download 
        <b> UltraEdit </b>
        for Windows</p>
        <img src="Reviews.png">
    </div>
    <div class="box">
        Download and try UltraEdit before you buy it! This download includes the full Windows version of the text
        editor.
    </div>

    <div class="main">
        download mac or linux version
    </div>
    <div class="languages">
        <div class="English">
            <h2>English</h2>

            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>Deutsch</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>Italiano</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>Español</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>Português brasileiro</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>français</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>日本</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>한국어</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>华语</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
        <div class="English">
            <h2>華語</h2>
            <h5>English</h5>
            <div class="icon"><a href="c:\ue_english_64.exe">Download 64-bit</a></div>
            <h6>SHA256</h6>
            <h9>8A1477125636ABE0E0D540F52AB7F6C99A5F1E37BBA5AEC8EFABE53D633231B7</h9>
        </div>
    </div>


</body>

</html>





CSS CODE





body {
     padding: 5px;
 }

 * {
     margin: 0;
     padding: 0;
 }

 .container {
     list-style: none;
     /* width: 00vw; */
     height: fit-content;
     display: flex;
     gap: 2px 1px;
     justify-content: space-around;
     /* float: left; */
 }

 .item {
     padding: 35px;
     font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
 }

 .image img {
     list-style: none;
     padding-left: 45px;
     padding-top: 10px;
 }

 .item1 {
     padding-left: 139px;
 }

 p {
     font: weight 100px;
     ;
     padding: 8px;
     font-size: 46px;
     font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
 }

 .mainbox :nth-child(2) {
     font-size: 46px;

     font-weight: 700;
     font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
 }

 .mainbox {
     margin-left: 180px;
     width: 70vw;
     display: flex;
     align-items: center;
     padding-top: 50px;
 }

 .box {
     font-size: 25px;
     padding-bottom: 34px;
     padding-top: 24px;
     word-spacing: 4px;
     text-align: center;
     padding-left: 93px;
     padding-right: 93px;
     font-family: "Poppins", sans-serif;
     font-weight: 200;
     font-style: normal;

     font-weight: lighter;
 }

 .main {
     margin-bottom: 29px;
     text-transform: uppercase;
     background-color: rgb(111, 214, 232);
     margin-left: 450px;
     margin-right: 450px;
     text-align: center;
     padding: 14px 1px 14px 1px;
     color: aliceblue;
     border-radius: 7px;
     font-family: "Poppins", sans-serif;
     ;
     cursor: pointer;
     font-weight: 600;
 }

 .main:hover {
     background-color: rgb(111, 196, 211);
 }

 .languages {
     height: 550px;
     justify-self: center;
     border-radius: 9px;
     display: grid;
     gap: 12px;
     padding: 12px;
     grid-template-columns: 1fr 1fr 1fr;
     grid-template-rows: 1fr 1fr 1fr 1fr;
 }

 .English {
     display: grid;
     gap: 12px;
     /* margin: 16px; */
     padding: 7px;
     background-color: rgb(243, 239, 239);
     /* border: 2px solid pink; */
     border-radius: 9px;
     align-content: space-around;
     text-align: center;

 }

 .icon {
     margin-left: 45px;
     margin-right: 45px;
     padding: 8px;
     text-decoration: none;
     border-radius: 6px;
     background-color: #5cb85c;
     cursor: pointer;
 }

 .icon :hover {
     background-color: #87ca87;
 }

 h2 {
     text-transform: capitalize;
 }

 a {
     color: #fff;
     text-decoration: none;
     font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
     cursor: pointer;
 }



 h9 {
     font-size: xx-small;
 }
 @media screen and (max-width: 1155px) {
    .languages {
        grid-template-columns: 1fr;   /* stack items vertically */
        background-color: aqua;       /* just for testing */
        gap: 12px;
    }}
