# Praktikum 5: Javascript

**Pengenalan javascript**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
<img width="398" height="175" alt="image" src="https://github.com/user-attachments/assets/b56a2b62-5367-475a-97df-fb9aac5b3980" />

---

**Javascript dasar**

Pemakaian Alert sebagai property window

```html
<html>
<head>
    <title>alert box</title>
</head>
<body>
    <script language = "javascript">
        <!--
        window.alert("ini merupakan pesan untuk anda");
        //-->
    </script>
</body>
</html>
```

<img width="511" height="242" alt="image" src="https://github.com/user-attachments/assets/e797a48d-0cb4-4d8a-87c5-6ac66e05ee89" />

---

Pemakaian method dalam objek
```html
<html>
<head>
    <title>skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script language = "javascript">
        <!--
        document.write("selamat mencoba javascript<br>");
        document.write("semoga sukses!");
        //-->
    </script>
</body>
</html>
```

<img width="246" height="86" alt="image" src="https://github.com/user-attachments/assets/53e56a7b-930a-4818-a32d-d9a421038714" />

---

Pemakaian Prompt
```html
<html>
<head>
    <title>pemasukan data</title>
</head>
<body>
    <script language = "javascript">
        <!--
        var nama = prompt("siapa nama anda", "masukkan nama anda");
        document.write("hai, " + nama);
        //-->
    </script>
</body>
</html>
```
<img width="503" height="295" alt="image" src="https://github.com/user-attachments/assets/906e6185-c88d-4f47-962e-4b07045f6693" />

<img width="369" height="102" alt="image" src="https://github.com/user-attachments/assets/f036115e-11b3-4fc3-ab13-0bf513c6f035" />

---

Pembuatan fungsi dan cara pemanggilannya
```html
<html>
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
        function pesan(){
            alert("memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload="pesan()">
</body>
</html>
```

<img width="519" height="203" alt="image" src="https://github.com/user-attachments/assets/9fc0b339-9146-4c2a-9e31-289f6df4d13d" />

---

**Dasar pemrograman Di Javascript**

Operasi dasar Aritmatika
```html
<html>
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
        function test(val1, val2) {
            document.write("<br>" + "perkalian : val1*val2 " + "<br>");
            document.write(val1 * val2);
            document.write("<br>" + "pembagian : val1/val2 " + "<br>");
            document.write(val1 / val2);
            document.write("<br>" + "penjumlahan : val1+val2 " + "<br>");
            document.write(val1 + val2);
            document.write("<br>" + "pengurangan : val1-val2 " + "<br>");
            document.write(val1 - val2);
            document.write("<br>" + "modulus : val1%val2 " + "<br>");
            document.write(val1 % val2);
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick="test(9,4)">
</body>
</html>
```
<img width="102" height="42" alt="image" src="https://github.com/user-attachments/assets/7d843f89-8c13-4faf-af43-b02f983efb74" />

<img width="185" height="223" alt="image" src="https://github.com/user-attachments/assets/5d7d79e8-b4b5-462f-b053-deab65f2f842" />

---

Seleksi kondisi(if..else)
```html
<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language = "javascript">
        <!--
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >= 60)
            hasil = "lulus";
        else
            hasil = "tidak lulus";
        document.write("hasil: " + hasil);
        //-->
    </script>
</body>
</html>
```
Bila nilai kurang dari 60

<img width="522" height="269" alt="image" src="https://github.com/user-attachments/assets/45224117-d88b-45ec-bdd3-ce54e4da8523" />

Hasilnya:

<img width="286" height="79" alt="image" src="https://github.com/user-attachments/assets/ee145cf4-ef92-4c33-b392-146d7f8ae89c" />

Bila nilai lebih dari 60

<img width="493" height="275" alt="image" src="https://github.com/user-attachments/assets/c3ad75c8-71ba-491b-a430-abaefd783345" />

Hasilnya:

<img width="317" height="101" alt="image" src="https://github.com/user-attachments/assets/32dcbaf4-c4d6-4925-9b72-8a3bf6bfd6ff" />

---

Penggunaan operator switch untuk seleksi kondisi
```html
<html>
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
        function test() {
            val = window.prompt("input nilai (1-5):");
            switch (val) {
                case "1":
                    document.write("bilangan satu");
                    break;
                case "2":
                    document.write("bilangan dua");
                    break;
                case "3":
                    document.write("bilangan tiga");
                    break;
                case "4":
                    document.write("bilangan empat");
                    break;
                case "5":
                    document.write("bilangan lima");
                    break;
                default:
                    document.write("bilangan lainnya");
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick="test()">
</body>
</html>
```

<img width="102" height="70" alt="image" src="https://github.com/user-attachments/assets/e23d092c-a2f0-4677-a5ce-8ee23326bff4" />

<img width="499" height="245" alt="image" src="https://github.com/user-attachments/assets/bac1527a-3b8d-4fc8-8686-2b0d833a3a21" />

<img width="169" height="96" alt="image" src="https://github.com/user-attachments/assets/78317831-3163-4fcc-846e-a427ff92cc24" />

---

**Pembuatan Form**

Form Input
```html
<html>
<head>
    <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value;
            if (val1 % 2 == 0)
                document.kirim.T2.value = "bilangan genap";
            else
                document.kirim.T2.value = "bilangan ganjil";
        }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p>
    </form>
</body>
</html>
```

<img width="570" height="126" alt="image" src="https://github.com/user-attachments/assets/a04fc000-65eb-474f-96c0-c00cb75609ad" />

<img width="564" height="152" alt="image" src="https://github.com/user-attachments/assets/09c8c611-93f9-410e-b87c-1577f82b5b36" />

---

Form Button
```html
<html>
<head>
    <title>objek document</title>
</head>
<body>
    <script language = "javascript">
        <!--
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
        //-->
    </script>

    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
    </form>
    <script language = "javascript">
        <!--
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
        //-->
    </script>
</body>
</html>
```

<img width="581" height="319" alt="image" src="https://github.com/user-attachments/assets/91c8c426-875d-4a51-a5ea-3b73b972a611" />

<img width="536" height="213" alt="image" src="https://github.com/user-attachments/assets/df2ca39c-d4c9-4c26-adb4-3e2ed6d6d4cb" />

---

# HTML DOM
**Pilihan menggunakan checkkbox dengan perhitungan otomatis**
```html
<html>
<head>
<title>Daftar Menu</title>
<script>
function hitung(ele) {
    var total = document.getElementById('total').value;
    var total = total ? parseInt(total) : 0;
    var harga = 0;
    
    if (ele.checked) {
        harga = ele.value;
        total += parseInt(harga);
    } else {
        harga = ele.value;
        if (total > 0)
        total -= parseInt(harga);
    }
    document.getElementById('total').value = total;
}
</script>
</head>
<body>
<label><input type="checkbox" value="5000" id="menu1" onClick="hitung(this);" /> Ayam Goreng Rp. 5.000</label><br />
<label><input type="checkbox" value="5000" id="menu2" onClick="hitung(this);" /> Tempe Goreng Rp. 5.000</label><br />
<label><input type="checkbox" value="2500" id="menu3" onClick="hitung(this);" /> Telur Dadar Rp. 2.500</label><br />
<strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>
```
<img width="349" height="130" alt="image" src="https://github.com/user-attachments/assets/b2ef821a-64bd-41d8-b668-6421706050f6" />

---

# Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.

**Jawaban**

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Validasi Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .container {
            max-width: 500px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 3px;
            box-sizing: border-box;
        }
        .error {
            color: red;
            font-size: 12px;
            margin-top: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Form Pendaftaran</h2>
        <form id="formPendaftaran" onsubmit="return validasiForm()">
            <div class="form-group">
                <label for="nama">Nama Lengkap:</label>
                <input type="text" id="nama" name="nama">
                <div class="error" id="errorNama"></div>
            </div>
            
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <div class="error" id="errorEmail"></div>
            </div>
            
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password">
                <div class="error" id="errorPassword"></div>
            </div>
            
            <div class="form-group">
                <label for="konfirmasiPassword">Konfirmasi Password:</label>
                <input type="password" id="konfirmasiPassword" name="konfirmasiPassword">
                <div class="error" id="errorKonfirmasiPassword"></div>
            </div>
            
            <button type="submit">Daftar</button>
        </form>
    </div>

    <script>
        function validasiForm() {
            // Reset error messages
            document.getElementById('errorNama').textContent = '';
            document.getElementById('errorEmail').textContent = '';
            document.getElementById('errorPassword').textContent = '';
            document.getElementById('errorKonfirmasiPassword').textContent = '';
            
            // Get form values
            const nama = document.getElementById('nama').value.trim();
            const email = document.getElementById('email').value.trim();
            const password = document.getElementById('password').value;
            const konfirmasiPassword = document.getElementById('konfirmasiPassword').value;
            
            let isValid = true;
            
            // Validasi Nama
            if (nama === '') {
                document.getElementById('errorNama').textContent = 'Nama harus diisi';
                isValid = false;
            } else if (nama.length < 3) {
                document.getElementById('errorNama').textContent = 'Nama minimal 3 karakter';
                isValid = false;
            }
            
            // Validasi Email
            const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (email === '') {
                document.getElementById('errorEmail').textContent = 'Email harus diisi';
                isValid = false;
            } else if (!emailPattern.test(email)) {
                document.getElementById('errorEmail').textContent = 'Format email tidak valid';
                isValid = false;
            }
            
            // Validasi Password
            if (password === '') {
                document.getElementById('errorPassword').textContent = 'Password harus diisi';
                isValid = false;
            } else if (password.length < 6) {
                document.getElementById('errorPassword').textContent = 'Password minimal 6 karakter';
                isValid = false;
            }
            
            // Validasi Konfirmasi Password
            if (konfirmasiPassword === '') {
                document.getElementById('errorKonfirmasiPassword').textContent = 'Konfirmasi password harus diisi';
                isValid = false;
            } else if (password !== konfirmasiPassword) {
                document.getElementById('errorKonfirmasiPassword').textContent = 'Password tidak cocok';
                isValid = false;
            }
            
            if (isValid) {
                alert('Form berhasil dikirim!');
                // Biasanya di sini akan ada pengiriman data ke server
            }
            
            return false; // Mencegah form submit untuk demo
        }
        
        // Validasi real-time
        document.getElementById('nama').addEventListener('blur', function() {
            const nama = this.value.trim();
            if (nama === '') {
                document.getElementById('errorNama').textContent = 'Nama harus diisi';
            } else if (nama.length < 3) {
                document.getElementById('errorNama').textContent = 'Nama minimal 3 karakter';
            } else {
                document.getElementById('errorNama').textContent = '';
            }
        });
        
        document.getElementById('email').addEventListener('blur', function() {
            const email = this.value.trim();
            const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (email === '') {
                document.getElementById('errorEmail').textContent = 'Email harus diisi';
            } else if (!emailPattern.test(email)) {
                document.getElementById('errorEmail').textContent = 'Format email tidak valid';
            } else {
                document.getElementById('errorEmail').textContent = '';
            }
        });
    </script>
</body>
</html>
```

Hasil dari code diatas :

<img width="643" height="560" alt="image" src="https://github.com/user-attachments/assets/14244819-16ab-4991-871d-4cd068f34ec9" />

Bila sudah berhasil diisi akan muncul seperti ini :

<img width="607" height="521" alt="image" src="https://github.com/user-attachments/assets/a574a7cd-7bf0-4404-8bcc-fd5c322f2eb3" />
