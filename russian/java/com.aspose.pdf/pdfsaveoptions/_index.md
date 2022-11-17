---
title: PdfSaveOptions
second_title: Aspose.PDF для справки по Java API
description: Сохранить параметры для экспорта в формат Pdf
type: docs
weight: 280
url: /ru/java/com.aspose.pdf/pdfsaveoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Сохранить параметры для экспорта в формат Pdf
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. |
| [getSaveFormat()](#getSaveFormat--) | Формат сохранения данных. |
| [getTempPath()](#getTempPath--) | Путь для временных файлов. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. |
| [setTempPath(String value)](#setTempPath-java.lang.String-) | Путь для временных файлов. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. Когда документ PDF, сохраненный в формате PDF, содержит шрифты, недоступные в самом документе и на устройстве, API заменяет эти шрифты шрифтом по умолчанию (если на устройстве найден шрифт с DefaultFontName)

**Возвращает:**
java.lang.String — строковое значение
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Формат сохранения данных.

**Возвращает:**
[SaveFormat](../../com.aspose.pdf/saveformat) - Значение формата сохранения
### getTempPath() {#getTempPath--}
```
public final String getTempPath()
```


Путь для временных файлов.

**Возвращает:**
java.lang.String — строковое значение
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. «Продолжить» — это действие по умолчанию, и операция «Сохранить» продолжается, однако пользователь может также вернуть команду «Прервать», и в этом случае операция «Сохранить» должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


Получает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

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




### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. Когда документ PDF, сохраненный в формате PDF, содержит шрифты, недоступные в самом документе и на устройстве, API заменяет эти шрифты шрифтом по умолчанию (если на устройстве найден шрифт с DefaultFontName)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTempPath(String value) {#setTempPath-java.lang.String-}
```
public final void setTempPath(String value)
```


Путь для временных файлов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. «Продолжить» — это действие по умолчанию, и операция «Сохранить» продолжается, однако пользователь может также вернуть команду «Прервать», и в этом случае операция «Сохранить» должна быть прекращена.

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
