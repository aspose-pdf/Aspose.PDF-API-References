---
title: "Aspose::Pdf::Annotations::FitBVExplicitDestination class"
linktitle: "FitBVExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FitBVExplicitDestination class. Представляет явный пункт назначения, который отображает страницу с горизонтальной координатой left, расположенной у левого края окна, и содержимое страницы увеличивается настолько, чтобы полностью вписать высоту её ограничивающего прямоугольника в окно. Значение null для left указывает, что текущее значение этого параметра должно оставаться без изменений в C++."
type: docs
weight: 3400
url: /ru/cpp/aspose.pdf.annotations/fitbvexplicitdestination/
---
## FitBVExplicitDestination class


Представляет явную точку назначения, отображающую страницу, при этом горизонтальная координата left размещается у левого края окна, а содержимое страницы увеличивается настолько, чтобы вся высота её ограничивающего прямоугольника помещалась в окне. Значение null для left указывает, что текущие значения этого параметра сохраняются без изменений.

```cpp
class FitBVExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Методы

| Метод | Описание |
| --- | --- |
| [FitBVExplicitDestination](./fitbvexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Создаёт локальное явное назначение. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Создаёт удалённое явное назначение. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/)(int32_t, double) | Создаёт удалённое явное назначение. |
| [get_Left](./get_left/)() | Получает горизонтальную координату left, расположенную у левого края окна. |
| [ToString](./tostring/)() const override | Преобразует состояние объекта в строковое значение. Пример: "1 FitBV 100". |
## См. также

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
