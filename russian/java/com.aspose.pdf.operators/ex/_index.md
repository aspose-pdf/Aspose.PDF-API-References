---
title: EX
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий оператор EX Конец раздела совместимости.
type: docs
weight: 35
url: /ru/java/com.aspose.pdf.operators/ex/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class EX extends Operator
```

Класс, представляющий оператор EX (конец раздела совместимости).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EX()](#EX--) | Инициализирует оператор. |
| [EX(int index, ICommand command)](#EX-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Принимает объект посетителя для обработки оператором. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Получает команду |
| [getCommandName()](#getCommandName--) | Получает имя оператора. |
| [getIndex()](#getIndex--) | Получить индекс оператора в списке операторов страницы. |
| [getParameters()](#getParameters--) | Получает массив параметров оператора. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [toString()](#toString--) | Преобразует команду и параметры в строковое представление. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EX() {#EX--}
```
public EX()
```


Инициализирует оператор.

### EX(int index, ICommand command) {#EX-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public EX(int index, ICommand command)
```


Конструктор класса оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

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

### toString() {#toString--}
```
public String toString()
```


Преобразует команду и параметры в строковое представление.

**Возвращает:**
java.lang.String — текст оператора
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
