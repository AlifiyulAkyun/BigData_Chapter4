# BigData_Chapter4
1. Silakan selesaikan praktikum tersebut sesuai langkah-langkah sebelumnya, lalu laporkan hasilnya berupa link repository GitHub dengan nama spark-sql-big-data disertai dengan screenshot hasilnya.
2. Jelaskan masing-masing maksud kode berikut sesuai nomor kodenya pada laporan praktikum Anda!
![Screenshot](soal.png)

<b>1.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>mylist</td>
    <td>mylist pada Python adalah tipe data list yang digunakan untuk menyimpan kumpulan objek dalam satu variabel. Dalam Python, list dapat berisi objek apa saja seperti string, angka, bahkan list lain</td>
 </tr>
 <tr>
    <td>myschema</td>
    <td>myschema pada Python tidak merujuk pada tipe data bawaan di Python. Namun, jika Anda merujuk pada penggunaan schema di Python, biasanya schema digunakan untuk mendefinisikan struktur data yang terdiri dari beberapa field dengan tipe data yang berbeda.Pada umumnya, schema ini digunakan untuk mengelola data dalam format yang terstruktur, seperti file CSV, file JSON, atau database.mylist pada Python adalah tipe data list yang digunakan untuk menyimpan kumpulan objek dalam satu variabel.</td>
 </tr>
 
</table>

<b>2.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>spark.createDataFrame</td>
    <td>create DataFrame adalah istilah umum yang merujuk pada pembuatan DataFrame di berbagai platform pengolahan data, termasuk PySpark. Dalam PySpark, kita dapat menggunakan fungsi spark.createDataFrame() untuk membuat DataFrame dari data yang ada di PySpark RDD, list, atau tuple. </td>
 </tr>
 
</table>

<b>3.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>parallelize</td>
    <td>parallelize() adalah sebuah fungsi pada PySpark yang digunakan untuk mengubah data dalam bentuk list atau tuple menjadi RDD (Resilient Distributed Datasets) yang dapat diproses secara paralel di dalam cluster Spark. Dalam proses paralelisasi data, Spark akan memecah data menjadi beberapa bagian (partisi) yang akan diproses secara terpisah pada setiap node di dalam cluster.</td>
 </tr>
 <tr>
    <td>toDF</td>
    <td>toDF() adalah sebuah fungsi pada PySpark yang digunakan untuk mengubah RDD (Resilient Distributed Datasets) menjadi DataFrame. Dalam proses ini, PySpark akan menentukan schema (struktur kolom dan tipe data) DataFrame secara otomatis berdasarkan tipe data dari setiap elemen RDD. Jika RDD berisi tuple, maka setiap elemen tuple akan dianggap sebagai satu baris data dalam DataFrame.</td>
 </tr>
</table>

<b>4.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>parallelize</td>
    <td>parallelize() adalah sebuah fungsi pada PySpark yang digunakan untuk mengubah data dalam bentuk list atau tuple menjadi RDD (Resilient Distributed Datasets) yang dapat diproses secara paralel di dalam cluster Spark. Dalam proses paralelisasi data, Spark akan memecah data menjadi beberapa bagian (partisi) yang akan diproses secara terpisah pada setiap node di dalam cluster.</td>
 </tr>
 <tr>
    <td>toDF</td>
    <td>toDF() adalah sebuah fungsi pada PySpark yang digunakan untuk mengubah RDD (Resilient Distributed Datasets) menjadi DataFrame. Dalam proses ini, PySpark akan menentukan schema (struktur kolom dan tipe data) DataFrame secara otomatis berdasarkan tipe data dari setiap elemen RDD. Jika RDD berisi tuple, maka setiap elemen tuple akan dianggap sebagai satu baris data dalam DataFrame.</td>
 </tr>
</table>

<b>4.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>hadoop</td>
    <td>Hadoop pada Spark digunakan untuk memproses data secara terdistribusi di dalam cluster. Hadoop adalah framework open-source yang digunakan untuk mengelola data dan menghitung data yang sangat besar pada cluster terdistribusi. Spark dapat berintegrasi dengan Hadoop untuk memanfaatkan sistem file Hadoop HDFS dan framework pengolahan batch Apache Hadoop MapReduce.</td>
 </tr>
 <tr>
    <td>fs</td>
    <td>fs pada Spark Python (PySpark) adalah singkatan dari File System, yang merupakan antarmuka untuk berinteraksi dengan sistem file di dalam cluster Spark. Dengan menggunakan antarmuka fs pada PySpark, kita dapat membaca, menulis, dan memanipulasi berbagai jenis file seperti CSV, JSON, Parquet, Avro, dan lain-lain pada Hadoop Distributed File System (HDFS) dan local file system.</td>
 </tr>
 <tr>
    <td>put</td>
    <td>put merupakan operasi untuk menulis file ke dalam HDFS (Hadoop Distributed File System) atau sistem file lainnya yang didukung oleh Spark.</td>
 </tr>
 </table>

<b>5.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>pyspark.sql</td>
    <td>pyspark.sql adalah modul di PySpark yang menyediakan antarmuka DataFrame yang lebih tinggi dan lebih efisien daripada RDD (Resilient Distributed Dataset). Modul ini digunakan untuk memproses data dalam skala besar secara terdistribusi pada Spark.Membaca dan menulis data dari berbagai sumber seperti CSV, JSON, dan parquet, Memproses data dengan menggunakan SQL atau fungsi DataFrame pada PySpark</td>
 </tr>
 <tr>
    <td>SQLContext</td>
    <td>SQLContext adalah entry point dari modul PySpark SQL. Dengan menggunakan SQLContext, kita dapat membaca dan menulis data dari berbagai sumber seperti CSV, JSON, dan parquet. Selain itu, SQLContext juga menyediakan antarmuka untuk memproses data dengan menggunakan SQL atau fungsi DataFrame pada PySpark.</td>
 </tr>
 <tr>
    <td>createOrReplaceTempView</td>
    <td>createOrReplaceTempView adalah fungsi pada PySpark yang digunakan untuk membuat atau mengganti view sementara dari DataFrame yang diberikan. View sementara adalah tampilan tabel virtual dari DataFrame yang dapat digunakan untuk menjalankan perintah SQL pada DataFrame tersebut.Dalam PySpark, createOrReplaceTempView dapat digunakan untuk memproses data menggunakan SQL pada DataFrame, tanpa perlu melakukan konversi DataFrame menjadi tabel SQL terlebih dahulu. Fungsi ini dapat menggantikan fungsi createTempView dan replaceTempView pada versi sebelumnya dari PySpark.</td>
 </tr>
 <tr>
    <td>show</td>
    <td>show() adalah fungsi pada PySpark yang digunakan untuk menampilkan isi dari DataFrame dalam bentuk tabel. Fungsi ini dapat digunakan untuk memeriksa hasil operasi pada DataFrame, seperti transformasi dan pemrosesan data.</td>
 </tr>
</table>

<b>6.</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Kode</b></td>
    <td><b style="font-size:30px">Keterangan</b></td>
 </tr>
 <tr>
    <td>textFile</td>
    <td>textFile() adalah fungsi pada PySpark yang digunakan untuk membaca file teks sebagai RDD (Resilient Distributed Dataset). Fungsi ini dapat membaca file yang disimpan dalam format teks, seperti file CSV, TSV, dan TXT. </td>
 </tr>
 <tr>
    <td>map</td>
    <td>map() adalah sebuah fungsi pada PySpark yang digunakan untuk melakukan transformasi pada setiap elemen RDD. Fungsi ini mengambil sebuah fungsi sebagai parameter dan menerapkannya pada setiap elemen RDD, sehingga menghasilkan RDD baru.</td>
 </tr>
 <tr>
    <td>lambda</td>
    <td>Pada Spark, lambda digunakan untuk membuat anonymous function yang dapat digunakan dalam operasi transformasi data seperti pada method map, filter, reduce, dan lain-lain. Lambda function memungkinkan penggunaan function yang pendek dan sederhana tanpa harus menuliskan kode function secara terpisah.</td>
 </tr>
  <tr>
    <td>strip</td>
    <td>Pada Spark, method strip() digunakan untuk menghapus whitespace atau karakter tertentu di awal dan akhir sebuah string dalam RDD. Method ini seringkali digunakan pada operasi transformasi data seperti map atau flatMap</td>
 </tr>
  <tr>
    <td>structField</td>
    <td>StructField mendefinisikan tipe data kolom dan nama kolom yang sesuai. Kelas ini sering digunakan bersama dengan kelas.</td>
 </tr>
  <tr>
    <td>stringType</td>
    <td>StringType pada Spark digunakan untuk merepresentasikan tipe data string dalam DataFrame. Tipe data ini dapat digunakan sebagai tipe data kolom pada schema DataFrame, yaitu sebagai salah satu jenis StructField. Data dengan tipe StringType dalam DataFrame dapat diubah atau dimanipulasi dengan menggunakan fungsi-fungsi yang disediakan oleh Spark SQL.</td>
 </tr>
</table>


