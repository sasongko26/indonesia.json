indonesia.json
==============

Daftar daerah-daerah di Indonesia lengkap sampai kota kecamatan dalam format JSON. Berguna untuk developer yang menginginkan user memilih kota asal mereka. Kota kecamatan belum lengkap untuk beberapa kabupaten. Sangat berterimakasih jika ada yang mau membantu melengkapinya.

Untuk membaca file JSON ke dalam array di PHP, gunakan:

    $json = file_get_contents("/indonesia.json");
    $array = json_decode($json, true);
