---
title: "AttributeName"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для значений имён атрибутов."
type: docs
weight: 50
url: /ru/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Представляет класс для значений имён атрибутов.

Тип AttributeName раскрывает следующие члены:
## Свойства
| Имя | Описание |
| :- | :- |
| name | Получает значение имени атрибута. |
| attribute_key | Получает ключ атрибута. |
| PLACEMENT_BLOCK | Размещение атрибута: Block - Стекается в направлении блочного прогрессирования внутри ограничивающей области ссылки или родительского BLSE. |
| PLACEMENT_INLINE | Размещение атрибута: Inline - Упаковывается в направлении встроенного прогрессирования внутри ограничивающего BLSE. |
| PLACEMENT_BEFORE | Размещение атрибута: Before - Размещается так, чтобы передний край прямоугольника размещения элемента совпадал с краем ближайшей ограничивающей области ссылки. |
| PLACEMENT_START | Размещение атрибута: Start - Размещается так, чтобы начальный край прямоугольника размещения элемента совпадал с краем ближайшей ограничивающей области ссылки. |
| PLACEMENT_END | Размещение атрибута: End - Размещается так, чтобы конечный край прямоугольника размещения элемента совпадал с краем ближайшей ограничивающей области ссылки. |
| WRITING_MODE_LR_TB | Режим записи атрибута: LrTb - Встроенный прогресс слева направо; блочный прогресс сверху вниз. Это типичный режим записи для западных систем письма. |
| WRITING_MODE_RL_TB | Режим записи атрибута: RlTb - Встроенный прогресс справа налево; блочный прогресс сверху вниз. Это типичный режим записи для арабских и еврейских систем письма. |
| WRITING_MODE_TB_RL | Режим записи атрибута: TbRl - Встроенный прогресс сверху вниз; блочный прогресс справа налево. Это типичный режим записи для китайских и японских систем письма. |
| BORDER_STYLE_NONE | Стиль границы атрибута: None - Нет границы. Принудительно устанавливает вычисленное значение BorderThickness равным 0. |
| BORDER_STYLE_HIDDEN | Стиль границы атрибута: Hidden - То же, что и None, за исключением разрешения конфликтов границ для элементов таблицы. |
| BORDER_STYLE_DOTTED | Стиль границы атрибута: Dotted - Граница представляет собой серию точек. |
| BORDER_STYLE_DASHED | Attribute BorderStyle: Dashed - Граница представляет собой серию коротких отрезков линии. |
| BORDER_STYLE_SOLID | Attribute BorderStyle: Solid - Граница представляет собой один отрезок линии. |
| BORDER_STYLE_DOUBLE | Attribute BorderStyle: Double - Граница состоит из двух сплошных линий. Сумма двух линий и пространства между ними равна значению BorderThickness. |
| BORDER_STYLE_GROOVE | Attribute BorderStyle: Groove - Граница выглядит так, как будто её вырезали в холсте. |
| BORDER_STYLE_RIDGE | Attribute BorderStyle: Ridge - Граница выглядит так, как будто она выступает из холста (противоположность Groove). |
| BORDER_STYLE_INSET | Attribute BorderStyle: Inset - Граница делает весь блок выглядящим так, как будто он вмонтирован в холст. |
| BORDER_STYLE_OUTSET | Attribute BorderStyle: Outset - Граница делает весь блок выглядящим так, как будто он выступает из холста (противоположность Inset). |
| TEXT_ALIGN_START | Attribute TextAlign: Start - Выравнено по начальному краю. |
| TEXT_ALIGN_CENTER | Attribute TextAlign: Center - Центрировано между начальным и конечным краем. |
| TEXT_ALIGN_END | Attribute TextAlign: End - Выравнено по конечному краю. |
| TEXT_ALIGN_JUSTIFY | Attribute TextAlign: Justify - Выравнено по начальному и конечному краям, при необходимости внутренний интервал в каждой строке расширяется для достижения такого выравнивания. Последняя (или единственная) строка должна быть выравнена только по начальному краю. |
| WIDTH_AUTO | Attribute Width: Auto - ширина элемента определяется внутренней шириной его содержимого. |
| HEIGHT_AUTO | Attribute Height: Auto - высота элемента определяется внутренней высотой его содержимого. |
| BLOCK_ALIGN_BEFORE | Attribute BlockAlign: Before - Передний край прямоугольника размещения первого дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| BLOCK_ALIGN_MIDDLE | Attribute BlockAlign: Middle- Дети центрированы внутри ячейки таблицы. Расстояние между передним краем прямоугольника размещения первого дочернего элемента и краем прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между задним краем прямоугольника размещения последнего дочернего элемента и краем прямоугольника содержимого ячейки таблицы. |
| BLOCK_ALIGN_AFTER | Attribute BlockAlign: После - После края последнего дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| BLOCK_ALIGN_JUSTIFY | Attribute BlockAlign: Justify - Элементы выравниваются по обоим краям (переднему и заднему) прямоугольника содержимого ячейки таблицы. Первый элемент размещается как описано для Before, а последний — как описано для After, с равными промежутками между элементами. Если элемент один, он выравнивается только по переднему краю, как для Before. |
| INLINE_ALIGN_START | Attribute InlineAlign: Start - Начальный край прямоугольника размещения каждого дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| INLINE_ALIGN_CENTER | Attribute InlineAlign: Center - Каждый элемент центрирован внутри ячейки таблицы. Расстояние между стартовыми краями прямоугольника размещения элемента и прямоугольника содержимого ячейки таблицы должно быть таким же, как расстояние между их конечными краями. |
| INLINE_ALIGN_END | Attribute InlineAlign: End - Конечный край прямоугольника размещения каждого дочернего элемента выравнивается с краем прямоугольника содержимого ячейки таблицы. |
| LINE_HEIGHT_NORMAL | Attribute LineHeight: Normal - Регулируйте высоту строки, включая любое ненулевое значение, указанное для BaselineShift. |
| LINE_HEIGHT_AUTO | Attribute LineHeight: Auto - Корректировка значения BaselineShift не будет выполнена. |
| TEXT_DECORATION_TYPE_NONE | Attribute TextDecorationType: None - Нет текстового оформления. |
| TEXT_DECORATION_TYPE_UNDERLINE | Attribute TextDecorationType: Underline - Линия под текстом. |
| TEXT_DECORATION_TYPE_OVERLINE | Attribute TextDecorationType: Overline - Линия над текстом. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Attribute TextDecorationType: LineThrough - Линия, проходящая через середину текста. |
| RUBY_ALIGN_START | Attribute RubyAlign: Start - Содержание должно быть выровнено по начальному краю в направлении inline‑progression. |
| RUBY_ALIGN_CENTER | Attribute RubyAlign: Center - Содержание должно быть центрировано в направлении inline‑progression. |
| RUBY_ALIGN_END | Attribute RubyAlign: End - Содержание должно быть выровнено по конечному краю в направлении inline‑progression. |
| RUBY_ALIGN_JUSTIFY | Attribute RubyAlign: Justify - Содержание должно быть расширено, чтобы заполнить доступную ширину в направлении inline‑progression. |
| RUBY_ALIGN_DISTRIBUTE | Attribute RubyAlign: Distribute - Содержание должно быть расширено, чтобы заполнить доступную ширину в направлении inline‑progression. Однако пробел также должен быть вставлен у начального и конечного краев текста. Распределение пробелов должно осуществляться по соотношению 1:2:1 (начало:внутренняя часть:конец). Оно должно быть изменено на соотношение 0:1:1, если ruby появляется в начале строки текста, или на 1:1:0, если ruby появляется в конце строки текста. |
| RUBY_POSITION_BEFORE | Attribute RubyPosition: Before - Содержание RT должно быть выровнено вдоль переднего края элемента. |
| RUBY_POSITION_AFTER | Attribute RubyPosition: After - Содержание RT должно быть выровнено вдоль заднего края элемента. |
| RUBY_POSITION_WARICHU | Attribute RubyPosition: Warichu - Элементы RT и связанные с ними RP должны быть отформатированы как warichu, следуя за элементом RB. |
| RUBY_POSITION_INLINE | Attribute RubyPosition: Inline - Элементы RT и связанные с ними RP должны быть отформатированы как комментарий в скобках, следуя за элементом RB. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Attribute GlyphOrientationVertical: Auto - Указывает ориентацию текста по умолчанию, в зависимости от того, является ли он полноширинным (ширина равна высоте). |
| LIST_NUMBERING_NONE | Attribute ListNumbering: None - Автонумерация отключена; элементы Lbl (если присутствуют) содержат произвольный текст, не подпадающий под какую‑либо схему нумерации. |
| LIST_NUMBERING_DISC | Attribute ListNumbering: Disc - Сплошной круглый маркер. |
| LIST_NUMBERING_CIRCLE | Attribute ListNumbering: Circle - Открытый круглый маркер. |
| LIST_NUMBERING_SQUARE | Атрибут ListNumbering: Square - Сплошной квадратный маркер. |
| LIST_NUMBERING_DECIMAL | Атрибут ListNumbering: Decimal - Десятичные арабские цифры (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Атрибут ListNumbering: UpperRoman - Римские цифры верхнего регистра (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Атрибут ListNumbering: LowerRoman - Римские цифры нижнего регистра (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Атрибут ListNumbering: UpperAlpha - Буквы верхнего регистра (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Атрибут ListNumbering: LowerAlpha - Буквы нижнего регистра (a, b, c, ...). |
| ROLE_RB | Атрибут Role: rb - Радиокнопка. |
| ROLE_CB | Атрибут Role: cb - Флажок. |
| ROLE_PB | Атрибут Role: pb - Кнопка. |
| ROLE_TV | Атрибут Role: tv - Поле текстового значения. |
| CHECKED_ON | Атрибут checked: On - Состояние радиокнопки или флажка. |
| CHECKED_OFF | Атрибут checked: Off - Состояние радиокнопки или флажка. |
| CHECKED_NEUTRAL | Атрибут проверен: Нейтральный - Состояние радиокнопки или флажка. |
| SCOPE_ROW | Область атрибута: Строка. |
| SCOPE_COLUMN | Область атрибута: Столбец. |
| SCOPE_BOTH | Область атрибута: Оба. |
## Методы
| Имя | Описание |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Получает имя атрибута по ключу атрибута. |

### См. также

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

