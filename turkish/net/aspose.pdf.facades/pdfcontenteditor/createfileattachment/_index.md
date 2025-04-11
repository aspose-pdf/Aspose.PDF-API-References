---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Dosya ekleme notasyonu oluşturur
type: docs
weight: 150
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Dosya ekleme notasyonu oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| contents | String | Notasyonun içeriği. |
| filePath | String | Eklenecek dosyanın yolu. |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayfa numarası. |
| name | String | Notasyonu görüntülemede kullanılacak simgenin adı. Bu değer şunlar olabilir: "Graph", "PushPin", "Paperclip", "Tag". |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Dosya ekleme notasyonu oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| contents | String | Notasyonun içeriği. |
| filePath | String | Eklenecek dosyanın yolu. |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayfa numarası. |
| name | String | Notasyonu görüntülemede kullanılacak simgenin adı. Bu değer şunlar olabilir: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Simgenin opaklığı 0 ile 1 arasında: 0 - tamamen şeffaf, 1 - tamamen opak. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Dosya ekleme notasyonu oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| contents | String | Notasyonun içeriği. |
| attachmentStream | Stream | Ekleme dosya akışı. |
| attachmentName | String | Ekleme adı. |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayfa numarası. |
| name | String | Notasyonu görüntülemede kullanılacak simgenin adı. Bu değer şunlar olabilir: "Graph", "PushPin", "Paperclip", "Tag". |

## Örnekler

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

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Dosya ekleme notasyonu oluşturur.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| contents | String | Notasyonun içeriği. |
| attachmentStream | Stream | Ekleme dosya akışı. |
| attachmentName | String | Ekleme adı. |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayfa numarası. |
| name | String | Notasyonu görüntülemede kullanılacak simgenin adı. Bu değer şunlar olabilir: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Simgenin opaklığı 0 ile 1 arasında: 0 - tamamen şeffaf, 1 - tamamen opak. |

## Örnekler

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

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)