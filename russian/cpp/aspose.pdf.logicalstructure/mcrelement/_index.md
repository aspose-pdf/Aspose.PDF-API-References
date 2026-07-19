---
title: "Класс Aspose::Pdf::LogicalStructure::MCRElement"
linktitle: "MCRElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LogicalStructure::MCRElement. Представляет объект ссылки на отмеченный контент в логической структуре в C++."
type: docs
weight: 3500
url: /ru/cpp/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement class


Представляет объект ссылки на отмеченное содержимое в логической структуре.

```cpp
class MCRElement : public Aspose::Pdf::LogicalStructure::Element
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_MCID](./get_mcid/)() | Получает MCID объекта ссылки на отмеченный контент. |
| [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) override | Привязать элемент структуры к оператору BDC потока содержимого. |
| [Tag](./tag/)(System::SharedPtr\<XForm\>) override | Привязать элемент структуры к потоку содержимого [XForm](../../aspose.pdf/xform/). |
| [Tag](./tag/)(System::SharedPtr\<XImage\>) override | Привязать элемент структуры к [XImage](../../aspose.pdf/ximage/). |
| [Tag](./tag/)(System::SharedPtr\<Artifact\>) override | Привязать элемент структуры к [Artifact](../../aspose.pdf/artifact/). |
| [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) override | Привязать элемент структуры к аннотации. |
| [ToString](./tostring/)() const override | Возвращает строку, представляющую текущий объект. |
## См. также

* Class [Element](../element/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
