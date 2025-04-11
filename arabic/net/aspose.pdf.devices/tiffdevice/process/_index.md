---
title: TiffDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: طريقة TiffDevice. تحويل صفحات معينة من المستند إلى tiff وحفظها في تدفق الإخراج
type: docs
weight: 90
url: /ar/net/aspose.pdf.devices/tiffdevice/process/
---
## Process(Document, int, int, Stream) {#process}

تحويل صفحات معينة من المستند إلى tiff وحفظها في تدفق الإخراج.

```csharp
public override void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | المستند المراد تحويله. |
| fromPage | Int32 | يحدد رقم الصفحة التي سيبدأ منها التحويل. |
| toPage | Int32 | يحدد رقم الصفحة التي سينتهي عندها التحويل. |
| output | Stream | تدفق الإخراج مع صورة tiff. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Page, Stream) {#process_4}

```csharp
public override void Process(Page page, Stream output)
```

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)