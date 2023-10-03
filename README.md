# WebsiteKuu
Tugas Pemograman Multimedia_Rini Apriliani

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>® My Profile Website - ®ini Apriliani🦋</title>
  </head>
  <body background="bg.jpg">
    <table cellspacing="20">
      <tr>
        <td><img src="images/profil-rini.png" alt="Gambar Profil"></td>
          
        <style>
            #text-container {
                font-size: 100px;
            }
        </style>
        <td><div id= "text-container">
                        ®ini A☆*
                    </div>
                    <script>
                        const textContainer = 
                              document.getElementById("text-container");
                        
                        let hue = 0;
                  
                        setInterval(() => {
                            hue = (hue + 1) % 360;
                            const color = `hsl(${hue}, 100%, 50%)`;
                            textContainer.style.color = color;
                        }, 50);
                  </script>
        <p><em>Mahasiswi</em><strong>
          <a href="https://unucirebon.ac.id" target="_blank">Universitas Nahdlatul Ulama Cirebon</a>
          </strong></p>
        <p><em><strong>Fakultas Ilmu Komputer</strong></em></p>
        <p><em>Program Studi Teknik Informatika</em></p></td>
      </tr>
    </table>
    <hr>
    <h3>Biodata</h3>
    <table>
      <tr>
        <td>Nama Lengkap          :</td>
        <td>Rini Apriliani</td>
      </tr>
      <tr>
        <td>Tempat, Tanggal Lahir :</td>
        <td>Kuningan, 20 April 2002</td>
      </tr>
      <tr>
        <td>Alamat                 :</td>
        <td>Desa Pasawahan RT.10 RW.03 Blok Wage Kec.Pasawahan Kab.Kuningan</td>
      </tr>
      <tr>
        <td>Email                 :</td>
        <td>riniapriliani264@gmail.com</td>
      </tr>
    </table>
    <hr>
    <h3>Pendidikan</h3>
    <table cellspacing="20">
      <tr>
        <td>2008 - 2014</td>
        <td>SDN 1 Pasawahan</td>
      </tr>
      <tr>
        <td>2014 - 2017</td>
        <td>SMPN Pasawahan</td>
      </tr>
      <tr>
        <td>2017 - 2020</td>
        <td>SMK Budi Bhakti Mandirancan</td>
      </tr>
    </table>
    <p>
    <a href="hobi-saya.html">Hobi Saya</a>
    <a href="kontak-saya.html">Hubungi Saya</a>
    </p>
  </body>
</html>
