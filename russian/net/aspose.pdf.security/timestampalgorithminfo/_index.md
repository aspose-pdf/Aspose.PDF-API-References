---
title: "Класс TimestampAlgorithmInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Security.TimestampAlgorithmInfo. Представляет класс, содержащий информацию об алгоритме подписи с отметкой времени."
type: docs
weight: 10210
url: /ru/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

Представляет класс для информации о алгоритме подписи с меткой времени.

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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Получает тип алгоритма подписи, используемого для подписания PDF‑документа. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Получает алгоритм хеширования, который хешировал содержимое документа, а затем подписал его с помощью [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Получает криптографический стандарт, используемый для подписания PDF‑документа. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Получает алгоритм хеш‑суммы (digest) используемый для подписи. Для отметки времени это алгоритм хеш‑суммы, с помощью которого подписывается хеш содержимого документа. |

### См. также

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


