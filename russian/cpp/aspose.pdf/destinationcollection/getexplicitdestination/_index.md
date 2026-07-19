---
title: "Aspose::Pdf::DestinationCollection::GetExplicitDestination метод"
linktitle: "GetExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DestinationCollection::GetExplicitDestination метод. Возвращает явный пункт назначения по имени в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf/destinationcollection/getexplicitdestination/
---
## DestinationCollection::GetExplicitDestination method


Возвращает явное назначение по имени.

```cpp
System::SharedPtr<Annotations::ExplicitDestination> Aspose::Pdf::DestinationCollection::GetExplicitDestination(const System::String &destinameName, bool useCache)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| destinameName | const System::String\& | Имя назначения. |
| useCache | bool | Определяет, используется ли кэшированная версия коллекции или нет. |

### ReturnValue

Объект ExplicitDestination для найденного назначения; в противном случае — null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ExplicitDestination](../../../aspose.pdf.annotations/explicitdestination/)
* Class [String](../../../system/string/)
* Class [DestinationCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
