Nama : M. Alfarezha R. Hi. Husain
npm  :07352311117
jadi untuk program ini saya mendeklarasikan variabel variabel yang diminta dengan tipe data yang sama 
kemudian saya membuat perintah untuk pengimputan untuk nama, jamkerjaoerminggu, upahperjam dan status
kryawan dengan perintah seperti ini
  stdout.write("Masukkan Nama : ");
  nama = stdin.readLineSync();

  stdout.write("Jam kerja per minggu : ");
  jamKerjaPerMinggu = int.parse(stdin.readLineSync()!);

  stdout.write("Upah per jam : ");
  upahPerJam = double.parse(stdin.readLineSync()!);

  stdout.write("Status karyawan (tetap/kontrak) : ");
  String? inputStatus = stdin.readLineSync();

kemudian terjadi if else untuk menentukan pekerja tetap atau kontrak dan mohon maaf sebelumnya karna saya
banyak menggunakan if else karena belum terlalu faham mengenai maping 
kemudian terjadi if else lagi untuk penentua biaya pajak 
dan kemudian terjadi perhitungan gajikotor lalu if else unntuk menghitung gaji bersih

kemudian mengeluarkan output
