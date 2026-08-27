---
title: "Table.ImportDataTable"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Table. Mengimpor data dari System.Data.DataTable ke dalam Aspose.Pdf.Table"
type: docs
weight: 260
url: /id/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Mengimpor data dari System.Data.DataTable ke Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedDataTable | DataTable | instansi sumber dari System.Data.DataTable |
| isColumnNamesImported | Boolean | menentukan apakah nama kolom akan diimpor sebagai baris pertama |
| firstFilledRow | Int32 | menentukan nomor berbasis nol dari baris pertama dalam tabel target tempat impor akan dimulai, jika baris dengan nomor tersebut (dan beberapa baris sebelumnya) tidak ada dalam tabel target, mereka akan dibuat terlebih dahulu |
| firstFilledColumn | Int32 | menentukan nomor kolom target pertama dalam tabel target, kolom harus ada dalam tabel target sebelum memulai impor |

### Lihat Juga

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
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
| firstFilledRow | Int32 | menentukan nomor berbasis nol dari baris pertama dalam tabel target tempat impor akan dimulai, jika baris dengan nomor tersebut (dan beberapa baris sebelumnya) tidak ada dalam tabel target, mereka akan dibuat terlebih dahulu |
| firstFilledColumn | Byte | menentukan nomor kolom target pertama dalam tabel target, kolom harus ada dalam tabel target sebelum memulai impor |
| maxRows | Int32 | Jumlah maksimum baris yang akan diimpor dari tabel sumber. |
| maxColumns | Int32 | Jumlah maksimum kolom yang akan diimpor dari tabel sumber. |
| isHtmlSupported | Boolean | Menentukan apakah teks tersebut adalah string html. |

### Lihat Juga

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Mengimpor objek DataTable, tetapi tidak sebagai keseluruhan. Hanya baris dan kolom yang ditentukan yang diimpor.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| importedDataTable | DataTable | Objek DataTable yang akan diimpor. |
| sourceRowList | Int32[] | Array berisi nomor baris dalam objek DataTable sumber yang harus diimpor. Daftar tidak boleh null dan harus hanya berisi nomor baris yang ada, jika tidak akan dilemparkan pengecualian. |
| sourceColumnList | Int32[] | Array berisi nomor kolom dalam objek DataTable sumber yang harus diimpor. Daftar tidak boleh null dan harus hanya berisi nomor kolom yang ada, jika tidak akan dilemparkan pengecualian. |
| firstFilledRow | Int32 | Nomor baris berbasis nol dari sel pertama di tabel targer tempat impor akan dimulai. Jika tabel target tidak memiliki baris tersebut, maka baris itu (dan semua sebelumnya jika diperlukan) akan dibuat |
| firstFilledColumn | Int32 | Nomor kolom berbasis nol dari sel pertama di tabel targer tempat impor akan dimulai. Tabel target harus memiliki kolom tersebut sebelum impor dimulai, jika tidak akan dilemparkan pengecualian. |
| showColumnNamesAsFirstRow | Boolean | Menentukan apakah nama kolom dari datatable sumber akan diimpor sebagai baris pertama. |
| isHtmlSupported | Boolean | Menentukan apakah teks tersebut adalah string html. |

### Lihat Juga

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


