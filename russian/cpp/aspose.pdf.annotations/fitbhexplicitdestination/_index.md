---
title: "Aspose::Pdf::Annotations::FitBHExplicitDestination class"
linktitle: "FitBHExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FitBHExplicitDestination class. Представляет явный пункт назначения, который отображает страницу с вертикальной координатой top, расположенной у верхнего края окна, и содержимое страницы увеличивается настолько, чтобы полностью вписать ширину её ограничивающего прямоугольника в окно. Значение null для top указывает, что текущее значение этого параметра должно оставаться неизменным в C++."
type: docs
weight: 3300
url: /ru/cpp/aspose.pdf.annotations/fitbhexplicitdestination/
---
## FitBHExplicitDestination class


Представляет явную точку назначения, отображающую страницу, при этом вертикальная координата top размещается у верхнего края окна, а содержимое страницы увеличивается настолько, чтобы вся ширина её ограничивающего прямоугольника помещалась в окне. Значение null для top указывает, что текущие значения этого параметра сохраняются без изменений.

```cpp
class FitBHExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Методы

| Метод | Описание |
| --- | --- |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Создаёт локальное явное назначение. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Создаёт удалённое явное назначение. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(int32_t, double) | Создаёт удалённое явное назначение. |
| [get_Top](./get_top/)() | Получает вертикальную координату top, расположенную у верхнего края окна. |
| [ToString](./tostring/)() const override | Преобразует состояние объекта в строковое значение. Пример: "1 FitBH 100". |
## См. также

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
