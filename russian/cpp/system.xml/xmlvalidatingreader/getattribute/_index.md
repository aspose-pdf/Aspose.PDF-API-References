---
title: "System::Xml::XmlValidatingReader::GetAttribute метод"
linktitle: "GetAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::GetAttribute метод. Возвращает значение атрибута с указанным индексом в C++."
type: docs
weight: 3200
url: /ru/cpp/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(int32_t) method


Возвращает значение атрибута с указанным индексом.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс атрибута. Индекс начинается с нуля. (Первый атрибут имеет индекс 0.) |

### ReturnValue

Значение указанного атрибута.

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::GetAttribute(String, String) method


Возвращает значение атрибута с указанным локальным именем и унифицированным идентификатором ресурса (URI) пространства имён.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**. Этот метод не перемещает позицию читателя.

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::GetAttribute(String) method


Возвращает значение атрибута с указанным именем.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя атрибута. |

### ReturnValue

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
