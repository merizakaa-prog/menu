<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قائمة الطعام</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8f0;
            text-align: center;
            padding: 20px;
        }

        h1 {
            color: #e67e22;
        }

        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .menu-item {
            background-color: #fff;
            border: 2px solid #e67e22;
            border-radius: 10px;
            padding: 20px;
            width: 200px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }

        .menu-item:hover {
            transform: scale(1.05);
        }

        .menu-item h2 {
            color: #d35400;
            margin-bottom: 10px;
        }

        .menu-item p {
            font-size: 16px;
            color: #555;
        }
    </style>
</head>
<body>

    <h1>قائمة الطعام</h1>

    <div class="menu">
        <div class="menu-item">
            <h2>كسكسي</h2>
            <p>السعر: 700 دج</p>
        </div>

        <div class="menu-item">
            <h2>شخشوخة</h2>
            <p>السعر: 650 دج</p>
        </div>

        <div class="menu-item">
            <h2>طاجين زيتون</h2>
            <p>السعر: 850 دج</p>
        </div>
    </div>

</body>
</html>
