---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: Метод SignaturesCompromiseDetector. Проверьте цифровые подписи документа на наличие компрометации
type: docs
weight: 20
url: /ru/net/aspose.pdf/signaturescompromisedetector/check/
---
## Метод SignaturesCompromiseDetector.Check

Проверьте цифровые подписи документа на наличие компрометации.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | Результат проверки документа. |

### Возвращаемое значение

True, если компрометация подписей не обнаружена.

## Примечания

Использование этого метода для документа, в котором нет цифровых подписей, вернет `True`.

### См. также

* класс [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* класс [SignaturesCompromiseDetector](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)