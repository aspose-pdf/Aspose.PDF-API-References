---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Делегат для пользовательской подписи хеша документа
type: docs
weight: 5260
url: /ru/net/aspose.pdf.forms/signhash/
---
## Делегат SignHash

Делегат для пользовательской подписи хеша документа.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | Byte[] | Входной хеш документа. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм дайджеста, используемый для создания хеша. Значение никогда не будет равно Auto. |

### Возвращаемое значение

Выходная подпись.

## Примечания

Обратите внимание, что независимо от того, является ли цифровая подпись отделенной или нет, аргумент хеша всегда будет окончательным хешем, который нужно подписать.

### См. также

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)