---
title: "Метод Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination"
linktitle: "CreateDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination. Создаёт экземпляры классов-наследников ExplicitDestination в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.annotations/explicitdestination/createdestination/
---
## ExplicitDestination::CreateDestination(const System::SharedPtr\<Aspose::Pdf::Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Создаёт экземпляры классов-наследников [ExplicitDestination](../).

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(const System::SharedPtr<Aspose::Pdf::Page> &page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Объект целевой страницы. |
| тип | ExplicitDestinationType | Тип явного назначения. |
| значения | const System::ArrayPtr\<double\>\& | Массив значений double. |

### ReturnValue

Объект явного назначения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## ExplicitDestination::CreateDestination(const System::SharedPtr\<Document\>\&, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Создаёт экземпляры классов-наследников [ExplicitDestination](../).

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(const System::SharedPtr<Document> &doc, int32_t pageNumber, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) где будет создано назначение. |
| pageNumber | int32_t | Номер страницы. |
| тип | ExplicitDestinationType | Тип назначения. |
| значения | const System::ArrayPtr\<double\>\& | Массив специфических значений назначения. |

### ReturnValue

Объект явного назначения.

## Deprecated
Используйте метод без аргумента Document.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Class [Document](../../../aspose.pdf/document/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## ExplicitDestination::CreateDestination(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) method


Создаёт экземпляры классов-наследников [ExplicitDestination](../).

```cpp
static System::SharedPtr<ExplicitDestination> Aspose::Pdf::Annotations::ExplicitDestination::CreateDestination(int32_t pageNumber, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int32_t | Номер страницы назначения. |
| тип | ExplicitDestinationType | Тип явного назначения. |
| значения | const System::ArrayPtr\<double\>\& | Массив значений double. |

### ReturnValue

Объект явного назначения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
