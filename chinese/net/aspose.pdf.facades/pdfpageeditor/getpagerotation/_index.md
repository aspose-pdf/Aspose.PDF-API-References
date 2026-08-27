---
title: "PdfPageEditor.GetPageRotation"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfPageEditor 方法。返回指定页的旋转角度。"
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

返回指定页面的旋转角度。

```csharp
public int GetPageRotation(int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | Int32 | 页索引。文档页面从 1 开始编号。 |

### 返回值

页面旋转角度（度）。

## 示例

以下示例演示如何获取页面旋转角度：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### 另请参见

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


