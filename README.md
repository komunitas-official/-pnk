<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PNK - Secure Portal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div id="loader" class="screen">
        <div class="glitch-wrapper">
            <div class="glitch" data-text="PNK SYSTEM">PNK SYSTEM</div>
        </div>
        <div class="progress-bar">
            <div class="progress-fill"></div>
        </div>
        <p class="loading-text">INITIALIZING SECURITY PROTOCOLS...</p>
    </div>

    <div id="login-screen" class="screen hidden">
        <div class="glass-panel">
            <h2>TERMINAL LOGIN</h2>
            <input type="text" id="user" placeholder="USERNAME" autocomplete="off">
            <input type="password" id="pass" placeholder="PASSWORD">
            <button onclick="checkLogin()">AUTHORIZE</button>
        </div>
    </div>

    <div id="reg-screen" class="screen hidden">
        <div class="glass-panel scrollable">
            <h3>PNK ENROLLMENT</h3>
            <input type="text" placeholder="Nama Lengkap">
            <input type="number" placeholder="Umur">
            <input type="date" placeholder="Tanggal Lahir">
            <select>
                <option value="" disabled selected>Jenis Kelamin</option>
                <option>Laki-laki</option>
                <option>Perempuan</option>
            </select>
            <input type="text" placeholder="Akun TikTok">
            <input type="text" placeholder="Asal Daerah">
            <textarea placeholder="Alasan Bergabung"></textarea>
            <button onclick="finalize()">JOIN COMMUNITY</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
