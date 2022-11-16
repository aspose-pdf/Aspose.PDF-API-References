---
title: AnnotationFlags
second_title: Aspose.PDF для справки по Java API
description: Набор флагов, определяющих различные характеристики аннотации.
type: docs
weight: 18
url: /ru/java/com.aspose.pdf/annotationflags/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnnotationFlags extends System.Enum
```

Набор флагов, определяющих различные характеристики аннотации.
## Поля

| Поле | Описание |
| --- | --- |
| [Default](#Default) | Значение по умолчанию. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [Hidden](#Hidden) | Если установлено, не отображайте и не печатайте аннотацию или не позволяйте ей взаимодействовать с пользователем, независимо от типа аннотации или доступности обработчика аннотаций. |
| [Invisible](#Invisible) | Если установлено, не отображать аннотацию, если она не принадлежит ни к одному из стандартных типов аннотаций и обработчик аннотаций недоступен. |
| [Locked](#Locked) | Если установлено, пользователь не может удалить аннотацию или изменить ее свойства (включая положение и размер). |
| [LockedContents](#LockedContents) | Если установлено, не позволяйте пользователю изменять содержимое аннотации. |
| [NoRotate](#NoRotate) | Если установлено, не поворачивайте внешний вид аннотации в соответствии с поворотом страницы. |
| [NoView](#NoView) | Если установлено, не отображайте аннотацию на экране и не позволяйте ей взаимодействовать с пользователем. |
| [NoZoom](#NoZoom) | Если установлено, не масштабируйте внешний вид аннотации в соответствии с увеличением страницы. |
| [Print](#Print) | Если установлено, печатать аннотацию при печати страницы. |
| [ReadOnly](#ReadOnly) | Если установлено, не позволяйте аннотации взаимодействовать с пользователем. |
| [ToggleNoView](#ToggleNoView) | Если установлено, инвертировать интерпретацию флага NoView для определенных событий. |
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
### Default {#Default}
```
public static final int Default
```


Значение по умолчанию.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### Hidden {#Hidden}
```
public static final int Hidden
```


Если установлено, не отображайте и не печатайте аннотацию или не позволяйте ей взаимодействовать с пользователем, независимо от типа аннотации или доступности обработчика аннотаций. В случаях, когда пространство на экране ограничено, возможность выборочного скрытия и отображения аннотаций может использоваться в сочетании с потоками внешнего вида для отображения вспомогательной всплывающей информации, аналогичной по функциям интерактивным справочным системам.

### Invisible {#Invisible}
```
public static final int Invisible
```


Если установлено, не отображать аннотацию, если она не принадлежит ни к одному из стандартных типов аннотаций и обработчик аннотаций недоступен. Если флажок установлен, отображать такую неизвестную аннотацию с использованием потока внешнего вида, заданного его словарем внешнего вида, если таковой имеется.

### Locked {#Locked}
```
public static final int Locked
```


Если установлено, пользователь не может удалить аннотацию или изменить ее свойства (включая положение и размер). Однако этот флаг не ограничивает изменения содержимого аннотации, например значения поля формы.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```


Если установлено, не позволяйте пользователю изменять содержимое аннотации. Этот флаг не ограничивает удаление аннотации или изменение других свойств аннотации, таких как положение и размер.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```


Если установлено, не поворачивайте внешний вид аннотации в соответствии с поворотом страницы. Верхний левый угол прямоугольника аннотации остается в фиксированном месте на странице независимо от поворота страницы.

### NoView {#NoView}
```
public static final int NoView
```


Если установлено, не отображайте аннотацию на экране и не позволяйте ей взаимодействовать с пользователем. Аннотация может быть распечатана (в зависимости от установки флажка «Печать»), но ее следует считать скрытой для целей отображения на экране и взаимодействия с пользователем.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```


Если установлено, не масштабируйте внешний вид аннотации в соответствии с увеличением страницы. Положение аннотации на странице (определяемое левым верхним углом прямоугольника аннотации) остается фиксированным, независимо от увеличения страницы.

### Print {#Print}
```
public static final int Print
```


Если установлено, печатать аннотацию при печати страницы. Если флажок снят, никогда не печатайте аннотацию, независимо от того, отображается ли она на экране. Это может быть полезно, например, для аннотаций, представляющих интерактивные кнопки, которые не будут иметь смысла на печатной странице.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Если установлено, не позволяйте аннотации взаимодействовать с пользователем. Аннотация может отображаться или печататься (в зависимости от настроек флажков NoView и Print), но не должна реагировать на щелчки мыши или изменять свой внешний вид в ответ на движения мыши. Этот флаг игнорируется для аннотаций виджета; его функция определяется флагом ReadOnly соответствующего поля формы.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```


Если установлено, инвертировать интерпретацию флага NoView для определенных событий. Типичное использование — иметь аннотацию, которая появляется только при наведении на нее курсора мыши.

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
