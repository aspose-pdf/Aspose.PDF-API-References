---
title: MarkupParagraph
second_title: Aspose.PDF для справки по Java API
description: Представляет абзац.
type: docs
weight: 207
url: /ru/java/com.aspose.pdf/markupparagraph/
---
**Наследование:**
java.lang.Object
```
public final class MarkupParagraph
```

Представляет абзац.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContinuationPageNumbers()](#getContinuationPageNumbers--) | Список номеров страниц, на которых абзац продолжается. |
| [getFragments()](#getFragments--) | Коллекция непустых объектов TextFragment абзаца. |
| [getLines()](#getLines--) | Строки абзаца. |
| [getPoints()](#getPoints--) | Точки многоугольника, описывающего абзац. |
| [getSecondaryPoints()](#getSecondaryPoints--) | Точки вторичного многоугольника описывают продолжение абзаца. |
| [getText()](#getText--) | Получает строковый текстовый объект, который представляет объект MarkupParagraph. |
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
### getContinuationPageNumbers() {#getContinuationPageNumbers--}
```
public final List<Integer> getContinuationPageNumbers()
```


Список номеров страниц, на которых абзац продолжается. Он будет соответствовать странице, на которой начался абзац, если он продолжается в следующем столбце на той же странице.

**Возвращает:**
java.util.List<java.lang.Integer> — список целых чисел
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


Коллекция непустых объектов TextFragment абзаца.

--------------------

Объект TextFragment предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т. д.).

**Возвращает:**
java.util.List<com.aspose.pdf.TextFragment> — список экземпляров TextFragment
### getLines() {#getLines--}
```
public List<System.Collections.Generic.List<TextFragment>> getLines()
```


Строки абзаца. Каждая строка представлена списком текстовых фрагментов.

--------------------

Объект TextFragment предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т. д.).

**Возвращает:**
java.util.List<com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.TextFragment>> — список экземпляров TextFragment
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Точки многоугольника, описывающего абзац. Отправной точкой является нижний левый угол абзаца. И следующие точки в последовательности против часовой стрелки.

**Возвращает:**
com.aspose.pdf.Point[] - массив экземпляров Point
### getSecondaryPoints() {#getSecondaryPoints--}
```
public final List<Point[]> getSecondaryPoints()
```


Точки вторичного многоугольника описывают продолжение абзаца. Он не будет нулевым, если абзац будет продолжен в следующем столбце или на следующей странице. Отправной точкой является нижний левый угол абзаца. И следующие точки в последовательности против часовой стрелки.

**Возвращает:**
java.util.List<com.aspose.pdf.Point[]> - список точек[]
### getText() {#getText--}
```
public String getText()
```


Получает строковый текстовый объект, который представляет объект MarkupParagraph.

**Возвращает:**
java.lang.String — строковое значение
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
