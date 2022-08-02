<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SANUMOD</title>
    <link rel="shortcut icon" href="images/logo.jpg">
    <meta property="og:image" content="images/logo.jpg" />
    <meta property="og:description" content="TEAM | EX All Tools ?$x-fast" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=0.0, user-scalable=no" >
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js" integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <style>:root{--pink:#03a9f4;}*{margin:0; padding:0;    box-sizing: border-box;    font-family: Verdana, Geneva, Tahoma, sans-serif;    outline: none; border:none;    text-decoration: none;    text-transform: capitalize;    transition: .2s linear;}html{    font-size: 62.5%;    scroll-behavior: smooth;    scroll-padding-top: 6rem;    overflow-x: hidden;}section{    padding:2rem 9%;}.heading{    text-align: center;    font-size: 4rem;    color:#333;    padding:1rem;    margin:2rem 0;    background:rgba(255, 51, 153,.05);}.heading span{    color:var(--pink);}.btn{    display: inline-block;    margin-top: 1rem;    border-radius: 5rem;    background:#333;    color:#fff;    padding:.9rem 3.5rem;    cursor: pointer;    font-size: 1.7rem;}.btn:hover{    background:var(--pink);}header{    position: fixed;    top:0; left:0; right:0;    background:#fff;    padding:2rem 9%;    display: flex;    align-items: center;    justify-content: space-between;    z-index: 1000;    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);}header .logo{    font-size: 3rem;    color:#333;    font-weight: bolder;}header .logo span{    color:var(--pink);}header .navbar a{    font-size: 2rem;    padding:0 1.5rem;    color:#666;}header .navbar a:hover{    color:var(--pink);}header .icons a{    font-size: 2.5rem;    color:#333;    margin-left: 1.5rem;}header .icons a:hover{    color:var(--pink);}header #toggler{    display: none;}header .fa-bars{    font-size: 3rem;    color:#333;    border-radius: .5rem;    padding:.5rem 1.5rem;    cursor: pointer;    border:.1rem solid rgba(0,0,0,.3);    display: none;}.home{    display: flex;    align-items: center;    min-height: 100vh;    background:url(../images/home-bg.jpg) no-repeat;    background-size: cover;    background-position: center;}.home .content{    max-width: 50rem;}.home .content h3{    font-size: 6rem;    color:#333;}.home .content span{    font-size: 3.5rem;    color:var(--pink);    padding:1rem 0;    line-height: 1.5;}.home .content p{    font-size: 1.5rem;    color:#999;    padding:1rem 0;    line-height: 1.5;}.about .row{    display: flex;    align-items: center;    gap:2rem;    flex-wrap: wrap;    padding:2rem 0;    padding-bottom: 3rem;}.about .row .video-container{    flex:1 1 40rem;    position: relative;}.about .row .video-container video{    width:100%;    border:1.5rem solid #fff;    border-radius: .5rem;    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);    height: 100%;    object-fit: cover;}.about .row .video-container h3{    position: absolute;    top:50%; transform: translateY(-50%);    font-size: 3rem;    background:#fff;    width:100%;    padding:1rem 2rem;    text-align: center;    mix-blend-mode: screen;}.about .row .content{    flex:1 1 40rem;}.about .row .content h3{    font-size: 3rem;    color:#333;}.about .row .content p{    font-size: 1.5rem;    color:#999;    padding:.5rem 0;    padding-top: 1rem;    line-height: 1.5;}.icons-container{    background:#eee;    display: flex;    flex-wrap: wrap;    gap:1.5rem;    padding-top: 5rem;    padding-bottom: 5rem;}.icons-container .icons{    background:#fff;    border:.1rem solid rgba(0,0,0,.1);    padding:2rem;    display: flex;    align-items: center;    flex:1 1 25rem;}.icons-container .icons img{    height:5rem;    margin-right: 2rem;}.icons-container .icons h3{    color:#333;    padding-bottom: .5rem;    font-size: 1.5rem;}.icons-container .icons span{    color:#555;    font-size: 1.3rem;}.products .box-container{    display: flex;    flex-wrap: wrap;    gap:1.5rem;}.products .box-container .box{    flex:1 1 30rem;    box-shadow: 0 .5rem 1.5rem rgba(0,0,0,.1);    border-radius: .5rem;    border:.1rem solid rgba(0,0,0,.1);    position: relative;}.products .box-container .box .discount{	position: absolute;    top: 1rem;    left: 1rem;    padding: 0.7rem 1rem;    font-size: 12px;    color: white;    background: #00bcd4;    z-index: 5;    border-radius: 0.5rem;    font-weight: bold;	}.products .box-container .box .image{    position: relative;    text-align: center;    padding-top: 2rem;    overflow:hidden;}.products .box-container .box .image img{    height:25rem;}.products .box-container .box:hover .image img{    transform: scale(1.1);}.products .box-container .box .image .icons{    position: absolute;    bottom:-7rem; left:0; right:0;    display: flex;}.products .box-container .box:hover .image .icons{    bottom:0;}.products .box-container .box .image .icons a{    height: 5rem;    line-height: 5rem;    font-size: 2rem;    width:50%;    background:var(--pink);    color:#fff;}.products .box-container .box .image .icons .cart-btn{    border-left: .1rem solid #fff7;    border-right: .1rem solid #fff7;    width:100%;}.products .box-container .box .image .icons a:hover{    background:#333;}.products .box-container .box .content{    padding:2rem;    text-align: center;}.products .box-container .box .content h3{    font-size: 2.5rem;    color:#333;}.products .box-container .box .content .price{    font-size: 2.5rem;    color:var(--pink);    font-weight: bolder;    padding-top: 1rem;}.products .box-container .box .content .price span{    font-size: 1.5rem;    color:#999;    font-weight: lighter;    text-decoration: line-through;}.review .box-container{    display: flex;    flex-wrap: wrap;    gap:1.5rem;}.review .box-container .box{    flex:1 1 30rem;    box-shadow: 0 .5rem 1.5rem rgba(0,0,0,.1);    border-radius: .5rem;    padding:3rem 2rem;    position: relative;    border:.1rem solid rgba(0,0,0,.1);}.review .box-container .box .fa-quote-right{    position: absolute;    bottom:3rem; right:3rem;    font-size: 6rem;    color:#eee;}.review .box-container .box .stars i{    color:var(--pink);    font-size: 2rem;}.review .box-container .box p{    color:#999;    font-size: 1.5rem;    line-height: 1.5;    padding-top: 2rem;}.review .box-container .box .user{    display: flex;    align-items: center;    padding-top: 2rem;}.review .box-container .box .user img{    height:6rem;    width:6rem;    border-radius: 50%;    object-fit: cover;    margin-right: 1rem;}.review .box-container .box .user h3{    font-size: 2rem;    color:#333;}.review .box-container .box .user span{    font-size: 1.5rem;    color:#999;}.contact .row{    display: flex;    flex-wrap: wrap-reverse;    gap:1.5rem;    align-items: center;}.contact .row form{    flex:1 1 40rem;    padding:2rem 2.5rem;    box-shadow: 0 .5rem 1.5rem rgba(0,0,0,.1);    border:.1rem solid rgba(0,0,0,.1);    background: #fff;    border-radius: .5rem;}.contact .row .image{    flex:1 1 40rem;}.contact .row .image img{    width: 100%;}.contact .row form .box{    padding:1rem;    font-size: 1.7rem;    color:#333;    text-transform: none;    border:.1rem solid rgba(0,0,0,.1);    border-radius: .5rem;    margin:.7rem 0;    width: 100%;}.contact .row form .box:focus{    border-color: var(--pink);}.contact .row form textarea{    height: 15rem;    resize: none;}.footer .box-container{    display: flex;    flex-wrap: wrap;    gap:1.5rem;}.footer .box-container .box{    flex:1 1 25rem;}.footer .box-container .box h3{    color:#333;    font-size: 2.5rem;    padding:1rem 0;}.footer .box-container .box a{    display: block;    color:#666;    font-size: 1.5rem;    padding:1rem 0;}.footer .box-container .box a:hover{    color:var(--pink);    text-decoration: underline;}.footer .box-container .box  img{    margin-top: 1rem;}.footer .credit{    text-align: center;    padding:1.5rem;    margin-top: 1.5rem;    padding-top: 2.5rem;    font-size: 2rem;    color:#333;    border-top: .1rem solid rgba(0,0,0,.1);    padding-bottom: 9rem;}.footer .credit span{    color:var(--pink);}/* media queries  */@media (max-width:991px){    html{        font-size: 55%;    }    header{        padding:2rem;    }    section{        padding:2rem;    }    .home{        background-position: left;    }}    header .fa-bars{        display: block; }    header .navbar{position: fixed;width: 100%;overflow: scroll;height: calc(100% - 72px);background: #024070;left: -100%;text-align: center;transition: all 1s;z-index: 9999;top: 72px;}    header #toggler:checked ~ .navbar{ left: 0;}    header .navbar a{        margin:1.5rem;        padding:1.5rem;        background:#fff;        border:.1rem solid rgba(0,0,0,.1);        display: block;    }    .home .content h3{        font-size: 5rem;    }    .home .content span{        font-size: 2.5rem;    }    .icons-container .icons h3{        font-size: 2rem;    }    .icons-container .icons span{        font-size: 1.7rem;    }}@media (max-width:450px){    html{        font-size: 50%;    }    .heading{        font-size: 3rem;    }</style></head>
<body>
<header>
    <input type="checkbox" name="" id="toggler">
    <label for="toggler" class="fas fa-bars"></label>
    <a href="#" class="logo">SANUMOD<span> All Tools</span></a>
    <nav class="navbar">
        <a href="#EX_BOMBER">EX BOMBER</a>
        <a href="#EX_Bomber">EX Bomber</a>
        <a href="#EX_Cam">EX Cam</a>
        <a href="#Ex_Deface_Creator">Ex Deface Creator</a>
        <a href="#EX_Encryptor">EX Encryptor</a>
        
</header>
<div style="margin-bottom:60px;"></div>


<section class="products" id="EX_BOMBER">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">5.5 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/XPZlxYja#y8mCpqoykQZjeTKgqHnV7LtQgl1nStj03txPvay3drc" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>SANUMOD 1.1</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="EX_Bomber">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">Website</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="http://teamex69.uneax.com/" class="cart-btn">Visit Now</a>
                </div>
            </div>
            <div class="content">
                <h3>SANUMOD</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="EX_Cam">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">4.2 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/XPZlxYja#y8mCpqoykQZjeTKgqHnV7LtQgl1nStj03txPvay3drc" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX Cam 2.0</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="Ex_Deface_Creator">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">6.2 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/efpTQK7a#GVnvbuzG9XHI6V_MyciTcc3lcEvIyByu0eEZlcBjuTc" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>Ex Deface Creator</h3>
            </div>
        </div>
    </div>
</section>
    

<section class="products" id="EX_Encryptor">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">Website</span>
            <div class="image">
                <img src="./images/encrypt.png" alt="">
                <div class="icons">
                    <a target="_blank" href="http://ex-encryptor.eu5.org/" class="cart-btn">Visit Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX Encryptor</h3>
            </div>
        </div>
    </div>
</section>
    

<section class="products" id="EX_Follow">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">Website</span>
            <div class="image">
                <img src="./images/follow.png" alt="">
                <div class="icons">
                    <a target="_blank" href="http://ex-follow.xyz/" class="cart-btn">Visit Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX Follow</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="EX_Get_Source_Code">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">437 KB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/mT4RWS4C#l9CvmXGRnuqPaH8nGAzqCKaN9ORpDWbnX7qpX-NKBbs" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX Get Source Code</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="EX_JSO_Converter">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">Website</span>
            <div class="image">
                <img src="./images/jso.png" alt="">
                <div class="icons">
                    <a target="_blank" href="http://ex-jso.ueuo.com/" class="cart-btn">Visit Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX JSO Converter</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="Ex_Link_Shortner">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">1.2 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/6fQWGYLZ#tTOq1WjzHbXdFuJAgORp2jkjagBIOpMXCO82bHS3bBM" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>Ex Link Shortner</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="EX_Mail_Sender">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">10.8 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank"href="https://mega.nz/file/yOh2maiQ#h4fojOTJ7LIqvoH9KHT-VJBcYv3QxjANtqZhvd3Y628" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX Mail Sender 1.0</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="EX_PISHING">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">5.4 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/qWRRADxT#GZ-hZIP-X5xNjKii9FMmfdFIzaDvkpueCDbhOICECJE" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>EX PISHING 1.0</h3>
            </div>
        </div>
    </div>
</section>

 <section class="products" id="Ex_Social_Video_Downloader">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">9.2 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/PHRDXIaL#beVyTcG-unMXDvELSpeoDBJcuDb4hxscsvb6z16Ofrw" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>Ex Social Video Downloader</h3>
            </div>
        </div>
    </div>
</section>
<section class="products" id="Ex_Social_Video_Downloader">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">9.2 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/PHRDXIaL#beVyTcG-unMXDvELSpeoDBJcuDb4hxscsvb6z16Ofrw" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>User Imo Phishing</h3>
            </div>
        </div>
    </div>
</section>
<section class="products" id="Ex_Social_Video_Downloader">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">9.2 MB</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="https://mega.nz/file/PHRDXIaL#beVyTcG-unMXDvELSpeoDBJcuDb4hxscsvb6z16Ofrw" class="cart-btn">Download Now</a>
                </div>
            </div>
            <div class="content">
                <h3>Imo Admin App</h3>
            </div>
        </div>
    </div>
</section>

<section class="products" id="Ex_URL_Shortener">
    <div style="margin-top:20px;"></div>
    <div class="box-container">
        <div class="box">
            <span class="discount">Website</span>
            <div class="image">
                <img src="./images/logo.jpg" alt="">
                <div class="icons">
                    <a target="_blank" href="http://www.ex-link.tk/" class="cart-btn">Visit Now</a>
                </div>
            </div>
            <div class="content">
                <h3>Ex URL Shortener</h3>
            </div>
        </div>
    </div>
</section>

<section class="footer">
    <div class="box-container">
        <div class="box">
            <h3>quick access</h3>
            <a href="index.php">Home</a>
        </div>
    </div>
    <div class="box-container">
        <div class="box">
            <h3>quick access apk</h3>
            <a href="#EX_BOMBER">EX BOMBER</a>
            <a href="#EX_Cam">EX Cam</a>
            <a href="#Ex_Deface_Creator">Ex Deface Creator</a>
            <a href="#EX_Get_Source_Code">EX Get Source Code</a>
            <a href="#Ex_Link_Shortner">Ex Link Shortner</a>
            <a href="#EX_Mail_Sender">EX Mail Sender</a>
            <a href="#EX_PISHING">EX PISHING</a>
            <a href="#Ex_Social_Video_Downloader">Ex Social Video Downloader</a>
            </div>
    </div>
    <div class="box-container">
        <div class="box">
            <h3>quick access website</h3>
            <a href="#EX_Bomber">EX Bomber</a>
            <a href="#EX_Encryptor">EX Encryptor</a>
            <a href="#EX_Follow">EX Follow</a>
            <a href="#EX_JSO_Converter">EX JSO Converter</a>
            <a href="#Ex_URL_Shortener">Ex URL Shortener</a>
        </div>
    </div>

    <div class="credit"> Created by <span> Team Ex </span> | all rights reserved </div>
</section>    
<script>
$(document).on("click",".navbar a", function(){
    document.getElementById('toggler').click();
});
</script>
</body>
</html>
