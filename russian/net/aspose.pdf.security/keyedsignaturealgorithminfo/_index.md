---
title: Class KeyedSignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Security.KeyedSignatureAlgorithmInfo. Представляет класс для информации о алгоритме подписания с ключом
type: docs
weight: 9980
url: /ru/net/aspose.pdf.security/keyedsignaturealgorithminfo/
---
## Класс KeyedSignatureAlgorithmInfo

Представляет класс для информации о алгоритме подписания с ключом.

```csharp
public abstract class KeyedSignatureAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Получает тип алгоритма подписи, используемого для подписания PDF документа. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Получает криптографический стандарт, используемый для подписания PDF документа. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Получает алгоритм хеширования дайджеста, используемый для подписи. Для временной метки это алгоритм хеширования дайджеста, с помощью которого подписывается хеш содержимого документа. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Получает размер криптографического ключа, используемого алгоритмом подписи. |

### См. также

* класс [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* пространство имен [Aspose.Pdf.Security](../../aspose.pdf.security/)
* сборка [Aspose.PDF](../../)