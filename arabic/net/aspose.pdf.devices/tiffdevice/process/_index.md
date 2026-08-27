---
title: "TiffDevice.Process"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TiffDevice. تحول صفحات مستند معينة إلى tiff وتحفظها في تدفق الإخراج"
type: docs
weight: 90
url: /ar/net/aspose.pdf.devices/tiffdevice/process/
---
## Process(Document, int, int, Stream) {#process}

يحوّل صفحات معينة من المستند إلى صيغة TIFF ويحفظها في تدفق الإخراج.

```csharp
public override void Process(Document document, int fromPage, int toPage, Stream output)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | المستند المراد تحويله. |
| fromPage | Int32 | يحدد رقم الصفحة التي سيبدأ التحويل منها. |
| toPage | Int32 | يحدد رقم الصفحة التي سيُنهي عندها التحويل. |
| الإخراج | Stream | دفق الإخراج مع صورة TIFF. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Page, Stream) {#process_4}

```csharp
public override void Process(Page page, Stream output)
```

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


