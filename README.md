# static-web-page
<!DOCTYPE html>
<html>
<head>
    <title>Simple Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .dashboard {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            grid-gap: 20px;
            margin: 20px;
        }

        .widget {
            padding: 20px;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            border-radius: 5px;
            text-align: center;
        }

        .widget h2 {
            font-size: 24px;
        }

        .widget p {
            font-size: 18px;
        }
    </style>
</head>
<body>
    <h1>Simple Dashboard</h1>
    <div class="dashboard">
        <div class="widget">
            <h2>Widget 1</h2>
            <p>Data: 100</p>
        </div>
        <div class="widget">
            <h2>Widget 2</h2>
            <p>Data: 200</p>
        </div>
        <div class="widget">
            <h2>Widget 3</h2>
            <p>Data: 300</p>
        </div>
    </div>
</body>
</html>
