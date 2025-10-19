# RafiP5
Tugas - Pemrograman web I

<html>
    <head>
        <title>Contoh Hyperlink</title>
    </head>
    <body>

        <pre>
<hr color="blue" size="3" width="50%" align="left"><font size="4" color="red">
<a href="#home">Home</a>    |   <a href="https://www.chungiyoo.com/">Profil</a>    |   <a href="About.html">About</a>  |  <a href="https://www.freepik.com/search?ai=excluded&format=search&last_filter=query&last_value=art&query=art&type=photo">Gallery</a>   |  <a href="mailto:Contoh@gmail.com">Kontak</a></font> <br> 
<hr color="blue" size="3" width="50%" align="left">

    <embed src="E:\rafi\Rafi\Pertemuan 5\Musix.mp3" width="250" height="50">
        <a name="Home"></a>
            <font size="3">Assalamualaikum Wr. Wb.
Apakabar semua. Salam kenal ini adalah web perdanaku. Web ini berisi informasi tentang kegemaranku.
semoga web ini dapar menginspirasi Anda pada waktu liburan. <a href="https://www.google.com/">google</a>
silakan hubungi saya jika ada yang ingin Anda diskusikan <a href="https://workspace.google.com/intl/en-US/gmail/">Email</a>
            </font>
    </pre>
        <div style="text-align:center">
            <button onclick="tekanPause()">Play/Pause</button>
            <button onclick="menjadiBig()">Big</button>
            <button onclick="menjadiSmall()">Small</button>
            <button onclick="menjadiNormal()">Normal</button>
            <br><br>
                <video id="videoku" width="430">
                <source src="E:\rafi\Rafi\Pertemuan 5\trailer.mp4" type="video/mp4">
Browser anda tidak support video HTML 5. </video>
        </div>
    <script>
        var VideoAku = document.getElementById("videoku");
            function tekanPause() {if (VideoAku.paused) VideoAku.play(); else VideoAku.pause(); }
            function menjadiBig() { VideoAku.width = 720;} function menjadiSmall() { VideoAku.width = 320;}
            function menjadiNormal() { VideoAku.width = 555;}
    </script>
        
    </body>
</html>
