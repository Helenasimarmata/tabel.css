 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran</title>
    <link rel="stylesheet" type="text/css" href="style.css">    
</head>
<body>
    <div class="wrap">
    <div class="container">
    <center>
    <h1> Form Data Diri </h1>
    <hr>
    <form action="detail_informasi.html" method="get">
        <table border="0" align="center">
            <tr>
                <td>Nama </td>
                <td>:</td>
                <td><input type="text" name="Nama"></td>
            </tr>
            <tr>
                <td>NIM</td>
                <td>:</td>
                <td><input type="NIM" name="NIM"></td>
            </tr>
            <tr>
                <td>Program Studi</td>
                <td>:</td>
                <td>
                    <select name="program_studi">
                        <option>---Pilih---</option>
                        <option>Program Studi Teknik Informatika (IF)</option>
                        <option>Program Studi Teknik Geologi</option>
                        <option>Program Studi Teknik Mesin</option>
                        <option>Program Studi Teknik Industri</option>
                        <option>Program Studi Teknik Kimia</option>
                        <option>Program Studi Teknik Fisika</option>
                        <option>Program Studi Teknik Biosistem</option>
                        <option>Program Studi Teknologi Industri Pertanian</option>
                        <option>Program Studi Teknologi Pangan</option>
                        <option> Program Studi Teknik Sistem Energi</option>
                        <option>Program Studi Teknik Pertambangan</option>
                        <option>Program Studi Teknik Material</option>
                        <option>Program Studi Teknik Telekomunikasi</option>
                        <option>Program Studi Rekayasa Kehutanan</option>
                        <option>Program Studi Teknik Biomedik</option>
                        <option> Program Studi Fisika (FI) </option>
                        <option>Program Studi Matematika </option>
                        <option>Program Studi Biologi </option>
                        <option>Program Studi Kimia </option>
                        <option> Program Studi Farmasi </option>
                        <option>Program Studi Atmosfer dan Keplanetan</option>
                        <option>Program Studi Sains Aktuaria </option>
                        <option>Progam Studi Sains Lingkungan Kelautan</option> 
                        <option>Program Studi Sains Data</option>
                        <option>Program Studi Teknik Geomatika (GT)</option>
                        <option>Program Studi Perencanaan Wilayah dan Kota (PWK)</option>
                        <option>Program Studi Teknik Sipil (SI)</option>
                        <option>Program Studi Arsitektur (AR)</option>
                        <option>Program Studi Teknik Lingkungan</option>
                        <option>Program Studi Teknik Kelautan</option>
                        <option>Program Studi Desain Komunikasi Visual</option>
                        <option>Program Studi Arsitektur Lanskap</option>
                        <option>Program Studi Teknik Perkeretaapian</option>
                        <option>Program Studi Teknik Elektro (EL)</option>
                        <option>Program Studi Teknik Geofisika (TG)</option>
                        
                    </select>
                </td>
            </tr>
            <tr>
                 <td>Jenis Kelamin </td>
                <td>:</td>
                <td><input type="radio" name="jk" value="Laki-Laki">Laki-Laki
                    <input type="radio" name="jk" value="Perempuan">Perempuan
               
            </tr>
            <tr>
             <td>Tanggal Lahir</td>
                <td>:</td>
                <td><input type="date" name="tanggal_lahir"></td>
                
                </td>
            </tr>
            <tr>
                <td>Golongan Darah</td>
                <td>:</td>
                <td>
                    <input type="radio" name="gd" id="A">A
                    <input type="radio" name="gd" id="AB">AB
                    <input type="radio" name="gd" id="O">O
                </td>                
            </tr>
            <tr>
                <td>Alamat</td>
                <td>:</td>
                <td><textarea name="alamat"></textarea></td>
            </tr>
            <tr>
                <td>Hobi</td>
                <td>:</td>
                <td>
                    <input type="checkbox" name="hobi" id="Menulis">Menulis
                    <input type="checkbox" name="hobi" id="Gaming">Gaming
                    <input type="checkbox" name="hobi" id="coding">coding
                    <input type="checkbox" name="hobi" id="Membaca">Membaca
                    <input type="checkbox" name="hobi" id="Berenang">Berenang
                </td>
            </tr>
            <tr>
                <td>No. Telp/Ponsel</td>
                <td>:</td>
                <td><input type="text" name="telp"></td>
            </tr>
            <tr>
                <td>Email</td>
                <td>:</td>
                <td><input type="email" name="email"></td>                
            </tr>            
            <tr>
                <td></td>
                <td></td>
                <td>
                    <button type="submit" name="kirim">Kirim </button>
                    <button type="reset" name="Batal" >Batal</button>
                </td>
            </tr>

        </table>
    </form>
    </center>
    </div>
    </div>
</body>
</html>
# tabel.css