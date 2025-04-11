---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 方法。返回指定页面的旋转
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation 方法

返回指定页面的旋转。

```csharp
public int GetPageRotation(int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 页面索引。文档页面从 1 开始编号。 |

### 返回值

页面旋转角度（以度为单位）。

## 示例

以下示例演示如何获取页面旋转：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### 另请参阅

* 类 [PdfPageEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)