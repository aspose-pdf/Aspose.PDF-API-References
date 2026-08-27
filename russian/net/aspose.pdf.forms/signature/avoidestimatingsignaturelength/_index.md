---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Signature. Получает и задаёт параметр, определяющий, следует ли избегать оценки длины подписи."
type: docs
weight: 30
url: /ru/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Примечания

Избегает оценки длины подписи до подписываемого документа. Используется для подписи через [`CustomSignHash`](../customsignhash/) и через [`ExternalSignature`](../../externalsignature/). Если [`CustomSignHash`](../customsignhash/) возвращает подпись, длина которой превышает [`DefaultSignatureLength`](../defaultsignaturelength/), будет выброшено исключение [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). Значение по умолчанию — `false`.

### См. также

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


