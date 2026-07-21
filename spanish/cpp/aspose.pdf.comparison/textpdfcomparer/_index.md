---
title: "Aspose::Pdf::Comparison::TextPdfComparer clase"
linktitle: "TextPdfComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::TextPdfComparer clase. Representa una clase para comparar dos páginas PDF o documentos PDF en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.comparison/textpdfcomparer/
---
## TextPdfComparer class


Representa una clase para comparar dos páginas PDF o documentos PDF.

```cpp
class TextPdfComparer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [AssemblyDestinationPageText](./assemblydestinationpagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Restaura el texto modificado de la lista de cambios. |
| static [AssemblySourcePageText](./assemblysourcepagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Restaura el texto original de la lista de cambios. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Compara dos documentos página por página. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Compara dos documentos página por página. El resultado se guarda en un archivo PDF. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Compara dos documentos página por página. Los documentos se comparan como un todo. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Compara dos documentos página por página. El resultado se guarda en un archivo PDF. Los documentos se comparan como un todo. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto. |
| static [ComparePages](./comparepages/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Compara páginas de documentos. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Obtiene estadísticas de comparación. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Obtiene estadísticas de comparación de documentos. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
