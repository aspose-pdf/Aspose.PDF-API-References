---
title: "Aspose::Pdf::Cell класс"
linktitle: "Cell"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Cell класс. Представляет ячейку строки таблицы в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf/cell/
---
## Cell class


Представляет ячейку строки таблицы.

```cpp
class Cell : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Cell](./cell/)(const System::SharedPtr\<Rectangle\>\&) | Инициализирует новый экземпляр класса [Cell](./). |
| [Cell](./cell/)() | Инициализирует новый экземпляр класса [Cell](./). |
| [Clone](./clone/)() override | Клонировать ячейку. |
| [get_Alignment](./get_alignment/)() const | Получает выравнивание. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Получает цвет фона. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Получает фоновое изображение. |
| [get_BackgroundImageFile](./get_backgroundimagefile/)() const | Получает файл фонового изображения. |
| [get_Border](./get_border/)() const | Получает границу. |
| [get_ColSpan](./get_colspan/)() const | Получает количество столбцов, охватываемых ячейкой. |
| [get_DefaultCellTextState](./get_defaultcelltextstate/)() | Получает состояние текста ячейки по умолчанию. |
| [get_IsNoBorder](./get_isnoborder/)() const | Получает, есть ли у ячейки граница. |
| [get_IsOverrideByFragment](./get_isoverridebyfragment/)() const | Устанавливает свойство TextState ячейки, переопределяется свойством TextState TextFragment. |
| [get_IsWordWrapped](./get_iswordwrapped/)() const | Получает, переносится ли текст ячейки по словам. |
| [get_Margin](./get_margin/)() const | Получает отступ. |
| [get_Paragraphs](./get_paragraphs/)() const | Получает отформатированный текст ячейки. |
| [get_RowSpan](./get_rowspan/)() const | Получает количество строк, охватываемых ячейкой. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Получает вертикальное выравнивание. |
| [get_Width](./get_width/)() const | Получает ширину столбца. |
| [set_Alignment](./set_alignment/)(HorizontalAlignment) | Устанавливает выравнивание. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Устанавливает цвет фона. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Image\>\&) | Устанавливает фоновое изображение. |
| [set_BackgroundImageFile](./set_backgroundimagefile/)(const System::String\&) | Устанавливает файл фонового изображения. |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Устанавливает границу. |
| [set_ColSpan](./set_colspan/)(int32_t) | Устанавливает охват столбца. |
| [set_DefaultCellTextState](./set_defaultcelltextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Устанавливает состояние текста ячейки по умолчанию. |
| [set_IsNoBorder](./set_isnoborder/)(bool) | Устанавливает наличие границы у ячейки. |
| [set_IsOverrideByFragment](./set_isoverridebyfragment/)(bool) | Устанавливает свойство TextState ячейки, переопределяется свойством TextState TextFragment. |
| [set_IsWordWrapped](./set_iswordwrapped/)(bool) | Устанавливает перенос слов в тексте ячейки. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает отступ. |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Устанавливает отформатированный текст ячейки. |
| [set_RowSpan](./set_rowspan/)(int32_t) | Устанавливает охват строки. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Устанавливает вертикальное выравнивание. |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
