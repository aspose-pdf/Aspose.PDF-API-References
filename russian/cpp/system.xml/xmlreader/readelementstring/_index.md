---
title: "System::Xml::XmlReader::ReadElementString метод"
linktitle: "ReadElementString"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadElementString метод. Считывает элемент, содержащий только текст. Однако рекомендуется использовать метод XmlReader::ReadElementContentAsString, поскольку он предоставляет более простой способ выполнения этой операции в C++."
type: docs
weight: 6400
url: /ru/cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Считывает элемент, содержащий только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../readelementcontentasstring/), поскольку он предоставляет более простой способ выполнения этой операции.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### ReturnValue

Текст, содержащийся в считанном элементе. Пустая строка, если элемент пуст.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String, String) method


Проверяет, что значения [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) найденного элемента соответствуют заданным строкам перед считыванием элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../readelementcontentasstring/), поскольку он предоставляет более простой способ выполнения этой операции.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localname | String | Локальное имя для проверки. |
| ns | String | URI пространства имён для проверки. |

### ReturnValue

Текст, содержащийся в считанном элементе. Пустая строка, если элемент пуст.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String) method


Проверяет, что значение [XmlReader::get_Name](../get_name/) найденного элемента соответствует заданной строке перед считыванием элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../readelementcontentasstring/), поскольку он предоставляет более простой способ выполнения этой операции.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя для проверки. |

### ReturnValue

Текст, содержащийся в считанном элементе. Пустая строка, если элемент пуст.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
