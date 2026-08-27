---
title: "Table.ImportDataView"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Table. Mengimpor data objek DataView ke dalam tabel"
type: docs
weight: 270
url: /id/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

Mengimpor data objek DataView ke dalam tabel.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceDataView | DataView | Objek DataView yang akan diimpor. |
| isColumnNamesImported | Boolean | Menunjukkan apakah nama kolom akan diimpor sebagai baris pertama. |
| firstFilledRow | Int32 | Nomor baris berbasis nol dari sel pertama di tabel targer tempat impor akan dimulai. Jika tabel target tidak memiliki baris tersebut, maka baris itu (dan semua sebelumnya jika diperlukan) akan dibuat |
| firstFilledColumn | Int32 | Nomor kolom berbasis nol dari sel pertama di tabel target tempat impor akan dimulai. Tabel target harus berisi kolom tersebut sebelum impor dimulai, jika tidak akan dilemparkan pengecualian. |
| maxRows | Int32 | Jumlah maksimum baris yang akan diimpor dari DataView sumber. |
| maxColumns | Int32 | Jumlah maksimum kolom yang akan diimpor dari DataView sumber. |

### Lihat Juga

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


