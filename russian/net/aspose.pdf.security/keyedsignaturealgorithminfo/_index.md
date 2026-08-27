---
title: "Класс KeyedSignatureAlgorithmInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Security.KeyedSignatureAlgorithmInfo. Представляет класс, содержащий информацию о алгоритме подписи с ключом"
type: docs
weight: 10160
url: /ru/net/aspose.pdf.security/keyedsignaturealgorithminfo/
---
## KeyedSignatureAlgorithmInfo class

Представляет класс для информации о алгоритме подписи с ключом.

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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Получает тип алгоритма подписи, используемого для подписания PDF‑документа. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Получает криптографический стандарт, используемый для подписания PDF‑документа. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Получает алгоритм хеш‑суммы (digest) используемый для подписи. Для отметки времени это алгоритм хеш‑суммы, с помощью которого подписывается хеш содержимого документа. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Получает размер криптографического ключа, используемого алгоритмом подписи. |

### См. также

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


