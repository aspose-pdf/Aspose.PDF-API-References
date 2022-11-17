---
title: ParagraphAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель объектов структуры страницы, таких как разделы и абзацы.
type: docs
weight: 269
url: /ru/java/com.aspose.pdf/paragraphabsorber/
---
**Наследование:**
java.lang.Object
```
public class ParagraphAbsorber
```

Представляет объект-поглотитель объектов структуры страницы, таких как разделы и абзацы. Выполняет поиск разделов и абзацев текста и предоставляет доступ к прямоугольникам и многоугольникам, описывающим его в текстовом координатном пространстве. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции TextFragments, сгруппированные по элементам структуры.

--------------------

В примере показано, как найти первый сегмент текста каждого абзаца на первой странице документа PDF и выделить его. // Открыть документ Document doc = new Document("input.pdf"); // Создаем объект ParagraphAbsorber ParagraphAbsorber Absorber = new ParagraphAbsorber(); // Принять поглотитель для первой страницы поглотителя.visit(doc.getPages.get\ _Элемент(1)); // Получить объект разметки первой страницы PageMarkup markup = поглотитель.getPageMarkups().get(0); // Перебираем элементы структуры текста страницы, чтобы найти первый текстовый фрагмент каждого абзаца для (раздел MarkupSection : markup.getSections())\ for (абзац MarkupParagraph: section.getParagraphs())\{ Фрагмент TextFragment = параграф.getFragments().get\ _Элемент (0); // Обновить свойства текста fragment.getTextState().setBackgroundColor (Color.getLightBlue());\ }\} // Сохраняем документ doc.save(GetOutputPath("output.pdf"));

--------------------

По завершении поиска коллекция ParagraphAbsorber.PageMarkups будет содержать объекты PageMarkup, которые представляют структуру страницы с помощью коллекций MarkupSection и MarkupParagraph . Объект TextFragment предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т. д.).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ParagraphAbsorber()](#ParagraphAbsorber--) | Инициализирует новый экземпляр ParagraphAbsorber, который выполняет поиск разделов/абзацев документа или страницы. |
| [ParagraphAbsorber(int sectionsSearchDepth)](#ParagraphAbsorber-int-) | Инициализирует новый экземпляр ParagraphAbsorber, который выполняет поиск разделов/абзацев документа или страницы. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageMarkups()](#getPageMarkups--) | Получает коллекцию поглощенных PageMarkup. |
| [getSectionsSearchDepth()](#getSectionsSearchDepth--) | Получает или задает значение, указывающее, сколько раз будет выполняться последовательный поиск более мелких элементов структуры. |
| [hashCode()](#hashCode--) |  |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | Получает или задает значение, указывающее, можно ли рассматривать начальные строки текста следующего раздела как продолжение последнего абзаца предыдущего раздела. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | Получает или задает значение, указывающее, можно ли рассматривать начальные строки текста следующего раздела как продолжение последнего абзаца предыдущего раздела. |
| [setSectionsSearchDepth(int value)](#setSectionsSearchDepth-int-) | Получает или задает значение, указывающее, сколько раз будет выполняться последовательный поиск более мелких элементов структуры. |
| [toString()](#toString--) |  |
| [visit(Document doc)](#visit-com.aspose.pdf.Document-) | Выполняет поиск разделов и абзацев по заданному[Document](../../com.aspose.pdf/document). |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Выполняет поиск на указанной странице. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ParagraphAbsorber() {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```


Инициализирует новый экземпляр ParagraphAbsorber, который выполняет поиск разделов/абзацев документа или страницы.

### ParagraphAbsorber(int sectionsSearchDepth) {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```


Инициализирует новый экземпляр ParagraphAbsorber, который выполняет поиск разделов/абзацев документа или страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| sectionsSearchDepth | int | Количество последовательных поисков более мелких элементов структуры, которые будут выполнены.

--------------------

Дополнительные сведения об этом параметре см. в описании свойства ParagraphAbsorber.SectionsSearchDepth.

 --------------------|

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getPageMarkups() {#getPageMarkups--}
```
public List<PageMarkup> getPageMarkups()
```


Получает коллекцию поглощенных PageMarkup.

**Возвращает:**
java.util.List<com.aspose.pdf.PageMarkup> — Список экземпляров PageMarkup
### getSectionsSearchDepth() {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```


Получает или задает значение, указывающее, сколько раз будет выполняться последовательный поиск более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска разделов, разделенных по горизонтали (заголовки, абзацы и т. д.), и три поиска разделов, разделенных по вертикали (столбцы).

--------------------

Увеличение этого значения может привести к незначительному снижению производительности без видимых изменений в результатах поиска. Уменьшение этого значения может привести к неправильному определению абзацев в разделах. Мы не рекомендуем устанавливать значение меньше значения по умолчанию, если вы не хотите получать только «грубые» элементы структуры страницы.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isMulticolumnParagraphsAllowed() {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```


Получает или задает значение, указывающее, можно ли рассматривать начальные строки текста следующего раздела как продолжение последнего абзаца предыдущего раздела.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMulticolumnParagraphsAllowed(boolean value) {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```


Получает или задает значение, указывающее, можно ли рассматривать начальные строки текста следующего раздела как продолжение последнего абзаца предыдущего раздела.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSectionsSearchDepth(int value) {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```


Получает или задает значение, указывающее, сколько раз будет выполняться последовательный поиск более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска разделов, разделенных по горизонтали (заголовки, абзацы и т. д.), и три поиска разделов, разделенных по вертикали (столбцы).

--------------------

Увеличение этого значения может привести к незначительному снижению производительности без видимых изменений в результатах поиска. Уменьшение этого значения может привести к неправильному определению абзацев в разделах. Мы не рекомендуем устанавливать значение меньше значения по умолчанию, если вы не хотите получать только «грубые» элементы структуры страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### visit(Document doc) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document doc)
```


Выполняет поиск разделов и абзацев по заданному[Document](../../com.aspose.pdf/document).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Объект документа PDF. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Выполняет поиск на указанной странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа PDF. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
