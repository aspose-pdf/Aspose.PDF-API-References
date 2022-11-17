---
title: XmpPdfAExtensionSchema
second_title: Aspose.PDF для справки по Java API
description: Описывает схему расширения XMP, предоставляемую PDF/A-1.
type: docs
weight: 423
url: /ru/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Наследование:**
java.lang.Object
```
public class XmpPdfAExtensionSchema
```

Описывает схему расширения XMP, предоставляемую PDF/A-1.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description)](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Инициализирует новый объект. |
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT-EXTENSION-NAMESPACE-PREFIX) | Префикс пространства имен расширения по умолчанию. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT-EXTENSION-NAMESPACE-URI) | URI пространства имен расширений по умолчанию. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT-FIELD-NAMESPACE-PREFIX) | Префикс пространства имен полей по умолчанию. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT-FIELD-NAMESPACE-URI) | URI пространства имен расширений по умолчанию. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT-PROPERTY-NAMESPACE-PREFIX) | Префикс пространства имен свойств по умолчанию. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT-PROPERTY-NAMESPACE-URI) | URI пространства имен свойств по умолчанию. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT-SCHEMA-NAMESPACE-PREFIX) | Префикс пространства имен схемы по умолчанию. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT-SCHEMA-NAMESPACE-URI) | URI пространства имен схемы по умолчанию. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT-VALUE-NAMESPACE-URI) | URI пространства имен значений по умолчанию. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT-VALUE-TYPE-NAMESPACE-PREFIX) | Префикс пространства имен действительного типа по умолчанию. |
| [RDF_NAMESPACE_URI](#RDF-NAMESPACE-URI) | URI пространства имен rdf по умолчанию. |
| [RDF_PREFIX](#RDF-PREFIX) | Префикс пространства имен rdf по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(XmpPdfAExtensionObject obj)](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Добавляет новый объект в схему. |
| [contains(XmpPdfAExtensionObject obj)](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Определяет, существует ли объект в схеме. |
| [createDescriptionValueXml(System.Xml.XmlDocument xmlDocument)](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Создает элемент описания xml для блока значений свойств. |
| [createDescriptionXml(System.Xml.XmlDocument xmlDocument)](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Создает элемент описания xml для всех схем. |
| [createSchemasElement(System.Xml.XmlNode rootNode)](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Создает список элементов схемы из дерева xml. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание схемы. |
| [getObjects1()](#getObjects1--) | Получает список объектов (свойств, типов значений). |
| [getObjectsInternal()](#getObjectsInternal--) | Получает список объектов (свойств, типов значений). |
| [getProperty(String name)](#getProperty-java.lang.String-) | Возвращает свойство PDF/A по его имени. |
| [getPropertyIndex(String name)](#getPropertyIndex-java.lang.String-) | Возвращает индекс свойства с заданным именем. |
| [getSchemaXml(System.Xml.XmlDocument xmlDocument)](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Возвращает элемент xml (тег - li), представляющий схему в дереве xml. |
| [getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement)](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Получает значения свойств в виде дерева xml. |
| [hashCode()](#hashCode--) |  |
| [initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema)](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Инициализирует значение свойства. |
| [isPdfAExtensionPrefix(String localName)](#isPdfAExtensionPrefix-java.lang.String-) | Определяет, является ли значение префикса частью расширения pdf-a. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XmpPdfAExtensionObject obj)](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Удаляет объект из схемы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description) {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
```
public XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description)
```


Инициализирует новый объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| description | [XmpPdfAExtensionSchemaDescription](../../com.aspose.pdf/xmppdfaextensionschemadescription) | Описание схемы. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT-EXTENSION-NAMESPACE-PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```


Префикс пространства имен расширения по умолчанию.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT-EXTENSION-NAMESPACE-URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```


URI пространства имен расширений по умолчанию.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT-FIELD-NAMESPACE-PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```


Префикс пространства имен полей по умолчанию.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT-FIELD-NAMESPACE-URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```


URI пространства имен расширений по умолчанию.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT-PROPERTY-NAMESPACE-PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```


Префикс пространства имен свойств по умолчанию.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT-PROPERTY-NAMESPACE-URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```


URI пространства имен свойств по умолчанию.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT-SCHEMA-NAMESPACE-PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```


Префикс пространства имен схемы по умолчанию.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT-SCHEMA-NAMESPACE-URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```


URI пространства имен схемы по умолчанию.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT-VALUE-NAMESPACE-URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```


URI пространства имен значений по умолчанию.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT-VALUE-TYPE-NAMESPACE-PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```


Префикс пространства имен действительного типа по умолчанию.

### RDF_NAMESPACE_URI {#RDF-NAMESPACE-URI}
```
public static final String RDF_NAMESPACE_URI
```


URI пространства имен rdf по умолчанию.

### RDF_PREFIX {#RDF-PREFIX}
```
public static final String RDF_PREFIX
```


Префикс пространства имен rdf по умолчанию.

### add(XmpPdfAExtensionObject obj) {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void add(XmpPdfAExtensionObject obj)
```


Добавляет новый объект в схему.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | Новый объект. |

### contains(XmpPdfAExtensionObject obj) {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public boolean contains(XmpPdfAExtensionObject obj)
```


Определяет, существует ли объект в схеме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | Объект, который нужно найти. |

**Возвращает:**
boolean - True - объект существует в схеме; в противном случае ложно.
### createDescriptionValueXml(System.Xml.XmlDocument xmlDocument) {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public static System.Xml.XmlElement createDescriptionValueXml(System.Xml.XmlDocument xmlDocument)
```


Создает элемент описания xml для блока значений свойств.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
com.aspose.ms.System.Xml.XmlElement — XML-элемент описания.
### createDescriptionXml(System.Xml.XmlDocument xmlDocument) {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public static System.Xml.XmlElement createDescriptionXml(System.Xml.XmlDocument xmlDocument)
```


Создает элемент описания xml для всех схем.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
com.aspose.ms.System.Xml.XmlElement — XML-элемент описания.
### createSchemasElement(System.Xml.XmlNode rootNode) {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
```
public static HashDictionary<String,XmpPdfAExtensionSchema> createSchemasElement(System.Xml.XmlNode rootNode)
```


Создает список элементов схемы из дерева xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rootNode | com.aspose.ms.System.Xml.XmlNode | Корневой узел для элементов схемы. |

**Возвращает:**
[HashDictionary](../../com.aspose.pdf.engine.collections/hashdictionary) - Словарь элементов схемы в формате (ключ, значение): схема\_prefix, значение схемы.
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
public XmpPdfAExtensionSchemaDescription getDescription()
```


Получает описание схемы.

**Возвращает:**
[XmpPdfAExtensionSchemaDescription](../../com.aspose.pdf/xmppdfaextensionschemadescription) - XmpPdfAExtensionSchemaDescription
### getObjects1() {#getObjects1--}
```
public List getObjects1()
```


Получает список объектов (свойств, типов значений).

**Возвращает:**
java.util.List — список массивов
### getObjectsInternal() {#getObjectsInternal--}
```
public System.Collections.Generic.List<XmpPdfAExtensionObject> getObjectsInternal()
```


Получает список объектов (свойств, типов значений).

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.XmpPdfAExtensionObject> — ArrayList
### getProperty(String name) {#getProperty-java.lang.String-}
```
public final XmpPdfAExtensionProperty getProperty(String name)
```


Возвращает свойство PDF/A по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |

**Возвращает:**
[XmpPdfAExtensionProperty](../../com.aspose.pdf/xmppdfaextensionproperty) - Экземпляр XmpPdfAExtensionProperty Свойство.
### getPropertyIndex(String name) {#getPropertyIndex-java.lang.String-}
```
public final int getPropertyIndex(String name)
```


Возвращает индекс свойства с заданным именем.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |

**Возвращает:**
int - индекс свойства в списке объектов,
### getSchemaXml(System.Xml.XmlDocument xmlDocument) {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Xml.XmlElement getSchemaXml(System.Xml.XmlDocument xmlDocument)
```


Возвращает элемент xml (тег - li), представляющий схему в дереве xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |

**Возвращает:**
com.aspose.ms.System.Xml.XmlElement — элемент xml.
### getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement) {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
```
public void getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement)
```


Получает значения свойств в виде дерева xml.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | Исходный xml-документ. |
| rootElement | com.aspose.ms.System.Xml.XmlElement | Корневой узел списка значений свойств. |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema) {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
```
public static void initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema)
```


Инициализирует значение свойства.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | com.aspose.ms.System.Xml.XmlNode | Текущий узел, в котором хранится значение свойства. |
| schema | [XmpPdfAExtensionSchema](../../com.aspose.pdf/xmppdfaextensionschema) | Схема, содержащая определение свойства. |

### isPdfAExtensionPrefix(String localName) {#isPdfAExtensionPrefix-java.lang.String-}
```
public static boolean isPdfAExtensionPrefix(String localName)
```


Определяет, является ли значение префикса частью расширения pdf-a.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | java.lang.String | Значение префикса для проверки. |

**Возвращает:**
boolean - True - префикс является частью расширения pdf-a; в противном случае ложно.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XmpPdfAExtensionObject obj) {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void remove(XmpPdfAExtensionObject obj)
```


Удаляет объект из схемы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | Объект для удаления. |

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
