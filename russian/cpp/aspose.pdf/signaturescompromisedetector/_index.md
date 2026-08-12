---
title: "Aspose::Pdf::SignaturesCompromiseDetector класс"
linktitle: "SignaturesCompromiseDetector"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::SignaturesCompromiseDetector class. Представляет класс для проверки компрометирующих подписей документа в C++."
type: docs
weight: 17300
url: /ru/cpp/aspose.pdf/signaturescompromisedetector/
---
## SignaturesCompromiseDetector class


Представляет класс для проверки компрометирующих подписей документа.

```cpp
class SignaturesCompromiseDetector : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Check](./check/)(System::SharedPtr\<Signatures::CompromiseCheckResult\>\&) | Проверьте цифровые подписи документа на наличие компрометации. |
| [SignaturesCompromiseDetector](./signaturescompromisedetector/)(const System::SharedPtr\<Document\>\&) | Создаёт экземпляр класса [SignaturesCompromiseDetector](./). |
## Примечания


Детектор проверяет только известные способы компрометации подписей. Проверка не может предоставить 100% гарантию отсутствия компрометации подписи и может дать ложный отрицательный результат для новых, неизвестных методов компрометации, отличающихся от тестируемых.
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
