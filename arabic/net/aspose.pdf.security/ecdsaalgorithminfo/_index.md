---
title: Class EcdsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Security.EcdsaAlgorithmInfo. تمثل فئة لمعلومات حول خوارزمية توقيع ECDSA
type: docs
weight: 9970
url: /ar/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo class

تمثل فئة لمعلومات حول خوارزمية توقيع ECDSA.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | يحصل على المعيار التشفيري المستخدم لتوقيع مستند PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | يحصل على خوارزمية تجزئة الهضم المستخدمة للتوقيع. بالنسبة للتوقيت، هذه هي خوارزمية تجزئة الهضم التي يتم بها توقيع تجزئة محتوى المستند. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | يحصل على اسم المنحنى البياني المستخدم بواسطة ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | يحصل على حجم المفتاح التشفيري المستخدم بواسطة خوارزمية التوقيع. |

### See Also

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)