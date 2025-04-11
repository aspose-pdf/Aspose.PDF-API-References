---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.PdfToXlsOptions. Mewakili opsi konverter PDF ke XLSX untuk plugin XlsConverter
type: docs
weight: 9150
url: /id/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## Kelas PdfToXlsOptions

Mewakili opsi konverter PDF ke XLSX untuk [`XlsConverter`](../xlsconverter/) plugin.

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
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Format keluaran. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Mengembalikan koleksi data plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Set true jika Anda perlu menyisipkan kolom kosong sebagai kolom pertama dari lembar kerja. Nilai default adalah false; ini berarti kolom kosong tidak akan disisipkan. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Set true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; ini berarti menyimpan setiap halaman PDF sebagai lembar kerja terpisah. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Mendapatkan nama operasi. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Mendapatkan koleksi target yang ditambahkan untuk menyimpan hasil operasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfToXLSXConverterOptions. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Memungkinkan untuk menentukan format file .xlsx, .xls/xml atau csv. Nilai default adalah XLSX. |

### Lihat Juga

* kelas [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)