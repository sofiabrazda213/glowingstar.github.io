<!DOCTYPE html>
<html>
    <head>
        <title>GHOUL WORLD</title>
        <link rel="icon" type="image/jpg" href="pictures/favicon.jpg">
        <style>
            .image {
                width: 150px;
                display: block;
                margin-left: auto;
                margin-right: auto;
            }
            .tabcontent {
                display: none;
                padding: 6px 12px;
                border: 1px solid #ccc;
                border-top: none;
            }
        </style>
        <link rel="styling" href="styling.css">
    </head>
    <body>
        <img class="image" src="pictures/IMG_9623.jpg">
        <div class="wrapper">
            <div class="container">
                <a href="pages/art.html"><button class ="tab_btn">art</button></a>
                <a href="pages/about.html"><button class ="tab_btn">about</button></a>
            </div>
        <div id="art" class="tabcontent">
            <h3>My Art</h3>
            <!--insert image gallery of art-->
          </div>
        <div id="about" class="tabcontent">
            <h3>About Me</h3>
            <!--insert about section-->
          </div>

        <p>This is gonna be my website</p>
        <a href="https://www.instagram.com/ghoulkween/" target="_blank">Link to my instagram</a>
    </div>
    <script>
        const tabs= document.querySelectorAll('.tab_btn');
        const all_content= document.querySelectorAll('.content');
        tabs.forEach(tab, index)
            tab.addEventListener('click', ()=>{
                tabs.forEach(tab=>{tab.classList.remove('active')});
                tab.classList.add('active');
            })
    </script>
    </body>
</html>
