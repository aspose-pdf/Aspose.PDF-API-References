---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 方法。根据指定的书签标题修改书签标题
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks 方法

根据指定的书签标题修改书签标题。

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sTitle | 字符串 | 源书签标题。 |
| dTitle | 字符串 | 修改后的书签标题。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfBookmarkEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)