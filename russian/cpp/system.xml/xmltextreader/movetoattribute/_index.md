---
title: "System::Xml::XmlTextReader::MoveToAttribute метод"
linktitle: "MoveToAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::MoveToAttribute метод. Переходит к атрибуту с указанным индексом в C++."
type: docs
weight: 3800
url: /ru/cpp/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(int32_t) method


Переходит к атрибуту с указанным индексом.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс атрибута. |

## См. также

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::MoveToAttribute(String, String) method


Переходит к атрибуту с указанным локальным именем и URI пространства имён.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::MoveToAttribute(String) method


Переходит к атрибуту с указанным именем.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
