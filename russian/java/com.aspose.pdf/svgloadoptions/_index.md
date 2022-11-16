---
title: SvgLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры для загрузки/импорта файла SVG в документ PDF.
type: docs
weight: 343
url: /ru/java/com.aspose.pdf/svgloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class SvgLoadOptions extends LoadOptions
```

Представляет параметры для загрузки/импорта файла SVG в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgLoadOptions()](#SvgLoadOptions--) | Создает объект SvgLoadOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConversionEngine()](#getConversionEngine--) | Позволяет выбрать механизм преобразования, который будет использоваться во время преобразования. |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getPageInfo()](#getPageInfo--) | Получает информацию о странице, которая должна применяться во время загрузки документа. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isAdjustPageSize()](#isAdjustPageSize--) | Преобразовать размер страницы pdf в размер svg |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdjustPageSize(boolean value)](#setAdjustPageSize-boolean-) | Преобразовать размер страницы pdf в размер svg |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | Позволяет выбрать механизм преобразования, который будет использоваться во время преобразования. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Устанавливает информацию о странице, которая должна применяться во время загрузки документа. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgLoadOptions() {#SvgLoadOptions--}
```
public SvgLoadOptions()
```


Создает объект SvgLoadOptions.

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
### getConversionEngine() {#getConversionEngine--}
```
public int getConversionEngine()
```


Позволяет выбрать механизм преобразования, который будет использоваться во время преобразования. В настоящее время новый движок находится на стадии B-тестирования, поэтому по умолчанию установлено значение ConversionEngines.LegacyEngine.

**Возвращает:**
int — элемент ConversionEngines
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Представляет формат файла, который описывает LoadOptions.

**Возвращает:**
[LoadFormat](../../com.aspose.pdf/loadformat) - Элемент формата загрузки
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Получает информацию о странице, которая должна применяться во время загрузки документа. ПРИМЕЧАНИЕ: этот параметр работает только в том случае, если ConversionEngine == ConversionEngine.NewEngine.

**Возвращает:**
[PageInfo](../../com.aspose.pdf/pageinfo) - объект PageInfo
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isAdjustPageSize() {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```


Преобразовать размер страницы pdf в размер svg

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




### setAdjustPageSize(boolean value) {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```


Преобразовать размер страницы pdf в размер svg

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


Позволяет выбрать механизм преобразования, который будет использоваться во время преобразования. В настоящее время новый движок находится на стадии B-тестирования, поэтому по умолчанию установлено значение ConversionEngines.LegacyEngine.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| conversionEngine | int | Элемент ConversionEngines |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Устанавливает информацию о странице, которая должна применяться во время загрузки документа. ПРИМЕЧАНИЕ: этот параметр работает только в том случае, если ConversionEngine == ConversionEngine.NewEngine.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | Объект PageInfo |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | Значение IWarningCallback |

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
