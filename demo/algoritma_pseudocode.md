# study case

saya disuruh mas fiqi untuk menghitung 10 kelereng susai warna. warna kelereng di antaranya adalah merah, kuning, hijau


## fauza
1. kelereng di kumpulkan dulu 
2. di siapkan tempat kan untuk memisahkan kelerang yang berbeda (wadah merah, wadah kuning, wadah hijau)
3. di ambil kelereng dengan masing masing warna
4. jika warna merah, di letak di wadah nomer wadah merah.
    jika warna kuning, di letak di wadah nomer wadah kuning.
    jika warna hijau, di letak di wadah nomer wadah hijau.
5. setelah itu kita hitung di wadah masing-masing

## hansen
1. dipisah"-hin wadahnya. (wadah merah, wadah kuning, wadah hijau)
2. ambil satu kelereng
3. jika warna merah, di letak di wadah merah
    jika warna kuning, di letak di wadah kuning
    jika warna hijau, di letak di wadah hijau
4. munculin jumlah kelereng dimasing-masing wadah.


### algoritma
1. dipisah"-hin wadahnya. (wadah merah, wadah kuning, wadah hijau)
2. (kelereng 10) 
2. ambil satu kelereng
3. jika warna merah, di letak di wadah merah
    jika warna kuning, di letak di wadah kuning
    jika warna hijau, di letak di wadah hijau
4. jika kelereng lebih dari 0, maka kembali nomer 2.
   jika kelerengnya sudah habis, maka lanjut ke nomer selanjutnya.
5. munculin jumlah kelereng dimasing-masing wadah.


### pseudocode
<!-- input, problem solving, result -->

<!-- julian -->
<!-- input -->
SET "wadah merah" to 0
SET "wadah kuning" to 0
SET "wadah hijau" to 0
SET "kelerang" to 0
<!-- problem solving: kita akan melakukan perulangan -->
WHILE kelereng > 0
    IF kelereng EQUAL "merah"
        "wadah merah" + 1
    ENDIF
    IF kelereng EQUAL "kuning"
        "wadah kuning" + 1
    ENDIF
    IF  kelereng EQUAL "hijau"
        "wadah hijau" + 1
    ENDIF
    kelereng - 1
ENDWHILE
<!-- result / output -->
DISPLAY "wadah merah", "wadah kuning",  "wadah hijau"
<!-- agung -->
<!-- kevin -->