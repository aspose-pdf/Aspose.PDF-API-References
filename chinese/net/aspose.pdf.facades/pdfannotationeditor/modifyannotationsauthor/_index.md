---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。修改指定页面范围内注释的作者
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor 方法

修改指定页面范围内注释的作者。

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页码。 |
| end | Int32 | 结束页码。 |
| srcAuthor | String | 必须修改的作者。 |
| desAuthor | String | 新的作者。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)