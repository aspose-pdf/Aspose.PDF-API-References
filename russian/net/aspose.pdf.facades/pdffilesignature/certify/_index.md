---
title: Certify
second_title: Aspose.PDF для справочника API .NET
description: Заверить документ подписью MDP. Такие данные как причина подписи контакт и местонахождение должны быть предоставлены соответствующими свойствами объекта Signature sig.
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Заверить документ подписью MDP. Такие данные, как причина подписи, контакт и местонахождение, должны быть предоставлены соответствующими свойствами объекта Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Страница, на которой делается подпись. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Место подписи. |
| visible | Boolean | Видимость подписи. |
| annotRect | Rectangle | Право подписи. |
| docMdpSignature | DocMDPSignature | Тип подписи документа MDP. |

### Смотрите также

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature)
* class [PdfFileSignature](../../pdffilesignature)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesignature)
* сборка [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Заверить документ подписью MDP, которая ставится в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf документе уже есть поле подписи, место для подписи указывать не нужно. штамп подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sigName | String | Имя поля подписи. |
| docMdpSignature | DocMDPSignature | Тип подписи может быть , а также |

### Смотрите также

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature)
* class [PdfFileSignature](../../pdffilesignature)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesignature)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
