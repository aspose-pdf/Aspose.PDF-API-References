---
title: DP
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий оператор DP, обозначает отмеченную точку содержимого.
type: docs
weight: 27
url: /ru/java/com.aspose.pdf.operators/dp/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class DP extends Operator
```

Класс, представляющий оператор DP (обозначается помеченной точкой содержимого).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DP(String tag)](#DP-java.lang.String-) | Инициализирует оператор. |
| [DP(int index, ICommand command)](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
| [DP(String tag, IPdfDictionary properties)](#DP-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Принимает объект посетителя для обработки оператором. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Получает команду |
| [getCommandName()](#getCommandName--) | Получает имя оператора. |
| [getIndex()](#getIndex--) | Получить индекс оператора в списке операторов страницы. |
| [getParameters()](#getParameters--) | Получает массив параметров оператора. |
| [getPropertiesDictionary()](#getPropertiesDictionary--) | Получает словарь свойств |
| [getPropertiesName()](#getPropertiesName--) | Получает имя свойства |
| [getTag()](#getTag--) | Получает отмеченный тег содержимого |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [setPropertiesDictionary(IPdfDictionary value)](#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-) | Задает словарь свойств |
| [setPropertiesName(IPdfName value)](#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-) | Задает имя свойства |
| [setTag(String value)](#setTag-java.lang.String-) | Устанавливает отмеченный тег содержимого |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | Возвращает текстовое представление оператора. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DP(String tag) {#DP-java.lang.String-}
```
public DP(String tag)
```


Инициализирует оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| tag | java.lang.String | Значение тега строки |

### DP(int index, ICommand command) {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public DP(int index, ICommand command)
```


Конструктор класса оператора. Инициализирует оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

### DP(String tag, IPdfDictionary properties) {#DP-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public DP(String tag, IPdfDictionary properties)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| tag | java.lang.String |  |
| properties | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Принимает объект посетителя для обработки оператором.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Объект посетителя. |

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
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCommand() {#getCommand--}
```
public ICommand getCommand()
```


Получает команду

**Возвращает:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) - Объект ICommand
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Получает имя оператора.

**Возвращает:**
java.lang.String — строковое значение
### getIndex() {#getIndex--}
```
public int getIndex()
```


Получить индекс оператора в списке операторов страницы.

**Возвращает:**
интервал - целочисленное значение
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Получает массив параметров оператора.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> — ArrayList значения CommandParameter
### getPropertiesDictionary() {#getPropertiesDictionary--}
```
public IPdfDictionary getPropertiesDictionary()
```


Получает словарь свойств

**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) Значение IPdfDictionary
### getPropertiesName() {#getPropertiesName--}
```
public IPdfName getPropertiesName()
```


Получает имя свойства

**Возвращает:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname) - значение IPdfName
### getTag() {#getTag--}
```
public String getTag()
```


Получает отмеченный тег содержимого

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isTextShowOperator(Operator op) {#isTextShowOperator-com.aspose.pdf.Operator-}
```
public static boolean isTextShowOperator(Operator op)
```


Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

**Возвращает:**
boolean - True, если это оператор вывода текста
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Только для внутреннего использования

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Установить индекс оператора в списке операторов страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPropertiesDictionary(IPdfDictionary value) {#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setPropertiesDictionary(IPdfDictionary value)
```


Задает словарь свойств

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | Значение IPdfDictionary |

### setPropertiesName(IPdfName value) {#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-}
```
public void setPropertiesName(IPdfName value)
```


Задает имя свойства

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) | Значение IPdfName |

### setTag(String value) {#setTag-java.lang.String-}
```
public void setTag(String value)
```


Устанавливает отмеченный тег содержимого

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Возвращает:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
### toString() {#toString--}
```
public String toString()
```


Возвращает текстовое представление оператора.

**Возвращает:**
java.lang.String — Текстовое представление оператора.
### toString(IPdfPrimitive primitive) {#toString-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static String toString(IPdfPrimitive primitive)
```


Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| primitive | [IPdfПримитивный](../../com.aspose.pdf.engine.data/ipdfprimitive) | Primitive |

**Возвращает:**
java.lang.String — Текстовое представление примитива
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
