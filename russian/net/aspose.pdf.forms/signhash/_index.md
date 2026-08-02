---
title: "Делегат SignHash"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Делегат для пользовательской подписи хеша документа"
type: docs
weight: 5380
url: /ru/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Делегат для пользовательского подписания хэша документа.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| хеш | Byte[] | Входной хеш документа. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм дайджеста, используемый для создания хеша. Значение никогда не будет равно Auto. |

### Возвращаемое значение

Выходная подпись.

## Примечания

Обратите внимание, что независимо от того, отсоединена ли цифровая подпись или нет, аргумент hash всегда будет окончательным хешем для подписи.

### См. также

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


