---
title: "Aspose::Pdf::LogicalStructure::ListLIElement::AddRef método"
linktitle: "AddRef"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::ListLIElement::AddRef método. Añade una referencia al StructureElement especificado dentro de este elemento Table of Contents Item (TOCI). Esto se usa típicamente cuando ListLIElement sirve como encabezado de TOC en tablas de contenido anidadas en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.logicalstructure/listlielement/addref/
---
## ListLIElement::AddRef method


Añade una referencia al [StructureElement](../../structureelement/) especificado dentro de este elemento [Table](../../../aspose.pdf/table/) of Contents Item (TOCI). Esto se usa típicamente cuando **[ListLIElement](../)** sirve como encabezado de TOC en tablas de contenido anidadas.

```cpp
void Aspose::Pdf::LogicalStructure::ListLIElement::AddRef(const System::SharedPtr<StructureElement> &referencedStructureElement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| referencedStructureElement | const System::SharedPtr\<StructureElement\>\& | El [StructureElement](../../structureelement/) que será referenciado por este elemento TOCI. |
## Observaciones



Asociar un elemento de estructura, como un encabezado u otra sección de contenido, con un elemento TOCI garantiza una estructura lógica correcta y mejora el comportamiento de navegación en PDFs etiquetados.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [ListLIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
