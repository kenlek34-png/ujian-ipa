<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ujian IPA - Tema Alam</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #4CAF50, #81C784);
            color: #fff;
            margin: 0;
            padding: 20px;
            background-image: url('https://example.com/nature-bg.jpg'); /* Ganti dengan URL gambar alam */
            background-size: cover;
            background-attachment: fixed;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }
        h1 {
            text-align: center;
            color: #FFD700;
        }
        form {
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
            background: #fff;
            color: #000;
        }
        .question {
            margin-bottom: 20px;
            background: rgba(255, 255, 255, 0.1);
            padding: 15px;
            border-radius: 5px;
        }
        .question h3 {
            margin-top: 0;
        }
        input[type="radio"] {
            margin-right: 10px;
        }
        button {
            display: block;
            width: 100%;
            padding: 15px;
            background: #FF5722;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }
        button:hover {
            background: #E64A19;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Ujian IPA - Tema Alam</h1>
        <form id="examForm">
            <label for="nama">Nama Siswa:</label>
            <input type="text" id="nama" name="nama" required>

            <label for="kelas">Kelas Siswa:</label>
            <input type="text" id="kelas" name="kelas" required>

            <h2>Soal Ujian IPA</h2>

            <div class="question">
                <h3>1. Apa yang dimaksud dengan fotosintesis?</h3>
                <input type="radio" name="q1" value="a"> Proses pembentukan energi dari cahaya matahari<br>
                <input type="radio" name="q1" value="b"> Proses pernapasan sel<br>
                <input type="radio" name="q1" value="c"> Proses penguapan air<br>
                <input type="radio" name="q1" value="d"> Proses pembusukan bahan organik
            </div>

            <div class="question">
                <h3>2. Unsur kimia apa yang paling banyak terdapat di atmosfer bumi?</h3>
                <input type="radio" name="q2" value="a"> Oksigen<br>
                <input type="radio" name="q2" value="b"> Nitrogen<br>
                <input type="radio" name="q2" value="c"> Karbon dioksida<br>
                <input type="radio" name="q2" value="d"> Hidrogen
            </div>

            <div class="question">
                <h3>3. Apa fungsi utama daun pada tumbuhan?</h3>
                <input type="radio" name="q3" value="a"> Penyerapan air<br>
                <input type="radio" name="q3" value="b"> Fotosintesis<br>
                <input type="radio" name="q3" value="c"> Penyimpanan makanan<br>
                <input type="radio" name="q3" value="d"> Reproduksi
            </div>

            <div class="question">
                <h3>4. Bagaimana cara kerja gaya gravitasi?</h3>
                <input type="radio" name="q4" value="a"> Menarik benda ke arah pusat bumi<br>
                <input type="radio" name="q4" value="b"> Mendorong benda ke atas<br>
                <input type="radio" name="q4" value="c"> Mengubah bentuk benda<br>
                <input type="radio" name="q4" value="d"> Menghasilkan cahaya
            </div>

            <div class="question">
                <h3>5. Apa yang terjadi pada air saat mendidih?</h3>
                <input type="radio" name="q5" value="a"> Berubah menjadi es<br>
                <input type="radio" name="q5" value="b"> Berubah menjadi uap<br>
                <input type="radio" name="q5" value="c"> Menyerap panas<br>
                <input type="radio" name="q5" value="d"> Membeku
            </div>

            <div class="question">
                <h3>6. Apa nama proses di mana tanaman melepaskan oksigen?</h3>
                <input type="radio" name="q6" value="a"> Respirasi<br>
                <input type="radio" name="q6" value="b"> Fotosintesis<br>
                <input type="radio" name="q6" value="c"> Transpirasi<br>
                <input type="radio" name="q6" value="d"> Fermentasi
            </div>

            <div class="question">
                <h3>7. Unsur apa yang diperlukan untuk pembentukan tulang?</h3>
                <input type="radio" name="q7" value="a"> Kalsium<br>
                <input type="radio" name="q7" value="b"> Besi<br>
                <input type="radio" name="q7" value="c"> Karbon<br>
                <input type="radio" name="q7" value="d"> Nitrogen
            </div>

            <div class="question">
                <h3>8. Apa yang dimaksud dengan ekosistem?</h3>
                <input type="radio" name="q8" value="a"> Sistem peredaran darah<br>
                <input type="radio" name="q8" value="b"> Komunitas makhluk hidup dan lingkungannya<br>
                <input type="radio" name="q8" value="c"> Proses pencernaan makanan<br>
                <input type="radio" name="q8" value="d"> Gerakan planet
            </div>

            <div class="question">
                <h3>9. Bagaimana cara kerja magnet?</h3>
                <input type="radio" name="q9" value="a"> Menarik logam besi<br>
                <input type="radio" name="q9" value="b"> Menghasilkan listrik<br>
                <input type="radio" name="q9" value="c"> Mengubah warna<br>
                <input type="radio" name="q9" value="d"> Menyerap cahaya
            </div>

            <div class="question">
                <h3>10. Apa fungsi utama jantung?</h3>
                <input type="radio" name="q10" value="a"> Memompa darah<br>
                <input type="radio" name="q10" value="b"> Menghasilkan energi<br>
                <input type="radio" name="q10" value="c"> Mengatur suhu tubuh<br>
                <input type="radio" name="q10" value="d"> Menyimpan makanan
            </div>

            <div class="question">
                <h3>11. Apa yang terjadi saat logam bereaksi dengan asam?</h3>
                <input type="radio" name="q11" value="a"> Terbentuk garam dan hidrogen<br>
                <input type="radio" name="q11" value="b"> Terbentuk air<br>
                <input type="radio" name="q11" value="c"> Terbentuk oksigen<br>
                <input type="radio" name="q11" value="d"> Terbentuk karbon dioksida
            </div>

            <div class="question">
                <h3>12. Apa nama lapisan atmosfer terluar?</h3>
                <input type="radio" name="q12" value="a"> Troposfer<br>
                <input type="radio" name="q12" value="b"> Stratosfer<br>
                <input type="radio" name="q12" value="c"> Mesosfer<br>
                <input type="radio" name="q12" value="d"> Eksosfer
            </div>

            <div class="question">
                <h3>13. Bagaimana proses terjadinya hujan?</h3>
                <input type="radio" name="q13" value="a"> Penguapan air dari laut<br>
                <input type="radio" name="q13" value="b"> Kondensasi uap air menjadi awan<br>
                <input type="radio" name="q13" value="c"> Presipitasi air dari awan<br>
                <input type="radio" name="q13" value="d"> Semua jawaban benar
            </div>

            <div class="question">
                <h3>14. Apa yang dimaksud dengan energi kinetik?</h3>
                <input type="radio" name="q14" value="a"> Energi diam<br>
                <input type="radio" name="q14" value="b"> Energi gerak<br>
                <input type="radio" name="q14" value="c"> Energi panas<br>
                <input type="radio" name="q14" value="d"> Energi cahaya
            </div>

            <div class="question">
                <h3>15. Apa fungsi klorofil pada daun?</h3>
                <input type="radio" name="q15" value="a"> Menyerap cahaya matahari<br>
                <input type="radio" name="q15" value="b"> Menyimpan air<br>
                <input type="radio" name="q15" value="c"> Mengatur suhu<br>
                <input type="radio" name="q15" value="d"> Melindungi dari hama
            </div>

            <div class="question">
                <h3>16. Apa nama reaksi kimia di mana energi dilepaskan?</h3>
                <input type="radio" name="q16" value="a"> Reaksi endotermik<br>
                <input type="radio" name="q16" value="b"> Reaksi eksotermik<br>
                <input type="radio" name="q16" value="c"> Reaksi netral<br>
                <input type="radio" name="q16" value="d"> Reaksi reversibel
            </div>

            <div class="question">
                <h3>17. Apa yang dimaksud dengan siklus air?</h3>
                <input type="radio" name="q17" value="a"> Peredaran air di bumi<br>
                <input type="radio" name="q17" value="b"> Peredaran udara<br>
                <input type="radio" name="q17" value="c"> Peredaran energi<br>
                <input type="radio" name="q17" value="d"> Peredaran makanan
            </div>

            <div class="question">
                <h3>18. Bagaimana cara kerja lensa cembung?</h3>
                <input type="radio" name="q18" value="a"> Memusatkan cahaya<br>
                <input type="radio" name="q18" value="b"> Menebarkan cahaya<br>
                <input type="radio" name="q18" value="c"> Menyerap cahaya<br>
                <input type="radio" name="q18" value="d"> Mengubah warna cahaya
            </div>

            <div class="question">
                <h3>19. Apa yang terjadi pada tanaman saat kekurangan air?</h3>
                <input type="radio" name="q19" value="a"> Layu<br>
                <input type="radio" name="q19" value="b"> Tumbuh lebih cepat<br>
                <input type="radio" name="q19" value="c"> Berubah warna menjadi merah<br>
                <input type="radio" name="q19" value="d"> Menghasilkan lebih banyak buah
            </div>

            <div class="question">
                <h3>20. Apa nama planet terdekat dengan matahari?</h3>
                <input type="radio" name="q20" value="a"> Venus<br>
                <input type="radio" name="q20" value="b"> Merkurius<br>
                <input type="radio" name="q20" value="c"> Bumi<br>
                <input type="radio" name="q20" value="d"> Mars
            </div>

            <button type="submit">Kirim Jawaban</button>
        </form>
    </div>

    <script>
        document.getElementById('examForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Jawaban telah dikirim! Terima kasih, ' + document.getElementById('nama').value + ' dari kelas ' + document.getElementById('kelas').value + '.');
            // Di sini bisa tambahkan logika untuk menyimpan atau mengirim data ke server.
        });
    </script>
</body>
</html>
