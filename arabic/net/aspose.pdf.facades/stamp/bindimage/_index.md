---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة Stamp. تعيين الصورة كختم
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

تعيين الصورة كختم.

```csharp
public void BindImage(string imageFile)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageFile | String | اسم ملف الصورة والمسار. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

تعيين الصورة التي ستستخدم كختم.

```csharp
public void BindImage(Stream image)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | Stream | تدفق يحتوي على بيانات الصورة. |

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)