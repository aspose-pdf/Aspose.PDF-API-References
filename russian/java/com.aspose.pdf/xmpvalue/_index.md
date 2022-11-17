---
title: XmpValue
second_title: Aspose.PDF для справки по Java API
description: Представляет значение XMP
type: docs
weight: 426
url: /ru/java/com.aspose.pdf/xmpvalue/
---
**Наследование:**
java.lang.Object
```
public class XmpValue
```

Представляет значение XMP
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpValue(String value)](#XmpValue-java.lang.String-) | Конструктор для строкового значения. |
| [XmpValue(int value)](#XmpValue-int-) | Конструктор для целочисленного значения. |
| [XmpValue(double value)](#XmpValue-double-) | Конструктор для значения с плавающей запятой. |
| [XmpValue(Date value)](#XmpValue-java.util.Date-) | Конструктор для значения даты и времени. |
| [XmpValue(XmpValue[] array)](#XmpValue-com.aspose.pdf.XmpValue---) | Конструктор для значения массива. |
| [XmpValue(Object value)](#XmpValue-java.lang.Object-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isArray()](#isArray--) | Возвращает true, если XmpValue является массивом. |
| [isDateTime()](#isDateTime--) | Возвращает true, если значение равно DateTime. |
| [isDouble()](#isDouble--) | Возвращает true, если значение является значением с плавающей запятой. |
| [isField()](#isField--) | Возвращает true, если XmpValue является полем. |
| [isInteger()](#isInteger--) | Возвращает true, если значение является целым числом. |
| [isNamedValue()](#isNamedValue--) | Возвращает true, если XmpValue является именованным значением. |
| [isNamedValues()](#isNamedValues--) | Возвращает true, если XmpValue представляет именованные значения. |
| [isRaw()](#isRaw--) | Значение не поддерживается/неизвестно, предоставляется необработанный XML-код. |
| [isString()](#isString--) | Возвращает true, если значение является строкой. |
| [isStructure()](#isStructure--) | Возвращает true, если XmpValue представляет структуру. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArray()](#toArray--) | Возвращает массив. |
| [toDateTime()](#toDateTime--) | Преобразует в дату и время. |
| [toDictionary()](#toDictionary--) | Возвращает словарь, содержащий именованные значения. |
| [toDouble()](#toDouble--) | Превращается в двойную. |
| [toField()](#toField--) | Возвращает значение XMP в виде поля XMP. |
| [toInteger()](#toInteger--) | Преобразует в целое число. |
| [toNamedValue()](#toNamedValue--) | Возвращает значение XMP как именованное значение. |
| [toNamedValueInternal()](#toNamedValueInternal--) | Только для внутреннего использования |
| [toNamedValues()](#toNamedValues--) | Возвращает значение XMP в виде набора именованных значений. |
| [toNamedValuesInternal()](#toNamedValuesInternal--) |  |
| [toRaw()](#toRaw--) | Необработанный XML-код для неизвестных/неподдерживаемых значений. |
| [toString()](#toString--) | Возвращает строковое представление XmpValue. |
| [toString(System.IFormatProvider formatProvider)](#toString-com.aspose.ms.System.IFormatProvider-) | Возвращает строковое представление. |
| [toStringValue()](#toStringValue--) | Преобразуется в строку. |
| [toStructure()](#toStructure--) | Возвращает значение XMP в виде структуры (набора полей). |
| [to_(XmpValue value)](#to--com.aspose.pdf.XmpValue-) | Преобразует XmpValue в массив. |
| [to_Array(XmpValue value)](#to-Array-com.aspose.pdf.XmpValue-) | Преобразует XmpValue в массив. |
| [to_Generic(XmpValue value)](#to-Generic-com.aspose.pdf.XmpValue-) | Получить массив KeyValuePair |
| [to_KeyValuePair(XmpValue value)](#to-KeyValuePair-com.aspose.pdf.XmpValue-) | Преобразует XmpValue в именованное значение. |
| [to_String(XmpValue value)](#to-String-com.aspose.pdf.XmpValue-) | Преобразует XmpValue в строку. |
| [to_XmpValue(double value)](#to-XmpValue-double-) | Преобразует double в XmpValue. |
| [to_XmpValue(int value)](#to-XmpValue-int-) | Преобразует целое число в XmpValue. |
| [to_XmpValue(Object[] value)](#to-XmpValue-java.lang.Object---) | Преобразует массив в XmpValue. |
| [to_XmpValue(String value)](#to-XmpValue-java.lang.String-) | Преобразует строку в XmpValue. |
| [to_XmpValue(Date value)](#to-XmpValue-java.util.Date-) | Преобразует DateTime в XmpValue. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpValue(String value) {#XmpValue-java.lang.String-}
```
public XmpValue(String value)
```


Конструктор для строкового значения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение. |

### XmpValue(int value) {#XmpValue-int-}
```
public XmpValue(int value)
```


Конструктор для целочисленного значения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Целочисленное значение. |

### XmpValue(double value) {#XmpValue-double-}
```
public XmpValue(double value)
```


Конструктор для значения с плавающей запятой.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Двойное значение. |

### XmpValue(Date value) {#XmpValue-java.util.Date-}
```
public XmpValue(Date value)
```


Конструктор для значения даты и времени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Значение даты и времени. |

### XmpValue(XmpValue[] array) {#XmpValue-com.aspose.pdf.XmpValue---}
```
public XmpValue(XmpValue[] array)
```


Конструктор для значения массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [XmpValue\[\]](../../com.aspose.pdf/xmpvalue) | Значение массива. |

### XmpValue(Object value) {#XmpValue-java.lang.Object-}
```
public XmpValue(Object value)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isArray() {#isArray--}
```
public boolean isArray()
```


Возвращает true, если XmpValue является массивом.

**Возвращает:**
boolean - логическое значение
### isDateTime() {#isDateTime--}
```
public boolean isDateTime()
```


Возвращает true, если значение равно DateTime.

**Возвращает:**
boolean - логическое значение
### isDouble() {#isDouble--}
```
public boolean isDouble()
```


Возвращает true, если значение является значением с плавающей запятой.

**Возвращает:**
boolean - логическое значение
### isField() {#isField--}
```
public boolean isField()
```


Возвращает true, если XmpValue является полем.

**Возвращает:**
boolean - логическое значение
### isInteger() {#isInteger--}
```
public boolean isInteger()
```


Возвращает true, если значение является целым числом.

**Возвращает:**
boolean - логическое значение
### isNamedValue() {#isNamedValue--}
```
public boolean isNamedValue()
```


Возвращает true, если XmpValue является именованным значением.

**Возвращает:**
boolean - логическое значение
### isNamedValues() {#isNamedValues--}
```
public boolean isNamedValues()
```


Возвращает true, если XmpValue представляет именованные значения.

**Возвращает:**
boolean - логическое значение
### isRaw() {#isRaw--}
```
public final boolean isRaw()
```


Значение не поддерживается/неизвестно, предоставляется необработанный XML-код.

**Возвращает:**
boolean — Истинно, если значение возвращается как необработанные данные.
### isString() {#isString--}
```
public boolean isString()
```


Возвращает true, если значение является строкой.

**Возвращает:**
boolean - логическое значение
### isStructure() {#isStructure--}
```
public boolean isStructure()
```


Возвращает true, если XmpValue представляет структуру.

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




### toArray() {#toArray--}
```
public XmpValue[] toArray()
```


Возвращает массив.

**Возвращает:**
com.aspose.pdf.XmpValue[] - Массив XmpValue
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Преобразует в дату и время.

**Возвращает:**
[Date](../../java.util/date) - экземпляр даты
### toDictionary() {#toDictionary--}
```
public final System.Collections.Generic.Dictionary<String,XmpValue> toDictionary()
```


Возвращает словарь, содержащий именованные значения.

**Возвращает:**
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) - Словарь
### toDouble() {#toDouble--}
```
public double toDouble()
```


Превращается в двойную.

**Возвращает:**
двойное - двойное значение
### toField() {#toField--}
```
public XmpField toField()
```


Возвращает значение XMP в виде поля XMP.

**Возвращает:**
[XmpField](../../com.aspose.pdf/xmpfield) - Экземпляр XmpField
### toInteger() {#toInteger--}
```
public int toInteger()
```


Преобразует в целое число.

**Возвращает:**
интервал - целочисленное значение
### toNamedValue() {#toNamedValue--}
```
public HashMap<String,XmpValue> toNamedValue()
```


Возвращает значение XMP как именованное значение.

**Возвращает:**
java.util.HashMap<java.lang.String,com.aspose.pdf.XmpValue> — (Именованное значение) экземпляр HashMap со строковым ключом и значением XmpValue
### toNamedValueInternal() {#toNamedValueInternal--}
```
public System.Collections.Generic.KeyValuePair<String,XmpValue> toNamedValueInternal()
```


Только для внутреннего использования

**Возвращает:**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - Только для внутреннего использования
### toNamedValues() {#toNamedValues--}
```
public HashMap<String,XmpValue> toNamedValues()
```


Возвращает значение XMP в виде набора именованных значений.

**Возвращает:**
java.util.HashMap<java.lang.String,com.aspose.pdf.XmpValue> — (именованное значение коллекции) экземпляр HashMap со строковым ключом и значением XmpValue
### toNamedValuesInternal() {#toNamedValuesInternal--}
```
public System.Collections.Generic.KeyValuePair<String,XmpValue>[] toNamedValuesInternal()
```




**Возвращает:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[]
### toRaw() {#toRaw--}
```
public final System.Xml.XmlNode toRaw()
```


Необработанный XML-код для неизвестных/неподдерживаемых значений.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNode — узел XML для этого значения.
### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление XmpValue.

**Возвращает:**
java.lang.String — строковое представление
### toString(System.IFormatProvider formatProvider) {#toString-com.aspose.ms.System.IFormatProvider-}
```
public String toString(System.IFormatProvider formatProvider)
```


Возвращает строковое представление.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatProvider | com.aspose.ms.System.IFormatProvider | Экземпляр IFormatProvider (поставщик форматов) |

**Возвращает:**
java.lang.String — строковое представление
### toStringValue() {#toStringValue--}
```
public String toStringValue()
```


Преобразуется в строку.

**Возвращает:**
java.lang.String — строковое значение
### toStructure() {#toStructure--}
```
public XmpField[] toStructure()
```


Возвращает значение XMP в виде структуры (набора полей).

**Возвращает:**
com.aspose.pdf.XmpField[] — массив XmpField
### to_(XmpValue value) {#to--com.aspose.pdf.XmpValue-}
```
public static XmpValue[] to_(XmpValue value)
```


Преобразует XmpValue в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Экземпляр XmpValue (значение для преобразования) |

**Возвращает:**
com.aspose.pdf.XmpValue[] - Массив XmpValue
### to_Array(XmpValue value) {#to-Array-com.aspose.pdf.XmpValue-}
```
public static XmpValue[] to_Array(XmpValue value)
```


Преобразует XmpValue в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Экземпляр XmpValue (значение для преобразования) |

**Возвращает:**
com.aspose.pdf.XmpValue[] - Массив XmpValue
### to_Generic(XmpValue value) {#to-Generic-com.aspose.pdf.XmpValue-}
```
public static System.Collections.Generic.KeyValuePair<String,XmpValue>[] to_Generic(XmpValue value)
```


Получить массив KeyValuePair

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Экземпляр XmpValue (значение для преобразования) |

**Возвращает:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] - Внутренний массив
### to_KeyValuePair(XmpValue value) {#to-KeyValuePair-com.aspose.pdf.XmpValue-}
```
public static System.Collections.Generic.KeyValuePair<String,XmpValue> to_KeyValuePair(XmpValue value)
```


Преобразует XmpValue в именованное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Экземпляр XmpValue (значение для преобразования) |

**Возвращает:**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - Внутренний массив
### to_String(XmpValue value) {#to-String-com.aspose.pdf.XmpValue-}
```
public static String to_String(XmpValue value)
```


Преобразует XmpValue в строку.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Экземпляр XmpValue (значение для преобразования) |

**Возвращает:**
java.lang.String — строковое значение
### to_XmpValue(double value) {#to-XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```


Преобразует double в XmpValue.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение (значение для преобразования) |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Экземпляр XmpValue
### to_XmpValue(int value) {#to-XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```


Преобразует целое число в XmpValue.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | int value (значение для преобразования) |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Экземпляр XmpValue
### to_XmpValue(Object[] value) {#to-XmpValue-java.lang.Object---}
```
public static XmpValue to_XmpValue(Object[] value)
```


Преобразует массив в XmpValue.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object[] | Массив объектов (значение для преобразования) |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Экземпляр XmpValue
### to_XmpValue(String value) {#to-XmpValue-java.lang.String-}
```
public static XmpValue to_XmpValue(String value)
```


Преобразует строку в XmpValue.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение (значение для преобразования) |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Экземпляр XmpValue
### to_XmpValue(Date value) {#to-XmpValue-java.util.Date-}
```
public static XmpValue to_XmpValue(Date value)
```


Преобразует DateTime в XmpValue.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Экземпляр даты (значение для преобразования) |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Экземпляр XmpValue
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
