<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hot Dog Sales Dashboard</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            padding: 20px;
            background: transparent;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        .dashboard-card {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            border-radius: 12px;
            padding: 30px;
            max-width: 400px;
            width: 100%;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }

        .dashboard-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
        }

        .icon {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        .title {
            color: white;
            font-size: 1.8rem;
            margin-bottom: 12px;
            font-weight: 600;
        }

        .description {
            color: rgba(255, 255, 255, 0.9);
            line-height: 1.6;
            margin-bottom: 20px;
            font-size: 1rem;
        }

        .button {
            color: white;
            text-decoration: none;
            font-weight: 600;
            border: 2px solid white;
            padding: 10px 20px;
            border-radius: 6px;
            display: inline-block;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .button:hover {
            background-color: white;
            color: #4facfe;
        }
    </style>
</head>
<body>
    <div class="dashboard-card">
        <div class="icon">🌭</div>
        <h2 class="title">Hot Dog Sales</h2>
        <p class="description">
            Analyze hot dog product sales trends, inventory levels, and regional performance. Track seasonal patterns and demand.
        </p>
        <a href="YOUR_DASHBOARD_LINK_HERE" class="button">
            View Dashboard →
        </a>
    </div>
</body>
</html>
