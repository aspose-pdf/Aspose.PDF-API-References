---
title: "Aspose::Pdf::OperatorCollection::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OperatorCollection::Add metod. Lägger till operatorer i slutet av innehållsoperatorerna i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/operatorcollection/add/
---
## OperatorCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Lägg till operatorer i slutet av innehållsoperatorerna.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Array av operatorer som ska läggas till. Varje operator kan ha vilket index som helst (standardvärde -1) eftersom de placeras i slutet av innehållsoperatorerna, d.v.s. index tilldelas automatiskt. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<Operator\>\&) method


Lägger till en ny operator i samlingen.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<Operator> &op) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| op | const System::SharedPtr\<Operator\>\& | [Operator](../../operator/) som måste läggas till |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) method


Lägger till alla operatorer från en annan samling i samlingen.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Operator>>> &ops)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\& | samling som innehåller operatorer som kommer att läggas till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
