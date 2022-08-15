---
title: AttributeName
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для значений имени атрибута.
type: docs
weight: 4050
url: /ru/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Представляет класс для значений имени атрибута.

```csharp
public sealed class AttributeName
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Получает ключ атрибута. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Получает значение имени атрибута. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Получает имя атрибута для ключа атрибута. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Возвращает строку, представляющую текущий объект. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Атрибут BlockAlign: After — после того, как край прямоугольника распределения последнего дочернего элемента выровнен с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Атрибут BlockAlign: До — перед краем прямоугольника выделения первого дочернего элемента, выровненного с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Атрибут BlockAlign: Justify — дочерние элементы выровнены как до, так и после краев прямоугольника содержимого ячейки таблицы. Первый дочерний элемент должен быть размещен, как описано для параметра «До», а последний дочерний элемент — как для «После», с равным интервалом между дочерними элементами. Если есть только один дочерний элемент, он должен быть выровнен только по переднему краю, как для Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Атрибут BlockAlign: Средний-дочерний элемент по центру ячейки таблицы. Расстояние между передним краем прямоугольника выделения первого дочернего элемента и краем прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между задним краем прямоугольника выделения последнего дочернего элемента и прямоугольником содержимого ячейки таблицы. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attribute BorderStyle: Dashed — граница представляет собой серию коротких сегментов линии. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attribute BorderStyle: Dotted — граница представляет собой набор точек. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Атрибут BorderStyle: Double — граница представляет собой две сплошные линии. Сумма двух строк и пространства между ними равна значению BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribute BorderStyle: Groove — граница выглядит так, как будто она вырезана на холсте. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attribute BorderStyle: Hidden — то же, что и None, за исключением разрешения конфликта границ для элементов таблицы. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Атрибут BorderStyle: Inset — граница придает всему блоку вид, будто он встроен в холст. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Атрибут BorderStyle: Нет — без рамки. Заставляет вычисленное значение BorderThickness равным 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Атрибут BorderStyle: Outset — граница заставляет весь блок выглядеть так, как будто он выходит из холста (противоположность Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Атрибут BorderStyle: Ridge — граница выглядит так, как будто она выходит из холста (противоположность Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Атрибут BorderStyle: Solid — граница представляет собой один сегмент линии. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Атрибут проверен: нейтральное — состояние переключателя или поля флажка. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Атрибут отмечен: Off — состояние переключателя или поля флажка. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Атрибут проверен: Включено — состояние переключателя или поля флажка. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Атрибут GlyphOrientationVertical: Auto — определяет ориентацию текста по умолчанию, в зависимости от того, является ли он полной ширины (ширина равна высоте). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Высота атрибута: Авто — высота элемента должна определяться внутренней высотой его содержимого. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Атрибут InlineAlign: Center — каждый дочерний элемент центрируется в ячейке таблицы. Расстояние между начальными краями прямоугольника выделения дочернего элемента и прямоугольником содержимого ячейки таблицы должно быть таким же, как расстояние между их конечными краями. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Атрибут InlineAlign: End — конечная кромка прямоугольника выделения каждого дочернего элемента, выровненная с кромкой прямоугольника содержимого ячейки таблицы. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Атрибут InlineAlign: Start — начальный край прямоугольника распределения каждого дочернего элемента, выровненный с краем прямоугольника содержимого ячейки таблицы. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Атрибут LineHeight: Auto — корректировка значения BaselineShift не должна выполняться. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Атрибут LineHeight: Normal — отрегулируйте высоту строки, чтобы включить любое ненулевое значение, указанное для BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Нумерация списка атрибутов: Круг — открытый круговой маркер. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Нумерация списка атрибутов: Decimal — десятичные арабские цифры (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Нумерация списка атрибутов: Диск — сплошная круглая пуля. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Нумерация списка атрибутов: LowerAlpha — Строчные буквы (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Attribute ListNumbering: LowerRoman - строчные римские цифры (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Attribute ListNumbering: None — нет автонумерации; Элементы Lbl (если они есть) содержат произвольный текст, не подпадающий под какую-либо схему нумерации. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Нумерация списка атрибутов: Квадрат — сплошной квадратный маркер. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Нумерация списка атрибутов: UpperAlpha — буквы верхнего регистра (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Список атрибутов Нумерация: UpperRoman - Прописные римские цифры (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Размещение атрибута: Перед — размещается так, чтобы передний край прямоугольника размещения элемента совпадал с краем ближайшей окружающей опорной области. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Размещение атрибута: Блок — Стек в направлении последовательности блоков внутри окружающей эталонной области или родительского BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Размещение атрибута: Конец — размещается так, чтобы конечный край прямоугольника размещения элемента совпадал с краем ближайшей окружающей опорной области. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Размещение атрибута: встроенное — упаковано в направлении встроенной последовательности внутри охватывающего BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Размещение атрибута: Начало — размещается так, чтобы начальный край прямоугольника выделения элемента совпадал с краем ближайшей окружающей опорной области. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Роль атрибута: cb — флажок. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Роль атрибута: pb — кнопка. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Роль атрибута: rb — переключатель. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Роль атрибута: tv — поле текстового значения. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Атрибут RubyAlign: Center — содержимое должно центрироваться в направлении встроенной последовательности. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Атрибут RubyAlign: Распространение — содержимое должно быть расширено, чтобы заполнить доступную ширину в направлении встроенной последовательности. Однако пробел также должен быть вставлен в начале и конце текста. Интервал должен распределяться с использованием соотношения 1:2:1 (начало:инфикс:конец). Соотношение должно быть изменено на 0:1:1, если рубин появляется в начале текстовой строки, или на соотношение 1:1:0, если рубин появляется в конце текстовой строки. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Атрибут RubyAlign: End — содержимое должно быть выровнено по конечному краю в направлении встроенной последовательности. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Атрибут RubyAlign: Justify — содержимое должно быть расширено, чтобы заполнить доступную ширину в направлении встроенной последовательности. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Атрибут RubyAlign: Start — содержимое должно быть выровнено по начальному краю в направлении встроенной последовательности. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Атрибут RubyPosition: After — содержимое RT должно быть выровнено по краю после элемента. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Атрибут RubyPosition: Before — содержимое RT должно быть выровнено по переднему краю элемента. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Атрибут RubyPosition: встроенный — RT и связанные с ним элементы RP должны быть отформатированы как комментарий в скобках после элемента RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Атрибут RubyPosition: Warichu — RT и связанные с ним элементы RP должны быть отформатированы как warichu после элемента RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Область действия атрибута: Оба. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Область действия атрибута: Столбец. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Область действия атрибута: Строка. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Атрибут TextAlign: Center — Центрируется между начальным и конечным краями. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Атрибут TextAlign: End — выравнивание по конечному краю. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Атрибут TextAlign: Justify — выравнивание по начальному и конечному краям с расширением внутреннего интервала внутри каждой строки, если это необходимо для достижения такого выравнивания. Последняя (или единственная) строка должна быть выровнена только по начальному краю. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Атрибут TextAlign: Начало — Выровнено по начальному краю. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Атрибут TextDecorationType: LineThrough — линия, проходящая через середину текста. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Атрибут TextDecorationType: None — без оформления текста. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Атрибут TextDecorationType: Overline — строка над текстом. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Атрибут TextDecorationType: Underline — строка под текстом. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Ширина атрибута: Авто — ширина элемента определяется внутренней шириной его содержимого. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Режим записи атрибутов: LrTb — встроенная последовательность слева направо; блокировать продвижение сверху вниз. Это типичный способ письма для западных систем письма. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Режим записи атрибутов: RlTb — встроенная последовательность справа налево; блокировать продвижение сверху вниз. Это типичный способ письма для систем письма на арабском языке и иврите. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Режим записи атрибутов: TbRl — встроенная последовательность сверху вниз; заблокировать продвижение справа налево. Это типичный режим письма для китайской и японской систем письма. |

### Смотрите также

* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
