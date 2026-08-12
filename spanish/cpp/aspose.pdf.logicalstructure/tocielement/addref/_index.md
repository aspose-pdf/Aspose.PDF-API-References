---
title: "Aspose::Pdf::LogicalStructure::TOCIElement::AddRef método"
linktitle: "AddRef"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::TOCIElement::AddRef método. Añade una referencia al elemento de estructura especificado dentro del elemento de tabla de contenidos (TOCI) en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.logicalstructure/tocielement/addref/
---
## TOCIElement::AddRef method


Añade una referencia al elemento de estructura especificado dentro del [Tabla](../../../aspose.pdf/table/) de Item de contenidos (TOCI) elemento.

```cpp
void Aspose::Pdf::LogicalStructure::TOCIElement::AddRef(const System::SharedPtr<StructureElement> &referencedStructureElement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| referencedStructureElement | const System::SharedPtr\<StructureElement\>\& | El [StructureElement](../../structureelement/) que será referenciado por este elemento TOCI. |
## Observaciones



Asociar un elemento de estructura, como un encabezado u otra sección de contenido, con un elemento TOCI garantiza una estructura lógica correcta y mejora el comportamiento de navegación en PDFs etiquetados.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [TOCIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
