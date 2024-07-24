<!DOCTYPE html>
<html lang="ja">
<head>
    <title>島田樂々/Lara Shimada</title>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="home.css" media="screen and (min-width: 930px)">
    <link rel="stylesheet" type="text/css" href="homephone.css" media="screen and (max-width: 929px)">
    <script type="text/javascript" src="jquery-3.3.1.js"></script>
    <script type="text/javascript" src="main.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
    <div class="pc">
        <div class="maruu">
            <a class="other">LaraShimada</a>
        </div>
    </div>
    <div class="mains">
        <div class="rak">
            <div class="shu"></div>
            <img src="img/logo.png" width="70px">
        </div>
        <div id="wrap">
            <div class="layer" data-depth="0.5">
                <div class="pc">
                    <div class="hebi">
                        <img src="img/hebi.png">
                        <img src="img/hebi2.png">
                    </div>
                </div>
                <div class="sm">
                    <div class="hebism">
                        <div class="huwa">
                            <img src="img/hebism.png">
                        </div>
                        <div class="maru"></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="menu">
            <div class="about">
                <a href='/about'>about</a>
            </div>
            <div class="artwork">
                <a href='/movie'>artwork</a>
            </div>
            <div class="contact">
                <a href='/contact'>contact</a>
            </div>
        </div>
    </div>
    <script>
        var scene = document.getElementById('wrap');
        var parallax = new Parallax(scene);
    </script>
</body>
</html>
