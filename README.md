### langkah 1 Javascrip Dasar
# Pemakaian Alert sebagai property window.

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

![image](https://github.com/user-attachments/assets/7692a25f-54ee-4a95-bd82-4b23b7f518eb)


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
<!DOCTYPE html>
<html>
<head>
  <title>Kotak Pesan</title>
</head>
<body>
  <script>
    alert("ini merupakan pesan untuk anda");
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Skrip JavaScript</title>
</head>
<body>
  <p>Percobaan memakai JavaScript:</p>
  <script>
    document.write("Selamat mencoba JavaScript<br>");
    document.write("Semoga sukses!");
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Pemasukan Data</title>
</head>
<body>
  <script>
    let nama = prompt("Siapa nama Anda?", "Masukkan nama Anda");
    document.write("Hai, " + nama + "!");
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Contoh Program JavaScript</title>
  <script>
    function pesan() {
      alert("Memanggil JavaScript lewat body onload");
    }
  </script>
</head>
<body onload="pesan()">
</body>
</html>

![image](https://github.com/user-attachments/assets/16a1a33f-8333-41c4-bb58-efd867273197)





### langkah 2 Dasar Pemrograman Di Javascript
# Operasi dasar aritmatika
# Menampilkan Bilangan Berdasarkan Input
# Menentukan Bilangan Ganjil atau Genap
# Mengubah Warna Latar Belakang dan Teks
# var total = document.getElementById("total").value;: Mendapatkan nilai total harga saat ini dari elemen input dengan id "total". Jika belum ada nilai, maka nilai total akan menjadi 0.
# parseInt(): Fungsi ini digunakan untuk mengubah nilai string menjadi bilangan bulat, karena nilai yang didapatkan dari elemen input adalah string.
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
<!DOCTYPE html>
<html>
<head>
  <title>Kotak Pesan</title>
</head>
<body>
  <script>
    alert("ini merupakan pesan untuk anda");
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Skrip JavaScript</title>
</head>
<body>
  <p>Percobaan memakai JavaScript:</p>
  <script>
    document.write("Selamat mencoba JavaScript<br>");
    document.write("Semoga sukses!");
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Pemasukan Data</title>
</head>
<body>
  <script>
    let nama = prompt("Siapa nama Anda?", "Masukkan nama Anda");
    document.write("Hai, " + nama + "!");
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Contoh Program JavaScript</title>
  <script>
    function pesan() {
      alert("Memanggil JavaScript lewat body onload");
    }
  </script>
</head>
<body onload="pesan()">
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Contoh Program JavaScript</title>
  <script>
    function test(val1, val2) {
      document.write("<br>Perkalian: " + val1 * val2 + "<br>");
      document.write("<br>Pembagian: " + val1 / val2 + "<br>");
      document.write("<br>Penjumlahan: " + (val1 + val2) + "<br>");
      document.write("<br>Pengurangan: " + (val1 - val2) + "<br>");
      document.write("<br>Modulus: " + (val1 % val2) + "<br>");
    }
  </script>
</head>
<body>
  <button onclick="test(9, 4)">Arithmetic</button>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Contoh if-else</title>
</head>
<body>
  <script>
    let nilai = prompt("Nilai (0-100):", 0);
    let hasil = nilai >= 60 ? "lulus" : "tidak lulus";
    document.write("Hasil: " + hasil);
  </script>
</body>
</html>
<html>
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
        function test() {
            val1 = window.prompt("input nilai (1-5):");
            switch (val1) {
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
<html>
<head>
    <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value;
            if (val1 % 2 == 0) {
                document.kirim.T2.value = "bilangan genap";
            } else {
                document.kirim.T2.value = "bilangan ganjil";
            }
        }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p>
    </form>
</body>
</html>
<html>
<head>
    <title>objek document</title>
</head>
<body>
    <script language="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
    </script>
    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>

    <script language="javascript">
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
    </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Daftar Menu Makanan</title>
  <script>
    function hitung(ele) {
      var total = document.getElementById("total").value;
      total = (total ? parseInt(total) : 0);
      var harga = parseInt(ele.value);
      if (ele.checked == true) {
        total += harga;
      } else {
        if (total > 0) {
          total -= harga;
        }
      }
      document.getElementById("total").value = total;
    }
  </script>
</head>
<body>
  <h1>Daftar Menu Makanan</h1>
  <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br>
  <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br>
  <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><br>
  <strong>Total Bayar: Rp. <input id="total" type="text"></strong>
</body>
</html>

![image](https://github.com/user-attachments/assets/9d7c31f3-43e6-44b3-8130-2eba334733d4)






### langkah membuat tugas Buat script untuk melakukan validasi pada isian form.
# Formulir: membuat formulir dengan field nama, NIM, jurusan, dan mata kuliah. Field pada matkul ini menggunakan select untuk pilihan ganda seperti meperti matkul pemograman web
# Validasi: NIM: Divalidasi agar hanya berisi 10 digit angka.
# Mata Kuliah: Divalidasi agar pengguna memilih opsi dari dropdown.
# Pesan Error: Jika validasi gagal, akan muncul alert dengan pesan error.
<!DOCTYPE html>
<html>
<head>
  <title>Formulir Pendaftaran Mata Kuliah</title>
</head>
<body>
  <form id="myForm">
    <label for="nama">Nama:</label>
    <input type="text" id="nama" name="nama" required>
    <br>
    <label for="nim">NIM:</label>
    <input type="text" id="nim" name="nim" required>
    <br>
    <label for="jurusan">Jurusan:</label>
    <input type="text" id="jurusan" name="jurusan" required>
    <br>
    <label for="matkul">Mata Kuliah:</label>
    <select id="matkul" name="matkul" required>
      <option value="">Pilih Mata Kuliah</option>
      <option value="Pemrograman Web">Pemrograman Web</option>
      <option value="Algoritma dan Struktur Data">Algoritma dan Struktur Data</option>
      </select>
    <br>
    <input type="submit" value="Daftar">
  </form>
  <script>
    document.getElementById("myForm").addEventListener("submit", function(event) {
      event.preventDefault();
      let nama = document.getElementById("nama").value;
      let nim = document.getElementById("nim").value;
      let jurusan = document.getElementById("jurusan").value;
      let matkul = document.getElementById("matkul").value;
      if (nim.length !== 10 || isNaN(nim)) {
        alert("NIM harus berupa angka dengan 10 digit.");
        return false;
      }

      if (matkul === "") {
        alert("Silahkan pilih mata kuliah.");
        return false;
      }
      alert("Data valid. Pendaftaran berhasil.");
    });
  </script>
</body>
</html>

![image](https://github.com/user-attachments/assets/af8aa277-191c-4e78-b45c-c5ecd96d82c0)





