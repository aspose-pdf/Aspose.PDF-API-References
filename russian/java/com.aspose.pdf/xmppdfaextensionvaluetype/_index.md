---
title: XmpPdfAExtensionValueType
second_title: Aspose.PDF для справки по Java API
description: Схема PDF/A ValueType требуется для всех типов значений свойств, которые не определены в спецификации XMP 2004, т. е. для типов значений, не входящих в следующий список. Типы массивов — это типы контейнеров, которые могут содержать одно или несколько полей Alt Bag Seq — Basic Типы значений Логическое открытое и закрытое Выбор Дата Размеры Целое Lang Alt Locale MIMEType Собственное имя Real Text Thumbnail URI URL XPath — типы значений Media Management AgentName RenditionClass ResourceEvent ResourceRef Version — тип значения Basic Job/Workflow Job — типы значений схемы EXIF Flash CFAPattern DeviceSettings GPSCoordinate OECF/ SFR Rational Schema URI пространства имен http//www.aiim.orgdfa/ns/type Требуемый префикс пространства имен схемы pdfaType
type: docs
weight: 425
url: /ru/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject)
```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

Схема PDF/A ValueType требуется для всех типов значений свойств, которые не определены в спецификации XMP 2004, т. е. для типов значений, не входящих в следующий список: - Типы массивов (это типы контейнеров, которые могут содержать одно или несколько полей): Alt, Bag, Seq — основные типы значений: логическое, (открытое и закрытое) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath — типы значений управления мультимедиа : AgentName, RenditionClass, ResourceEvent, ResourceRef, Version — тип значения Basic Job/Workflow: Job — типы значений схемы EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, URI пространства имен Rational Schema: http://www.aiim. org/pdfa/ns/тип\# Обязательный префикс пространства имен схемы: pdfaType
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description)](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый объект. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(XmpPdfAExtensionField field)](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Добавить новое поле. |
| [addRange(XmpPdfAExtensionField[] fields)](#addRange-com.aspose.pdf.XmpPdfAExtensionField---) | Добавляет диапазон полей. |
| [clear()](#clear--) | Очищает все поля. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание. |
| [getFields()](#getFields--) | Получает список полей. |
| [getNamespaceUri()](#getNamespaceUri--) | Получает URI пространства имен. |
| [getPrefix()](#getPrefix--) | Получает префикс. |
| [getType()](#getType--) | Получает тип значения. |
| [getValue()](#getValue--) | Получает значение. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Возвращает список элементов xml, представляющих тип значения в дереве xml. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Возвращает список элементов xml, представляющих поле в дереве xml. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XmpPdfAExtensionField field)](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Удаляет поле из списка полей. |
| [setValue(String value)](#setValue-java.lang.String-) | Устанавливает значение. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description) {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description)
```


Инициализирует новый объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | java.lang.String | Тип значения. |
| namespaceUri | java.lang.String | URI пространства имен. |
| prefix | java.lang.String | Префикс. |
| description | java.lang.String | Описание. |

### add(XmpPdfAExtensionField field) {#add-com.aspose.pdf.XmpPdfAExtensionField-}
```
public void add(XmpPdfAExtensionField field)
```


Добавить новое поле.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield) | Поле для добавления. |

### addRange(XmpPdfAExtensionField[] fields) {#addRange-com.aspose.pdf.XmpPdfAExtensionField---}
```
public void addRange(XmpPdfAExtensionField[] fields)
```


Добавляет диапазон полей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | [XmpPdfAExtensionField\[\]](../../com.aspose.pdf/xmppdfaextensionfield) | Поля для добавления. |

### clear() {#clear--}
```
public void clear()
```


Очищает все поля.

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
### getFields() {#getFields--}
```
public System.Collections.Generic.List<XmpPdfAExtensionField> getFields()
```


Получает список полей.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.XmpPdfAExtensionField> — IList
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Получает URI пространства имен.

**Возвращает:**
java.lang.String — Строка
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает префикс.

**Возвращает:**
java.lang.String — Строка
### getType() {#getType--}
```
public String getType()
```


Получает тип значения.

**Возвращает:**
java.lang.String — Строка
### getValue() {#getValue--}
```
public String getValue()
```


Получает значение.

**Возвращает:**
java.lang.String — Строка
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


Возвращает список элементов xml, представляющих тип значения в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> — список элементов xml.
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List getXml_(System.Xml.XmlDocument xmlDocument)
```


Возвращает список элементов xml, представляющих поле в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
java.util.List — Список полей.
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




### remove(XmpPdfAExtensionField field) {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
```
public void remove(XmpPdfAExtensionField field)
```


Удаляет поле из списка полей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield) | Поле для удаления. |

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
