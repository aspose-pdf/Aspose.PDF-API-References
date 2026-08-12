---
title: "Aspose::Pdf::Facades::Facade class"
linktitle: "Facade"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::Facade class. Базовый фасадный класс в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.facades/facade/
---
## Facade class


Базовый фасадный класс.

```cpp
class Facade : public virtual Aspose::Pdf::Facades::IFacade,
               public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Инициализирует фасад. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Инициализирует фасад. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Инициализирует фасад. |
| [Close](./close/)() override | Освобождает [Aspose.Pdf.Document](../../aspose.pdf/document/) связанный с фасадом. |
| [Dispose](./dispose/)() override | Освобождает фасад. |
| [get_Document](./get_document/)() const | Получает фасад документа, над которым работает. |
## См. также

* Class [IFacade](../ifacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
