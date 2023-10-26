---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates a bookmark with the specified action
type: docs
weight: 120
url: /net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

Creates a bookmark with the specified action.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | The title of the bookmark. |
| color | Color | The colour of the bookmark's title. |
| boldFlag | Boolean | The flag of bold attribution. |
| italicFlag | Boolean | The flag of italic attribution. |
| file | String | Another file or application required when the action type is "GoToR" or "Launch". |
| actionType | String | The action type. The value can be: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | The local destination or remote destination or URL. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


