---
title: "Stamp.BindImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "Stamp 方法。将图像设置为印章。"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

将图像设置为印章。

```csharp
public void BindImage(string imageFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | String | 图像文件名和路径。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

设置将用作印章的图像。

```csharp
public void BindImage(Stream image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | Stream | 包含图像数据的流。 |

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


