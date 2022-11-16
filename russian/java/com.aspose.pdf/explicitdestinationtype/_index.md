---
title: ExplicitDestinationType
second_title: Aspose.PDF для справки по Java API
description: Перечисляет типы явных назначений.
type: docs
weight: 103
url: /ru/java/com.aspose.pdf/explicitdestinationtype/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExplicitDestinationType extends System.Enum
```

Перечисляет типы явных назначений.
## Поля

| Поле | Описание |
| --- | --- |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [Fit](#Fit) | Отобразите страницу с ее содержимым, увеличенным настолько, чтобы вся страница поместилась в окне как по горизонтали, так и по вертикали. |
| [FitB](#FitB) | Отобразите страницу с ее содержимым, увеличенным настолько, чтобы его ограничивающая рамка полностью помещалась в окне как по горизонтали, так и по вертикали. |
| [FitBH](#FitBH) | Отобразите страницу с вертикальным координатным верхом, расположенным на верхнем краю окна, и содержимым страницы, увеличенным настолько, чтобы соответствовать всей ширине ограничивающего прямоугольника в окне. |
| [FitBV](#FitBV) | Отобразите страницу с горизонтальной координатой слева, расположенной на левом краю окна, и содержимое страницы, увеличенное настолько, чтобы соответствовать всей высоте ее ограничивающей рамки в окне. |
| [FitH](#FitH) | Отобразите страницу с вертикальной координатой top, расположенной на верхнем краю окна, и содержимым страницы, увеличенным настолько, чтобы заполнить всю ширину страницы в окне. |
| [FitR](#FitR) | Отобразите страницу с ее содержимым, увеличенным настолько, чтобы соответствовать прямоугольнику, заданному координатами слева, внизу, справа и вверху внутри окна как по горизонтали, так и по вертикали. |
| [FitV](#FitV) | Отобразите страницу с горизонтальной координатой слева, расположенной на левом краю окна, и содержимым страницы, увеличенным настолько, чтобы заполнить всю высоту страницы в окне. |
| [XYZ](#XYZ) | Отобразите страницу с координатами (слева, сверху), расположенными в верхнем левом углу окна, и содержимым страницы, увеличенным с помощью коэффициента масштабирования. |
## Методы

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### Fit {#Fit}
```
public static final int Fit
```


Отобразите страницу с ее содержимым, увеличенным настолько, чтобы вся страница поместилась в окне как по горизонтали, так и по вертикали. Если требуемые коэффициенты увеличения по горизонтали и вертикали различаются, используйте меньший из двух, центрируя страницу в окне в другом измерении.

### FitB {#FitB}
```
public static final int FitB
```


Отобразите страницу с ее содержимым, увеличенным настолько, чтобы его ограничивающая рамка полностью помещалась в окне как по горизонтали, так и по вертикали. Если требуемые коэффициенты увеличения по горизонтали и вертикали различаются, используйте меньший из двух, центрируя ограничивающую рамку внутри окна в другом измерении.

### FitBH {#FitBH}
```
public static final int FitBH
```


Отобразите страницу с вертикальным координатным верхом, расположенным на верхнем краю окна, и содержимым страницы, увеличенным настолько, чтобы соответствовать всей ширине ограничивающего прямоугольника в окне. Нулевое значение для top указывает, что текущее значение этого параметра должно быть сохранено без изменений.

### FitBV {#FitBV}
```
public static final int FitBV
```


Отобразите страницу с горизонтальной координатой слева, расположенной на левом краю окна, и содержимое страницы, увеличенное настолько, чтобы соответствовать всей высоте ее ограничивающей рамки в окне. Нулевое значение для левого указывает, что текущее значение этого параметра должно быть сохранено без изменений.

### FitH {#FitH}
```
public static final int FitH
```


Отобразите страницу с вертикальной координатой top, расположенной на верхнем краю окна, и содержимым страницы, увеличенным настолько, чтобы заполнить всю ширину страницы в окне. Нулевое значение для top указывает, что текущее значение этого параметра должно быть сохранено без изменений.

### FitR {#FitR}
```
public static final int FitR
```


Отобразите страницу с ее содержимым, увеличенным настолько, чтобы соответствовать прямоугольнику, заданному координатами слева, внизу, справа и вверху внутри окна как по горизонтали, так и по вертикали. Если требуемые коэффициенты увеличения по горизонтали и вертикали различаются, используйте меньший из двух, центрируя прямоугольник внутри окна в другом измерении. Нулевое значение любого из параметров может привести к непредсказуемому поведению.

### FitV {#FitV}
```
public static final int FitV
```


Отобразите страницу с горизонтальной координатой слева, расположенной на левом краю окна, и содержимым страницы, увеличенным настолько, чтобы заполнить всю высоту страницы в окне. Нулевое значение для левого указывает, что текущее значение этого параметра должно быть сохранено без изменений.

### XYZ {#XYZ}
```
public static final int XYZ
```


Отобразите страницу с координатами (слева, сверху), расположенными в верхнем левом углу окна, и содержимым страницы, увеличенным с помощью коэффициента масштабирования. Нулевое значение для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно быть сохранено без изменений. Значение масштабирования 0 имеет то же значение, что и нулевое значение.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Возвращает:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Возвращает:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Возвращает:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Возвращает:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Возвращает:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Возвращает:**
[Collection](../../java.util/collection)
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Возвращает:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Возвращает:**
java.lang.Класс<? расширяет java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Возвращает:**
длинная
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Возвращает:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Возвращает:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Возвращает:**
длинная
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Возвращает:**
логический
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Возвращает:**
логический
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Возвращает:**
логический
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Возвращает:**
логический
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Возвращает:**
длинная
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Возвращает:**
длинная
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Возвращает:**
длинная
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Возвращает:**
длинная
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Возвращает:**
java.lang.Объект
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
