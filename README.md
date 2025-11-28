# belajarwebpenggajian
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<style>
<style>
    body{
      background-color: rgb(155, 191, 217);
    }
    form {
            background-color: rgb(210, 224, 234);
            width: 35%;
            max-width: 700px;
            margin: 60px auto;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(27, 7, 7, 0.87);
            transition: transform 0.3s ease;
            color : blue;
    }
  </style>
 <form method="POST" action="pas2dafha.php">
    <table align="center">
  <h3 align= "center">Kalkulator Slip Gaji Karyawan</h3>
     <tr>
      <td>Nama karyawan <br>
      <input type="text" name='nama' ></td>
     </tr>
     <tr>
      <td>Jabatan <br>
      <select name="jabatan"[]>
      <option value="jabatan" >jabatan</option>
          <option value="direktur" >direktur</option>
            <option value="manager"  >manager</option>
            <option value="staff" >staff</option></td>
     </tr> 
     <tr> 
    <td>bulan <br>
    <select name ="pilih" required>
        <option value="">PIlih Bulan</option>
        <option value="Januari">Januari</option>
        <option value="Februari">Februari</option>
        <option value="Maret">Maret</option>
        <option value="April">April</option>
        <option value="Mei">Mei</option>
        <option value= "Juni">Juni</option>
        <option value= "Juli">Juli</option>
        <option value= "Agustus">Agustus</option>
        <option value= "September">September</option>
        <option value= "Oktober">Oktober</option>
        <option value= "November">November</option>
        <option value= "Desember">Desember</option>
     </select>

     <td>Tahun <br>
     <select name ="pilih1" required colspan=10>
        <option value=""PIlih Tahun</option>
        <option value="2020">2020</option>
        <option value="2021">2021</option>
        <option value="2022">2022</option>
        <option value="2023">2023</option>
        <option value="2024">2024</option>
        <option value="2025">2025</option>
</td>
</tr> 
     <tr>
      <td> Masuk kerja <br>
      <input type="number" name='hari' max="25"></td>
     </tr>
     <tr>
      <td> Minjam koperasi <br>
      <input type="number" name='minjam'></td>
     </tr>
     <td></td>
      <td></td>
      <td><input type="submit" name='save'></td>
     </tr>
    </table>
   </form>
 </body>
</html>
