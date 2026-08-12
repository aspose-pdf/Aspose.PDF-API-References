---
title: "System::Xml::XmlValidatingReader::MoveToAttribute метод"
linktitle: "MoveToAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::MoveToAttribute метод. Переходит к атрибуту с указанным индексом в C++."
type: docs
weight: 3500
url: /ru/cpp/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(int32_t) method


Переходит к атрибуту с указанным индексом.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс атрибута. |

## См. также

* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String, String) method


Переходит к атрибуту с указанным локальным именем и унифицированным идентификатором ресурса (URI) пространства имён.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String) method


Переходит к атрибуту с указанным именем.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
