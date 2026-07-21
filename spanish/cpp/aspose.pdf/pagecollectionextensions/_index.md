---
title: "Aspose::Pdf::PageCollectionExtensions clase"
linktitle: "PageCollectionExtensions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageCollectionExtensions clase. Representa el método de extensión para actualizar la paginación de encabezado y pie de página en C++."
type: docs
weight: 13300
url: /es/cpp/aspose.pdf/pagecollectionextensions/
---
## PageCollectionExtensions class


Representa el método de extensión para actualizar la paginación de encabezado y pie de página.

```cpp
class PageCollectionExtensions
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [AddBatesNumbering](./addbatesnumbering/)(const System::SharedPtr\<PageCollection\>\&, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) | Agrega numeración Bates a cada página de la colección de páginas dada usando la acción especificada para configurar el [BatesNArtifact](../batesnartifact/). |
| static [AddBatesNumbering](./addbatesnumbering/)(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<BatesNArtifact\>\&) | Agrega el artefacto de numeración Bates especificado a cada página de la colección de páginas dada. |
| static [AddPagination](./addpagination/)(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<PaginationArtifact\>\>\>\&) | Agrega los artefactos de paginación especificados a cada página de la colección de páginas dada. |
| static [DeleteBatesNumbering](./deletebatesnumbering/)(const System::SharedPtr\<PageCollection\>\&) | Elimina todos los artefactos de numeración Bates de cada página en la colección de páginas proporcionada. |
| [PageCollectionExtensions](./pagecollectionextensions/)() |  |
| static [UpdatePagination](./updatepagination/)(const System::SharedPtr\<PageCollection\>\&) | Actualiza los números de página y las fechas del encabezado y pie de página para todas las páginas. Esto funcionará si el documento tiene al menos un artefacto de paginación con datos de configuración especiales. Todas las páginas de la colección se actualizarán con el artefacto de origen según sus configuraciones. |
## Ver también

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
