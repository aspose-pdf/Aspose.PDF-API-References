---
title: "Класс AttributeName"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.LogicalStructure.AttributeName. Представляет класс для значений имён атрибутов."
type: docs
weight: 6360
url: /ru/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Представляет класс для значений имён атрибутов.

```csharp
public sealed class AttributeName
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Получает ключ атрибута. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Получает значение имени атрибута. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Получает имя атрибута по ключу атрибута. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Возвращает строку, представляющую текущий объект. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribute BlockAlign: After - После края последнего дочернего выделенного прямоугольника, выровненного с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribute BlockAlign: Before - Передний край первого дочернего выделенного прямоугольника, выровненного с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attribute BlockAlign: Justify - Дети выравниваются по обоим краям (до и после) прямоугольника содержимого ячейки таблицы. Первый ребёнок размещается, как описано для Before, а последний — как описано для After, с равными промежутками между детьми. Если ребёнок один, он выравнивается только по переднему краю, как для Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attribute BlockAlign: Middle- Дети центрированы внутри ячейки таблицы. Расстояние между передним краем первого дочернего выделенного прямоугольника и краем прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между задним краем последнего дочернего выделенного прямоугольника и краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attribute BorderStyle: Dashed - Граница представляет собой серию коротких отрезков линии. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attribute BorderStyle: Dotted - Граница состоит из серии точек. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Атрибут BorderStyle: Double — Граница состоит из двух сплошных линий. Сумма двух линий и промежутка между ними равна значению BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Атрибут BorderStyle: Groove — Граница выглядит так, как будто её вырезали в холсте. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Атрибут BorderStyle: Hidden — То же, что и None, но в контексте разрешения конфликтов границ для элементов таблицы. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Атрибут BorderStyle: Inset — Граница делает весь блок выглядящим так, как будто он вмонтирован в холст. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Атрибут BorderStyle: None — Нет границы. Принуждает вычисленное значение BorderThickness быть 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Атрибут BorderStyle: Outset — Граница делает весь блок выглядящим так, как будто он выходит из холста (противоположность Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Атрибут BorderStyle: Ridge — Граница выглядит так, как будто она выходит из холста (противоположность Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Атрибут BorderStyle: Solid — Граница представляет собой один линейный сегмент. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Атрибут checked: Neutral — Состояние радиокнопки или флажка. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Атрибут checked: Off — Состояние радиокнопки или флажка. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Атрибут checked: On — Состояние радиокнопки или флажка. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Атрибут GlyphOrientationVertical: Auto — Указывает ориентацию текста по умолчанию, в зависимости от того, является ли он полноширинным (так же широким, как высокий). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Атрибут Height: Auto — Высота элемента определяется внутренней высотой его содержимого. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Атрибут InlineAlign: Center — Каждый дочерний элемент центрируется внутри ячейки таблицы. Расстояние между начальными краями выделенного прямоугольника дочернего элемента и прямоугольника содержимого ячейки таблицы должно быть равно расстоянию между их конечными краями. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Атрибут InlineAlign: End — Конечный край выделенного прямоугольника каждого дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Атрибут InlineAlign: Start — Начальный край выделенного прямоугольника каждого дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Атрибут LineHeight: Auto — Корректировка значения BaselineShift не будет выполнена. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Атрибут LineHeight: Normal — Регулирует высоту строки, включая любое ненулевое значение, указанное для BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Атрибут ListNumbering: Circle — Открытый круглый маркер. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Атрибут ListNumbering: Decimal — Десятичные арабские цифры (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Атрибут ListNumbering: Disc — Сплошной круглый маркер. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Атрибут ListNumbering: LowerAlpha — Строчные буквы (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Атрибут ListNumbering: LowerRoman — Строчные римские цифры (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Атрибут ListNumbering: None — Нет автоматической нумерации; элементы Lbl (если присутствуют) содержат произвольный текст, не подпадающий под какую-либо схему нумерации. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Атрибут ListNumbering: Square — Сплошной квадратный маркер. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Атрибут ListNumbering: UpperAlpha - Заглавные буквы (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Атрибут ListNumbering: UpperRoman - Заглавные римские цифры (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Атрибут Placement: Before - Размещено так, чтобы передний край прямоугольника размещения элемента совпадал с краем ближайшей охватывающей области ссылки. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Атрибут Placement: Block - Стекается в направлении блокового прогрессирования внутри охватывающей области ссылки или родительского BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Атрибут Placement: End - Размещено так, чтобы конечный край прямоугольника размещения элемента совпадал с краем ближайшей охватывающей области ссылки. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Атрибут Placement: Inline - Упаковано в направлении встроенного прогрессирования внутри охватывающего BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Атрибут Placement: Start - Размещено так, чтобы начальный край прямоугольника размещения элемента совпадал с краем ближайшей охватывающей области ссылки. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Атрибут Role: cb - Флажок. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Атрибут Role: pb - Кнопка. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Атрибут Role: rb - Радиокнопка. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Атрибут Role: tv - Текстовое поле значения. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Атрибут RubyAlign: Center - Содержимое должно быть центрировано в направлении встроенного прогрессирования. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Атрибут RubyAlign: Distribute - Содержимое должно расширяться, заполняя доступную ширину в направлении встроенного прогрессирования. Однако пробел также должен быть вставлен у начального и конечного края текста. Распределение пробелов должно происходить по соотношению 1:2:1 (начало:внутренняя часть:конец). Оно должно изменяться на 0:1:1, если руби появляется в начале строки текста, или на 1:1:0, если руби появляется в конце строки текста. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Атрибут RubyAlign: End - Содержимое должно быть выровнено по конечному краю в направлении встроенного прогрессирования. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Атрибут RubyAlign: Justify - Содержимое должно расширяться, заполняя доступную ширину в направлении встроенного прогрессирования. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Атрибут RubyAlign: Start - Содержимое должно быть выровнено по начальному краю в направлении встроенного прогрессирования. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Атрибут RubyPosition: After - Содержимое RT должно быть выровнено вдоль последующего края элемента. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Атрибут RubyPosition: Before - Содержимое RT должно быть выровнено вдоль переднего края элемента. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Атрибут RubyPosition: Inline - Элементы RT и связанные RP должны быть отформатированы как комментарий в скобках, следуя за элементом RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Атрибут RubyPosition: Warichu - Элементы RT и связанные RP должны быть отформатированы как warichu, следуя за элементом RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Атрибут Scope: Both - Оба. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Атрибут Scope: Column - Колонка. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Атрибут Scope: Row - Строка. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Атрибут TextAlign: Center - Центрировано между начальным и конечным краем. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Атрибут TextAlign: End - Выравнено по конечному краю. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attribute TextAlign: Justify - Выравнивается по обеим краям, при необходимости увеличивая внутренние интервалы в каждой строке для достижения такого выравнивания. Последняя (или единственная) строка должна выравниваться только по начальному краю. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attribute TextAlign: Start - Выравнивается по начальному краю. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attribute TextDecorationType: LineThrough - Линия, проходящая через середину текста. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attribute TextDecorationType: None - Нет декораций текста. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attribute TextDecorationType: Overline - Линия над текстом. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attribute TextDecorationType: Underline - Линия под текстом. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attribute Width: Auto - ширина элемента определяется внутренней шириной его содержимого. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attribute WritingMode: LrTb - Последовательность по строке слева направо; последовательность блоков сверху вниз. Это типичный режим письма для западных систем письма. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attribute WritingMode: RlTb - Последовательность по строке справа налево; последовательность блоков сверху вниз. Это типичный режим письма для арабских и еврейских систем письма. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attribute WritingMode: TbRl - Последовательность по строке сверху вниз; последовательность блоков справа налево. Это типичный режим письма для китайских и японских систем письма. |

### См. также

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


