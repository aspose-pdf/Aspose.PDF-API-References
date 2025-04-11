---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen eylemle bir yer imi oluşturur
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction metodu

Belirtilen eylemle bir yer imi oluşturur.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| title | String | Yer iminin başlığı. |
| color | Color | Yer iminin başlığının rengi. |
| boldFlag | Boolean | Kalın atıf bayrağı. |
| italicFlag | Boolean | İtalik atıf bayrağı. |
| file | String | Eylem türü "GoToR" veya "Launch" olduğunda gereken başka bir dosya veya uygulama. |
| actionType | String | Eylem türü. Değer şunlar olabilir: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Yerel hedef veya uzak hedef veya URL. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)