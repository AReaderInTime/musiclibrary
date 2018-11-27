# musiclibrary
my music library website for my independent research class
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Final for Independent Research</title>
        <style>
            #book-pic {
                border: 1px solid blue;
                width: 100px;
            }
            
            #book-text { 
                font-family: Monospace;
                color:rgb(17, 34, 222);
            } 
            body {
                background-color: rgb(179,179,179);
            }
            
            #genres {
                font-family: Monospace;
                color:rgb(102, 12, 102);
            }
            
        </style>
    </head>
    <body>
    
        <img id="book-pic" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Record-Album-02.jpg/220px-Record-Album-02.jpg">
        
        <h1 id="book-text"> Music Library! </h1>
        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
        
     <ul> 
         
         <li> <a href= "#songs-of-year"> View the Best Songs of 2018 </a>  </li> 
         <li> <a href = "#genres"> Browse Genres </a> </li> 
         <li> <a href = "#discover"> Discover New Music by Listening to Spotify Playlists</a> </li> 
     </ul>
     
     <h2 id = "songs-of-year"> Best Songs of 2018</h2>
     <ol> 
         <li> thank u next by Ariana Grande </li> 
         <li> The Middle by Maren Morris </li>
         <li> God's Plan by Drake </li> 
         <li> One Kiss by Dua Lipa </li> 
         <li> Better Now by Post Malone </li> 
         <li> Back to You by Selena Gomez </li> 
         <li> Natural by Imagine Dragons </li> 
         <li> God is a woman by Ariana Grande </li> 
         <li> Youngblood by 5 Seconds of Summer </li> 
         <li> 3:15 by Bazzi </li> 
         
     </ol>
     <img src = "https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwip4e_K0vXeAhW0IzQIHbEDDJkQjRx6BAgBEAU&url=https%3A%2F%2Fgifer.com%2Fen%2F7d20&psig=AOvVaw3lVCWuH0mgaEcIHchWSs_7&ust=1543444911363754">  
     
       <h2 id = "genres"> Genres </h2> 
       
       <h3> Classical </h3>
       <h3> Country </h3>
       <h3> Electronic </h3>
       <h3> Indie / Alternative </h3>
       <h3> Jazz</h3>
       <h3> K - Pop</h3>
       <h3> Pop </h3>
       <h3> R & B </h3>
       <h3> Rock </h3>
       <h3> Soul / Blues </h3>
     
       <h2 id = "discover">  Playlists </h2>
        <p> Follow the links below to discover great music playlists for each genre.</p> 
        
         <h4> <a href = "https://www.youtube.com/watch?v=w3HCPVMtd8M"> Classical </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=J2hkM6G1bDY">Country Music  </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=ZYmTeUAOStA"> Electronic</a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=mmbroK0o2d0"> Indie / Alternative </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=kUM7ZvE9deI"> Jazz </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=6xinJn6LuxM"> K - Pop </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=9UY6P75vMmA"> Pop </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=MC6YLqio-bI&list=RDGMEMb2Vctm4zQjEID_BdYM0vuQ&start_radio=1"> R & B</a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=0I647GU3Jsc&list=PL3oW2tjiIxvQWubWyTI8PF80gV6Kpk6Rr">Rock </a></h4>
        <h4> <a href = "https://www.youtube.com/watch?v=sbDRos0P1xE"> Soul / Blues </a></h4>
       
        
       
        <script>
      
        $("#book-pic").animate ({
              width: "370px",
            marginLeft: "30px",
            borderWidth: "10px"
        }, 1500);
        
        $("#book-text").animate({
           marginLeft: "100px",
           fontSize: "3em"
        });
        
        $("#genres").animate({
           marginLeft: "100px",
           fontSize: "2em",
        });
        
          
        </script>
        
    </body>
</html>
