---
title: "Aspose::Pdf::FloatingBox class"
linktitle: "FloatingBox"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::FloatingBox class. Представляет FloatingBox в PDF‑документе. FloatingBox имеет пользовательское позиционирование в C++."
type: docs
weight: 5700
url: /ru/cpp/aspose.pdf/floatingbox/
---
## FloatingBox class


Представляет [FloatingBox](./) в документе [Pdf](../). [FloatingBox](./) имеет пользовательское позиционирование.

```cpp
class FloatingBox : public Aspose::Pdf::BaseParagraph
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонирует новый объект [FloatingBox](./). [Paragraphs](../paragraphs/) во всплывающем блоке не клонируются. |
| [FloatingBox](./floatingbox/)(float, float) | Инициализирует новый экземпляр класса [FloatingBox](./) с указанной шириной и высотой. |
| [FloatingBox](./floatingbox/)() | Инициализирует новый экземпляр класса [FloatingBox](./). |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Получает объект [Aspose::Pdf::Color](../color/), указывающий цвет фона всплывающего блока. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Получает фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [get_Border](./get_border/)() const | Получает объект [BorderInfo](../borderinfo/), указывающий информацию о границе всплывающего блока. |
| [get_ColumnInfo](./get_columninfo/)() const | Получает информацию о колонке. |
| [get_Height](./get_height/)() const | Получает значение типа float, указывающее высоту плавающего блока. |
| [get_IsNeedRepeating](./get_isneedrepeating/)() const | Получает значение типа bool, указывающее, нужно ли повторять абзац на следующей странице. Значение по умолчанию — false. Атрибут действителен только тогда, когда сам абзац и объект, на который ссылается его ReferenceParagraphID, оба включены в RepeatingRows. |
| [get_Left](./get_left/)() const | Получает левую координату таблицы. |
| [get_Padding](./get_padding/)() const | Получает объект [MarginInfo](../margininfo/), указывающий отступы плавающего блока. |
| [get_Paragraphs](./get_paragraphs/)() const | Получает коллекцию [Paragraphs](../paragraphs/), содержащую все абзацы в ячейке. |
| [get_PositioningMode](./get_positioningmode/)() const | Указывает вариант определения расположения [FloatingBox](./) на странице. |
| [get_Top](./get_top/)() const | Получает верхнюю координату таблицы. |
| [get_Width](./get_width/)() const | Получает значение типа float, указывающее ширину плавающего блока. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Устанавливает объект [Aspose::Pdf::Color](../color/), указывающий цвет фона плавающего блока. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Image\>\&) | Устанавливает фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Устанавливает объект [BorderInfo](../borderinfo/), указывающий информацию о границе плавающего блока. |
| [set_ColumnInfo](./set_columninfo/)(const System::SharedPtr\<Aspose::Pdf::ColumnInfo\>\&) | Устанавливает информацию о столбце. |
| [set_Height](./set_height/)(double) | Устанавливает значение типа float, указывающее высоту плавающего блока. |
| [set_IsNeedRepeating](./set_isneedrepeating/)(bool) | Устанавливает значение типа bool, указывающее, нужно ли повторять абзац на следующей странице. Значение по умолчанию — false. Атрибут действителен только тогда, когда сам абзац и объект, на который ссылается его ReferenceParagraphID, оба включены в RepeatingRows. |
| [set_Left](./set_left/)(double) | Устанавливает левую координату таблицы. |
| [set_Padding](./set_padding/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает объект [MarginInfo](../margininfo/), указывающий отступы плавающего блока. |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Устанавливает коллекцию [Paragraphs](../paragraphs/), содержащую все абзацы в ячейке. |
| [set_PositioningMode](./set_positioningmode/)(ParagraphPositioningMode) | Указывает вариант определения расположения [FloatingBox](./) на странице. |
| [set_Top](./set_top/)(double) | Устанавливает верхнюю координату таблицы. |
| [set_Width](./set_width/)(double) | Устанавливает значение типа float, указывающее ширину плавающего блока. |
## См. также

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
