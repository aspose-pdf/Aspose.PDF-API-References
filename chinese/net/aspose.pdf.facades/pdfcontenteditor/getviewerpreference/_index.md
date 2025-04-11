---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。返回视图偏好
type: docs
weight: 390
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference 方法

返回视图偏好。

```csharp
public int GetViewerPreference()
```

### 返回值

返回一组 ViewerPrefernece 标志

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)