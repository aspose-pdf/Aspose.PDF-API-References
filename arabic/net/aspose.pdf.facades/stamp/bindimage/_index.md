---
title: "Stamp.BindImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Stamp. تعيين الصورة كختم"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

يعيّن الصورة كطابع.

```csharp
public void BindImage(string imageFile)
```

| معامل | النوع | الوصف |
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

يعيّن الصورة التي ستُستخدم كطابع.

```csharp
public void BindImage(Stream image)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صورة | Stream | دفق يحتوي على بيانات الصورة. |

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


