---
title: "Класс Aspose::Pdf::Flow::StructureRecognitionVisitor"
linktitle: "StructureRecognitionVisitor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Flow::StructureRecognitionVisitor. Базовый класс для пользовательского посетителя распознавания структуры документа в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.flow/structurerecognitionvisitor/
---
## StructureRecognitionVisitor class


Базовый класс для пользовательского посетителя распознавания структуры документа.

```cpp
class StructureRecognitionVisitor : public Aspose::Pdf::Flow::IStructureRecognitionVisitor
```

## Методы

| Метод | Описание |
| --- | --- |
| [EndDocument](./enddocument/)() override | Сигнализирует о завершении обработки документа. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Document\>) | Начать распознавание документа. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Page\>) | Начать распознавание страницы. |
| [StartDocument](./startdocument/)() override | Вызывается, когда начинается обход документа. |
| [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) override | Вызывается, когда посещается узел абзаца. |
| [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) override | Посещает конец распознанного раздела в документе. |
| [VisitTable](./visittable/)(System::SharedPtr\<Table\>) override | Посещает распознанную таблицу в структуре документа. |
## См. также

* Class [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
