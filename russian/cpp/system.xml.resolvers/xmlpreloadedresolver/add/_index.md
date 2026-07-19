---
title: "Метод System::Xml::Resolvers::XmlPreloadedResolver::Add"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Resolvers::XmlPreloadedResolver::Add. Добавляет массив байтов в хранилище XmlPreloadedResolver и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method


Добавляет массив байтов в хранилище [XmlPreloadedResolver](../) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const ArrayPtr\<uint8_t\>\& | Массив байтов с данными, соответствующими указанному URI. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Добавляет массив байтов в хранилище [XmlPreloadedResolver](../) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const ArrayPtr\<uint8_t\>\& | Массив байтов с данными, соответствующими указанному URI. |
| смещение | int32_t | Смещение в предоставленном массиве байтов, где начинаются данные. |
| count | int32_t | Количество байтов для чтения из массива байтов, начиная с указанного смещения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method


Добавляет объект Stream в хранилище [XmlPreloadedResolver](../) и сопоставляет его с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const SharedPtr\<IO::Stream\>\& | Объект Stream с данными, соответствующими указанному URI. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method


Добавляет строку с предзагруженными данными в хранилище [XmlPreloadedResolver](../) и сопоставляет её с URI. Если хранилище уже содержит сопоставление для того же URI, существующее сопоставление переопределяется.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | URI данных, которые добавляются в хранилище [XmlPreloadedResolver](../). |
| value | const String\& | [String](../../../system/string/) с данными, соответствующими указанному URI. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
