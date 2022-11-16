---
title: StampInfo
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий информацию штампа.
type: docs
weight: 60
url: /ru/java/com.aspose.pdf.facades/stampinfo/
---
**Наследование:**
java.lang.Object
```
public final class StampInfo
```

Класс, представляющий информацию штампа.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getForm()](#getForm--) | Получает XForm штампа. |
| [getImage()](#getImage--) | Получает изображение штампа. |
| [getImageInternal()](#getImageInternal--) | Получает изображение штампа. |
| [getIndexOnPage()](#getIndexOnPage--) | Получает индекс штампа на странице. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник, в который помещается штамп. |
| [getStampId()](#getStampId--) | Получает идентификатор штампа. |
| [getStampType()](#getStampType--) | Получает тип штампа (изображение/форма). |
| [getText()](#getText--) | Получает текст в штампе. |
| [getVisible()](#getVisible--) | Получает видимость штампа. |
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
### getForm() {#getForm--}
```
public XForm getForm()
```


Получает XForm штампа.

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - XForm объект
### getImage() {#getImage--}
```
public BufferedImage getImage()
```


Получает изображение штампа. Может быть нулевым, если штамп не содержит изображений (например, для текстового штампа).

**Возвращает:**
java.awt.image.BufferedImage — объект BufferedImage
### getImageInternal() {#getImageInternal--}
```
public System.Drawing.Image getImageInternal()
```


Получает изображение штампа. Может быть нулевым, если штамп не содержит изображений (например, для текстового штампа).

**Возвращает:**
[Image](../../com.aspose.ms.system.drawing/image) - Объект изображения
### getIndexOnPage() {#getIndexOnPage--}
```
public int getIndexOnPage()
```


Получает индекс штампа на странице.

**Возвращает:**
интервал - целочисленное значение
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник, в который помещается штамп.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный элемент
### getStampId() {#getStampId--}
```
public int getStampId()
```


Получает идентификатор штампа.

**Возвращает:**
интервал - целочисленное значение
### getStampType() {#getStampType--}
```
public int getStampType()
```


Получает тип штампа (изображение/форма).

**Возвращает:**
int - элемент StampType
### getText() {#getText--}
```
public String getText()
```


Получает текст в штампе.

**Возвращает:**
java.lang.String — строковое значение
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Получает видимость штампа. Если false, то штамп скрыт (с HideStampById). Скрытый штамп можно восстановить с помощью ShowStampById.

**Возвращает:**
boolean - логическое значение
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
