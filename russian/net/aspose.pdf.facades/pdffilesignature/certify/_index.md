---
title: "PdfFileSignature.Certify"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileSignature. Сертифицирует документ с помощью MDP‑подписи. Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig"
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Сертифицируйте документ с помощью MDP‑подписи. Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Int32 | Страница, на которой выполнена подпись. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Местоположение подписи. |
| видимый | Boolean | Видимость подписи. |
| annotRect | Rectangle | Прямоугольник подписи. |
| docMdpSignature | DocMDPSignature | Тип MDP документа подписи. |

### См. также

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Сертифицируйте документ с помощью MDP‑подписи, размещённой в уже существующем поле подписи. Перед подписанием поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sigName | String | Имя поля подписи. |
| docMdpSignature | DocMDPSignature | Тип подписи, может быть [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) и [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### См. также

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


