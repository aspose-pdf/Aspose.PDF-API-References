---
title: TeXLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры для загрузки/импорта файла TeX в документ PDF.
type: docs
weight: 357
url: /ru/java/com.aspose.pdf/texloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public class TeXLoadOptions extends LoadOptions
```

Представляет параметры для загрузки/импорта файла TeX в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TeXLoadOptions()](#TeXLoadOptions--) | Создает параметры загрузки по умолчанию для преобразования файла TeX в документ PDF. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | Получает/устанавливает определенное значение для примитивов даты/времени, таких как\ \год,\ \месяц,\ \день и\\время. |
| [getInputDirectory()](#getInputDirectory--) | Получает/устанавливает входной каталог TeX. |
| [getJobName()](#getJobName--) | Получает/устанавливает имя задания. |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getNoLigatures()](#getNoLigatures--) | Получает/устанавливает флаг, который отменяет лигатуры во всех шрифтах. |
| [getOutputDirectory()](#getOutputDirectory--) | Получает/устанавливает выходной каталог TeX. |
| [getRasterizeFormulas()](#getRasterizeFormulas--) | Получает/устанавливает флаг, позволяющий растеризовать математические формулы. |
| [getRepeat()](#getRepeat--) | Получает/устанавливает флаг, указывающий, нужно ли запускать задание TeX дважды, если, например, во входных файлах TeX есть ссылки. |
| [getShowTerminalOutput()](#getShowTerminalOutput--) | Получает/устанавливает флаг, указывающий, следует ли отображать выходные данные терминала на консоли. |
| [getSubsetFonts()](#getSubsetFonts--) | Получает/устанавливает флаг, указывающий, следует ли подмножать шрифты в выходном файле или нет. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | Получает/устанавливает определенное значение для примитивов даты/времени, таких как\ \год,\ \месяц,\ \день и\\время. |
| [setInputDirectory(ITeXInputDirectory value)](#setInputDirectory-com.aspose.tex.ITeXInputDirectory-) | Получает/устанавливает входной каталог TeX. |
| [setJobName(String value)](#setJobName-java.lang.String-) | Получает/устанавливает имя задания. |
| [setNoLigatures(boolean value)](#setNoLigatures-boolean-) | Получает/устанавливает флаг, который отменяет лигатуры во всех шрифтах. |
| [setOutputDirectory(ITeXOutputDirectory value)](#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-) | Получает/устанавливает выходной каталог TeX. |
| [setRasterizeFormulas(boolean value)](#setRasterizeFormulas-boolean-) | Получает/устанавливает флаг, позволяющий растеризовать математические формулы. |
| [setRepeat(boolean value)](#setRepeat-boolean-) | Получает/устанавливает флаг, указывающий, нужно ли запускать задание TeX дважды, если, например, во входных файлах TeX есть ссылки. |
| [setShowTerminalOutput(boolean value)](#setShowTerminalOutput-boolean-) | Получает/устанавливает флаг, указывающий, следует ли отображать выходные данные терминала на консоли. |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | Получает/устанавливает флаг, указывающий, следует ли подмножать шрифты в выходном файле или нет. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TeXLoadOptions() {#TeXLoadOptions--}
```
public TeXLoadOptions()
```


Создает параметры загрузки по умолчанию для преобразования файла TeX в документ PDF.

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
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


Получает/устанавливает определенное значение для примитивов даты/времени, таких как\ \год,\ \месяц,\ \день и\\время.

**Возвращает:**
[Date](../../java.util/date) - экземпляр даты
### getInputDirectory() {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```


Получает/устанавливает входной каталог TeX.

**Возвращает:**
com.aspose.tex.ITeXInputDirectory — экземпляр ITeXInputDirectory
### getJobName() {#getJobName--}
```
public final String getJobName()
```


Получает/устанавливает имя задания.

**Возвращает:**
java.lang.String — строковое значение
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Представляет формат файла, который описывает LoadOptions.

**Возвращает:**
[LoadFormat](../../com.aspose.pdf/loadformat) - Элемент формата загрузки
### getNoLigatures() {#getNoLigatures--}
```
public final boolean getNoLigatures()
```


Получает/устанавливает флаг, который отменяет лигатуры во всех шрифтах.

**Возвращает:**
boolean - логическое значение
### getOutputDirectory() {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```


Получает/устанавливает выходной каталог TeX.

**Возвращает:**
com.aspose.tex.ITeXOutputDirectory — экземпляр ITeXOutputDirectory
### getRasterizeFormulas() {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```


Получает/устанавливает флаг, позволяющий растеризовать математические формулы.

**Возвращает:**
boolean - логическое значение
### getRepeat() {#getRepeat--}
```
public final boolean getRepeat()
```


Получает/устанавливает флаг, указывающий, нужно ли запускать задание TeX дважды, если, например, во входных файлах TeX есть ссылки. В общем, такое поведение полезно, когда движок собирает некоторые данные в процессе набора текста и сохраняет их во вспомогательном файле, и все это при первом запуске. И при втором запуске движок каким-то образом использует эти данные.

**Возвращает:**
boolean - логическое значение
### getShowTerminalOutput() {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```


Получает/устанавливает флаг, указывающий, следует ли отображать выходные данные терминала на консоли.

**Возвращает:**
boolean - логическое значение
### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


Получает/устанавливает флаг, указывающий, следует ли подмножать шрифты в выходном файле или нет.

**Возвращает:**
boolean - логическое значение
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


Получает/устанавливает определенное значение для примитивов даты/времени, таких как\ \год,\ \месяц,\ \день и\\время.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Экземпляр даты |

### setInputDirectory(ITeXInputDirectory value) {#setInputDirectory-com.aspose.tex.ITeXInputDirectory-}
```
public final void setInputDirectory(ITeXInputDirectory value)
```


Получает/устанавливает входной каталог TeX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.tex.ITeXInputDirectory | Экземпляр ITeXInputDirectory |

### setJobName(String value) {#setJobName-java.lang.String-}
```
public final void setJobName(String value)
```


Получает/устанавливает имя задания.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setNoLigatures(boolean value) {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```


Получает/устанавливает флаг, который отменяет лигатуры во всех шрифтах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOutputDirectory(ITeXOutputDirectory value) {#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-}
```
public final void setOutputDirectory(ITeXOutputDirectory value)
```


Получает/устанавливает выходной каталог TeX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.tex.ITeXOutputDirectory | Экземпляр ITeXOutputDirectory |

### setRasterizeFormulas(boolean value) {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```


Получает/устанавливает флаг, позволяющий растеризовать математические формулы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRepeat(boolean value) {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```


Получает/устанавливает флаг, указывающий, нужно ли запускать задание TeX дважды, если, например, во входных файлах TeX есть ссылки. В общем, такое поведение полезно, когда движок собирает некоторые данные в процессе набора текста и сохраняет их во вспомогательном файле, и все это при первом запуске. И при втором запуске движок каким-то образом использует эти данные.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setShowTerminalOutput(boolean value) {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```


Получает/устанавливает флаг, указывающий, следует ли отображать выходные данные терминала на консоли.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


Получает/устанавливает флаг, указывающий, следует ли подмножать шрифты в выходном файле или нет.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
