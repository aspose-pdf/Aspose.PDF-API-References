---
title: Class EcdsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Security.EcdsaAlgorithmInfo. Представляет класс для информации о алгоритме подписи ECDSA
type: docs
weight: 9970
url: /ru/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo class

Представляет класс для информации о алгоритме подписи ECDSA.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Получает имя поля подписи. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Преобразует текущий объект информации в его строковое представление. |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Получает тип алгоритма подписи, используемого для подписания PDF-документа. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Получает криптографический стандарт, используемый для подписания PDF-документа. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Получает алгоритм хеширования дайджеста, используемый для подписи. Для временной метки это алгоритм хеширования дайджеста, с помощью которого подписывается хеш содержимого документа. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Получает имя эллиптической кривой, используемой ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Получает размер криптографического ключа, используемого алгоритмом подписи. |

### See Also

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)