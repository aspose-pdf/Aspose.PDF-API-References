---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSignature. Удостоверить документ с помощью подписи MDP. Такие данные, как причина подписи, контакт и местоположение, должны быть предоставлены соответствующими свойствами объекта Signature sig
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Удостоверить документ с помощью подписи MDP. Такие данные, как причина подписи, контакт и местоположение, должны быть предоставлены соответствующими свойствами объекта Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Страница, на которой сделана подпись. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Местоположение подписи. |
| visible | Boolean | Видимость подписи. |
| annotRect | Rectangle | Прямоугольник подписи. |
| docMdpSignature | DocMDPSignature | Тип подписи документа MDP. |

### См. также

* класс [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Удостоверить документ с помощью подписи MDP, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, если в документе PDF уже есть поле подписи, вам не нужно указывать место для штампа подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sigName | String | Имя поля подписи. |
| docMdpSignature | DocMDPSignature | Тип подписи, может быть [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) и [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### См. также

* класс [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)