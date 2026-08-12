---
title: "Aspose::Pdf::OperatorCollection::Add método"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::OperatorCollection::Add método. Añade operadores al final de los operadores de contenido en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/operatorcollection/add/
---
## OperatorCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Añade operadores al final de los operadores de contenido.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ops | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Arreglo de operadores a añadir. Cada operador puede tener cualquier índice (por defecto -1) porque llegan al final de los operadores de contenido, es decir, los índices se asignan automáticamente. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<Operator\>\&) method


Agrega un nuevo operador a la colección.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<Operator> &op) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| op | const System::SharedPtr\<Operator\>\& | [Operator](../../operator/) que debe ser añadido |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) method


Añade a la colección todos los operadores de otra colección.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Operator>>> &ops)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ops | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\& | colección que contiene operadores que serán añadidos. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
