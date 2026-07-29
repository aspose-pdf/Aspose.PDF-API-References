---
title: "Stamp.Rotation"
second_title: "Aspose.PDF for .NET API 参考"
description: "Stamp 属性。获取或设置印章的旋转角度（以度为单位）。"
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

获取或设置印章的旋转角度（以度为单位）。

```csharp
public float Rotation { get; set; }
```

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


