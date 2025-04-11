---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen kimliklere sahip damgaları belgenin tüm sayfalarından siler
type: docs
weight: 350
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Belirtilen kimliklere sahip damgaları belgenin tüm sayfalarından siler.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stampIds | Int32[] | Damga kimlikleri dizisi. |

## Örnekler

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Belirtilen sayfadaki damgaları birden fazla damga kimliği ile siler.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Damgaların silineceği sayfa numarası. |
| stampIds | Int32[] | Damga kimlikleri dizisi. |

## Örnekler

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)