---
title: "Aspose::Pdf::PageCollection::Insert método"
linktitle: "Insertar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageCollection::Insert método. Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En el caso de que solo haya dos páginas diferentes, se utilizará el tamaño de la primera página en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf/pagecollection/insert/
---
## PageCollection::Insert(int32_t) method


Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int32_t | Posición de la nueva página. |

### ReturnValue

Página insertada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Inserta páginas del arreglo en el documento.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int32_t | Número inicial de las nuevas páginas. |
| páginas | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Matriz de páginas que se insertarán. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::SharedPtr\<Page\>\&) method


Inserta la página en la colección de páginas en el lugar especificado.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::SharedPtr<Page> &entity)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int32_t | Índice de página requerido en la colección. |
| entity | const System::SharedPtr\<Page\>\& | [Page](../../page/) a insertar. |

### ReturnValue

Página insertada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Inserta páginas de la colección en el documento.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int32_t | Posición inicial de las nuevas páginas. |
| páginas | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | Colección de páginas. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
