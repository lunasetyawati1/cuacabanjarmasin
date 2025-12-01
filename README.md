<!DOCTYPE html>
<html lang="id">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Halaman Web Pantauan Suhu Harian</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f4f8;
      margin: 0;
      padding: 0;
    }

    h2 {
      text-align: center;
      margin-top: 20px;
      color: #333;
    }

    h4 {
      margin-left: 20px;
      color: #444;
    }

    p {
      margin-left: 20px;
      font-size: 16px;
    }

    iframe {
      display: block;
      margin: 20px auto;
      border-radius: 8px;
    }

    table {
      width: 90%;
      margin: 20px auto;
      border-collapse: collapse;
      background: #fff;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    th {
      background-color: #4CAF50;
      color: white;
      padding: 12px;
      text-align: center;
    }

    td {
      padding: 10px;
      text-align: center;
      border-bottom: 1px solid #ddd;
    }

    tr:nth-child(even) {
      background-color: #f9f9f9;
    }

    tr:hover {
      background-color: #f1f1f1;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #333;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>

<body>
  <h2>Kondisi Cuaca Daerah Banjarmasin</h2>
  <hr>

  <h4>Lokasi</h4>
  <p>Daerah</p>

  <!-- Google Maps Embed -->
  <iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15951.84915152841!2d127.35928859999999!3d0.7937965999999999!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3283289069151b69%3A0x67399f36f90543e3!2sKota%20Ternate%2C%20Maluku%20Utara!5e0!3m2!1sid!2sid!4v1733021554165!5m2!1sid!2sid"
    width="600" height="450" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
  </iframe>

  <table border="1">
    <tr>
      <th>No.</th>
      <th>Hari</th>
      <th>Tanggal</th>
      <th>Suhu (C°)</th>
      <th>Kelembapan</th>
    </tr>
    <tr>
      <td>01</td>
      <td>Senin</td>
      <td>1/12/2025</td>
      <td>30°/76°</td>
      <td>76%</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Selasa</td>
      <td>2/12/2025</td>
      <td>24°/28°</td>
      <td>80%</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Rabu</td>
      <td>3/12/2025</td>
      <td>24°/30°</td>
      <td>77%</td>
    </tr>
    <tr>
      <td>04</td>
      <td>Kamis</td>
      <td>4/12/2025</td>
      <td>28°/24°</td>
      <td>84%</td>
    </tr>
    <tr>
      <td>05</td>
      <td>Jumat</td>
      <td>5/12/2025</td>
      <td>29°/24°</td>
      <td>81%</td>
    </tr>
    <tr>
      <td>06</td>
      <td>Sabtu</td>
      <td>6/12/2025</td>
      <td>28°/24°</td>
      <td>82%</td>
    </tr>
    <tr>
      <td>07</td>
      <td>Minggu</td>
      <td>7/12/2025</td>
      <td>28°/24°</td>
      <td>81%</td>
    </tr>
  </table>

  <footer>
    <p>dibuat oleh &copy; Luna Setyawati</p>
  </footer>
</body>

</html>
