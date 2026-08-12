---
title: "Aspose::Pdf::OperatorCollection::Insert método"
linktitle: "Insertar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::OperatorCollection::Insert método. Inserta operadores en la posición dada en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf/operatorcollection/insert/
---
## OperatorCollection::Insert(int32_t, const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Inserta operadores en la posición indicada.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| at | int32_t | Índice desde el cual se comienzan a insertar los operadores. |
| ops | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Arreglo de operadores a insertar. Cada operador puede tener cualquier índice (por defecto -1) porque sus índices se ajustan automáticamente comenzando desde *at*. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) method


Inserta operadores en la posición indicada.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> &ops)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| at | int32_t | Índice desde el cual se comienzan a insertar los operadores. |
| ops | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\& | Arreglo de operadores a insertar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, System::SharedPtr\<Operator\>) method


Inserta el operador en la colección.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t index, System::SharedPtr<Operator> op) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int32_t | Índice donde se debe agregar el nuevo operador |
| op | System::SharedPtr\<Operator\> | [Operator](../../operator/) que será insertado |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
