---
title: "System::Reflection::PropertyInfo::GetValue metod"
linktitle: "GetValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::PropertyInfo::GetValue metod. Hämtar egenskapsvärdet från ett specifikt objekt i C++."
type: docs
weight: 400
url: /sv/cpp/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) method


Hämtar egenskapsvärde från ett specifikt objekt.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | System::SharedPtr\<System::Object\> | [Object](../../../system/object/) att läsa egenskap från. |

### ReturnValue

Värde på angiven egenskap för angivet objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method


Hämtar egenskapsvärde från ett specifikt objekt.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | System::SharedPtr\<System::Object\> | [Object](../../../system/object/) att läsa egenskap från. |
| indexerare | System::ArrayPtr\<System::SharedPtr\<System::Object\>\> | Dessa är valfria indexvärden för indexerade egenskaper. För icke-indexerade egenskaper bör detta värde vara null. |

### ReturnValue

Värde på angiven egenskap för angivet objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
