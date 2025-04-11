---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde yerel bir bağlantı oluşturur
type: docs
weight: 190
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

PDF belgesinde yerel bir bağlantı oluşturur.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| desPage | Int32 | Hedef sayfa. |
| originalPage | Int32 | Yerel bağlantı ile bağlı dikdörtgenin oluşturulacağı orijinal sayfanın numarası. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |
| actionName | Enum[] | Acrobat görüntüleyicisinde menü öğelerini yürütmekle ilgili eylemlerin (PredefinedAction enum'unun üyeleri) dizisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

PDF belgesinde yerel bir bağlantı oluşturur.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| desPage | Int32 | Hedef sayfa. |
| originalPage | Int32 | Yerel bağlantı ile bağlı dikdörtgenin oluşturulacağı orijinal sayfanın numarası. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

PDF belgesinde yerel bir bağlantı oluşturur.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| desPage | Int32 | Hedef sayfa. |
| originalPage | Int32 | Yerel bağlantı ile bağlı dikdörtgenin oluşturulacağı orijinal sayfanın numarası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)