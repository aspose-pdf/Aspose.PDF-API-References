---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.StructureTypeStandard. Представляет стандартные типы структуры
type: docs
weight: 6730
url: /ru/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## Класс StructureTypeStandard

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
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Выполняет явное преобразование из строки в `StructureTypeStandard`. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Аннотация; PDF 1.5) Ассоциация между частью содержимого ILSE и соответствующей аннотацией PDF. Annot должен использоваться для всех аннотаций PDF, кроме аннотаций ссылок и виджетов. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Статья) Относительно самостоятельный текст, составляющий одно повествование или изложение. Статьи должны быть раздельными; то есть они не должны содержать другие статьи в качестве составных элементов. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Запись библиографии) Ссылка, идентифицирующая внешний источник некоторого цитируемого содержимого. Она может содержать метку (тип структуры Lbl) в качестве дочернего элемента. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Блок-цитата) Часть текста, состоящая из одного или нескольких абзацев, приписываемых кому-то, кроме автора окружающего текста. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Подпись) Краткая часть текста, описывающая таблицу или рисунок. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Код) Фрагмент текста компьютерной программы. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Раздел) Общий блочный элемент или группа элементов. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Документ) Полный документ. Это корневой элемент любого дерева структуры, содержащего несколько частей или несколько статей. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Рисунок) Элемент графического содержимого. Его размещение может быть указано с помощью атрибута компоновки Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Форма) Виджет-аннотация, представляющая интерактивное поле формы. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Формула) Математическая формула. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Заголовок) Метка для подраздела содержимого документа. Она должна быть первым дочерним элементом подраздела, который она возглавляет. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Заголовок уровня 1, для использования в соответствующих писателях, которые не могут иерархически вложить свои разделы и, следовательно, не могут определить уровень заголовка по его уровню вложенности. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Заголовок уровня 2, для использования в соответствующих писателях, которые не могут иерархически вложить свои разделы и, следовательно, не могут определить уровень заголовка по его уровню вложенности. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Заголовок уровня 3, для использования в соответствующих писателях, которые не могут иерархически вложить свои разделы и, следовательно, не могут определить уровень заголовка по его уровню вложенности. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Заголовок уровня 4, для использования в соответствующих писателях, которые не могут иерархически вложить свои разделы и, следовательно, не могут определить уровень заголовка по его уровню вложенности. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Заголовок уровня 5, для использования в соответствующих писателях, которые не могут иерархически вложить свои разделы и, следовательно, не могут определить уровень заголовка по его уровню вложенности. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Заголовок уровня 6, для использования в соответствующих писателях, которые не могут иерархически вложить свои разделы и, следовательно, не могут определить уровень заголовка по его уровню вложенности. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Указатель) Последовательность записей, содержащих идентифицирующий текст, сопровождаемый элементами ссылки, указывающими на вхождения указанного текста в основном теле документа. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Список) Последовательность элементов одинакового значения и важности. Его непосредственными дочерними элементами должны быть необязательная подпись (тип структуры Caption), за которой следуют один или несколько элементов списка (тип структуры LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Метка) Имя или номер, который отличает данный элемент от других в том же списке или другой группе подобных элементов. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Тело списка) Описательное содержимое элемента списка. В словарном списке, например, оно содержит определение термина. Оно может содержать содержимое непосредственно или иметь другие BLSE, возможно, включая вложенные списки, в качестве дочерних элементов. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Элемент списка) Индивидуальный член списка. Его дочерними элементами могут быть одна или несколько меток, тела списка или оба (типы структуры Lbl или LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Ссылка) Ассоциация между частью содержимого ILSE и соответствующей аннотацией или аннотациями ссылки. Его дочерними элементами должны быть один или несколько элементов содержимого или дочерние ILSE и одна или несколько ссылок на объекты, идентифицирующих связанные аннотации ссылки. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Несструктурный элемент) Элемент группировки, не имеющий внутреннего структурного значения; он служит исключительно для целей группировки. Этот тип элемента отличается от раздела (тип структуры Div) тем, что он не должен интерпретироваться или экспортироваться в другие форматы документов; однако его потомки должны обрабатываться нормально. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Заметка) Элемент пояснительного текста, такой как сноска или конечная заметка, на которую ссылаются из основного текста документа. Она может иметь метку (тип структуры Lbl) в качестве дочернего элемента. Заметка может быть включена в качестве дочернего элемента структуры в основном тексте, который на нее ссылается, или она может быть включена в другом месте (например, в разделе конечных заметок) и доступна посредством ссылки (тип структуры Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Абзац) Низкоуровневое деление текста. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Часть) Крупное деление документа. Этот тип элемента подходит для группировки статей или разделов. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Приватный элемент) Элемент группировки, содержащий частное содержимое, принадлежащее приложению, его создающему. Структурное значение этого типа элемента не указано и должно определяться полностью соответствующим писателем. Ни приватный элемент, ни любой из его потомков не должны интерпретироваться или экспортироваться в другие форматы документов. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Цитата) Встроенная часть текста, приписываемая кому-то, кроме автора окружающего текста. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Основной текст руби) Полноразмерный текст, к которому применяется аннотация руби. RB может содержать текст, другие встроенные элементы или их смесь. Он может иметь атрибут RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Ссылка) Цитата на содержимое в другом месте документа. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Пунктуация руби) Пунктуация, окружающая текст аннотации руби. Она используется только тогда, когда аннотация руби не может быть правильно отформатирована в стиле руби и вместо этого форматируется как обычный комментарий, или когда она форматируется как warichu. Она содержит текст (обычно один ЛЕВЫЙ или ПРАВЫЙ СКОБКА или аналогичный символ обрамления). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Текст аннотации руби) Текст меньшего размера, который должен быть размещен рядом с основным текстом руби. Он может содержать текст, другие встроенные элементы или их смесь. Он может иметь атрибуты RubyAlign и RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Руби; PDF 1.5) Примечание (аннотация), написанное меньшим размером текста и размещенное рядом с основным текстом, к которому оно относится. Элемент Ruby также может содержать элементы RB, RT и RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Раздел) Контейнер для группировки связанных элементов содержимого. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Интервал) Общая встроенная часть текста, не имеющая особых внутренних характеристик. Она может использоваться, например, для обозначения диапазона текста с заданным набором атрибутов стиля. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Таблица) Двумерная компоновка прямоугольных ячеек данных, возможно, имеющая сложную подсистему. Она содержит либо одну или несколько строк таблицы (тип структуры TR) в качестве дочерних элементов; либо необязательную шапку таблицы (тип структуры THead), за которой следуют один или несколько элементов тела таблицы (тип структуры TBody) и необязательный нижний колонтитул таблицы (тип структуры TFoot). Кроме того, таблица может иметь подпись (тип структуры Caption) в качестве своего первого или последнего дочернего элемента. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Группа строк тела таблицы; PDF 1.5) Группа строк, составляющих основную часть таблицы. Если таблица разбита на несколько страниц, область тела может быть разбита на границе строки. У таблицы может быть несколько элементов TBody, чтобы позволить нарисовать границу или фон для набора строк. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Ячейка данных таблицы) Ячейка таблицы, содержащая данные, которые являются частью содержимого таблицы. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Группа строк нижнего колонтитула таблицы; PDF 1.5) Группа строк, составляющих нижний колонтитул таблицы. Если таблица разбита на несколько страниц, эти строки могут быть перерисованы внизу каждого фрагмента таблицы (хотя существует только один элемент TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Ячейка заголовка таблицы) Ячейка таблицы, содержащая текст заголовка, описывающий одну или несколько строк или столбцов таблицы. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Группа строк заголовка таблицы; PDF 1.5) Группа строк, составляющих заголовок таблицы. Если таблица разбита на несколько страниц, эти строки могут быть перерисованы вверху каждого фрагмента таблицы (хотя существует только один элемент THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Оглавление) Список, состоящий из записей элементов оглавления (тип структуры TOCI) и/или других вложенных записей оглавления (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Элемент оглавления) Индивидуальный член оглавления. Дочерними элементами этого элемента могут быть любые из следующих типов структуры: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Строка таблицы) Строка заголовков или данных в таблице. Она может содержать ячейки заголовка таблицы и ячейки данных таблицы (типы структур TH и TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Комментарий или аннотация меньшего размера текста, отформатированная на две меньшие строки в пределах высоты содержащей строки текста и размещенная после (встроенно) основного текста, к которому она относится. Элемент Warichu также может содержать элементы WT и WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Пунктуация Warichu) Пунктуация, окружающая текст WT. Она содержит текст (обычно один ЛЕВЫЙ или ПРАВЫЙ СКОБКА или аналогичный символ обрамления). Согласно JIS X 4051-1995, скобки, окружающие warichu, могут быть преобразованы в ПРОБЕЛ (номинально 1/4 EM в ширину) по усмотрению форматировщика. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Текст Warichu) Текст меньшего размера комментария warichu, который отформатирован в две строки и размещен между окружающими элементами WP. |

### См. также

* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)