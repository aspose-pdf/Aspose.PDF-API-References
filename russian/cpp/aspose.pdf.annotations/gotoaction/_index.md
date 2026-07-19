---
title: "Aspose::Pdf::Annotations::GoToAction класс"
linktitle: "GoToAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::GoToAction класс. Представляет действие перехода, которое изменяет вид на указанное назначение (страницу, место и коэффициент увеличения) в C++."
type: docs
weight: 4300
url: /ru/cpp/aspose.pdf.annotations/gotoaction/
---
## GoToAction class


Представляет действие перехода (go-to), которое изменяет вид на указанную точку назначения (страницу, местоположение и коэффициент масштабирования).

```cpp
class GoToAction : public Aspose::Pdf::Annotations::PdfAction
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_Destination](./get_destination/)() | Получает назначение для перехода. |
| [GoToAction](./gotoaction/)(int32_t) | Конструктор класса [GoToAction](./). |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<Page\>\&) | Конструктор класса [GoToAction](./). |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Конструктор класса [GoToAction](./). |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<ExplicitDestination\>\&) | Конструктор. |
| [GoToAction](./gotoaction/)() | Конструктор. |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<Document\>\&, const System::String\&) | Действие, связанное с именованным назначением. |
| virtual [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) | Устанавливает назначение для перехода. |
## См. также

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
