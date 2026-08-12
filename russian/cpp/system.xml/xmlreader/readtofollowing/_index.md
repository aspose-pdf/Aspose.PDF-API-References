---
title: "System::Xml::XmlReader::ReadToFollowing метод"
linktitle: "ReadToFollowing"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadToFollowing метод. Читает до тех пор, пока не будет найден элемент с указанным локальным именем и URI пространства имён в C++."
type: docs
weight: 7200
url: /ru/cpp/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String, String) method


Читает до тех пор, пока не будет найден элемент с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя элемента. |
| namespaceURI | String | URI пространства имен элемента. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToFollowing(String) method


Читает до тех пор, пока не будет найден элемент с указанным квалифицированным именем.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Квалифицированное имя элемента. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
