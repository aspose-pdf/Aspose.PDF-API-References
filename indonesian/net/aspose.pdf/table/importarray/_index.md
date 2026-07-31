---
title: "Table.ImportArray"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Table. Mengimpor array satu dimensi data ke dalam tabel. Impor menempatkan satu sel untuk setiap item array dan dimulai dari baris serta kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan masih tidak ada, misalnya tabel target terlalu kecil untuk menampung semua data, baris yang diperlukan akan dibuat."
type: docs
weight: 250
url: /id/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

Mengimpor array satu dimensi data ke dalam tabel. Impor menempatkan satu sel per setiap item array dan dimulai dari baris serta kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan masih belum ada (misalnya tabel target terlalu kecil untuk menampung semua data), baris yang diperlukan akan dibuat

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedArray | Object[] | Data yang diimpor, null akan diimpor sebagai string kosong. |
| firstFilledRow | Int32 | Tentukan nomor baris target pertama dalam tabel target dari mana impor akan dimulai. Jika jumlah baris dalam tabel target kurang dari yang diperlukan, baris yang hilang akan dibuat terlebih dahulu. |
| firstFilledColumn | Int32 | menentukan nomor kolom target pertama dalam tabel target, kolom harus ada dalam tabel target sebelum memulai impor |
| isLeftColumnsFilled | Boolean | Jika 'isLeftColumnsFilled'=false, maka pada baris terisi kedua dan semua baris berikutnya, sel yang berada di sebelah kiri dari firstFilledColumn akan dilewati |

### Lihat Juga

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


