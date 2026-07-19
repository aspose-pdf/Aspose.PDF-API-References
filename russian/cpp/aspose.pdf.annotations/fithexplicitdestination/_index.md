---
title: "Aspose::Pdf::Annotations::FitHExplicitDestination класс"
linktitle: "FitHExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FitHExplicitDestination класс. Представляет явный пункт назначения, который отображает страницу с вертикальной координатой top, расположенной у верхнего края окна, и содержимое страницы увеличивается ровно настолько, чтобы вся ширина страницы помещалась в окне. Значение null для top указывает, что текущее значение этого параметра должно оставаться без изменений в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.pdf.annotations/fithexplicitdestination/
---
## FitHExplicitDestination class


Представляет явную точку назначения, отображающую страницу, при этом вертикальная координата top размещается у верхнего края окна, а содержимое страницы увеличивается настолько, чтобы вся её ширина полностью помещалась в окне. Значение null для top указывает, что текущие значения этого параметра сохраняются без изменений.

```cpp
class FitHExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Методы

| Метод | Описание |
| --- | --- |
| [FitHExplicitDestination](./fithexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Создаёт локальное явное назначение. |
| [FitHExplicitDestination](./fithexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Создаёт удалённое явное назначение. |
| [FitHExplicitDestination](./fithexplicitdestination/)(int32_t, double) | Создаёт удалённое явное назначение. |
| [get_Top](./get_top/)() | Получает вертикальную координату top, расположенную у верхнего края окна. |
| [ToString](./tostring/)() const override | Преобразует состояние объекта в строковое значение. Пример: "1 FitH 100". |
## См. также

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
