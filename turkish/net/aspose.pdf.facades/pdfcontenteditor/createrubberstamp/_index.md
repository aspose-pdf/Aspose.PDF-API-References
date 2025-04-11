---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Bir kauçuk damga notasyonu oluşturur
type: docs
weight: 260
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Bir kauçuk damga notasyonu oluşturur.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa | Int32 | Notasyonun oluşturulacağı orijinal sayfanın numarası. |
| annotRect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| simge | String | Notasyonu görüntülemek için kullanılacak bir simge. Varsayılan değer: 'Taslak'. |
| annotContents | String | Notasyonun içeriği. |
| renk | Color | Notasyonun rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Bir kauçuk damga notasyonu oluşturur.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa | Int32 | Notasyonun oluşturulacağı orijinal sayfanın numarası. |
| annotRect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| annotContents | String | Notasyonun içeriği. |
| renk | Color | Notasyonun rengi. |
| appearanceFile | String | Görünüm dosyasının yolu. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Bir kauçuk damga notasyonu oluşturur.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa | Int32 | Notasyonun oluşturulacağı orijinal sayfanın numarası. |
| annotRect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| annotContents | String | Notasyonun içeriği. |
| renk | Color | Notasyonun rengi. |
| appearanceStream | Stream | Görünüm dosyasının akışı. |

## Örnekler

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

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)