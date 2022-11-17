---
title: FigureElement
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий фигуру логической структуры.
type: docs
weight: 109
url: /ru/java/com.aspose.pdf/figureelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Element](../../com.aspose.pdf/element)
```
public class FigureElement extends Element
```

Класс, представляющий фигуру логической структуры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FigureElement(ITrailerable tr, IPdfDictionary engineDict)](#FigureElement-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActualText()](#getActualText--) | (Необязательно; PDF�1.4) Текст, который является точной заменой элемента структуры и его дочерних элементов. |
| [getAlt()](#getAlt--) | (Необязательно) Альтернативное описание элемента структуры и его дочерних элементов в удобочитаемой форме, что полезно при извлечении документа.\содержание в поддержку доступности для пользователей с ограниченными возможностями или для других целей. |
| [getChildren()](#getChildren--) | Получает коллекцию дочерних элементов. |
| [getClass()](#getClass--) |  |
| [getE()](#getE--) | (Необязательно; PDF�1.5) Расширенная форма аббревиатуры. |
| [getImage()](#getImage--) | Получает значение элемента структуры фигуры. |
| [getLang()](#getLang--) | (Необязательно; PDF�1.4) Язык, указывающий естественный язык для всего текста в элементе структуры, за исключением случаев, когда он переопределен языковыми спецификациями для вложенных элементов структуры или выделенного содержимого. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | (Необязательно; PDF�1.4) Текст, который является точной заменой элемента структуры и его дочерних элементов. |
| [setAlt(String value)](#setAlt-java.lang.String-) | (Необязательно) Альтернативное описание элемента структуры и его дочерних элементов в удобочитаемой форме, что полезно при извлечении документа.\содержание в поддержку доступности для пользователей с ограниченными возможностями или для других целей. |
| [setE(String value)](#setE-java.lang.String-) | (Необязательно; PDF�1.5) Расширенная форма аббревиатуры. |
| [setLang(String value)](#setLang-java.lang.String-) | (Необязательно; PDF�1.4) Язык, указывающий естественный язык для всего текста в элементе структуры, за исключением случаев, когда он переопределен языковыми спецификациями для вложенных элементов структуры или выделенного содержимого. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FigureElement(ITrailerable tr, IPdfDictionary engineDict) {#FigureElement-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public FigureElement(ITrailerable tr, IPdfDictionary engineDict)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| tr | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |
| engineDict | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

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
### getActualText() {#getActualText--}
```
public String getActualText()
```


(Необязательно; PDF�1.4) Текст, который является точной заменой элемента структуры и его дочерних элементов. Этот замещающий текст (который должен применяться к как можно меньшему фрагменту содержимого) полезен при извлечении документа.\содержание в поддержку доступности для пользователей с ограниченными возможностями или для других целей.

**Возвращает:**
java.lang.String — строковый объект
### getAlt() {#getAlt--}
```
public String getAlt()
```


(Необязательно) Альтернативное описание элемента структуры и его дочерних элементов в удобочитаемой форме, что полезно при извлечении документа.\содержание в поддержку доступности для пользователей с ограниченными возможностями или для других целей.

**Возвращает:**
java.lang.String — строковый объект
### getChildren() {#getChildren--}
```
public List<Element> getChildren()
```


Получает коллекцию дочерних элементов.

**Возвращает:**
java.util.List<com.aspose.pdf.Element> — объект java.util.List
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getE() {#getE--}
```
public String getE()
```


(Необязательно; PDF�1.5) Расширенная форма аббревиатуры.

**Возвращает:**
java.lang.String — строковый объект
### getImage() {#getImage--}
```
public BufferedImage getImage()
```


Получает значение элемента структуры фигуры.

**Возвращает:**
java.awt.image.BufferedImage — объект изображения
### getLang() {#getLang--}
```
public String getLang()
```


(Необязательно; PDF�1.4) Язык, указывающий естественный язык для всего текста в элементе структуры, за исключением случаев, когда он переопределен языковыми спецификациями для вложенных элементов структуры или выделенного содержимого.

**Возвращает:**
java.lang.String — строковый объект
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




### setActualText(String value) {#setActualText-java.lang.String-}
```
public void setActualText(String value)
```


(Необязательно; PDF�1.4) Текст, который является точной заменой элемента структуры и его дочерних элементов. Этот замещающий текст (который должен применяться к как можно меньшему фрагменту содержимого) полезен при извлечении документа.\содержание в поддержку доступности для пользователей с ограниченными возможностями или для других целей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setAlt(String value) {#setAlt-java.lang.String-}
```
public void setAlt(String value)
```


(Необязательно) Альтернативное описание элемента структуры и его дочерних элементов в удобочитаемой форме, что полезно при извлечении документа.\содержание в поддержку доступности для пользователей с ограниченными возможностями или для других целей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setE(String value) {#setE-java.lang.String-}
```
public void setE(String value)
```


(Необязательно; PDF�1.5) Расширенная форма аббревиатуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setLang(String value) {#setLang-java.lang.String-}
```
public void setLang(String value)
```


(Необязательно; PDF�1.4) Язык, указывающий естественный язык для всего текста в элементе структуры, за исключением случаев, когда он переопределен языковыми спецификациями для вложенных элементов структуры или выделенного содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

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
