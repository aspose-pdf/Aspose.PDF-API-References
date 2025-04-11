---
title: Class DsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Security.DsaAlgorithmInfo. تمثل فئة لمعلومات حول خوارزمية توقيع DSA
type: docs
weight: 9960
url: /ar/net/aspose.pdf.security/dsaalgorithminfo/
---
## DsaAlgorithmInfo class

تمثل فئة لمعلومات حول خوارزمية توقيع DSA.

```csharp
public sealed class DsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | يحصل على اسم حقل التوقيع. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | يحول كائن المعلومات الحالي إلى تمثيله كسلسلة. |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | يحصل على نوع خوارزمية التوقيع المستخدمة لتوقيع مستند PDF. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | يحصل على المعيار التشفيري المستخدم لتوقيع مستند PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | يحصل على خوارزمية تجزئة التوقيع المستخدمة للتوقيع. بالنسبة للطابع الزمني، هذه هي خوارزمية تجزئة التوقيع التي يتم بها توقيع تجزئة محتوى المستند. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | يحصل على حجم المفتاح التشفيري المستخدم بواسطة خوارزمية التوقيع. |

### See Also

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)