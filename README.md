<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>甜味心脏</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            background: linear-gradient(to bottom right, #cfe9ff, #e8d9ff);
            font-family: "Microsoft YaHei", sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
        }

        h1 {
            font-size: 60px;
            color: white;
            margin-bottom: 50px;
            text-shadow: 0 0 15px rgba(255,255,255,0.8);
        }

        .menu {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .btn {
            width: 220px;
            padding: 15px;
            font-size: 20px;
            border-radius: 30px;
            border: none;
            background-color: rgba(255,255,255,0.8);
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: white;
            transform: scale(1.05);
            box-shadow: 0 0 15px rgba(255,255,255,0.8);
        }

        a {
            text-decoration: none;
            color: #6b6b6b;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>甜味心脏</h1>

    <div class="menu">
        <button class="btn"><a href="characters.html">角色介绍</a></button>
        <button class="btn"><a href="map.html">世界地图</a></button>
        <button class="btn"><a href="story.html">主线故事</a></button>
        <button class="btn"><a href="theater.html">小剧场</a></button>
    </div>
</div>

</body>
</html>
