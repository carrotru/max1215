<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>筆記本網頁</title>
    <style>
        body {
            font-family: "Microsoft JhengHei", sans-serif;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .photo-section {
            display: flex;
            justify-content: space-around;
            margin-bottom: 40px;
            flex-wrap: wrap;
            gap: 20px;
        }

        .photo-container {
            flex: 0 1 45%;
            text-align: center;
        }

        .photo-container img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .text-section {
            background: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 40px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .participants {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 20px;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .participant {
            text-align: center;
        }

        .participant img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .participant p {
            margin: 5px 0;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>筆記本網頁</h1>
    </div>

    <div class="photo-section">
        <div class="photo-container">
            <img src="/api/placeholder/400/300" alt="照片1">
        </div>
        <div class="photo-container">
            <img src="/api/placeholder/400/300" alt="照片2">
        </div>
    </div>

    <div class="text-section">
        <p>在這裡放置您想要的文字內容。可以描述活動內容、心得感想或是其他想要分享的訊息。</p>
    </div>

    <div class="participants">
        <div class="participant">
            <img src="/api/placeholder/120/120" alt="參與者1">
            <p>王小明</p>
        </div>
        <div class="participant">
            <img src="/api/placeholder/120/120" alt="參與者2">
            <p>李大華</p>
        </div>
        <div class="participant">
            <img src="/api/placeholder/120/120" alt="參與者3">
            <p>張小芳</p>
        </div>
        <div class="participant">
            <img src="/api/placeholder/120/120" alt="參與者4">
            <p>陳大明</p>
        </div>
    </div>
</body>
</html>
