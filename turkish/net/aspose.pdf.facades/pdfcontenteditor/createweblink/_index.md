---
title: PdfContentEditor.CreateWebLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde bir web bağlantısı oluşturur
type: docs
weight: 300
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

PDF belgesinde bir web bağlantısı oluşturur.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| url | String | Web bağlantısı hedefi. |
| originalPage | Int32 | Web bağlantısıyla bağlı dikdörtgenin oluşturulacağı orijinal sayfa numarası. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |
| actionName | Enum[] | Acrobat görüntüleyicisinde menü öğelerini yürütmekle ilgili eylemlerin (PredefinedAction enum'unun üyeleri) dizisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

PDF belgesinde bir web bağlantısı oluşturur.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| url | String | Web bağlantısı hedefi. |
| originalPage | Int32 | Web bağlantısıyla bağlı dikdörtgenin oluşturulacağı orijinal sayfa numarası. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

PDF belgesinde bir web bağlantısı oluşturur.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| url | String | Web bağlantısı hedefi. |
| originalPage | Int32 | Web bağlantısıyla bağlı dikdörtgenin oluşturulacağı orijinal sayfa numarası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)