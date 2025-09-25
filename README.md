<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stock Navigation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f4fa;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      padding: 20px;
    }

    .container {
      text-align: center;
      width: 100%;
      max-width: 500px;
      background: #fff;
      padding: 30px 25px;
      border-radius: 16px;
      box-shadow: 0 6px 16px rgba(0,0,0,0.1);
    }

    h1 {
      margin-bottom: 25px;
      color: #333;
      font-size: 1.6rem;
    }

    .btn-container {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .btn {
      flex: 1 1 180px;
      padding: 14px 20px;
      font-size: 1rem;
      font-weight: bold;
      color: white;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: 0.3s;
      text-decoration: none;
      box-shadow: 0 4px 6px rgba(0,0,0,0.12);
      text-align: center;
    }

    .btn:hover {
      transform: scale(1.04);
    }

    .btn-primary {
      background: linear-gradient(135deg, #4CAF50, #2e7d32);
    }

    .btn-primary:hover {
      background: linear-gradient(135deg, #45a049, #256d2d);
    }

    .btn-secondary {
      background: linear-gradient(135deg, #2196F3, #1565c0);
    }

    .btn-secondary:hover {
      background: linear-gradient(135deg, #1e88e5, #0d47a1);
    }

    /* Responsive Adjustments */
    @media (max-width: 480px) {
      h1 {
        font-size: 1.3rem;
      }
      .btn {
        font-size: 0.95rem;
        padding: 12px;
      }
      .btn-container {
        flex-direction: column;
        gap: 12px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Select Stock Report</h1>
    <div class="btn-container">
      <a href="https://ireshdudde.github.io/24-Sep-Cold-Stock/" target="_blank" class="btn btn-primary">Cold Storage Balance Stock</a>
      <a href="https://ireshdudde.github.io/24-Sep-Godown-Stock/" target="_blank" class="btn btn-secondary">Godown Stock Details</a>
    </div>
  </div>
</body>
</html>
