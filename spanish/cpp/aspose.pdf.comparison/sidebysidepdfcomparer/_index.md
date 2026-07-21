---
title: "Aspose::Pdf::Comparison::SideBySidePdfComparer class"
linktitle: "SideBySidePdfComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar Aspose::Pdf::Comparison::SideBySidePdfComparer class en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.comparison/sidebysidepdfcomparer/
---
## SideBySidePdfComparer class




```cpp
class SideBySidePdfComparer
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Compare](./compare/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) | Compara dos páginas. El resultado se guarda en un documento PDF en el que la primera página se escribe primero, y luego la segunda. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha. |
| static [Compare](./compare/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) | Compara dos documentos. Las páginas se comparan una a una. Las páginas de los documentos comparados se copian una tras otra en el documento resultante. Primero la primera página del primer documento, luego la primera página del segundo documento. Después la segunda del primer documento y luego la segunda del segundo documento, etc. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha. |
| static [Compare](./compare/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) | Compara dos páginas. El resultado se guarda en un documento PDF en el que la primera página se escribe primero, y luego la segunda. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha. |
| static [Compare](./compare/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) | Compara dos documentos. Las páginas se comparan una a una. Las páginas de los documentos comparados se copian una tras otra en el documento resultante. Primero la primera página del primer documento, luego la primera página del segundo documento. Después la segunda del primer documento y luego la segunda del segundo documento, etc. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha. |
| [SideBySidePdfComparer](./sidebysidepdfcomparer/)() |  |
## Ver también

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
