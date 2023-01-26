# Prac-2
Music Store Page
<html>
<head>
<style>
    body{
    background-image: url('music.jpg');
    background-repeat:no-repeat;
    background-size: cover;
    }
    .dropdown {
    float: left;
    overflow: hidden;
    padding-top:0px ;
    }

    .dropdown .dropbtn {
    font-size: 20px;  
    border: none;
    outline: none;
    color: white;
    padding: 20px 20px;
    background-color: black;
    font-family :'Times New Roman', Times, serif;
    margin: 0px;
    top:0px;
    text-align: center;

    }

    .dropdown-content {
    display: none;
    position: absolute;
    background-color: white;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
    }
    .dropdown-content a {
    float: none;
    color: black;
    padding: 15px 15px;
    text-decoration: none;
    display: block;
    text-align: left;
    }

    .dropdown-content a:hover {
    background-color: hotpink;
    }

    .dropdown:hover .dropdown-content {
    display: block;

    }
    h1{
    position: absolute;
    bottom:20%;
    right: 40%;
    left: 40%;
    bottom:30%;
    color:hotpink;
    font-size: 60px;
    }
    p{
    position: absolute;
    font-size:25px;
    top:0;
    left: 45%;
    color: hotpink;
    word-spacing: 2px;
    }
    footer {
    position: relative;
    font-size: 20px;
    color: white;
    padding: 5px;
    width: 100%;
    position:absolute;
    bottom:0;
    right: 40%;
    left: 30%;
    text-align: center;
    list-style-type: none;
    }
</style>
<body>
    <div class="dropdown">
    <button class="dropbtn">Genre</button>
    <div class="dropdown-content">
    <a href="https://wynk.in/music/playlist/100-greatest-pop-songs/bb_1520945725492">Pop</a>
    <a href="https://wynk.in/music/playlist/rock-on-bollywood/bb_1473845503525">Rock</a>
    <a href="https://gaana.com/playlist/gaana-dj-non-classical">Classical</a>
    <a href="https://wynk.in/music/package/rap-superhits/bb_1443091666299">Rap</a>
    <a href="https://wynk.in/music/playlist/bollywood-style-jazz/bb_1426749379594">Jazz</a>
    </div>
    </div>

    <div class="dropdown">
    <button class="dropbtn">Year</button>
    <div class="dropdown-content">
    <a href="https://wynk.in/music/playlist/popular-hits-2022-hindi/amsta_6eye15481669119335390">2022</a>
    <a href="https://wynk.in/music/playlist/popular-hits-2021-hindi/bb_1466066302448">2021</a>
    <a href="https://wynk.in/music/playlist/popular-hits-2020-hindi/amsta_xfug71631607674751138">2020</a>
    <a href="https://wynk.in/music/playlist/party-hits-2019-hindi/bb_1480406311408">2019</a>
    <a href="https://wynk.in/music/playlist/best-of-2018-bollywood/bb_1545028087238">2018</a>
    </div>
    </div>

    <div class="dropdown">
    <button class="dropbtn">Singer</button>
    <div class="dropdown-content">
    <a href="https://www.jiosaavn.com/artist/arijit-singh-songs/LlRWpHzy3Hk_">Arijit Singh</a>
    <a href="https://www.jiosaavn.com/artist/badshah-songs/d4OwAaEcnD0_">Badshah</a>
    <a href="https://www.jiosaavn.com/artist/neha-kakkar-songs/EkEBV7JAU-I_">Neha Kakkar</a>
    <a href="https://www.jiosaavn.com/artist/jubin-nautiyal-songs/uGdfg6zGf4s_">Jubin Noutiyal</a>
    <a href="https://www.jiosaavn.com/artist/king-songs/axyoun05Pkg_">King</a>
    </div>
    </div>

    <div class="dropdown">
    <button class="dropbtn">Albums</button>
    <div class="dropdown-content">
    <a href="https://www.jiosaavn.com/search/album/best%20albums">Best Albums</a>
    </div>
    </div>

    <div class="dropdown">
    <button class="dropbtn">Subscription</button>
    <div class="dropdown-content">
    <a href="pay.html">Weekly</a>
    <a href="pay.html">Monthly</a>
    <a href="pay.html">Yearly</a>
    </div>
    </div>

    <h1>My Sounds</h1>
    <p>Music is a powerful force. It can bring people together, help us express ourselves, and provide a soundtrack to our lives.
    Our Music website provides a platform for exploring all kinds of music, discovering new tunes, and connecting with other music fans. 
    We provide a comprehensive database of music information, including artist bios, album reviews, and streaming music, as well as a 
    wide range of tools to help you find the perfect track. Our website also offers streaming radio, music videos, and live events. 
    Join us and discover the power of music.</p>
    <footer>
    <div class="container">
    <div class="row">
    <div class="col-md-3">
    <h2>Contact Us</h2>
    <ul>
    <li>Phone: +91 8888888888</li>
    <li>Email: mysounds@gmail.com</li>
    </ul>
    </div>
    </div>
    </div>
    </footer>
</body>
</head>
</html>
