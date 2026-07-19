---
title: "Класс Aspose::Pdf::LogicalStructure::TableCellElement"
linktitle: "TableCellElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LogicalStructure::TableCellElement. Представляет базовый класс для элементов ячеек таблицы (TH и TD) в логической структуре в C++."
type: docs
weight: 6000
url: /ru/cpp/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class


Представляет базовый класс для элементов ячеек таблицы (TH и TD) в логической структуре.

```cpp
class TableCellElement : public Aspose::Pdf::LogicalStructure::TableChildElement,
                         public Aspose::Pdf::LogicalStructure::ITextElement,
                         public Aspose::Pdf::Tagged::IAdjustPosition
```

## Методы

| Метод | Описание |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_Alignment](./get_alignment/)() const | Получает выравнивание ячейки. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Получает цвет фона ячейки. |
| [get_Border](./get_border/)() const | Получает границу ячейки. |
| [get_ColSpan](./get_colspan/)() const | Получает количество столбцов, охватываемых ячейкой. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Получает состояние текста ячейки по умолчанию. |
| [get_IsNoBorder](./get_isnoborder/)() const | Получает, есть ли у ячейки граница. |
| [get_IsWordWrapped](./get_iswordwrapped/)() const | Получает, переносится ли текст ячейки по словам. |
| [get_Margin](./get_margin/)() const | Получает отступ. |
| [get_RowSpan](./get_rowspan/)() const | Получает количество строк, охватываемых ячейкой. |
| [get_StructureTextState](./get_structuretextstate/)() override | Получает объект [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) для текущего элемента. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Получает вертикальное выравнивание. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Устанавливает выравнивание ячейки. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Устанавливает цвет фона ячейки. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Устанавливает границу ячейки. |
| [set_ColSpan](./set_colspan/)(int32_t) | Устанавливает охват столбца. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Устанавливает состояние текста ячейки по умолчанию. |
| [set_IsNoBorder](./set_isnoborder/)(bool) | Устанавливает наличие границы у ячейки. |
| [set_IsWordWrapped](./set_iswordwrapped/)(bool) | Устанавливает перенос слов в тексте ячейки. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает отступ. |
| [set_RowSpan](./set_rowspan/)(int32_t) | Устанавливает охват строки. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Устанавливает вертикальное выравнивание. |
| [SetText](./settext/)(System::String) override | Добавляет текстовое содержимое к текущему текстовому элементу. |
## См. также

* Class [TableChildElement](../tablechildelement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
