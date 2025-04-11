---
title: PdfExtractor.GetNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfExtractor. Menyimpan teks satu halaman ke file
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

Menyimpan teks satu halaman ke file.

```csharp
public void GetNextPageText(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Jalur dan nama file untuk menyimpan teks. |

## Contoh

Contoh ini menunjukkan penggunaan metode GetNextPageText dalam skenario ekstraksi teks.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

Menyimpan teks satu halaman ke stream.

```csharp
public void GetNextPageText(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan teks. |

## Contoh

Contoh ini menunjukkan penggunaan metode `GetNextPageText` dalam skenario ekstraksi teks.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    FileStream fs = new FileStream(prefix + pageCount + suffix, FileMode.Create);
    extractor.GetNextPageText(prefix + pageCount + suffix);
    fs.Close();
    pageCount++;
}
```

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)