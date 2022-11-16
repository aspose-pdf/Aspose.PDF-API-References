---
title: PrinterMargins
second_title: Aspose.PDF для справки по Java API
description: Задает размеры полей печатной страницы.
type: docs
weight: 19
url: /ru/java/com.aspose.pdf.printing/printermargins/
---
**Наследование:**
java.lang.Object
```
public class PrinterMargins
```

Задает размеры полей печатной страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrinterMargins()](#PrinterMargins--) | Инициализирует новый экземпляр класса Margins с полями шириной 1 дюйм. |
| [PrinterMargins(int left, int right, int top, int bottom)](#PrinterMargins-int-int-int-int-) | Инициализирует новый экземпляр класса Margins с указанными левым, правым, верхним и нижним полями. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Извлекает дубликат этого объекта, член за членом. |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнивает это поле с указанным объектом, чтобы определить, имеют ли они одинаковые размеры. |
| [getBottom()](#getBottom--) | Получает или задает нижнее поле в сотых долях дюйма. |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | Получает или задает ширину левого поля в сотых долях дюйма. |
| [getRight()](#getRight--) | Получает или задает ширину правого поля в сотых долях дюйма. |
| [getTop()](#getTop--) | Получает или задает ширину верхнего поля в сотых долях дюйма. |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PrinterMargins m1, PrinterMargins m2)](#op-Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Сравнивает два поля Margin, чтобы определить, имеют ли они одинаковые размеры. |
| [op_Inequality(PrinterMargins m1, PrinterMargins m2)](#op-Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Сравнивает два поля Margin, чтобы определить, имеют ли они разную ширину. |
| [setBottom(int value)](#setBottom-int-) | Получает или задает нижнее поле в сотых долях дюйма. |
| [setLeft(int value)](#setLeft-int-) | Получает или задает ширину левого поля в сотых долях дюйма. |
| [setRight(int value)](#setRight-int-) | Получает или задает ширину правого поля в сотых долях дюйма. |
| [setTop(int value)](#setTop-int-) | Получает или задает ширину верхнего поля в сотых долях дюйма. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrinterMargins() {#PrinterMargins--}
```
public PrinterMargins()
```


Инициализирует новый экземпляр класса Margins с полями шириной 1 дюйм.

### PrinterMargins(int left, int right, int top, int bottom) {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```


Инициализирует новый экземпляр класса Margins с указанными левым, правым, верхним и нижним полями.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | int | целое значение |
| right | int | целое значение |
| top | int | целое значение |
| bottom | int | целое значение |

### deepClone() {#deepClone--}
```
public PrinterMargins deepClone()
```


Извлекает дубликат этого объекта, член за членом.

**Возвращает:**
[PrinterMargins](../../com.aspose.pdf.printing/printermargins) - Объект PrinterMargins
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Сравнивает это поле с указанным объектом, чтобы определить, имеют ли они одинаковые размеры. (Переопределяет Object.Equals(Object).)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Возвращает:**
boolean - логическое значение
### getBottom() {#getBottom--}
```
public int getBottom()
```


Получает или задает нижнее поле в сотых долях дюйма.

**Возвращает:**
интервал - целочисленное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getLeft() {#getLeft--}
```
public int getLeft()
```


Получает или задает ширину левого поля в сотых долях дюйма.

**Возвращает:**
интервал - целочисленное значение
### getRight() {#getRight--}
```
public int getRight()
```


Получает или задает ширину правого поля в сотых долях дюйма.

**Возвращает:**
интервал - целочисленное значение
### getTop() {#getTop--}
```
public int getTop()
```


Получает или задает ширину верхнего поля в сотых долях дюйма.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает значение хэш-кода для объекта. Этот метод поддерживается для хеш-таблиц, таких как предоставляемые java.util.HashMap.

Общий контракт hashCode:

 *  Всякий раз, когда он вызывается для одного и того же объекта более одного раза во время выполнения приложения Java, метод hashCode должен постоянно возвращать одно и то же целое число, при условии, что никакая информация, используемая в сравнениях на равенство для объекта, не изменяется. Это целое число не обязательно должно оставаться постоянным от одного выполнения приложения к другому выполнению того же приложения.
 *  Если два объекта равны в соответствии с методом equals(Object), то вызов метода hashCode для каждого из двух объектов должен давать одинаковый целочисленный результат.
 *   это*not* требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что создание различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется для языка программирования JavaTM.)

**Возвращает:**
int - значение хеш-кода для этого объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PrinterMargins m1, PrinterMargins m2) {#op-Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public static boolean op_Equality(PrinterMargins m1, PrinterMargins m2)
```


Сравнивает два поля Margin, чтобы определить, имеют ли они одинаковые размеры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| m1 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | Объект PrinterMargins |
| m2 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | Объект PrinterMargins |

**Возвращает:**
boolean - логическое значение
### op_Inequality(PrinterMargins m1, PrinterMargins m2) {#op-Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public static boolean op_Inequality(PrinterMargins m1, PrinterMargins m2)
```


Сравнивает два поля Margin, чтобы определить, имеют ли они разную ширину.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| m1 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | Объект PrinterMargins |
| m2 | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | Объект PrinterMargins |

**Возвращает:**
boolean - логическое значение
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Получает или задает нижнее поле в сотых долях дюйма.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Получает или задает ширину левого поля в сотых долях дюйма.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Получает или задает ширину правого поля в сотых долях дюйма.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Получает или задает ширину верхнего поля в сотых долях дюйма.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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
