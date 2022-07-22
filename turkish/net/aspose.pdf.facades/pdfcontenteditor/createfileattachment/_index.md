---
title: CreateFileAttachment
second_title: Aspose.PDF for .NET API Referansı
description: Dosya eki açıklamasını oluşturur.
type: docs
weight: 150
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Dosya eki açıklamasını oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| contents | String | Açıklamanın içeriği. |
| filePath | String | Dosyanın yolu eklenecektir. |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| name | String | Açıklamanın görüntülenmesinde bir simgenin adı kullanılacaktır. Bu değer şunlar olabilir: "Grafik", "PushPin", "Ataş", "Etiket". |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Dosya eki açıklamasını oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| contents | String | Açıklamanın içeriği. |
| filePath | String | Dosyanın yolu eklenecektir. |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| name | String | Açıklamanın görüntülenmesinde bir simgenin adı kullanılacaktır. Bu değer şunlar olabilir: "Grafik", "PushPin", "Ataş", "Etiket". |
| opacity | Double | 0'dan 1: 0'a kadar simgenin opaklığı - tamamen şeffaf, 1 - tamamen opak. |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Dosya eki açıklamasını oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| contents | String | Açıklamanın içeriği. |
| attachmentStream | Stream | Ek dosya akışı. |
| attachmentName | String | Ek adı. |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| name | String | Açıklamanın görüntülenmesinde bir simgenin adı kullanılacaktır. Bu değer şunlar olabilir: "Grafik", "PushPin", "Ataş", "Etiket". |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Dosya eki açıklamasını oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| contents | String | Açıklamanın içeriği. |
| attachmentStream | Stream | Ek dosya akışı. |
| attachmentName | String | Ek adı. |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| name | String | Açıklamanın görüntülenmesinde bir simgenin adı kullanılacaktır. Bu değer şunlar olabilir: "Grafik", "PushPin", "Ataş", "Etiket". |
| opacity | Double | 0'dan 1: 0'a kadar simgenin opaklığı - tamamen şeffaf, 1 - tamamen opak. |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
