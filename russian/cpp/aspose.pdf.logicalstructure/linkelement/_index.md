---
title: "Класс Aspose::Pdf::LogicalStructure::LinkElement"
linktitle: "LinkElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LogicalStructure::LinkElement. Представляет элемент структуры ссылки в логической структуре в C++."
type: docs
weight: 2900
url: /ru/cpp/aspose.pdf.logicalstructure/linkelement/
---
## LinkElement class


Представляет элемент структуры Link в логической структуре.

```cpp
class LinkElement : public Aspose::Pdf::LogicalStructure::AnnotationElement,
                    public Aspose::Pdf::LogicalStructure::ITextElement,
                    public Aspose::Pdf::Tagged::IAdjustPosition
```

## Методы

| Метод | Описание |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Hyperlink](./get_hyperlink/)() const | Получает или задает [Hyperlink](../../aspose.pdf/hyperlink/) для ссылки [Element](../element/). |
| [get_StructureTextState](./get_structuretextstate/)() override | Получает объект [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) для текущего элемента. |
| [set_Hyperlink](./set_hyperlink/)(const System::SharedPtr\<Aspose::Pdf::Hyperlink\>\&) | Получает или задает [Hyperlink](../../aspose.pdf/hyperlink/) для ссылки [Element](../element/). |
| [SetText](./settext/)(System::String) override | Добавляет текстовое содержимое к текущему текстовому элементу. |
## См. также

* Class [AnnotationElement](../annotationelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
