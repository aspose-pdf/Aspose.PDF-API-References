---
title: "Aspose::Pdf::Facades::PdfFileSignature::GetSignNames метод"
linktitle: "GetSignNames"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::GetSignNames метод. Получает имена всех непустых подписей в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature::GetSignNames method


Получает имена всех непустых подписей.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Pdf::Facades::PdfFileSignature::GetSignNames(bool onlyActive=true)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| onlyActive | bool | если true, вернуть только активные подписи; иначе вернуть все подписи. |

### ReturnValue

Возвращает IList<string>.

## Deprecated
Метод может генерировать одинаковые имена подписей, которые невозможно различить при проверке. Вместо этого используйте GetSignatureNames(bool onlyActive).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
