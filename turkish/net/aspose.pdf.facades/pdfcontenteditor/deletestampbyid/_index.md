---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen sayfadaki damgayı damga ID'sine göre siler
type: docs
weight: 340
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Belirtilen sayfadaki damgayı damga ID'sine göre siler.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Damganın silineceği sayfa numarası. |
| stampId | Int32 | Silinmesi gereken damganın tanımlayıcısı. |

## Örnekler

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Tüm belgedeki sayfalardan ID ile damgayı siler.

```csharp
public void DeleteStampById(int stampId)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stampId | Int32 | Silinmesi gereken damganın tanımlayıcısı. |

## Örnekler

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)