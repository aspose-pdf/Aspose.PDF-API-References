---
title: "Класс EcdsaAlgorithmInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Security.EcdsaAlgorithmInfo. Представляет класс, содержащий информацию о алгоритме подписи ECDSA"
type: docs
weight: 10130
url: /ru/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo class

Представляет класс для информации о алгоритме подписи ECDSA.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Получает имя поля подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Преобразует текущий объект информации в его строковое представление. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Получает тип алгоритма подписи, используемого для подписания PDF‑документа. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Получает криптографический стандарт, используемый для подписания PDF‑документа. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Получает алгоритм хеш‑суммы (digest) используемый для подписи. Для отметки времени это алгоритм хеш‑суммы, с помощью которого подписывается хеш содержимого документа. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Получает название эллиптической кривой, используемой в ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Получает размер криптографического ключа, используемого алгоритмом подписи. |

### См. также

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


