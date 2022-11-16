---
title: FontAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель шрифтов.
type: docs
weight: 131
url: /ru/java/com.aspose.pdf/fontabsorber/
---
**Наследование:**
java.lang.Object
```
public class FontAbsorber
```

Представляет объект-поглотитель шрифтов. Выполняет поиск шрифтов и предоставляет доступ к результатам поиска через коллекцию FontAbsorber.Fonts.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontAbsorber()](#FontAbsorber--) | Инициализирует новый экземпляр FontAbsorber, выполняющий поиск шрифтов в документе. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFonts()](#getFonts--) | Получает коллекцию вхождений поиска, представленных объектами Font. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(Document pdf)](#visit-com.aspose.pdf.Document-) | Выполняет поиск по указанному документу. |
| [visit(Document pdf, int startPage, int pageCount)](#visit-com.aspose.pdf.Document-int-int-) | Выполняет поиск в указанном диапазоне страниц документа. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontAbsorber() {#FontAbsorber--}
```
public FontAbsorber()
```


Инициализирует новый экземпляр FontAbsorber, выполняющий поиск шрифтов в документе.

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
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Получает коллекцию вхождений поиска, представленных объектами Font.

**Возвращает:**
[FontCollection](../../com.aspose.pdf/fontcollection) - Объект FontCollection
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
### visit(Document pdf) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document pdf)
```


Выполняет поиск по указанному документу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf объект документа. |

### visit(Document pdf, int startPage, int pageCount) {#visit-com.aspose.pdf.Document-int-int-}
```
public void visit(Document pdf, int startPage, int pageCount)
```


Выполняет поиск в указанном диапазоне страниц документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf объект документа. |
| startPage | int | Стартовая страница документа Pdf. |
| pageCount | int | количество страниц в PDF-документе |

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
