---
title: "Kelas PdfToXlsOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "kelas Aspose.Pdf.Plugins.PdfToXlsOptions. Mewakili opsi konverter PDF ke XLSX untuk plugin XlsConverter"
type: docs
weight: 9300
url: /id/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

Mewakili opsi konverter PDF ke XLSX untuk plugin [`XlsConverter`](../xlsconverter/).

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Format output. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Mengembalikan koleksi data plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Atur true jika Anda memerlukan penyisipan kolom kosong sebagai kolom pertama lembar kerja. Nilai default adalah false; artinya kolom kosong tidak akan disisipkan. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Atur true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; artinya setiap halaman PDF disimpan sebagai lembar kerja terpisah. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Mendapatkan nama operasi. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Mendapatkan koleksi target yang ditambahkan untuk menyimpan hasil operasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfToXLSXConverterOptions. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Memungkinkan untuk menentukan format file .xlsx, .xls/xml, atau csv. Nilai default adalah XLSX. |

### Lihat Juga

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


