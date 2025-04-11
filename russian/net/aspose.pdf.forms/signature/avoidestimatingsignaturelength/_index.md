---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Свойство Signature. Получает и устанавливает опцию, означающую, следует ли избегать оценки длины подписи
type: docs
weight: 30
url: /ru/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Свойство Signature.AvoidEstimatingSignatureLength

Получает и устанавливает опцию, означающую, следует ли избегать оценки длины подписи.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Примечания

Избегает оценки длины подписи перед подписанием документа. Используется для подписания через [`CustomSignHash`](../customsignhash/) и через [`ExternalSignature`](../../externalsignature/). Если [`CustomSignHash`](../customsignhash/) возвращает подпись длиной больше, чем [`DefaultSignatureLength`](../defaultsignaturelength/), то будет выброшено исключение [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). Значение по умолчанию — `false`.

### См. также

* класс [Signature](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)