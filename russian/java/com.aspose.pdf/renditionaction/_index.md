---
title: RenditionAction
second_title: Aspose.PDF для справки по Java API
description: Действие воспроизведения, управляющее воспроизведением мультимедийного содержимого.
type: docs
weight: 306
url: /ru/java/com.aspose.pdf/renditionaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class RenditionAction extends PdfAction
```

Действие воспроизведения, управляющее воспроизведением мультимедийного содержимого.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RenditionAction(String mediaFile, ScreenAnnotation screen)](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Создает действие представления. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getJavaScript()](#getJavaScript--) | Получает или задает код JavaScript, связанный с действием. |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [getRendition()](#getRendition--) | Получает или задает представление, связанное с действием. |
| [getRenditionOperation()](#getRenditionOperation--) | Операция, выполняемая при запуске действия. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setJavaScript(String value)](#setJavaScript-java.lang.String-) | Получает или задает код JavaScript, связанный с действием. |
| [setRenditionOperation(int value)](#setRenditionOperation-int-) | Операция, выполняемая при запуске действия. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenditionAction(String mediaFile, ScreenAnnotation screen) {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
```
public RenditionAction(String mediaFile, ScreenAnnotation screen)
```


Создает действие представления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| mediaFile | java.lang.String | Путь к мультимедийному файлу. |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | Объект ScreenAnnotation, с которым будет связан RenditionAction. |

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
### getJavaScript() {#getJavaScript--}
```
public final String getJavaScript()
```


Получает или задает код JavaScript, связанный с действием.

**Возвращает:**
java.lang.String — строковое значение
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Следующие действия по порядку.

**Возвращает:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - Объект ActionCollection
### getRendition() {#getRendition--}
```
public final Rendition getRendition()
```


Получает или задает представление, связанное с действием.

**Возвращает:**
[Rendition](../../com.aspose.pdf/rendition) - экземпляр представления
### getRenditionOperation() {#getRenditionOperation--}
```
public final int getRenditionOperation()
```


Операция, выполняемая при запуске действия.

**Возвращает:**
int — элемент RenditionOperation
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




### setJavaScript(String value) {#setJavaScript-java.lang.String-}
```
public final void setJavaScript(String value)
```


Получает или задает код JavaScript, связанный с действием.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Стартовая стоимость |

### setRenditionOperation(int value) {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```


Операция, выполняемая при запуске действия.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент RenditionOperation |

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
