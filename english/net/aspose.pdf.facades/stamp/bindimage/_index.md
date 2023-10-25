---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Stamp method. Sets image as a stamp
type: docs
weight: 100
url: /net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Sets image as a stamp.

```csharp
public void BindImage(string imageFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Image file name and path. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Sets image which will be used as stamp.

```csharp
public void BindImage(Stream image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream which contains image data. |

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


