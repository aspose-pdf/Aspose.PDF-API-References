---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Security.TimestampAlgorithmInfo. Представляет класс для информации о алгоритме подписи временной метки
type: docs
weight: 10030
url: /ru/net/aspose.pdf.security/timestampalgorithminfo/
---
## Класс TimestampAlgorithmInfo

Представляет класс для информации о алгоритме подписи временной метки.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Получает алгоритм хеширования, который хешировал содержимое документа, а затем подписал его с использованием [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Получает криптографический стандарт, используемый для подписания PDF документа. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Получает алгоритм хеширования дайджеста, используемый для подписи. Для временной метки это алгоритм хеширования дайджеста, с помощью которого подписывается хеш содержимого документа. |

### См. также

* класс [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* пространство имен [Aspose.Pdf.Security](../../aspose.pdf.security/)
* сборка [Aspose.PDF](../../)