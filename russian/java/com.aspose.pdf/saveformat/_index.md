---
title: SaveFormat
second_title: Aspose.PDF для справки по Java API
description: Определяет формат
type: docs
weight: 445
url: /ru/java/com.aspose.pdf/saveformat/
---
**Наследование:**
java.lang.Object, java.lang.Enum
```
public enum SaveFormat extends Enum<SaveFormat>
```

Определяет формат
## Поля

| Поле | Описание |
| --- | --- |
| [Aps](#Aps) | Сохранение в виде XML-файла APS. |
| [Doc](#Doc) | означает сохранение в формате DOC |
| [DocX](#DocX) | означает сохранение в формате DOCX |
| [Epub](#Epub) | означает сохранение в формате EPUB(специальный формат электронных книг) |
| [Excel](#Excel) | означает сохранение в формате MsExcel |
| [Html](#Html) | означает сохранение в формате HTML |
| [MobiXml](#MobiXml) | означает сохранение в формате MobiXML (специальный формат электронных книг) |
| [None](#None) | означает сохранение без изменения формата, т.е. в формате PDF. Он устарел и со временем будет удален, используйте вместо него «SaveFormat.Pdf» |
| [Pdf](#Pdf) | означает сохранение без изменения формата, т.е. как PDF используйте его, пожалуйста, вместо 'SaveFormat.None', который устарел |
| [PdfXml](#PdfXml) | Внутренняя структура документа PDF в формате XML |
| [Plugin](#Plugin) | означает сохранение с помощью плагина |
| [Pptx](#Pptx) | означает сохранение в MHT(WebArchieve) /// |
| [Svg](#Svg) | означает сохранение в формате SVG |
| [TeX](#TeX) | означает сохранение в формате TEX, т.е. в формате, подходящем для текстового редактора Latex. |
| [Xml](#Xml) | означает сохранение в формате XML |
| [Xps](#Xps) | означает сохранение в формате XPS |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Aps {#Aps}
```
public static final SaveFormat Aps
```


Сохранение в виде XML-файла APS.

### Doc {#Doc}
```
public static final SaveFormat Doc
```


означает сохранение в формате DOC

### DocX {#DocX}
```
public static final SaveFormat DocX
```


означает сохранение в формате DOCX

### Epub {#Epub}
```
public static final SaveFormat Epub
```


означает сохранение в формате EPUB(специальный формат электронных книг)

### Excel {#Excel}
```
public static final SaveFormat Excel
```


означает сохранение в формате MsExcel

### Html {#Html}
```
public static final SaveFormat Html
```


означает сохранение в формате HTML

### MobiXml {#MobiXml}
```
public static final SaveFormat MobiXml
```


означает сохранение в формате MobiXML (специальный формат электронных книг)

### None {#None}
```
public static final SaveFormat None
```


означает сохранение без изменения формата, т.е. в формате PDF. Он устарел и со временем будет удален, используйте вместо него «SaveFormat.Pdf»

### Pdf {#Pdf}
```
public static final SaveFormat Pdf
```


означает сохранение без изменения формата, т.е. как PDF используйте его, пожалуйста, вместо 'SaveFormat.None', который устарел

### PdfXml {#PdfXml}
```
public static final SaveFormat PdfXml
```


Внутренняя структура документа PDF в формате XML

### Plugin {#Plugin}
```
public static final SaveFormat Plugin
```


означает сохранение с помощью плагина

### Pptx {#Pptx}
```
public static final SaveFormat Pptx
```


означает сохранение в MHT(WebArchieve) ///

 Преобразовать документ в формат MHT. Этот код был экспериментальным и использовался во время работ, связанных сhttps://pdf.aspose.com/jira/browse/PDFNEWNET-36340не идет в производство, т.к. возникают кроссбраузерные проблемы с созданным MHT - так что его можно будет использовать в будущем, если, наконец, возникнет необходимость создать сам MHT. PDFNEWNET-36340 устранен с использованием URL-адресов DataSceme (встраивание данных в HTMLhttp://en.wikipedia.org/wiki/Data\_URI\_scheme) Так вот, это преобразование действительно сейчас не используется.

означает сохранение в формате PPTX

### Svg {#Svg}
```
public static final SaveFormat Svg
```


означает сохранение в формате SVG

### TeX {#TeX}
```
public static final SaveFormat TeX
```


означает сохранение в формате TEX, т.е. в формате, подходящем для текстового редактора Latex.

### Xml {#Xml}
```
public static final SaveFormat Xml
```


означает сохранение в формате XML

### Xps {#Xps}
```
public static final SaveFormat Xps
```


означает сохранение в формате XPS

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Возвращает:**
Т
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | E |  |

**Возвращает:**
инт
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Возвращает:**
java.lang.Класс<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Возвращает:**
инт
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Возвращает:**
инт
### name() {#name--}
```
public final String name()
```




**Возвращает:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Возвращает:**
инт
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SaveFormat valueOf(String name)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Возвращает:**
[SaveFormat](../../com.aspose.pdf/saveformat)
### values() {#values--}
```
public static SaveFormat[] values()
```




**Возвращает:**
com.aspose.pdf.SaveFormat[]
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
