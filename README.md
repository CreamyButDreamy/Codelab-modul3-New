# Proyek Kalkulator Sederhana (Demo Git)

Ini adalah proyek latihan sederhana yang dibuat untuk mempraktikkan alur kerja dasar Git, seperti *commit* dan melihat riwayat perubahan.

## Deskripsi Proyek

Program ini adalah kalkulator sederhana berbasis konsol yang ditulis dalam bahasa Java. Awalnya, program ini hanya memiliki satu fitur, yaitu penjumlahan.

## Perkembangan Fitur

Proyek ini menunjukkan evolusi kode melalui dua *commit*:

1.  **Commit Awal:**
    * Program hanya dapat melakukan operasi penjumlahan antara dua angka (`angka1` dan `angka2`).

2.  **Commit Kedua (Pembaruan):**
    * Sebuah fitur baru ditambahkan ke program.
    * Selain penjumlahan, program sekarang juga dapat melakukan operasi **pengurangan**.

## Kode Final dan Cara Menjalankan

Berikut adalah kode final dari program (`KalkulatorSederhana.java`) setelah adanya pembaruan, beserta cara untuk menjalankannya.

### Kode: `KalkulatorSederhana.java`

```java
public class KalkulatorSederhana {
    public static void main(String[] args) {
        int angka1 = 10;
        int angka2 = 5;
        
        // Kode dari commit pertama
        int hasilTambah = angka1 + angka2;
        System.out.println("Hasil Penjumlahan: " + hasilTambah);
        
        // Perubahan: Menambahkan operasi pengurangan
        int hasilKurang = angka1 - angka2;
        System.out.println("Hasil Pengurangan: " + hasilKurang);
    }
}
```

## Cara Menjalankan:
Buka Terminal atau Command Prompt di folder tempat Anda menyimpan file.

Kompilasi file Java:

``` java
javac KalkulatorSederhana.java
```

Jalankan program:
``` java
java KalkulatorSederhana
```

Output yang akan tampil di konsol:
``` java
Hasil Penjumlahan: 15
Hasil Pengurangan: 5
```