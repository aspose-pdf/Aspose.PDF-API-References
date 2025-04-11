---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen sayfadaki belirtilen görüntüleri siler
type: docs
weight: 320
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Belirtilen sayfadaki belirtilen görüntüleri siler.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Görüntülerin silinmesi gereken sayfanın numarası. |
| index | Int32[] | Görüntülerin indekslerini temsil eden bir dizi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

PDF belgesinden tüm görüntüleri siler.

```csharp
public void DeleteImage()
```

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)