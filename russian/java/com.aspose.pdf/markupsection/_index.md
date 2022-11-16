---
title: MarkupSection
second_title: Aspose.PDF для справки по Java API
description: Представляет собой раздел разметки — прямоугольную область страницы, которая содержит текст и может быть визуально отделена от других текстовых блоков.
type: docs
weight: 208
url: /ru/java/com.aspose.pdf/markupsection/
---
**Наследование:**
java.lang.Object
```
public final class MarkupSection
```

Представляет собой раздел разметки — прямоугольную область страницы, которая содержит текст и может быть визуально отделена от других текстовых блоков.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFragments()](#getFragments--) | Коллекция непустых объектов TextFragment, находящихся внутри секции. |
| [getParagraphs()](#getParagraphs--) | Коллекция объектов MarkupParagraph, находящихся внутри раздела. |
| [getRectangle()](#getRectangle--) | Прямоугольник сечения |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
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
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


Коллекция непустых объектов TextFragment, находящихся внутри секции.

--------------------

Объект TextFragment предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т. д.).

**Возвращает:**
java.util.List<com.aspose.pdf.TextFragment> — список экземпляров TextFragment
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


Коллекция объектов MarkupParagraph, находящихся внутри раздела.

**Возвращает:**
java.util.List<com.aspose.pdf.MarkupParagraph> — список экземпляров MarkupParagraph
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Прямоугольник сечения

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Экземпляр прямоугольника
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
