---
title: "Класс StructureTypeStandard"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.LogicalStructure.StructureTypeStandard класс. Представляет стандартные типы структуры"
type: docs
weight: 6870
url: /ru/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Представляет стандартные типы структуры.

```csharp
public sealed class StructureTypeStandard
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Получает категорию стандартного типа структуры. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Получает имя тега [`StructureElement`](../structureelement/). |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Выполняет явное преобразование из String в `StructureTypeStandard`. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) Связь между частью содержимого ILSE и соответствующей аннотацией PDF. Annot следует использовать для всех аннотаций PDF, за исключением аннотаций ссылок и аннотаций виджетов. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) Относительно самостоятельный блок текста, представляющий собой единый рассказ или изложение. Статьи должны быть раздельными; то есть они не должны содержать другие статьи в качестве составных элементов. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliography entry) Ссылка, идентифицирующая внешний источник некоторого цитируемого содержания. Она может содержать метку (тип структуры Lbl) как дочерний элемент. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Block quotation) Фрагмент текста, состоящий из одного или нескольких абзацев, приписываемый лицу, отличному от автора окружающего текста. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Caption) Краткий фрагмент текста, описывающий таблицу или рисунок. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) Фрагмент текста компьютерной программы. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Универсальный блочный элемент или группа элементов. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) Полный документ. Это корневой элемент любой структуры дерева, содержащего несколько частей или несколько статей. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) Элемент графического содержимого. Его размещение может быть указано с помощью атрибута макета Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) Виджет‑аннотация, представляющая интерактивное поле формы. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) Математическая формула. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Heading) Метка для подраздела содержимого документа. Она должна быть первым дочерним элементом раздела, который она обозначает. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Заголовок уровня 1, для использования в совместимых редакторах, которые не могут иерархически вложить свои разделы и поэтому не могут определить уровень заголовка по уровню вложения. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Заголовок уровня 2, для использования в совместимых редакторах, которые не могут иерархически вложить свои разделы и поэтому не могут определить уровень заголовка по уровню вложения. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Заголовок уровня 3, для использования в совместимых редакторах, которые не могут иерархически вложить свои разделы и поэтому не могут определить уровень заголовка по уровню вложения. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Заголовок уровня 4, для использования в совместимых редакторах, которые не могут иерархически вложить свои разделы и поэтому не могут определить уровень заголовка по уровню вложения. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Заголовок уровня 5, для использования в совместимых редакторах, которые не могут иерархически вложить свои разделы и поэтому не могут определить уровень заголовка по уровню вложения. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Заголовок уровня 6, для использования в совместимых редакторах, которые не могут иерархически вложить свои разделы и поэтому не могут определить уровень заголовка по уровню вложения. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) Последовательность записей, содержащих идентифицирующий текст, сопровождаемый ссылочными элементами, указывающими на вхождения указанного текста в основной части документа. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (List) Последовательность элементов одинакового значения и важности. Его непосредственные дочерние элементы должны включать необязательную подпись (тип структуры Caption), за которой следуют один или несколько пунктов списка (тип структуры LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) Имя или номер, отличающий данный элемент от остальных в том же списке или в другой группе подобных элементов. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (List body) Описательное содержание пункта списка. Например, в словарном списке оно содержит определение термина. Оно может содержать содержание напрямую или иметь другие BLSE, возможно, включая вложенные списки, в качестве дочерних элементов. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (List item) Отдельный элемент списка. Его дочерние элементы могут быть одной или несколькими метками, телами списка или и теми, и другими (типы структуры Lbl или LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) Связь между частью содержимого ILSE и соответствующей аннотацией ссылки или аннотациями ссылок. Его дочерние элементы должны включать один или несколько элементов содержимого или дочерних ILSE и одну или несколько объектных ссылок, идентифицирующих связанные аннотации ссылок. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Nonstructural element) Группирующий элемент, не имеющий внутреннего структурного значения; он служит исключительно для целей группировки. Этот тип элемента отличается от раздела (тип структуры Div) тем, что не должен интерпретироваться или экспортироваться в другие форматы документов; однако его потомки должны обрабатываться нормально. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Note) Элемент пояснительного текста, такой как сноска или концевая сноска, на который ссылаются из основного текста документа. Он может иметь метку (тип структуры Lbl) как дочерний элемент. Примечание может быть включено как дочерний элемент структурного элемента в основном тексте, который на него ссылается, либо может быть размещено в другом месте (например, в разделе концевых сносок) и доступно посредством ссылки (тип структуры Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragraph) Низкоуровневое деление текста. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Part) Крупномасштабное деление документа. Этот тип элемента подходит для группировки статей или разделов. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Private element) Группирующий элемент, содержащий приватный контент, принадлежащий приложению, его создавшему. Структурное значение этого типа элемента не определено и должно полностью определяться соответствующим автором. Ни элемент Private, ни любые его потомки не должны интерпретироваться или экспортироваться в другие форматы документов. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Quotation) Встроенный фрагмент текста, приписываемый кому‑то, кроме автора окружающего текста. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby base text) Текст полного размера, к которому применяется руби‑аннотация. RB может содержать текст, другие встроенные элементы или их смесь. Может иметь атрибут RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Reference) Ссылка на содержимое в другом месте документа. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby punctuation) Знаки препинания, окружающие текст руби‑аннотации. Используется только когда руби‑аннотация не может быть правильно оформлена в стиле ruby и вместо этого форматируется как обычный комментарий, либо когда она оформлена как warichu. Содержит текст (обычно одну левую или правую скобку или аналогичный ограничительный символ). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby annotation text) Текст меньшего размера, который должен располагаться рядом с базовым текстом ruby. Может содержать текст, другие встроенные элементы или их смесь. Может иметь атрибуты RubyAlign и RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Пояснительная записка (аннотация), написанная меньшим размером шрифта и расположенная рядом с базовым текстом, к которому она относится. Элемент Ruby также может содержать элементы RB, RT и RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Section) Контейнер для группировки связанных элементов контента. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Универсальный встроенный фрагмент текста без особых характеристик. Может использоваться, например, для ограничения диапазона текста заданным набором атрибутов стиля. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Table) Двумерное расположение прямоугольных ячеек данных, возможно со сложной подструктурой. Содержит одну или несколько строк таблицы (тип структуры TR) как дочерние элементы; либо необязательный заголовок таблицы (тип структуры THead), за которым следуют одна или несколько элементов тела таблицы (тип структуры TBody) и необязательный нижний колонтитул (тип структуры TFoot). Кроме того, таблица может иметь подпись (тип структуры Caption) в качестве первого или последнего дочернего элемента. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Table body row group; PDF 1.5) Группа строк, составляющих основную часть тела таблицы. Если таблица разбивается на несколько страниц, область тела может быть разделена по границе строки. Таблица может иметь несколько элементов TBody для отрисовки границы или фона набора строк. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Table data cell) Ячейка таблицы, содержащая данные, являющиеся частью содержимого таблицы. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Table footer row group; PDF 1.5) Группа строк, составляющих нижний колонтитул таблицы. Если таблица разбивается на несколько страниц, эти строки могут быть перерисованы внизу каждого фрагмента таблицы (хотя существует только один элемент TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Table header cell) Ячейка таблицы, содержащая заголовочный текст, описывающий одну или несколько строк или столбцов таблицы. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Table header row group; PDF 1.5) Группа строк, составляющих заголовок таблицы. Если таблица разбивается на несколько страниц, эти строки могут быть перерисованы вверху каждого фрагмента таблицы (хотя существует только один элемент THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Table of contents) Список, состоящий из записей элементов оглавления (тип структуры TOCI) и/или других вложенных записей оглавления (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Table of contents item) Отдельный элемент оглавления. Дочерними элементами этой записи могут быть любые из следующих типов структур: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Table row) Строка заголовков или данных в таблице. Она может содержать ячейки заголовков таблицы и ячейки данных таблицы (типы структуры TH и TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Комментарий или аннотация меньшего размера текста, отформатированная в две более короткие строки в пределах высоты содержащей строки текста и размещённая после (встроенно) базового текста, к которому она относится. Элемент Warichu также может содержать элементы WT и WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu punctuation) Знаки препинания, окружающие текст WT. Они содержат текст (обычно одну левую или правую скобку или аналогичный ограничительный символ). Согласно JIS X 4051-1995, скобки, окружающие warichu, могут быть заменены ПРОБЕЛОМ (условно 1/4 EM в ширину) по усмотрению форматировщика. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) Текст комментария warichu меньшего размера, отформатированный в две строки и размещённый между окружающими элементами WP. |

### См. также

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


