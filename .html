<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Termux Status Monitor</title>
  <style>
    body {
      background-color: #1e1e1e;
      color: #00ff00;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
    }
    .card {
      margin: 10px auto;
      padding: 15px;
      border: 1px solid #00ff00;
      width: 80%;
      max-width: 500px;
    }
  </style>
</head>
<body>
  <h1>Termux System Monitor</h1>
  <div class="card" id="battery-status">Battery: Loading...</div>
  <div class="card" id="internet-status">Internet: Loading...</div>
  <div class="card" id="hashrate">Hashrate: Loading...</div>

  <script>
    async function fetchData() {
      try {
        const response = await fetch('http://localhost:8080/status.json');
        const data = await response.json();

        document.getElementById('battery-status').innerText = `Battery: ${data.battery}% (${data.status})`;
        document.getElementById('internet-status').innerText = `Internet: ${data.internet}`;
        document.getElementById('hashrate').innerText = `Luckpool Hashrate: ${data.hashrate} H/s`;
      } catch (error) {
        console.error('Error fetching data:', error);
      }
    }

    // Refresh data every 5 seconds
    setInterval(fetchData, 5000);
    fetchData(); // Initial fetch
  </script>
</body>
</html>
