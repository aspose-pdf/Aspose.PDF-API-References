---
title: CreateRubberStamp
second_title: Aspose.PDF for .NET API Referansı
description: Bir lastik damga ek açıklaması oluşturur.
type: docs
weight: 260
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Bir lastik damga ek açıklaması oluşturur.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| annotRect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| icon | String | Açıklamanın görüntülenmesinde bir simge kullanılacaktır. Varsayılan değer: 'Taslak'." |
| annotContents | String | Açıklamanın içeriği. |
| color | Color | Açıklamanın rengi. |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Bir lastik damga ek açıklaması oluşturur.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| annotRect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| annotContents | String | Açıklamanın içeriği. |
| color | Color | Açıklamanın rengi. |
| appearanceFile | String | Görünüm dosyasının yolu. |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Bir lastik damga ek açıklaması oluşturur.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| annotRect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan açıklama dikdörtgeni. |
| annotContents | String | Açıklamanın içeriği. |
| color | Color | Açıklamanın rengi. |
| appearanceStream | Stream | Görünüm dosyasının akışı. |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
