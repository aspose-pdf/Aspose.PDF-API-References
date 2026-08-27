---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。返回视图首选项"
type: docs
weight: 390
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

返回视图首选项。

```csharp
public int GetViewerPreference()
```

### 返回值

返回 ViewerPrefernece 标志集合

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


