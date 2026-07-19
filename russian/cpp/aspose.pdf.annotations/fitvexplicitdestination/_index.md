---
title: "Aspose::Pdf::Annotations::FitVExplicitDestination class"
linktitle: "FitVExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FitVExplicitDestination class. Представляет явный пункт назначения, который отображает страницу с горизонтальной координатой left, расположенной у левого края окна, и содержимое страницы увеличивается ровно настолько, чтобы полностью поместить высоту страницы в окно. Значение null для left указывает, что текущее значение этого параметра должно оставаться без изменений в C++."
type: docs
weight: 3800
url: /ru/cpp/aspose.pdf.annotations/fitvexplicitdestination/
---
## FitVExplicitDestination class


Представляет явную точку назначения, отображающую страницу, при этом горизонтальная координата left размещается у левого края окна, а содержимое страницы увеличивается настолько, чтобы вся её высота полностью помещалась в окне. Значение null для left указывает, что текущие значения этого параметра сохраняются без изменений.

```cpp
class FitVExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Методы

| Метод | Описание |
| --- | --- |
| [FitVExplicitDestination](./fitvexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Создаёт локальное явное назначение. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Создаёт удалённое явное назначение. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(int32_t, double) | Создаёт удалённое явное назначение. |
| [get_Left](./get_left/)() | Получает горизонтальную координату left, расположенную у левого края окна. |
| [ToString](./tostring/)() const override | Преобразует состояние объекта в строковое значение. Пример: "1 FitV 100". |
## См. также

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
