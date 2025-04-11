---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Metode Tabel. Mengimpor array data satu dimensi ke dalam tabel. Impor dilakukan satu sel untuk setiap item array dan dimulai dari baris dan kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan masih tidak ada, yaitu tabel target terlalu kecil untuk menyerap semua data, baris yang diperlukan akan dibuat.
type: docs
weight: 250
url: /id/net/aspose.pdf/table/importarray/
---
## Metode Table.ImportArray

Mengimpor array data satu dimensi ke dalam tabel. Impor dilakukan satu sel untuk setiap item array dan dimulai dari baris dan kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan masih tidak ada (yaitu tabel target terlalu kecil untuk menyerap semua data), baris yang diperlukan akan dibuat.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedArray | Object[] | data yang diimpor, null akan diimpor sebagai string kosong |
| firstFilledRow | Int32 | menentukan nomor baris target pertama di tabel target dari mana impor akan dimulai. Jika jumlah baris di tabel target kurang dari yang diperlukan, baris yang hilang akan dibuat terlebih dahulu. |
| firstFilledColumn | Int32 | menentukan nomor kolom target pertama di tabel target, kolom harus ada di tabel target sebelum mulai impor |
| isLeftColumnsFilled | Boolean | Jika 'isLeftColumnsFilled'=false, maka di baris yang terisi kedua dan semua baris terisi berikutnya, sel yang berada di sebelah kiri firstFilledColumn akan dilewati |

### Lihat Juga

* kelas [Tabel](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)