---
title: "System::Xml::XmlNodeReader::GetAttribute метод"
linktitle: "GetAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeReader::GetAttribute метод. Возвращает значение атрибута с указанным индексом в C++."
type: docs
weight: 2400
url: /ru/cpp/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(int32_t) method


Возвращает значение атрибута с указанным индексом.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeIndex | int32_t | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### ReturnValue

Значение указанного атрибута.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String) method


Возвращает значение атрибута с указанным именем.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String, String) method


Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
