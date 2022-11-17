---
title: LatexFragment
second_title: Aspose.PDF для справки по Java API
description: Представляет фрагмент TeX.
type: docs
weight: 185
url: /ru/java/com.aspose.pdf/latexfragment/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment), [com.aspose.pdf.TeXFragment](../../com.aspose.pdf/texfragment)
```
public class LatexFragment extends TeXFragment
```

Представляет фрагмент TeX.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LatexFragment(String text)](#LatexFragment-java.lang.String-) | Инициализирует новый экземпляр класса HtmlFragment. |
| [LatexFragment(String text, boolean removeIndents)](#LatexFragment-java.lang.String-boolean-) | Инициализирует новый экземпляр класса HtmlFragment. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Фрагмент клонов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getLatexLoadOptionsOfInstance()](#getLatexLoadOptionsOfInstance--) | Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getTeXLoadOptionsOfInstance()](#getTeXLoadOptionsOfInstance--) | Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setLatexLoadOptionsOfInstance(TeXLoadOptions value)](#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setTeXLoadOptionsOfInstance(TeXLoadOptions value)](#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | Получает или задает LatexLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LatexFragment(String text) {#LatexFragment-java.lang.String-}
```
public LatexFragment(String text)
```


Инициализирует новый экземпляр класса HtmlFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Фрагмент текста |

### LatexFragment(String text, boolean removeIndents) {#LatexFragment-java.lang.String-boolean-}
```
public LatexFragment(String text, boolean removeIndents)
```


Инициализирует новый экземпляр класса HtmlFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Фрагмент текста |
| removeIndents | boolean | Определяет, не делать ли отступы при наборе фрагмента LaTeX. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Фрагмент клонов.

**Возвращает:**
java.lang.Object — Клонированный фрагмент.
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
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает гиперссылку фрагмента (для генератора pdf).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - гиперссылка на фрагмент (для генератора pdf).
### getLatexLoadOptionsOfInstance() {#getLatexLoadOptionsOfInstance--}
```
public final TeXLoadOptions getLatexLoadOptionsOfInstance()
```


Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать определенные настройки для импорта LaTeX для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определенный BasePath для импортированного LaTeX или должен использовать определенный загрузчик внешних ресурсов) Если параметр установлен по умолчанию (нулевой), то будут использоваться стандартные параметры загрузки LaTeX.

**Возвращает:**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - Экземпляр TeXLoadOptions
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getTeXLoadOptionsOfInstance() {#getTeXLoadOptionsOfInstance--}
```
public TeXLoadOptions getTeXLoadOptionsOfInstance()
```


Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать определенные настройки для импорта LaTeX для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определенный BasePath для импортированного LaTeX или должен использовать определенный загрузчик внешних ресурсов) Если параметр установлен по умолчанию (нулевой), то будут использоваться стандартные параметры загрузки LaTeX.

**Возвращает:**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - Экземпляр TeXLoadOptions
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setLatexLoadOptionsOfInstance(TeXLoadOptions value) {#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public final void setLatexLoadOptionsOfInstance(TeXLoadOptions value)
```


Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать определенные настройки для импорта LaTeX для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определенный BasePath для импортированного LaTeX или должен использовать определенный загрузчик внешних ресурсов) Если параметр установлен по умолчанию (нулевой), то будут использоваться стандартные параметры загрузки LaTeX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | Экземпляр TeXLoadOptions |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setTeXLoadOptionsOfInstance(TeXLoadOptions value) {#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public void setTeXLoadOptionsOfInstance(TeXLoadOptions value)
```


Получает или задает LatexLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать определенные настройки для импорта LaTeX для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определенный BasePath для импортированного LaTeX или должен использовать определенный загрузчик внешних ресурсов) Если параметр установлен по умолчанию (нулевой), то будут использоваться стандартные параметры загрузки LaTeX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | Экземпляр TeXLoadOptions |

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
