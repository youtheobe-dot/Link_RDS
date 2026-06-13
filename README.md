<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RDS Rusun Daan Mogot KM 18</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            /* Background gradasi estetik modern */
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #20b2aa 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            color: white;
        }

        .container {
            width: 100%;
            max-width: 450px;
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
            padding: 30px 20px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .profile-img {
            width: 90px;
            height: 90px;
            background-color: white;
            border-radius: 50%;
            margin-bottom: 15px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        h1 {
            font-size: 1.4rem;
            font-weight: 700;
            margin-bottom: 5px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        p {
            font-size: 0.9rem;
            color: #e0e0e0;
            margin-bottom: 30px;
        }

        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-btn {
            display: block;
            background: white;
            color: #1e3c72;
            padding: 16px 20px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.15);
            border: 2px solid transparent;
        }

        /* Efek Interaktif Saat Tombol Ditekan/Disentuh di HP */
        .link-btn:active, .link-btn:hover {
            transform: scale(0.98);
            background: #20b2aa;
            color: white;
            box-shadow: 0 2px 8px rgba(0,0,0,0.2);
        }

        .footer {
            margin-top: 40px;
            font-size: 0.75rem;
            color: rgba(255,255,255,0.6);
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Icon / Logo Utama -->
        <div class="profile-img">🏢</div>
        
        <h1>RDS Rusun Daan Mogot</h1>
        <p>KM 18 • Provinsi DKI Jakarta</p>

        <!-- Wadah Tombol Tautan -->
        <div class="links-container">
            
            <!-- Tombol 1 -->
            <a href="https://survey.byalwan.my.id/index.php/912115?lang=en" class="link-btn" target="_blank">
                📝 Isi Kuesioner Warga
            </a>
            
            <!-- Tombol 2 -->
            <a href="https://rusun-dprkp-dki-jkt.scui.web.id/" class="link-btn" target="_blank">
                👋 Website Perkenalan
            </a>

        </div>

        <div class="footer">
            © 2026 RUSUN DAAN MOGOT KM 18
        </div>
    </div>

</body>
</html>
