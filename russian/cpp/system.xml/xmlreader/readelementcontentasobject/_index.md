---
title: "System::Xml::XmlReader::ReadElementContentAsObject метод"
linktitle: "ReadElementContentAsObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadElementContentAsObject метод. Читает текущий элемент и возвращает содержимое как Object в C++."
type: docs
weight: 6200
url: /ru/cpp/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method


Читает текущий элемент и возвращает содержимое как [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### ReturnValue

Упакованный объект наиболее подходящего типа. Значение [XmlReader::get_ValueType](../get_valuetype/) определяет подходящий тип. Если содержимое имеет тип списка, этот метод возвращает массив упакованных объектов соответствующего типа.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAsObject(String, String) method


Проверяет, что указанные локальное имя и URI пространства имен соответствуют текущему элементу, затем читает текущий элемент и возвращает содержимое как [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя элемента. |
| namespaceURI | String | URI пространства имен элемента. |

### ReturnValue

Упакованный объект наиболее подходящего типа. Значение [XmlReader::get_ValueType](../get_valuetype/) определяет подходящий тип. Если содержимое имеет тип списка, этот метод возвращает массив упакованных объектов соответствующего типа.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
