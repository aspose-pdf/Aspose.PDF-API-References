---
title: "Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering method"
linktitle: "AddBatesNumbering"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering method. Añade el artefacto de numeración Bates especificado a cada página en la colección de páginas proporcionada en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<BatesNArtifact\>\&) method


Agrega el artefacto de numeración Bates especificado a cada página de la colección de páginas dada.

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr<PageCollection> &pageCollection, const System::SharedPtr<BatesNArtifact> &artifact)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageCollection | const System::SharedPtr\<PageCollection\>\& | La colección de páginas a la que se añadirá el artefacto de numeración Bates. |
| artifact | const System::SharedPtr\<BatesNArtifact\>\& | La instancia [BatesNArtifact](../../batesnartifact/) que se añadirá a cada página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr\<PageCollection\>\&, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) method


Añade numeración Bates a cada página en la colección de páginas proporcionada usando la acción especificada para configurar el [BatesNArtifact](../../batesnartifact/).

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr<PageCollection> &pageCollection, System::Action<System::SharedPtr<BatesNArtifact>> action)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageCollection | const System::SharedPtr\<PageCollection\>\& | La colección de páginas a la que se añadirá la numeración Bates. |
| action | System::Action\<System::SharedPtr\<BatesNArtifact\>\> | Una acción para configurar el [BatesNArtifact](../../batesnartifact/) antes de añadirlo a cada página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Typedef [Action](../../../system/action/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
