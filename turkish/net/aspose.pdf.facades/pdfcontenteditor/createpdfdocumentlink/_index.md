---
title: PdfContentEditor.CreatePdfDocumentLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Başka bir PDF belge sayfasına bağlantı oluşturur
type: docs
weight: 220
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

Başka bir PDF belge sayfasına bağlantı oluşturur.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| remotePdf | String | Açılacak PDF belgesinin sayfası. |
| originalPage | Int32 | Bağlantı ile birlikte dikdörtgenin oluşturulacağı orijinal sayfa numarası. |
| destinationPage | Int32 | Hedef sayfa. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |
| actionName | Enum[] | Acrobat görüntüleyicisinde menü öğelerini çalıştırmakla ilgili eylemlerin (PredefinedAction enum'unun üyeleri) dizisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

Başka bir PDF belge sayfasına bağlantı oluşturur.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| remotePdf | String | Açılacak PDF belgesinin sayfası. |
| originalPage | Int32 | Bağlantı ile birlikte dikdörtgenin oluşturulacağı orijinal sayfa numarası. |
| destinationPage | Int32 | Hedef sayfa. |
| clr | Color | Aktif tıklama için dikdörtgenin rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

Başka bir PDF belge sayfasına bağlantı oluşturur.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| remotePdf | String | Açılacak PDF belgesinin sayfası. |
| originalPage | Int32 | Bağlantı ile birlikte dikdörtgenin oluşturulacağı orijinal sayfa numarası. |
| destinationPage | Int32 | Hedef sayfa. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)