---
title: Redaction
second_title: Aspose.PDF для справки по Java API
description: Только для внутреннего использования
type: docs
weight: 301
url: /ru/java/com.aspose.pdf/redaction/
---
**Наследование:**
java.lang.Object
```
public class Redaction
```

Только для внутреннего использования
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Redaction()](#Redaction--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [_RedactText(Page page, Rectangle rect)](#-RedactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getRedactionAppearance(Rectangle rect, Color color)](#getRedactionAppearance-com.aspose.pdf.Rectangle-java.awt.Color-) | получить внешний вид редакции |
| [getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color)](#getRedactionAppearanceInternal-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-) | Для внутреннего использования получите только внешний вид Redaction. |
| [getredactArea(Page page, Rectangle rect, Color color)](#getredactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | получить область редактирования |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [redactAnnotations(Page page, Rectangle rect)](#redactAnnotations-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Удаляет аннотацию, которая находится в нужном прямоугольнике |
| [redactArea(Page page, Rectangle rect, Color color)](#redactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | Для внутреннего использования получите только отредактированную область |
| [redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea)](#redactAreaInternal-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-boolean-) |  |
| [redactImages(Page page, Rectangle rect, Color color)](#redactImages-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | Удаляет изображения (или редактирует содержимое изображения, если изображение частично закрыто прямоугольником) |
| [redactText(Page page, Rectangle rect)](#redactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Удаляет текст, который находится в нужном прямоугольнике |
| [redactText(XForm form, Rectangle rect)](#redactText-com.aspose.pdf.XForm-com.aspose.pdf.Rectangle-) | Удаляет текст, который находится в нужном прямоугольнике |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Redaction() {#Redaction--}
```
public Redaction()
```


### _RedactText(Page page, Rectangle rect) {#-RedactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void _RedactText(Page page, Rectangle rect)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

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
### getRedactionAppearance(Rectangle rect, Color color) {#getRedactionAppearance-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static List<Operator> getRedactionAppearance(Rectangle rect, Color color)
```


получить внешний вид редакции

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |
| color | java.awt.Color | Цвет объекта |

**Возвращает:**
java.util.List<com.aspose.pdf.Operator> — объект списка 
### getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color) {#getRedactionAppearanceInternal-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-}
```
public static System.Collections.Generic.List<Operator> getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color)
```


Для внутреннего использования получите только внешний вид Redaction.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |
| color | com.aspose.ms.System.Drawing.Color | Цвет объекта |

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> — объект списка 
### getredactArea(Page page, Rectangle rect, Color color) {#getredactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void getredactArea(Page page, Rectangle rect, Color color)
```


получить область редактирования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |
| color | java.awt.Color | Цвет объекта |

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




### redactAnnotations(Page page, Rectangle rect) {#redactAnnotations-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void redactAnnotations(Page page, Rectangle rect)
```


Удаляет аннотацию, которая находится в нужном прямоугольнике

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### redactArea(Page page, Rectangle rect, Color color) {#redactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void redactArea(Page page, Rectangle rect, Color color)
```


Для внутреннего использования получите только отредактированную область

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |
| color | java.awt.Color | Цвет объекта |

### redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea) {#redactAreaInternal-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-boolean-}
```
public static void redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |
| color | com.aspose.ms.System.Drawing.Color |  |
| exactArea | boolean |  |

### redactImages(Page page, Rectangle rect, Color color) {#redactImages-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void redactImages(Page page, Rectangle rect, Color color)
```


Удаляет изображения (или редактирует содержимое изображения, если изображение частично закрыто прямоугольником)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |
| color | java.awt.Color | Цвет объекта |

### redactText(Page page, Rectangle rect) {#redactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void redactText(Page page, Rectangle rect)
```


Удаляет текст, который находится в нужном прямоугольнике

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### redactText(XForm form, Rectangle rect) {#redactText-com.aspose.pdf.XForm-com.aspose.pdf.Rectangle-}
```
public static void redactText(XForm form, Rectangle rect)
```


Удаляет текст, который находится в нужном прямоугольнике

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | объект XForm |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

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
