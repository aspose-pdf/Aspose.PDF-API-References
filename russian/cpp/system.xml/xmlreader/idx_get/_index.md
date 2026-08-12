---
title: "System::Xml::XmlReader::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::idx_get метод. При переопределении в производном классе получает значение атрибута с указанным индексом в C++."
type: docs
weight: 2900
url: /ru/cpp/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) method


При переопределении в производном классе возвращает значение атрибута с указанным индексом.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс атрибута. |

### ReturnValue

Значение указанного атрибута.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::idx_get(String) method


При переопределении в производном классе получает значение атрибута с указанным значением [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::idx_get(String, String) method


При переопределении в производном классе получает значение атрибута с указанными значениями [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
