---
title: "Aspose::Pdf::PageCollection::Add método"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageCollection::Add método. Añade una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se utilizará el tamaño de la primera página en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/pagecollection/add/
---
## PageCollection::Add() method


Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Add()
```


### ReturnValue

Página añadida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Agrega a la colección todas las páginas del arreglo.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| páginas | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Matriz de páginas que se añadirán. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Agrega a la colección todas las páginas de la lista.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| páginas | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | Lista que contiene todas las páginas que deben añadirse. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
