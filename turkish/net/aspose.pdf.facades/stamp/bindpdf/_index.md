---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Stamp yöntemi. Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfFile | String | PDF dosyasının yolu. |
| pageNumber | Int32 | PDF dosyasındaki sayfa numarası |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfStream | Stream | PDF belgesini içeren akış. |
| pageNumber | Int32 | Damga olarak kullanılacak belgenin sayfa indeksi. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)