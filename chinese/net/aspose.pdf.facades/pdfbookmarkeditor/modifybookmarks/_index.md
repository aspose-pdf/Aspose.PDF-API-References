---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfBookmarkEditor 方法。根据指定的书签标题修改书签标题"
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

根据指定的书签标题修改书签标题。

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sTitle | String | 源书签标题。 |
| dTitle | String | 已修改的书签标题。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


