# Thanh-Tam
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
      
        body {
            background: url('https://scontent.fsgn5-9.fna.fbcdn.net/v/t39.30808-6/394664024_767699288495177_5596661602949269172_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_ohc=CLmMbY_eDBwAX-heYru&_nc_ht=scontent.fsgn5-9.fna&oh=00_AfAEk5zCz-OzuAJEjJh3_OZIeCLMU9pKMac5Qn8zG_w0Yg&oe=6556B07A');
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: 100% 100%;
            background-attachment: fixed;
            height: 100vh;
            width: 100vw;
            font-family: 'Roboto', sans-serif;
            color: white;
        }

        #logo {
            width: 150px;
            margin-bottom: 10px;
        }

        #avatar {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .left-column {
            width: 300px;
            display: flex;
            flex-direction: column;
            align-items: center;
            border-right: 1px solid rgba(255, 255, 255, 0.2);
            padding-right: 30px;
        }

        .right-column {
            width: 470px;
            margin-left: 30px;
        }

        .card {
            background: rgba(0, 0, 0, 0.3);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
            width: 900px;
            height: 600px;
            padding: 50px;
            border-radius: 12px;
            display: flex;
            justify-content: space-between;
        }

        h1,
        h2 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        p {
            font-size: 16px;
            line-height: 1.5;
        }

        a {
            color: white;
        }

        .section {
            margin-bottom: 20px;
        }

        main {
            height: 100%;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .contacts {
            
            border: 2px dashed rgb(189, 195, 199);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.2);
           
            padding: 20px;
            border-radius: 12px;
            margin-top: 20px;
        }

        .contacts a {
            display: block;
            margin-bottom: 10px;
            text-decoration: none;
            color: white;
        }

        .contacts img {
            width: 20px; 
            height: 20px; 
            margin-right: 5px;
        }

    </style>
</head>

<body>
    <main>
        <div class="card">
            <!-- Left Column -->
            <div class="left-column">
                <!-- Content for left column goes here --> 
                <img id="logo" src="https://lh3.googleusercontent.com/pw/ADCreHdaOMYiUdjIlNAkd_b5__H927yPc0fySkMRdRf1qaRgU26I1UW89DW_9LsfRbU7yvUEOfkbvk1sYWqNZIgNFAf40q51O1fZeMm91sAFycV-reJJcLw=w2400" />
                <img id="avatar" src="https://i.imgur.com/mfHDK4G.jpg" alt="" />
                <div class="highlights">
                    <h1>Lê Thị Thanh Tâm</h1>
                    <p>KHMT2023.4</p>
                    <p>University of Information Technology, VNUHCM</p>
                    <p>From Quang Tri</p>
                </div>
            </div> <!-- Right Column -->
            <div class="right-column">
                <!-- Content for right column goes here -->
                <div class="section">
                    <h2>About Me</h2>
                    <p>Năng động 🙈, Tích cực 🙊, Hòa đồng 🐵</p>
                </div>
                <div class="section">
                    <h2>My Hobbies</h2>
                    <p>Nghe nhạc 🎧, đọc sách 📘</p>
                    <p>Đánh cầu lông 🏸, chạy bộ </p>
                    <p>Chơi nhạc cụ 🎸, chụp ảnh 📷</p>
                </div>
                <div class="section">
                    <h2>My Future Goals</h2>
                    <p>Du lịch châu Âu ✈️</p>
                    <p>Tốt nghiệp bằng giỏi 🐳</p>
                </div>
                 <div class="contacts">
                    <h2>Contact me</h2>
                    <a href="mailto:lethithanhtam071205@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/6244/6244710.png" alt="">Mail</a>
                    <a href="https://github.com/ThanhTam712"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111432.png" alt="">Github</a>
                    <a href="https://www.linkedin.com/in/l%C3%AA-th%E1%BB%8B-thanh-t%C3%A2m-009774285/"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384014.png" alt="">Linkedin</a>
            </div>
        </div>
    </main>
</body>

</html>
