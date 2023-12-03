 <html>
    <head>
        <link rel="stylesheet" href="./new.css">
        <title>web designer</title>
    </head>
    <body>
        <div class="main">
            <div class="navbar">
                <div class="icon">
                    <h2 class="logo">mohamad</h2>
                </div>
                <div class="menu">
                    <ul>
                        <li><a href="#">home</a></li>
                        <li><a href="#">about</a></li>
                        <li><a href="#">service</a></li>
                        <li><a href="#">design</a></li>
                        <li><a href="#">contact</a></li>
                    </ul>
                </div>
                <div class="search">
                    <input class="srch" type="search" name="" placeholder="type to text">
                    <a href="#"> <button class="btn">search</button></a>
                </div>

            </div>
            <div class="content">
                <h1> web design & <br><span>development</span> <br>course</h1>
                <p class="par">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Numquam facerebr
                     laborum accusantium,<p> harum provident aperiam autem neque reprehenderit praesentium ut, perferendis <br>ratione cumque eius molestiae et nostrum aliquam tempora. Ab.</p>

                     <button class="cn"><a href="#">JOIN US</a></button>

                     <div class="form">
                        <h2>login Here</h2>
                        <input type="email" name="email" placeholder="Enter email here">
                        <input type="password" name="" placeholder="Enter password here">
                        <button class="btnn"><a href="#">login</a></button>

                        <p class="link">Don't have an account<br>
                        <a href="#">sign up</a> here</a></p>
                        <p class="liw">log in with</p>
                        
                        <div class="icon">
                            <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                        </div>
                        
                        </div>

                    </div>     
                       </div>
                   </div>  
           </div>
        </div>
        <script src="./new.js"></script>   
    </body>
    </html>
   *{
    margin: 0;
    padding: 0;

}
.main{
    width: 100%;
    background: linear-gradient(to top,rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%), url(./stock-photo-a-computer-programmer-or-hacker-prints-a-code-on-a-laptop-keyboard-to-break-into-a-secret-1166453734.jpg);
    background-position: center;
    background-size: cover;
    height: 109vh;
}
.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}
.icon{
    width: 200px;
    float: left;
    height: 70px;

}
.logo{
    color:#ff7200;
    font-size: 35px;
    font-family: arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
}
.menu{
    width: 400px;
    float: left;
    height: 70px;
}
ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}
ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}
ul li a{
    text-decoration: none;
    color: #fff;
    font-family: arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}
ul li a:hover{
    color: #ff7200;

}
.search{
    width: 330px;
    float: left;
    margin-left: 270px;

}
.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
.btn:focus{
    outline: none;

}
.srch:focus{
    outline: none;
}
.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: #fff;
    position: relative;

}
.content .par{
 padding-left: 20px;
 padding-bottom: 25px;
 font-family: arial;
 letter-spacing: 1.2px;
 line-height: 30px;   
}
.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;
}
.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;   


}
.content .cn a{
    text-decoration: none;
    color: #000;
    transition: .3s ease;
}
.cn:hover{
    background-color: #fff;
}
.content span{
 color: #ff7200;
 font-size: 60px;   
}
.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    border-radius: 10px;
    padding: 25px;
}
.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #ff7200;
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;

}
.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}
.form input:focus{
    outline: none;
}
::placeholder{
    color: #fff;
    font-family: arial;
}
.btnn{
    width: 240px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;
}
.btnn:hover{
    background: #fff;
    color: #ff7200;
}
.btnn a{
    text-decoration: none;
    color: #000;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: #ff7200;
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
 
    
 
