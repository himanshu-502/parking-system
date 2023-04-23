# parking-system
<html>
  <head>
    <title>Title of the document</title>
    <style>

    ul{
    float: center;
    list-style-type: none;
    }
    ul li{
    display :inline-block;
    }
    h1 {
    text-align: center;
    }
    .overlay {
    width: 100px;
    height: 100px;
    }
    .image {
    width: 100%;
    height: 19%;
    margin-bottom: 20px;
    background-image: url('image1.jpeg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    }
    .button-54 {
      font-family: "Open Sans", sans-serif;
      font-size: 16px;
      letter-spacing: 2px;
      text-decoration: none;
      text-transform: uppercase;
      color: #000;
      cursor: pointer;
      border: 3px solid;
      padding: 0.25em 0.5em;
      box-shadow: 1px 1px 0px 0px, 2px 2px 0px 0px, 3px 3px 0px 0px, 4px 4px 0px 0px, 5px 5px 0px 0px;
      position: relative;
      user-select: none;
      -webkit-user-select: none;
      touch-action: manipulation;
    }

    .button-54:active {
      box-shadow: 0px 0px 0px 0px;
      top: 5px;
      left: 5px;
    }

    @media (min-width: 768px) {
      .button-54 {
        padding: 0.25em 0.75em;
      }
      .overlay {
        width:360px;
        height:108px
      }
      .image{
        height:108px;
      }
      .search input{
        height:40px;
      }

    }
    .search input[type=text]{
        width:1000px;
        height:40px;
        border-radius:0px;
        border: none;

    }

    .search{
        float:right;
        margin:7px;

    }

    .search button{
        background-color: #e7e7e7;
        color: black;
        float: right;
        padding: 0px 0px;
        margin-right: 20px;
        font-size: 20px;
        border: none;
        cursor: pointer;
    }
    .footer {
       position: fixed;
       left: 0;
       bottom: 0;
       height:50;
       width: 100%;
       background-color: black;
       color: white;
       text-align: center;
    }
    </style>
  </head>
  <body>
    <header>
    <div class="image">
         <div style="position: absolute; height: px; top:28px; right: 0;  left: 0; ">
        <div class="search">
            <form action="#">
                <input type="text"
                    placeholder=" Search Products"
                    name="search">
                 &ensp;
                <button><input type="image" src="search_b.jpg" name="submit" width="40" height="40" alt="submit"/>
                </button>
            </form>
        </div>
    </div>
      <div class="overlay">
        <img src="locator1.jpg" alt="locatoricon" width="35%" height="100%"/>
      </div>
    </div>
    <div class="main">
        <ul>
            <li>&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; </li>
            <li><form><button class="button-54" role="button" formaction="www.google.com"> HOME </button></form></li>
            <li>&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;</li>
            <li><button class="button-54" role="button" > LOGIN </button></li>
            <li>&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;</li>
            <li><button class="button-54" role="button" > SIGNUP </button></li>
            <li>&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;</li>
            <li><button class="button-54" role="button" >ABOUT US</button></li>
            <li>&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;</li>
            <li><button class="button-54" role="button" >CONTACT US</button></li>
            <li>&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;</li>

        </ul>

    </div>
    <img src="matte.jpeg" width=100% height=100%></img>
    <div class="footer">
      <p>PSINIZO SINCE 2108 Copyright <span>&copy;</span> supportparkingcustomercare@gmail.com  Telephone- +9111002233</p>
    </div>
    </header>
  </body>
</html>
