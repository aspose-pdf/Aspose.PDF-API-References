---
title: "Aspose::Pdf::LogicalStructure::AttributeName класс"
linktitle: "AttributeName"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::AttributeName класс. Представляет класс для значений имен атрибутов в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class


Представляет класс для значений имён атрибутов.

```cpp
class AttributeName : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [FromNameAttributeKey](./fromnameattributekey/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::LogicalStructure::AttributeKey\>\&) | Получает имя атрибута по ключу атрибута. |
| [get_AttributeKey](./get_attributekey/)() const | Получает ключ атрибута. |
| [get_Name](./get_name/)() const | Получает значение имени атрибута. |
| [ToString](./tostring/)() const override | Возвращает строку, представляющую текущий объект. |
## Поля

| Поле | Описание |
| --- | --- |
| static [BlockAlign_After](./blockalign_after/) | Атрибут BlockAlign: After — После‑край последнего прямоугольника размещения дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| static [BlockAlign_Before](./blockalign_before/) | Атрибут BlockAlign: Before — Передний край первого прямоугольника размещения дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| static [BlockAlign_Justify](./blockalign_justify/) | Атрибут BlockAlign: Justify — Дети выравниваются по обоим краям (до и после) прямоугольника содержимого ячейки таблицы. Первый дочерний элемент размещается как описано для Before, а последний — как описано для After, при равных промежутках между дочерними элементами. Если дочерний элемент один, он выравнивается только по переднему краю, как для Before. |
| static [BlockAlign_Middle](./blockalign_middle/) | Атрибут BlockAlign: Middle — Дети центрируются внутри ячейки таблицы. Расстояние между передним краем первого прямоугольника размещения дочернего элемента и краем прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между задним краем последнего прямоугольника размещения дочернего элемента и краем прямоугольника содержимого ячейки таблицы. |
| static [BorderStyle_Dashed](./borderstyle_dashed/) | Атрибут BorderStyle: Dashed — Граница представляет собой серию коротких отрезков линии. |
| static [BorderStyle_Dotted](./borderstyle_dotted/) | Атрибут BorderStyle: Dotted — Граница представляет собой серию точек. |
| static [BorderStyle_Double](./borderstyle_double/) | Атрибут BorderStyle: Double — Граница состоит из двух сплошных линий. Сумма двух линий и промежутка между ними равна значению BorderThickness. |
| static [BorderStyle_Groove](./borderstyle_groove/) | Атрибут BorderStyle: Groove — Граница выглядит так, как будто её вырезали в холсте. |
| static [BorderStyle_Hidden](./borderstyle_hidden/) | Атрибут BorderStyle: Hidden — То же, что и None, за исключением разрешения конфликтов границ для элементов таблицы. |
| static [BorderStyle_Inset](./borderstyle_inset/) | Атрибут BorderStyle: Inset — Граница заставляет весь блок выглядеть так, как будто он вмонтирован в холст. |
| static [BorderStyle_None](./borderstyle_none/) | Атрибут BorderStyle: None — Нет границы. Принуждает вычисленное значение BorderThicknessto быть 0. |
| static [BorderStyle_Outset](./borderstyle_outset/) | Атрибут BorderStyle: Outset — Граница заставляет весь блок выглядеть так, как будто он выходит из холста (противоположность Inset). |
| static [BorderStyle_Ridge](./borderstyle_ridge/) | Атрибут BorderStyle: Ridge — Граница выглядит так, как будто она выходит из холста (противоположность Groove). |
| static [BorderStyle_Solid](./borderstyle_solid/) | Атрибут BorderStyle: Solid — Граница представляет собой один отрезок линии. |
| static [Checked_neutral](./checked_neutral/) | Атрибут checked: Neutral — Состояние радиокнопки или флажка. |
| static [Checked_off](./checked_off/) | Атрибут checked: Off — Состояние радиокнопки или флажка. |
| static [Checked_on](./checked_on/) | Атрибут checked: On — Состояние радиокнопки или флажка. |
| static [GlyphOrientationVertical_Auto](./glyphorientationvertical_auto/) | Атрибут GlyphOrientationVertical: Auto — Указывает ориентацию текста по умолчанию, в зависимости от того, является ли он полноширинным (так же широким, как высокий). |
| static [Height_Auto](./height_auto/) | Атрибут Height: Auto — Высота элемента определяется внутренней высотой его содержимого. |
| static [InlineAlign_Center](./inlinealign_center/) | Атрибут InlineAlign: [Center](../../aspose.pdf/center/) — Каждый дочерний элемент центрируется внутри ячейки таблицы. Расстояние между стартовыми краями прямоугольника размещения дочернего элемента и прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между их конечными краями. |
| static [InlineAlign_End](./inlinealign_end/) | Атрибут InlineAlign: End — Конечный край каждого прямоугольника размещения дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| static [InlineAlign_Start](./inlinealign_start/) | Атрибут InlineAlign: Start — Начальный край каждого прямоугольника размещения дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| static [LineHeight_Auto](./lineheight_auto/) | Атрибут LineHeight: Auto — Коррекция значения BaselineShift не будет выполнена. |
| static [LineHeight_Normal](./lineheight_normal/) | Атрибут LineHeight: Normal - Настройте высоту строки, чтобы включить любое ненулевое значение, указанное для BaselineShift. |
| static [ListNumbering_Circle](./listnumbering_circle/) | Атрибут ListNumbering: Circle - Открытый круглый маркер. |
| static [ListNumbering_Decimal](./listnumbering_decimal/) | Атрибут ListNumbering: Decimal - Десятичные арабские цифры (1-9, 10-99, ...). |
| static [ListNumbering_Disc](./listnumbering_disc/) | Атрибут ListNumbering: Disc - Сплошной круглый маркер. |
| static [ListNumbering_LowerAlpha](./listnumbering_loweralpha/) | Атрибут ListNumbering: LowerAlpha - Строчные буквы (a, b, c, ...). |
| static [ListNumbering_LowerRoman](./listnumbering_lowerroman/) | Атрибут ListNumbering: LowerRoman - Строчные римские цифры (i, ii, iii, iv, ...). |
| static [ListNumbering_None](./listnumbering_none/) | Атрибут ListNumbering: None - Автонумерация отключена; элементы Lbl (если присутствуют) содержат произвольный текст, не подпадающий под какую-либо схему нумерации. |
| static [ListNumbering_Square](./listnumbering_square/) | Атрибут ListNumbering: Square - Сплошной квадратный маркер. |
| static [ListNumbering_UpperAlpha](./listnumbering_upperalpha/) | Атрибут ListNumbering: UpperAlpha - Прописные буквы (A, B, C, ...). |
| static [ListNumbering_UpperRoman](./listnumbering_upperroman/) | Атрибут ListNumbering: UpperRoman - Прописные римские цифры (I, II, III, IV, ...). |
| static [Placement_Before](./placement_before/) | Атрибут Placement: Before - Размещено так, чтобы передний край прямоугольника размещения элемента совпадал с краем ближайшей охватывающей ссылочной области. |
| static [Placement_Block](./placement_block/) | Атрибут Placement: Block - Стекается в направлении блочного прогрессирования внутри охватывающей ссылочной области или родительского BLSE. |
| static [Placement_End](./placement_end/) | Атрибут Placement: End - Размещено так, чтобы конечный край прямоугольника размещения элемента совпадал с краем ближайшей охватывающей ссылочной области. |
| static [Placement_Inline](./placement_inline/) | Атрибут Placement: Inline - Упаковано в направлении встроенного прогрессирования внутри охватывающего BLSE. |
| static [Placement_Start](./placement_start/) | Атрибут Placement: Start - Размещено так, чтобы начальный край прямоугольника размещения элемента совпадал с краем ближайшей охватывающей ссылочной области. |
| static [Role_cb](./role_cb/) | Атрибут Role: cb - Флажок. |
| static [Role_pb](./role_pb/) | Атрибут Role: pb - Кнопка. |
| static [Role_rb](./role_rb/) | Атрибут Role: rb - Переключатель. |
| static [Role_tv](./role_tv/) | Атрибут Role: tv - Текстово-значимое поле. |
| static [RubyAlign_Center](./rubyalign_center/) | Атрибут RubyAlign: [Center](../../aspose.pdf/center/) - Содержание должно быть центрировано в направлении встроенного прогрессирования. |
| static [RubyAlign_Distribute](./rubyalign_distribute/) | Атрибут RubyAlign: Distribute - Содержание должно быть расширено, чтобы заполнить доступную ширину в направлении встроенного прогрессирования. Однако пространство также должно быть вставлено у начального и конечного краев текста. Распределение интервалов должно происходить по соотношению 1:2:1 (начало:внутренняя часть:конец). Оно должно изменяться на 0:1:1, если ruby появляется в начале строки текста, или на 1:1:0, если ruby появляется в конце строки текста. |
| static [RubyAlign_End](./rubyalign_end/) | Атрибут RubyAlign: End - Содержание должно быть выровнено по конечному краю в направлении встроенного прогрессирования. |
| static [RubyAlign_Justify](./rubyalign_justify/) | Атрибут RubyAlign: Justify - Содержание должно быть расширено, чтобы заполнить доступную ширину в направлении встроенного прогрессирования. |
| static [RubyAlign_Start](./rubyalign_start/) | Атрибут RubyAlign: Start - Содержание должно быть выровнено по начальному краю в направлении встроенного прогрессирования. |
| static [RubyPosition_After](./rubyposition_after/) | Атрибут RubyPosition: After - Содержание RT должно быть выровнено вдоль последующего края элемента. |
| static [RubyPosition_Before](./rubyposition_before/) | Атрибут RubyPosition: Before - Содержимое RT должно быть выровнено вдоль переднего края элемента. |
| static [RubyPosition_Inline](./rubyposition_inline/) | Атрибут RubyPosition: Inline - Элементы RT и связанные с ними RP должны быть отформатированы как комментарий в скобках, следуя за элементом RB. |
| static [RubyPosition_Warichu](./rubyposition_warichu/) | Атрибут RubyPosition: Warichu - Элементы RT и связанные с ними RP должны быть отформатированы как warichu, следуя за элементом RB. |
| static [Scope_Both](./scope_both/) | Атрибут Scope: Both. |
| static [Scope_Column](./scope_column/) | Атрибут Scope: Column. |
| static [Scope_Row](./scope_row/) | Атрибут Scope: [Row](../../aspose.pdf/row/). |
| static [TextAlign_Center](./textalign_center/) | Атрибут TextAlign: [Center](../../aspose.pdf/center/) - Выравнено по центру между начальным и конечным краями. |
| static [TextAlign_End](./textalign_end/) | Атрибут TextAlign: End - Выравнено по конечному краю. |
| static [TextAlign_Justify](./textalign_justify/) | Атрибут TextAlign: Justify - Выравнено по обоим краям, при необходимости внутренний интервал в каждой строке расширяется для достижения такого выравнивания. Последняя (или единственная) строка должна быть выровнена только по начальному краю. |
| static [TextAlign_Start](./textalign_start/) | Атрибут TextAlign: Start - Выравнено по начальному краю. |
| static [TextDecorationType_LineThrough](./textdecorationtype_linethrough/) | Атрибут TextDecorationType: LineThrough - Линия, проведённая через середину текста. |
| static [TextDecorationType_None](./textdecorationtype_none/) | Атрибут TextDecorationType: None - Нет декорации текста. |
| static [TextDecorationType_Overline](./textdecorationtype_overline/) | Атрибут TextDecorationType: Overline - Линия над текстом. |
| static [TextDecorationType_Underline](./textdecorationtype_underline/) | Атрибут TextDecorationType: Underline - Линия под текстом. |
| static [Width_Auto](./width_auto/) | Атрибут Width: Auto - ширина элемента определяется внутренней шириной его содержимого. |
| static [WritingMode_LrTb](./writingmode_lrtb/) | Атрибут WritingMode: LrTb - Прогрессия по строке слева направо; прогрессия блока сверху вниз. Это типичный режим письма для западных систем письма. |
| static [WritingMode_RlTb](./writingmode_rltb/) | Атрибут WritingMode: RlTb - Прогрессия по строке справа налево; прогрессия блока сверху вниз. Это типичный режим письма для арабских и еврейских систем письма. |
| static [WritingMode_TbRl](./writingmode_tbrl/) | Атрибут WritingMode: TbRl - Прогрессия по строке сверху вниз; прогрессия блока справа налево. Это типичный режим письма для китайских и японских систем письма. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
