---
title: "Aspose::Pdf::Annotations::ExplicitDestination class"
linktitle: "ExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::ExplicitDestination class. Представляет базовый класс для явных назначений в PDF‑документе на C++."
type: docs
weight: 2700
url: /ru/cpp/aspose.pdf.annotations/explicitdestination/
---
## ExplicitDestination class


Представляет базовый класс для явных точек назначения в PDF‑документе.

```cpp
class ExplicitDestination : public Aspose::Pdf::Annotations::IAppointment
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CreateDestination](./createdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Создаёт экземпляры наследников [ExplicitDestination](./). |
| static [CreateDestination](./createdestination/)(const System::SharedPtr\<Document\>\&, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Создаёт экземпляры наследников [ExplicitDestination](./). |
| static [CreateDestination](./createdestination/)(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Создаёт экземпляры наследников [ExplicitDestination](./). |
| [get_Page](./get_page/)() const | Получает объект целевой страницы. |
| [get_PageNumber](./get_pagenumber/)() const | Получает номер целевой страницы. |
| virtual [ToString](./tostring/)() const | Возвращает строковое представление объекта [ExplicitDestination](./). |
## См. также

* Class [IAppointment](../iappointment/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
