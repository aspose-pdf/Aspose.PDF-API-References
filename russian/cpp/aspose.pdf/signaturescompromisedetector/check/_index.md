---
title: "Метод Aspose::Pdf::SignaturesCompromiseDetector::Check"
linktitle: "Отметка"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::SignaturesCompromiseDetector::Check. Проверяет цифровые подписи документа на компрометацию в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector::Check method


Проверьте цифровые подписи документа на наличие компрометации.

```cpp
bool Aspose::Pdf::SignaturesCompromiseDetector::Check(System::SharedPtr<Signatures::CompromiseCheckResult> &compromiseCheckResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| compromiseCheckResult | System::SharedPtr\<Signatures::CompromiseCheckResult\>\& | Результат проверки документа. |

### ReturnValue

True, если компрометация подписей не обнаружена.
## Примечания



Использование этого метода для документа, в котором нет цифровых подписей, вернёт **True**.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* Class [SignaturesCompromiseDetector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
