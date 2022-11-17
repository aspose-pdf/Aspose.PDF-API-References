---
title: PageMarkup
second_title: Aspose.PDF для справки по Java API
description: Разметка страницы представлена коллекциями MarkupSection и MarkupParagraph.
type: docs
weight: 265
url: /ru/java/com.aspose.pdf/pagemarkup/
---
**Наследование:**
java.lang.Object
```
public final class PageMarkup
```

Разметка страницы представлена коллекциями MarkupSection и MarkupParagraph.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNumber()](#getNumber--) | Получает обработанный номер страницы. |
| [getParagraphs()](#getParagraphs--) | Получает коллекцию MarkupParagraph, которая была найдена на странице. |
| [getRectangle()](#getRectangle--) | Получает обработанный прямоугольник страницы. |
| [getSections()](#getSections--) | Получает коллекцию MarkupSection, найденную на странице. |
| [getTextFragments()](#getTextFragments--) | Получает коллекцию TextFragment, найденную на странице. |
| [hashCode()](#hashCode--) |  |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | Получает или задает значение, указывающее, можно ли рассматривать начальные строки текста следующего раздела как продолжение последнего абзаца предыдущего раздела. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | Получает или задает значение, указывающее, можно ли рассматривать начальные строки текста следующего раздела как продолжение последнего абзаца предыдущего раздела. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getNumber() {#getNumber--}
```
public int getNumber()
```


Получает обработанный номер страницы.

**Возвращает:**
интервал - целочисленное значение
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


Получает коллекцию MarkupParagraph, которая была найдена на странице.

**Возвращает:**
java.util.List<com.aspose.pdf.MarkupParagraph> — Список экземпляров MarkupParagraph
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает обработанный прямоугольник страницы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getSections() {#getSections--}
```
public List<MarkupSection> getSections()
```


Получает коллекцию MarkupSection, найденную на странице.

**Возвращает:**
java.util.List<com.aspose.pdf.MarkupSection> — Список экземпляров MarkupSection
### getTextFragments() {#getTextFragments--}
```
public List<TextFragment> getTextFragments()
```


Получает коллекцию TextFragment, найденную на странице.

--------------------

Объект TextFragment предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т. д.).

**Возвращает:**
java.util.List<com.aspose.pdf.TextFragment> — Список экземпляров TextFragment
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
