---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Security.TimestampAlgorithmInfo. تمثل فئة لمعلومات خوارزمية توقيع الطابع الزمني
type: docs
weight: 10030
url: /ar/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

تمثل فئة لمعلومات خوارزمية توقيع الطابع الزمني.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | يحصل على اسم حقل التوقيع. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | يحول كائن المعلومات الحالي إلى تمثيله النصي. |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | يحصل على نوع خوارزمية التوقيع المستخدمة لتوقيع مستند PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | يحصل على خوارزمية التجزئة التي قامت بتجزئة محتوى المستند ثم قامت بتوقيعه باستخدام [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | يحصل على المعيار التشفيري المستخدم لتوقيع مستند PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | يحصل على خوارزمية تجزئة الهضم المستخدمة للتوقيع. بالنسبة للطابع الزمني، هذه هي خوارزمية تجزئة الهضم التي يتم بها توقيع تجزئة محتوى المستند. |

### See Also

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)