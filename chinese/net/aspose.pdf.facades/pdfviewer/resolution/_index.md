---
title: "PdfViewer.Resolution"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfViewer 属性。获取或设置在查看和打印期间的分辨率。分辨率越高，速度越慢。默认值为 150。"
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

获取或设置查看和打印时的分辨率。分辨率越高，速度越慢。默认值为 150。

```csharp
public int Resolution { get; set; }
```

## 备注

此属性在页面转图像的转换流程中更改图像分辨率：当 [`PrintAsImage`](../printasimage/) 设置为 `true`，或调用 [`DecodePage`](../decodepage/) 或 [`DecodeAllPages`](../decodeallpages/) 方法时。若要为直接打印到打印机设置打印机分辨率，请在 [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) 类中使用 [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) 属性。

### 另请参见

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


