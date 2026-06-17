<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan Andre & Syafira</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            background-color: #dfd7ca;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .invitation-wrapper {
            max-width: 450px;
            width: 100%;
            background-color: #dfd7ca;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            box-sizing: border-box;
            position: relative;
        }

        /* 1. COVER ATAS (Marun Beludru Penuh) */
        .section-cover {
            background-color: #420b11 !important; /* Warna marun beludru pekat */
            padding: 60px 25px 90px 25px;
            color: #ffffff;
            text-align: center;
            border-bottom: 5px solid #d4af37;
            position: relative;
            box-sizing: border-box;
        }

        /* BACKGROUND BUNGA KAMU DI SISI KIRI */
        .section-cover::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 60%; /* Menyesuaikan lebar bunga */
            height: 100%;
            background-image: url('bunga.jpg'); /* Memanggil file bunga.jpg */
            background-size: contain;
            background-repeat: no-repeat;
            background-position: left center;
            opacity: 0.9;
            z-index: 1;
            pointer-events: none;
        }

        .main-title, .cover-names, .box-tamu, .scroll-hint {
            position: relative;
            z-index: 2;
        }

        .main-title {
            font-size: 13px;
            letter-spacing: 3px;
            color: #d4af37;
            text-transform: uppercase;
            margin-bottom: 30px;
        }

        .cover-names {
            font-size: 38px;
            font-family: 'Georgia', serif;
            color: #ffffff;
            margin: 20px 0;
            line-height: 1.2;
            text-shadow: 0 2px 4px rgba(0,0,0,0.8);
        }
        .cover-names span {
            display: block;
            font-size: 26px;
            color: #d4af37;
            margin: 10px 0;
        }

        .box-tamu {
            background: #ffffff !important;
            border: 3px double #d4af37;
            border-radius: 12px;
            padding: 20px 10px;
            margin: 40px auto 20px auto;
            max-width: 85%;
            color: #000000 !important;
            box-shadow: 0 4px 15px rgba(0,0,0,0.4);
        }
        .yth-tamu {
            font-size: 11px;
            color: #666666;
            margin: 0 0 6px 0;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        #namaTamu {
            font-size: 24px;
            font-weight: bold;
            color: #111111;
            margin: 0;
            text-transform: uppercase;
        }
        .label-bawah-tamu {
            font-size: 11px;
            color: #666666;
            margin: 8px 0 0 0;
            font-style: italic;
        }

        .scroll-hint {
            font-size: 12px;
            color: #dfd7ca;
            opacity: 0.9;
            margin-top: 30px;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-8px); }
            60% { transform: translateY(-4px); }
        }

        /* 2. ISI TENGAH (Krem Kertas) */
        .section-content {
            padding: 80px 25px 40px 25px;
            text-align: center;
            color: #26070a;
            background-color: #dfd7ca !important;
            flex-grow: 1;
        }

        .tanggal-atas {
            font-size: 18px;
            font-weight: bold;
            letter-spacing: 4px;
            color: #b38f2d;
            margin-bottom: 25px;
        }

        .ayat {
            font-style: italic;
            font-size: 13.5px;
            line-height: 1.6;
            color: #554441;
            margin: 0 10px 30px 10px;
            padding-bottom: 20px;
            border-bottom: 1px dashed rgba(66, 17, 23, 0.2);
        }

        .mempelai-box {
            margin: 25px 0;
        }
        .nama-lengkap {
            font-size: 22px;
            font-weight: bold;
            color: #421117;
            margin-bottom: 4px;
        }
        .orang-tua {
            font-size: 12.5px;
            color: #554441;
        }
        .simbol-dan-isi {
            font-size: 32px;
            color: #b38f2d;
            font-family: 'Georgia', serif;
            margin: 20px 0;
        }
    </style>
</head>
<body>

    <div class="invitation-wrapper">
        
        <div class="section-cover">
            <div class="main-title">Undangan Pernikahan</div>
            <div class="cover-names">
                Andre
                <span>&</span>
                Syafira
            </div>
            <div class="box-tamu">
                <p class="yth-tamu">Kepada YTH Bapak/Ibu/Saudara/i</p>
                <h2 id="namaTamu">Nama Tamu</h2>
                <p class="label-bawah-tamu">Maaf apabila ada kesalahan dalam penulisan nama / gelar</p>
            </div>
            <div class="scroll-hint">▼ Scroll ke bawah</div>
        </div>

        <div class="section-content">
            <div class="tanggal-atas">26 JUNI 2026</div>
            <div class="ayat">
                Matius 19:6: "Demikianlah mereka bukan lagi dua melainkan satu. Karena itu, apa yang dipersatukan Allah tidak boleh diceraikan manusia".
            </div>
            <div class="mempelai-box">
                <div class="nama-lengkap">Andre Bagus Putra Aditya, S.Kom.</div>
                <div class="orang-tua">Putra kedua dari Bapak Liem Bing Djiang & Ibu Ong Moy Liang</div>
            </div>
            <div class="simbol-dan-isi">&</div>
            <div class="mempelai-box">
                <div class="nama-lengkap">Anisa Syafira Salsabila, S.H.</div>
                <div class="orang-tua">Putri Keempat dari Bapak Mahatma Rahendra & Ibu Indah Puspita Ratih</div>
            </div>
        </div>

    </div>

    <script>
        function getGuestName() {
            const urlParams = new URLSearchParams(window.location.search);
            const nama = urlParams.get('to');
            if (nama) {
                document.getElementById('namaTamu').innerText = decodeURIComponent(nama);
            } else {
                document.getElementById('namaTamu').innerText = "Tamu Undangan";
            }
        }
        window.onload = getGuestName;
    </script>

</body>
</html>
