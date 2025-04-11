---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建具有指定操作的书签
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction 方法

创建具有指定操作的书签。

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| title | 字符串 | 书签的标题。 |
| color | 颜色 | 书签标题的颜色。 |
| boldFlag | 布尔值 | 粗体属性的标志。 |
| italicFlag | 布尔值 | 斜体属性的标志。 |
| file | 字符串 | 当操作类型为 "GoToR" 或 "Launch" 时所需的另一个文件或应用程序。 |
| actionType | 字符串 | 操作类型。值可以是： "GoToR", "Launch", "GoTo", "URI"。 |
| destination | 字符串 | 本地目标或远程目标或 URL。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)