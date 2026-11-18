# Tugas-.5
Membuat tabel angka
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table border="1" width="30%" cellpadding="8" cellspacing="2" align="center">
        <caption>
            <h1>TABEL ANGKA 1-100</h1>
        </caption>
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td colspan="5" rowspan="2" class="red" style="background-color: red;" align="center">
                <a href="form login.html">?</a>
            </td>
            <td>9</td>
            <td>10</td>
        </tr>
        <tr>
            <td colspan="2" rowspan="4" class="yellow" style="background-color: yellow;" align="center">
                <a href="contact.html" target="_blank">?</a>
            </td>
            <td>13</td>
            <td>19</td>
            <td>20</td>
        </tr>
        <tr>
            <td>23</td>
            <td>24</td>
            <td>25</td>
            <td>26</td>
            <td>27</td>
            <td>28</td>
            <td>29</td>
            <td>30</td>
        </tr>
        <tr>
            <td>33</td>
            <td>34</td>
            <td>35</td>
            <td>36</td>
            <td>37</td>
            <td>38</td>
            <td colspan="1" rowspan="4" class="green" style="background-color: green; "align"= "center">
                <a href="url.html" target="_blank">?</a>
            </td>
            <td>40</td>
        </tr>
        <tr>
            <td>43</td>
            <td>44</td>
            <td>45</td>
            <td>46</td>
            <td>47</td>
            <td>48</td>
            <td>49</td>
        </tr>
        <tr>
            <td>51</td>
            <td>52</td>
            <td>53</td>
            <td>54</td>
            <td colspan="3" rowspan="3" class="aqua" style="background-color: aqua;" align="center">
                <a href="pendaftaran.html" target="_blank">?</a>
            </td>
            <td>56</td>
            <td>57</td>
        </tr>
        <tr>
            <td>61</td>
            <td>62</td>
            <td>63</td>
            <td>64</td>
            <td>65</td>
            <td>66</td>
        </tr>
        <tr>
            <td>71</td>
            <td>72</td>
            <td>73</td>
            <td>74</td>
            <td>75</td>
            <td>76</td>
            <td>77</td>
        </tr>
        <tr>
            <td>81</td>
            <td>82</td>
            <td>83</td>
            <td>84</td>
            <td>85</td>
            <td>86</td>
            <td>87</td>
            <td>88</td>
            <td>89</td>
            <td>90</td>
        </tr>
        <tr>
            <td>91</td>
            <td>92</td>
            <td>93</td>
            <td>94</td>
            <td>95</td>
            <td>96</td>
            <td>97</td>
            <td>98</td>
            <td>99</td>
            <td>100</td>
        </tr>
    </table>
</body>
</html>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Login</title>
    
</head>
<body>
    <h2>Form Login</h2>
        <form>
            <fieldset>
                <legend>Login</legend>
                <p>
                <div class="form-group">
                    <label>Username:</label>
                    <input type="text" placeholder="Masukkan username">
                </div>
                </p>
                <p>
                <div class="form-group">
                    <label>Password:</label>
                    <input type="password" placeholder="Masukkan password">
                </div>
                </p>
                <p>
                <div class="form-group">
                    <label style="width: auto;"><input type="checkbox"> Remember me</label>
                </div>
                </p>
                <p>
                <div style="margin-top: 15px;">
                    <button type="submit">Login</button>
                    <button type="reset">Reset</button>
                </div>
                </p>
            </fieldset>
        </form>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="proses.php" method="post" enctype="multipart/form-data">
        <fieldset>
            <Legend>Pendaftaran Siswa</Legend> 
             <label for="nama">Nama lengkap:</label><br> 
             <input type="text" id="nama" name="nama" placeholder="Masukan Nama Lengkap"required><br><br>
             
       <label for="Nis">NIS:</label><br> 
             <input type="text" id="NIS name="NIS" placeholder="Masukan NIS"required><br><br>
             <label>jenis Kelamin</label><br>
             <input type="radio" id="jk_1" name="name" value="Laki-laki"required>
             <label for="jk_1">Laki-laki</label><br>
            <input type="radio" id="jk_1" name="name" value="Perempuan"required>
            <label for="jk_1">Perempuan</label><br><br>
            <input type="datetime-local" name="jadwal"/><br><br>

            <label for="jurusan">Pilihan Jurusan:</label><br>
            <select id="jurusan" name="jurusan" required>
            <option value="">- Pilih Jurusan</option>
            <option value="RPL">Rekayasa Perangkat Lunak (RPL)</option>
            <option value="PPLG">Pengembangan Perangkat Lunak dan GIM (PPLG)</option>
            <option value="TKJ">Teknik Komputer & Jaringan (TK3)</option>
            </select><br><br>
            <label for="alamat">Alamat lengkap</label><br>
            <textarea id="alamat" name="alamat" rows="4" cols="40" placeholder="Tuliskan alamat lengkap anda..."></textarea><br><br>
           
            <label for="foto">Foto:</label>
            <input type="file" name="foto"/><br><br>

           
         <input type="checkbox" id="chek" name="chek[]" value="Saya metujui data yang saya masukan"> Saya metujui data yang saya masukan <br><br>
        <button type="Daftar">daftar</button>
         <input type="reset" value="Reset"/>
        </fieldset>
    </form>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UT<label for="TaF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="proses.php" method="post" enctype="multipart/form-data">
        <fieldset>
            <Legend>URL</Legend> 
    <label for="Url">URL:</label> 
             <input type="text" id="Url" name="Url" placeholder="Masukan URL..."required><br><br>
             <label for="Tanggal" >Tanggal:</label>
             <input type="date" name="tgl" /><br><br>
             <label for="Waktu">Waktu:</label>
             <input type="time" name="jam"/>  <br><br>
             <label for="Jumlah" >Jumlah:</label>
             <input type="text" name=""/><br><br>
             <button type="Send">Send</button>
              <input type="reset" value="Reset"/>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
        
    <h2>Form Contact</h2>

    <form action="proses.php" method="post" enctype="multipart/form-data">
    <fieldset>
            <legend>Contact</legend><br> 

             <label for="nama">Nama:</label>
             <input type="text" id="nama" name="nama" placeholder="Masukan Nama"required><br><br>
            
             <label for="email">Email:</label>
             <input type="email" id="email" name="email" placeholder="Masukan Email"required><br><br>

             <label for="subject">Subject:</label>
             <input type="subject" id="subject" name="subject" placeholder="Masukan Subject"required><br><br>

             <label for="pesan">Pesan:</label><br>
             <textarea id="pesan" name="pesan" rows="4" cols="40" placeholder="Tuliskan pesan anda..."></textarea><br><br>
             
            <button type="kirim">Send</button>
            <button type="reset">Reset</button>
</body>
</html>
