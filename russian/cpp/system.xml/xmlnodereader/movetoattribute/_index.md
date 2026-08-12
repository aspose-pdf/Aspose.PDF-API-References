---
title: "System::Xml::XmlNodeReader::MoveToAttribute метод"
linktitle: "MoveToAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeReader::MoveToAttribute метод. Переходит к атрибуту с указанным индексом в C++."
type: docs
weight: 2600
url: /ru/cpp/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(int32_t) method


Переходит к атрибуту с указанным индексом.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeIndex | int32_t | Индекс атрибута. |

## См. также

* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String) method


Переходит к атрибуту с указанным именем.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String, String) method


Переходит к атрибуту с указанным локальным именем и URI пространства имён.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
