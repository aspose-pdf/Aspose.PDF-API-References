---
title: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult class"
linktitle: "SideBySideDocsComparisonResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult class. Representa la clase del resultado de una operación de comparación lado a lado realizada en dos documentos en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult class


Representa la clase del resultado de una operación de comparación lado a lado realizada en dos documentos.

```cpp
class SideBySideDocsComparisonResult : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FirstDocChanges](./get_firstdocchanges/)() const | Obtenga una lista de cambios en las páginas del primer documento. |
| [get_FullChanges](./get_fullchanges/)() const | Obtenga una lista completa de cambios en las páginas del documento. Cada índice de la lista representa las dos páginas del documento que se están comparando, y la lista de operaciones de cambio representa la lista de cambios en esas páginas. |
| [get_HasChanges](./get_haschanges/)() const | Obtiene el valor que indica si hay cambios entre los documentos comparados. |
| [get_SecondDocChanges](./get_seconddocchanges/)() const | Obtenga una lista de cambios en las páginas del segundo documento. |
| [SideBySideDocsComparisonResult](./sidebysidedocscomparisonresult/)(bool, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Crea una instancia de la clase [SideBySideDocsComparisonResult](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
