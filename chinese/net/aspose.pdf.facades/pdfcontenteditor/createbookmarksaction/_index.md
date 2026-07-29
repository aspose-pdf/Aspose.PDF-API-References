---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建具有指定操作的书签"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

使用指定操作创建书签。

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| title | String | 书签的标题。 |
| 颜色 | Color | 书签标题的颜色。 |
| boldFlag | Boolean | 粗体属性的标志。 |
| italicFlag | Boolean | 斜体属性的标志。 |
| file | String | 当操作类型为 "GoToR" 或 "Launch" 时，需要另一个文件或应用程序。 |
| actionType | String | 操作类型。其值可以是："GoToR"、"Launch"、"GoTo"、"URI"。 |
| destination | String | 本地目标、远程目标或 URL。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


