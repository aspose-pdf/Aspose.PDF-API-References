---
title: XmpPdfAExtensionProperty
second_title: Aspose.PDF для справки по Java API
description: Описывает одно свойство.
type: docs
weight: 422
url: /ru/java/com.aspose.pdf/xmppdfaextensionproperty/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject), [com.aspose.pdf.XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield)
```
public final class XmpPdfAExtensionProperty extends XmpPdfAExtensionField
```

 Описывает одно свойство. URI пространства имен схемы:http://www.aiim.org/pdfa/ns/property\# Обязательный префикс пространства имен схемы: pdfaProperty
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPdfAExtensionProperty(String name, String value, String valueType, int category, String description)](#XmpPdfAExtensionProperty-java.lang.String-java.lang.String-java.lang.String-int-java.lang.String-) | Инициализирует новый объект. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategory()](#getCategory--) | Получает категорию свойства. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание. |
| [getName()](#getName--) | Имя поля. |
| [getValue()](#getValue--) | Получает значение. |
| [getValueType()](#getValueType--) | Тип значения поля, взятый из спецификации XMP 2004, или встроенная схема расширения типа значения PDF/A. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Возвращает список элементов xml, представляющих свойство в дереве xml. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Возвращает список элементов xml, представляющих свойство в дереве xml. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(String value)](#setValue-java.lang.String-) | Устанавливает значение. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionProperty(String name, String value, String valueType, int category, String description) {#XmpPdfAExtensionProperty-java.lang.String-java.lang.String-java.lang.String-int-java.lang.String-}
```
public XmpPdfAExtensionProperty(String name, String value, String valueType, int category, String description)
```


Инициализирует новый объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |
| value | java.lang.String | Стоимость свойства. |
| valueType | java.lang.String | Тип значения свойства. |
| category | int | Категория имущества. |
| description | java.lang.String | Описание свойства. |

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
### getCategory() {#getCategory--}
```
public int getCategory()
```


Получает категорию свойства.

**Возвращает:**
интервал - целочисленное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


Получает описание.

**Возвращает:**
java.lang.String — Строка
### getName() {#getName--}
```
public String getName()
```


Имя поля. Имена полей должны быть допустимыми именами элементов XML.

**Возвращает:**
java.lang.String — Строка
### getValue() {#getValue--}
```
public String getValue()
```


Получает значение.

**Возвращает:**
java.lang.String — Строка
### getValueType() {#getValueType--}
```
public String getValueType()
```


Тип значения поля, взятый из спецификации XMP 2004, или встроенная схема расширения типа значения PDF/A. Предопределенные имена типов XMP или имена пользовательских типов.

**Возвращает:**
java.lang.String — Строка
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


Возвращает список элементов xml, представляющих свойство в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> — список элементов xml.
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```


Возвращает список элементов xml, представляющих свойство в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
java.util.List<com.aspose.ms.System.Xml.XmlElement> — список элементов xml.
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




### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Устанавливает значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Нить | String |

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
