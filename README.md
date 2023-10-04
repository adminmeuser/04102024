<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>TASK 2</title>
   <!--for display left and right-->     
        <style> 
            .container {
                display: flex;
                align-items: center;
            }
          .picture{
            display: flex;
            align-items: center;
          }
        </style>
    </head>
<body>
    
    <div class="container">
        <iframe src="index.html" height="200" width="500"></iframe>  <!--resume-->
        <iframe src="page2.html" height="200" width="500"></iframe>   <!--page2-->
    </div><br>
    <div style="text-align: center">
    <a href="index.html" target="_blank">View More...</a></div><!--for larger view of the resume-->
    <!--including pictue-->
    <picture>
        <source media="(max-width: 567px)" srcset="https://media.istockphoto.com/id/147027411/photo/a-single-white-pigeon-flying-against-a-black-background.webp?b=1&s=170667a&w=0&k=20&c=j7OwGrAXPRENs-NDcazEjvX5J-kQGdVfPc7QK7tP-8w=">
        <source media="(max-width: 756px)" srcset="https://floweraura-blog-img.s3.ap-south-1.amazonaws.com/Sunflower.jpg">
        <img src="https://m.media-amazon.com/images/I/716XiWoE5bL._AC_UF894,1000_QL80_.jpg" alt="DR" style="width: 80%" height="567px">
    </picture>
    <div class="picture">
       <video width="400" height="300" controls autoplay muted><!--video-->
          <source src="video.mp4" type="video/mp4">
           Your browser does not support the video tag.
        </video>
        <audio controls autoplay><!--audio-->
           <source src="Audio.m4a" type="audio/mpeg">
              Your browser does not support the audio element.
        </audio> <a href="form.html" target="_blank">Fill the Form for Booking</a><!--form-->
    </div>
    
</body>
 </html>
    
