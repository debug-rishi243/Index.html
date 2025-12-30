# Index.html
This is my first html project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS card Design</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Poppins:wght@300&display=swap');
        *{
            margin: 0px;
            padding: 0px;
        }
        body {
            background-color: gray;
            padding: 45px;
            display: flex;
        }

        .card {
            background-color: white;
            width: 205px;
            height: 350px;
            border: 2px solid gray;
            border-radius: 10px;
            margin: 20px;
        }

        .image{
            /* padding: 5px; */
            margin: 5px;
        }

        .image img{
            border-radius: 10px;
            /* margin:  */
            /* background-color: aquamarine; */
        }

        .capsules span{
            /* display: flex; */
            border: 1px solid gray;
            border-radius: 12px;
            /* outline: 1px solid gray; */
            /* outline-offset: 2px; */
            margin: 6px;
            padding: 0px 4px;
            /* color:aqua */
            /* background-color:beige; */
            font-size: 12px;
            font-family: 'Baloo Bhai 2', sans-serif;
        }
        
        .content{
            padding: 5px;
            font-family: 'Poppins', sans-serif;
        }

        .content p{
            font-size: 12px;
            /* text-align:justify */
        }

        .content h2{
            font-size: 24px;
        }

        .press button{
            border-radius: 16px;
            border: 2px solid gray;
            padding: 7px 10px;
            margin: 8px auto 0px;
            display: block;
            font-size: 11px;
            cursor: pointer;
        }
        .button{
            text-align: center;
        }

        .press button:hover{
            background-color: rgb(194, 225, 246);
            color: rgb(10, 136, 214);
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="image">
            <img width="195" src="https://images.pexels.com/photos/1133957/pexels-photo-1133957.jpeg" alt="">
        </div>
        
        <div class="capsules">
            <span> Nature </span>
            <span> Bird </span>
        </div>

        <div class="content">
            <h2>Nature</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis eveniet,
                 nihil laboriosam maiores, dolore fuga temporibus animi cumque?</p>
        </div>

        <div class="press">
            <button>
                Read more
            </button>
        </div>
    </div>

    <div class="card">
        <div class="image">
            <img width="195" height="130" src="https://images.pexels.com/photos/1576657/pexels-photo-1576657.jpeg" alt="">
        </div>
        
        <div class="capsules">
            <span> Nature </span>
            <span> Lake </span>
        </div>

        <div class="content">
            <h2>Vibing</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis eveniet,
                 nihil laboriosam maiores, dolore fuga temporibus animi cumque?</p>
        </div>

        <div class="press">
            <button>
                Read more
            </button>
        </div>
    </div>

    <div class="card">
        <div class="image">
            <img width="195" src="https://images.pexels.com/photos/19566202/pexels-photo-19566202.jpeg" alt="">
        </div>
        
        <div class="capsules">
            <span> Nature </span>
            <span> Night </span>
        </div>

        <div class="content">
            <h2>God's Gift</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis eveniet,
                 nihil laboriosam maiores, dolore fuga temporibus animi cumque?</p>
        </div>

        <div class="press">
            <button>
                Read more
            </button>
        </div>
    </div>
</body>

</html>
