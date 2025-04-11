---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur
type: docs
weight: 110
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| application | String | Başlatılacak uygulamanın yolu. |
| page | Int32 | Bağlantıyla birlikte dikdörtgenin oluşturulacağı orijinal sayının numarası. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |
| actionName | Enum[] | Acrobat görüntüleyicisinde menü öğelerini yürütmekle ilgili eylemlerin (PredefinedAction enum'unun üyeleri) dizisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| application | String | Başlatılacak uygulamanın yolu. |
| page | Int32 | Bağlantıyla birlikte dikdörtgenin oluşturulacağı orijinal sayının numarası. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| application | String | Başlatılacak uygulamanın yolu. |
| page | Int32 | Bağlantıyla birlikte dikdörtgenin oluşturulacağı orijinal sayının numarası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)