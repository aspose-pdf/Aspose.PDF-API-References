---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.AttributeName. Представляет класс для значений имени атрибута
type: docs
weight: 6220
url: /ru/net/aspose.pdf.logicalstructure/attributename/
---
## Класс AttributeName

Представляет класс для значений имени атрибута.

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
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Получает имя атрибута для ключа атрибута. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Возвращает строку, представляющую текущий объект. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Атрибут BlockAlign: After - Задний край прямоугольника выделения последнего дочернего элемента выровнен с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Атрибут BlockAlign: Before - Передний край прямоугольника выделения первого дочернего элемента выровнен с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Атрибут BlockAlign: Justify - Дети выровнены как с передними, так и с задними краями прямоугольника содержимого ячейки таблицы. Первый ребенок будет размещен, как описано для Before, а последний ребенок - как описано для After, с равным расстоянием между детьми. Если есть только один ребенок, он будет выровнен только с передним краем, как для Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Атрибут BlockAlign: Middle - Дети центрированы внутри ячейки таблицы. Расстояние между передним краем прямоугольника выделения первого дочернего элемента и краем прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между задним краем прямоугольника выделения последнего дочернего элемента и краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Атрибут BorderStyle: Dashed - Граница представляет собой серию коротких отрезков линий. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Атрибут BorderStyle: Dotted - Граница представляет собой серию точек. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Атрибут BorderStyle: Double - Граница состоит из двух сплошных линий. Сумма двух линий и расстояние между ними равно значению BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Атрибут BorderStyle: Groove - Граница выглядит так, как будто она вырезана в холсте. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Атрибут BorderStyle: Hidden - То же самое, что и None, за исключением разрешения конфликтов границ для элементов таблицы. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Атрибут BorderStyle: Inset - Граница заставляет весь блок выглядеть так, как будто он встроен в холст. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Атрибут BorderStyle: None - Без границы. Принуждает вычисленное значение BorderThicknessto быть 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Атрибут BorderStyle: Outset - Граница заставляет весь блок выглядеть так, как будто он выходит из холста (противоположность Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Атрибут BorderStyle: Ridge - Граница выглядит так, как будто она выходит из холста (противоположность Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Атрибут BorderStyle: Solid - Граница представляет собой один отрезок линии. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Атрибут checked: Neutral - Состояние радиокнопки или поля флажка. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Атрибут checked: Off - Состояние радиокнопки или поля флажка. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Атрибут checked: On - Состояние радиокнопки или поля флажка. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Атрибут GlyphOrientationVertical: Auto - Указывает стандартную ориентацию для текста, в зависимости от того, является ли он полноширинным (так же широким, как и высоким). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Атрибут Height: Auto - Высота элемента будет определяться внутренней высотой его содержимого. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Атрибут InlineAlign: Center - Каждый ребенок центрирован внутри ячейки таблицы. Расстояние между начальными краями прямоугольника выделения ребенка и прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между их конечными краями. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Атрибут InlineAlign: End - Конечный край каждого прямоугольника выделения ребенка выровнен с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Атрибут InlineAlign: Start - Начальный край каждого прямоугольника выделения ребенка выровнен с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Атрибут LineHeight: Auto - Корректировка значения BaselineShift не будет производиться. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Атрибут LineHeight: Normal - Настройте высоту строки, чтобы включить любое ненулевое значение, указанное для BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Атрибут ListNumbering: Circle - Открытая круглая пуля. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Атрибут ListNumbering: Decimal - Десятичные арабские цифры (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Атрибут ListNumbering: Disc - Сплошная круглая пуля. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Атрибут ListNumbering: LowerAlpha - Строчные буквы (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Атрибут ListNumbering: LowerRoman - Строчные римские цифры (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Атрибут ListNumbering: None - Без автоматической нумерации; элементы Lbl (если они присутствуют) содержат произвольный текст, не подлежащий никакой нумерации. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Атрибут ListNumbering: Square - Сплошная квадратная пуля. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Атрибут ListNumbering: UpperAlpha - Заглавные буквы (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Атрибут ListNumbering: UpperRoman - Заглавные римские цифры (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Атрибут Placement: Before - Размещен так, чтобы передний край прямоугольника выделения элемента совпадал с краем ближайшей enclosing reference area. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Атрибут Placement: Block - Упакован в направлении блок-прогрессии внутри enclosing reference area или родительского BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Атрибут Placement: End - Размещен так, чтобы конечный край прямоугольника выделения элемента совпадал с краем ближайшей enclosing reference area. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Атрибут Placement: Inline - Упакован в направлении inline-прогрессии внутри enclosing BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Атрибут Placement: Start - Размещен так, чтобы начальный край прямоугольника выделения элемента совпадал с краем ближайшей enclosing reference area. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Атрибут Role: cb - Флажок. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Атрибут Role: pb - Кнопка. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Атрибут Role: rb - Радиокнопка. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Атрибут Role: tv - Поле текстового значения. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Атрибут RubyAlign: Center - Содержимое должно быть центрировано в направлении inline-прогрессии. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Атрибут RubyAlign: Distribute - Содержимое должно быть расширено, чтобы заполнить доступную ширину в направлении inline-прогрессии. Однако пространство также должно быть вставлено на начальном и конечном краях текста. Расстояние должно распределяться с использованием соотношения 1:2:1 (начало:инфикс:конец). Оно должно изменяться на соотношение 0:1:1, если руби появляется в начале строки текста, или на соотношение 1:1:0, если руби появляется в конце строки текста. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Атрибут RubyAlign: End - Содержимое должно быть выровнено по конечному краю в направлении inline-прогрессии. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Атрибут RubyAlign: Justify - Содержимое должно быть расширено, чтобы заполнить доступную ширину в направлении inline-прогрессии. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Атрибут RubyAlign: Start - Содержимое должно быть выровнено по начальному краю в направлении inline-прогрессии. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Атрибут RubyPosition: After - Содержимое RT должно быть выровнено вдоль заднего края элемента. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Атрибут RubyPosition: Before - Содержимое RT должно быть выровнено вдоль переднего края элемента. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Атрибут RubyPosition: Inline - Элементы RT и связанные RP должны быть отформатированы как комментарий в скобках, следуя элементу RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Атрибут RubyPosition: Warichu - Элементы RT и связанные RP должны быть отформатированы как warichu, следуя элементу RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Атрибут Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Атрибут Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Атрибут Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Атрибут TextAlign: Center - Центрировано между начальным и конечным краями. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Атрибут TextAlign: End - Выровнено по конечному краю. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Атрибут TextAlign: Justify - Выровнено как по начальным, так и по конечным краям, с внутренним расстоянием внутри каждой строки, расширенным, если необходимо, для достижения такого выравнивания. Последняя (или единственная) строка должна быть выровнена только по начальному краю. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Атрибут TextAlign: Start - Выровнено по начальному краю. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Атрибут TextDecorationType: LineThrough - Линия через середину текста. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Атрибут TextDecorationType: None - Без текстового оформления. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Атрибут TextDecorationType: Overline - Линия над текстом. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Атрибут TextDecorationType: Underline - Линия под текстом. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Атрибут Width: Auto - ширина элемента будет определяться внутренней шириной его содержимого. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Атрибут WritingMode: LrTb - Прогрессия inline слева направо; прогрессия блока сверху вниз. Это типичный режим письма для западных письменных систем. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Атрибут WritingMode: RlTb - Прогрессия inline справа налево; прогрессия блока сверху вниз. Это типичный режим письма для арабских и ивритских письменных систем. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Атрибут WritingMode: TbRl - Прогрессия inline сверху вниз; прогрессия блока справа налево. Это типичный режим письма для китайских и японских письменных систем. |

### См. также

* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)