---
title: "PdfFileStamp.AddStamp"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileStamp 方法。向文件添加印章"
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

在文件添加印章。

```csharp
public void AddStamp(Stamp stamp)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 印章 | 印章 | 印章对象。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


