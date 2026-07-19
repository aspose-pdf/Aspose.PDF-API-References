---
title: "Класс Aspose::Pdf::Flow::IStructureRecognitionVisitor"
linktitle: "IStructureRecognitionVisitor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Flow::IStructureRecognitionVisitor. Базовый интерфейс для пользовательского посетителя распознавания структуры документа в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.flow/istructurerecognitionvisitor/
---
## IStructureRecognitionVisitor class


Базовый интерфейс для пользовательского посетителя распознавания структуры документа.

```cpp
class IStructureRecognitionVisitor : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [EndDocument](./enddocument/)() | Сигнализирует о завершении обработки документа. |
| virtual [StartDocument](./startdocument/)() | Вызывается, когда начинается обход документа. |
| virtual [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) | Вызывается, когда посещается узел абзаца. |
| virtual [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) | Посещает конец распознанного раздела в документе. |
| virtual [VisitTable](./visittable/)(System::SharedPtr\<Table\>) | Посещает распознанную таблицу в структуре документа. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
