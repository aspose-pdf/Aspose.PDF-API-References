---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics método"
linktitle: "CreateComparisonStatistics"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics método. Obtiene estadísticas de comparación en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/
---
## TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) method


Obtiene estadísticas de comparación.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &diffs)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| diferencias | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | La lista de cambios. |

### ReturnValue

Las estadísticas.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) method


Obtiene estadísticas de comparación de documentos.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &diffs)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| diferencias | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\& | La lista de cambios. |

### ReturnValue

Las estadísticas.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
