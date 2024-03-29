---
title: ModifyBookmarks
second_title: Aspose.PDF for .NET API 参考
description: 根据指定的书签标题修改书签标题
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

根据指定的书签标题修改书签标题。

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sTitle | String | 源书签标题。 |
| dTitle | String | 修改书签标题。 |

### 例子

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
