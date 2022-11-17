---
title: PdfFormatConversionOptions.PdfANonSpecificationFlags
second_title: Aspose.PDF для справки по Java API
description: Этот класс содержит флаги для управления преобразованием PDF/A в случаях, когда исходный документ PDF не соответствует спецификации PDF.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Наследование:**
java.lang.Object
```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags
```

Этот класс содержит флаги для управления преобразованием PDF/A в случаях, когда исходный документ PDF не соответствует спецификации PDF. Использование флагов этого класса снижает производительность, но необходимо, когда исходный документ PDF не может быть конвертирован в формат PDF/A обычным способом. По умолчанию все флаги установлены в false.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfANonSpecificationFlags()](#PdfANonSpecificationFlags--) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckDifferentNamesInFontDictionaries()](#getCheckDifferentNamesInFontDictionaries--) | Некоторые документы PDF содержат шрифты, которые имеют разные имена во внутренних данных. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCheckDifferentNamesInFontDictionaries(boolean value)](#setCheckDifferentNamesInFontDictionaries-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfANonSpecificationFlags() {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```


Конструктор

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
### getCheckDifferentNamesInFontDictionaries() {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```


Некоторые документы PDF содержат шрифты, которые имеют разные имена во внутренних данных. Использование этого флага обеспечивает выполнение специальной логики обработки для случаев, когда поля BaseFont и FontDescriptor.FontName различаются.

**Возвращает:**
логический - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
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




### setCheckDifferentNamesInFontDictionaries(boolean value) {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

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
