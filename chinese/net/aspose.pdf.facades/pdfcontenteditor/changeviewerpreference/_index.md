---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。更改视图首选项"
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

更改视图首选项。

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| viewerAttribution | Int32 | 在 ViewerPreference 类中定义的视图属性。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


