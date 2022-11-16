---
title: XmpPdfAExtensionField
second_title: Aspose.PDF для справки по Java API
description: Эта схема описывает поле структурированного типа.
type: docs
weight: 420
url: /ru/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject)
```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

Эта схема описывает поле структурированного типа. Она очень похожа на схему типа значения свойства PDF/A, но определяет поле в структуре вместо свойства. URI пространства имен схемы: http://www.aiim.org/pdfa/ns/field\# Обязательный префикс пространства имен схемы: pdfaField.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPdfAExtensionField(String name, String value, String valueType, String description)](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует объект. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание. |
| [getName()](#getName--) | Имя поля. |
| [getValue()](#getValue--) | Получает значение. |
| [getValueType()](#getValueType--) | Тип значения поля, взятый из спецификации XMP 2004, или встроенная схема расширения типа значения PDF/A. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Возвращает список элементов xml, представляющих поле в дереве xml. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Возвращает список элементов xml, представляющих поле в дереве xml. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(String value)](#setValue-java.lang.String-) | Устанавливает значение. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionField(String name, String value, String valueType, String description) {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public XmpPdfAExtensionField(String name, String value, String valueType, String description)
```


Инициализирует объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя поля. |
| value | java.lang.String | Значение поля. |
| valueType | java.lang.String | Тип значения поля. |
| description | java.lang.String | Описание поля. |

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


Возвращает список элементов xml, представляющих поле в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> — список полей.
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```


Возвращает список элементов xml, представляющих поле в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
java.util.List<com.aspose.ms.System.Xml.XmlElement> — список полей.
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
