---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Metode Tabel. Mengimpor data dari System.Data.DataTable ke dalam Aspose.Pdf.Table
type: docs
weight: 260
url: /id/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Mengimpor data dari System.Data.DataTable ke dalam Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedDataTable | DataTable | instance sumber dari System.Data.DataTable |
| isColumnNamesImported | Boolean | menentukan apakah nama kolom akan diimpor sebagai baris pertama |
| firstFilledRow | Int32 | menentukan nomor baris pertama berbasis nol di tabel target dari mana impor akan dimulai, jika baris dengan nomor tersebut (dan beberapa baris sebelumnya) tidak ada di tabel target, mereka akan dibuat terlebih dahulu |
| firstFilledColumn | Int32 | menentukan nomor kolom target pertama di tabel target, kolom harus ada di tabel target sebelum mulai impor |

### Lihat Juga

* kelas [Tabel](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Mengimpor objek DataTable ke dalam tabel.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedDataTable | DataTable | Objek DataTable yang akan diimpor. |
| isColumnNamesShown | Boolean | Menentukan apakah nama kolom dari datatable sumber akan diimpor sebagai baris pertama. |
| firstFilledRow | Int32 | menentukan nomor baris pertama berbasis nol di tabel target dari mana impor akan dimulai, jika baris dengan nomor tersebut (dan beberapa baris sebelumnya) tidak ada di tabel target, mereka akan dibuat terlebih dahulu |
| firstFilledColumn | Byte | menentukan nomor kolom target pertama di tabel target, kolom harus ada di tabel target sebelum mulai impor |
| maxRows | Int32 | Jumlah maksimum baris yang akan diimpor dari tabel sumber. |
| maxColumns | Int32 | Jumlah maksimum kolom yang akan diimpor dari tabel sumber. |
| isHtmlSupported | Boolean | Menentukan apakah teks adalah string html. |

### Lihat Juga

* kelas [Tabel](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Mengimpor objek DataTable, tetapi tidak sebagai entitas keseluruhan. Hanya baris dan kolom yang ditentukan yang diimpor.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedDataTable | DataTable | Objek DataTable yang akan diimpor. |
| sourceRowList | Int32[] | Array nomor baris dalam objek DataTable sumber yang harus diimpor. Daftar tidak boleh null dan harus hanya berisi nomor baris yang ada, jika tidak, pengecualian akan dilemparkan. |
| sourceColumnList | Int32[] | Array nomor kolom dalam objek DataTable sumber yang harus diimpor. Daftar tidak boleh null dan harus hanya berisi nomor kolom yang ada, jika tidak, pengecualian akan dilemparkan. |
| firstFilledRow | Int32 | Nomor baris berbasis nol dari sel pertama di tabel target dari mana impor akan dimulai. Jika tabel target tidak mengandung baris tersebut, itu (dan semua sebelumnya jika perlu) akan dibuat |
| firstFilledColumn | Int32 | Nomor kolom berbasis nol dari sel pertama di tabel target dari mana impor akan dimulai. Tabel target harus mengandung kolom tersebut sebelum impor dimulai, jika tidak, pengecualian akan dilemparkan. |
| showColumnNamesAsFirstRow | Boolean | Menentukan apakah nama kolom dari datatable sumber akan diimpor sebagai baris pertama. |
| isHtmlSupported | Boolean | Menentukan apakah teks adalah string html. |

### Lihat Juga

* kelas [Tabel](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)