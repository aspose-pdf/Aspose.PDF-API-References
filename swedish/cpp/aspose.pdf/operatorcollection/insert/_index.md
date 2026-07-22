---
title: "Aspose::Pdf::OperatorCollection::Insert metod"
linktitle: "Infoga"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OperatorCollection::Insert metod. Infogar operatorer på den angivna positionen i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf/operatorcollection/insert/
---
## OperatorCollection::Insert(int32_t, const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Infoga operatorer på den angivna positionen.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| at | int32_t | Index från vilket operatorer startas att infogas. |
| ops | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Array av operatorer som ska infogas. Varje operator kan ha vilket index som helst (standardvärde -1) eftersom deras index justeras automatiskt med början från *at*. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) method


Infoga operatorer på den angivna positionen.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> &ops)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| at | int32_t | Index från vilket operatorer startas att infogas. |
| ops | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\& | Array av operatorer som ska infogas. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, System::SharedPtr\<Operator\>) method


Infogar operator i samlingen.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t index, System::SharedPtr<Operator> op) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Index där ny operator måste läggas till. |
| op | System::SharedPtr\<Operator\> | [Operator](../../operator/) som kommer att infogas |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
