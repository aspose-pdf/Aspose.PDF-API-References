---
title: "System::Xml::XmlTextReader::GetAttribute метод"
linktitle: "GetAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::GetAttribute метод. Возвращает значение атрибута с указанным индексом в C++."
type: docs
weight: 3300
url: /ru/cpp/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(int32_t) method


Возвращает значение атрибута с указанным индексом.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### ReturnValue

Значение указанного атрибута.

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::GetAttribute(String, String) method


Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**. Этот метод не перемещает позицию читателя.

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::GetAttribute(String) method


Возвращает значение атрибута с указанным именем.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
