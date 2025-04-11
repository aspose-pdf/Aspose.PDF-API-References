---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。更改视图偏好
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference 方法

更改视图偏好。

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| viewerAttribution | Int32 | 在 ViewerPreference 类中定义的视图归属。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)