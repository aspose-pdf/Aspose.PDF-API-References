---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSignature. Извлекает отдельный сертификат X.509 подписи"
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Извлекает единственный сертификат X.509 подписи.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |
| сертификат | X509Certificate2& | Если сертификат найден, возвращает объект отдельного сертификата X.509; иначе — null. |

### Возвращаемое значение

Сертификат найден.

### См. также

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Извлекает единственный сертификат X.509 подписи в виде потока.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |
| stream | Stream& | Если сертификат найден, возвращает поток отдельного сертификата X.509; иначе — null. |

### Возвращаемое значение

Сертификат найден.

### См. также

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


