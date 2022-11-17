---
title: HtmlFragment
second_title: Aspose.PDF для справки по Java API
description: Представляет HTML-фрагмент.
type: docs
weight: 157
url: /ru/java/com.aspose.pdf/htmlfragment/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment)
```
public final class HtmlFragment extends FormattedFragment
```

Представляет HTML-фрагмент.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlFragment(String text)](#HtmlFragment-java.lang.String-) | Инициализирует новый экземпляр класса HtmlFragment. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонирует фрагмент html. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHtmlLoadOptions()](#getHtmlLoadOptions--) | Получает HtmlLoadOptions, которые будут использоваться для загрузки (и отрисовки) HTML в этот экземпляр класса. |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getRectangle()](#getRectangle--) | Получает прямоугольник HtmlFragment |
| [getTextState()](#getTextState--) | Получает или устанавливает шрифт |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isBreakWords()](#isBreakWords--) | Получает или задает разрыв слов |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [isParagraphHasMargin()](#isParagraphHasMargin--) | Получает или задает, имеет ли абзац поле по умолчанию, в противном случае поле равно 0 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBreakWords(boolean value)](#setBreakWords-boolean-) | Получает или задает разрыв слов |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHtmlLoadOptions(HtmlLoadOptions value)](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Задает HtmlLoadOptions, которые будут использоваться для загрузки (и рендеринга) HTML в этот экземпляр класса. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setParagraphHasMargin(boolean value)](#setParagraphHasMargin-boolean-) | Получает или задает, имеет ли абзац поле по умолчанию, в противном случае поле равно 0 |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Получает или устанавливает шрифт |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlFragment(String text) {#HtmlFragment-java.lang.String-}
```
public HtmlFragment(String text)
```


Инициализирует новый экземпляр класса HtmlFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Фрагмент текста |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует фрагмент html.

**Возвращает:**
java.lang.Object — клонированный объект HTML-фрагмента.
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
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание абзаца

**Возвращает:**
int - значение HorizontalAlignment
### getHtmlLoadOptions() {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```


Получает HtmlLoadOptions, которые будут использоваться для загрузки (и отрисовки) HTML в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать определенные настройки для импорта HTML для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определенный BasePath для импортируемого HTML или должен использовать определенный загрузчик внешних ресурсов) Если параметр установлен по умолчанию (нулевой), то будут использоваться стандартные параметры загрузки HTML.

**Возвращает:**
[HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) - значение хтмллоадоптионс
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает гиперссылку фрагмента (для генератора pdf).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - гиперссылка на фрагмент (для генератора pdf).
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```


Получает прямоугольник HtmlFragment

**Возвращает:**
java.awt.geom.Rectangle2D.Float — экземпляр java.awt.geom.Rectangle2D.Float
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Получает или устанавливает шрифт

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Объект TextState
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание абзаца

**Возвращает:**
int - элемент вертикального выравнивания
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Получает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isBreakWords() {#isBreakWords--}
```
public final boolean isBreakWords()
```


Получает или задает разрыв слов

**Возвращает:**
boolean - логическое значение
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Получает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isParagraphHasMargin() {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```


Получает или задает, имеет ли абзац поле по умолчанию, в противном случае поле равно 0

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




### setBreakWords(boolean value) {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```


Получает или задает разрыв слов

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает горизонтальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHtmlLoadOptions(HtmlLoadOptions value) {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
```
public void setHtmlLoadOptions(HtmlLoadOptions value)
```


Задает HtmlLoadOptions, которые будут использоваться для загрузки (и рендеринга) HTML в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать определенные настройки для импорта HTML для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определенный BasePath для импортируемого HTML или должен использовать определенный загрузчик внешних ресурсов) Если параметр установлен по умолчанию (нулевой), то будут использоваться стандартные параметры загрузки HTML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) | значение хтмллоадоптионс |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Устанавливает гиперссылку (для генератора pdf).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | гиперссылка (для генератора pdf). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Устанавливает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setParagraphHasMargin(boolean value) {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```


Получает или задает, имеет ли абзац поле по умолчанию, в противном случае поле равно 0

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```


Получает или устанавливает шрифт

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Объект TextState |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

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
