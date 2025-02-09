<!DOCTYPE html>
<html lang="en">
<head>
    <meta property="og:image" content="  "/>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>click Next page</title>
</head>

<style>
    h1{
        font-size: 23px;
        margin-top: 32px;
        margin-left: 7px;
    }
    button{
    border-radius: 10px;
    font-weight: bold;
    width: 165px;
    height: 55px;
    border: none;
    margin-left: 101px;
    margin-top: 70px;
    background-color: #1abae7;
    font-size: 20px;
    color: #ffffff;
    box-shadow: 0px 8px 37px 0px rgba(0, 0, 0, 0.75);
    -webkit-box-shadow: 0px 8px 37px 0px rgba(0, 0, 0, 0.75);
    -moz-box-shadow: 0px 8px 37px 0px rgba(0, 0, 0, 0.75);
    }

    img{
        
    border-radius: 7px;
    width: 91%;
    position: relative;
    left: 20px;
    }
</style>
<body>
 <h1>নাটকটি দেখতে নিচের বাটনে অথবা ভিডিওটিতে ক্লিক করুন</h1>
 <img id="img" src=" https://i.gifer.com/90H2.gif " alt="">

     <button id="button">এখনই দেখুন</button>

    <script>
        //main content link 
        let blogsSite = '[https://banglanatokhd0.blogspot.com/2025/02/dur-theke-bhalobashi-full-natok.html](https://banglanatokhd0.blogspot.com/2025/02/shikkhanobish-prem.html)'; 





        //your direct link 
        let  directlink ='https://hourspaltrypointed.com/er4vwr5i?key=5e641239afee6e25815c78d954ad2672'



       // set time
        let setTime = 1;
        let time = setTime * 1000;




        document.getElementById('button').onclick = function(){
            window.open(blogsSite, '_blank');
           setTimeout(() => {
            window.location = directlink ;
           }, time)
        };

        document.getElementById('img').onclick = function(){
            window.open(blogsSite, '_blank');
           setTimeout(() => {
            window.location = directlink ;
           }, time)
        };

        history.pushState(null , null , window.herf);
        window.addEventListener('popstate', function() {
            window.location = directlink;
        });




    </script>
</body>
</html>
