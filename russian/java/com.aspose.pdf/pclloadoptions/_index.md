---
title: PclLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры для загрузки файла импорта PCL в документ PDF.
type: docs
weight: 273
url: /ru/java/com.aspose.pdf/pclloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)

**Все реализованные интерфейсы:**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Представляет параметры для загрузки (импорта) файла PCL в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PclLoadOptions()](#PclLoadOptions--) | Создает объект PclLoadOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBatchSize()](#getBatchSize--) | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [getClass()](#getClass--) |  |
| [getConversionEngine()](#getConversionEngine--) | Определяет механизм преобразования, который будет использоваться для преобразования |
| [getExceptions()](#getExceptions--) | Список ошибок преобразования. |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isSupressErrors()](#isSupressErrors--) | Получает или задает логическое значение, указывающее, следует ли подавлять ошибки преобразования PCL. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBatchSize(int value)](#setBatchSize-int-) | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | Определяет механизм преобразования, который будет использоваться для преобразования |
| [setSupressErrors(boolean supressErrors)](#setSupressErrors-boolean-) | Получает или задает логическое значение, указывающее, следует ли подавлять ошибки преобразования PCL. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PclLoadOptions() {#PclLoadOptions--}
```
public PclLoadOptions()
```


Создает объект PclLoadOptions.

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
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов.

**Возвращает:**
интервал - целочисленное значение
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


Определяет механизм преобразования, который будет использоваться для преобразования

**Возвращает:**
int — элемент ConversionEngines
### getExceptions() {#getExceptions--}
```
public List<Exception> getExceptions()
```


Список ошибок преобразования.

**Возвращает:**
java.util.List<java.lang.Exception> — Список исключений
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Представляет формат файла, который описывает LoadOptions.

**Возвращает:**
[LoadFormat](../../com.aspose.pdf/loadformat) - Элемент формата загрузки
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
### isSupressErrors() {#isSupressErrors--}
```
public boolean isSupressErrors()
```


Получает или задает логическое значение, указывающее, следует ли подавлять ошибки преобразования PCL.

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




### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


Определяет механизм преобразования, который будет использоваться для преобразования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| conversionEngine | int | Элемент ConversionEngines |

### setSupressErrors(boolean supressErrors) {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```


Получает или задает логическое значение, указывающее, следует ли подавлять ошибки преобразования PCL.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| supressErrors | boolean | логическое значение |

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
