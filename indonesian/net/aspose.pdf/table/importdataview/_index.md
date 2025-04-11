---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Metode Tabel. Mengimpor data objek DataView ke dalam tabel
type: docs
weight: 270
url: /id/net/aspose.pdf/table/importdataview/
---
## Metode Table.ImportDataView

Mengimpor data objek DataView ke dalam tabel.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceDataView | DataView | Objek DataView yang akan diimpor. |
| isColumnNamesImported | Boolean | Menunjukkan apakah nama kolom akan diimpor sebagai baris pertama. |
| firstFilledRow | Int32 | Nomor baris berbasis nol dari sel pertama di tabel target dari mana impor akan dimulai. Jika tabel target tidak mengandung baris tersebut, baris itu (dan semua sebelumnya jika perlu) akan dibuat |
| firstFilledColumn | Int32 | Nomor kolom berbasis nol dari sel pertama di tabel target dari mana impor akan dimulai. Tabel target harus mengandung kolom tersebut sebelum impor dimulai, jika tidak, pengecualian akan dilemparkan. |
| maxRows | Int32 | Jumlah maksimum baris yang akan diimpor dari DataView sumber. |
| maxColumns | Int32 | Jumlah maksimum kolom yang akan diimpor dari DataView sumber. |

### Lihat Juga

* kelas [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)