---
title: "Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics método"
linktitle: "BuildStatistics"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics método. Crea un objeto de estadísticas para el resultado de comparar páginas PDF o comparación de documentos planos en la que se comparan documentos completos en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.comparison/comparisonstatisticsbuilder/buildstatistics/
---
## ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) method


Crea un objeto de estadísticas para el resultado de comparar páginas PDF o comparación de documentos planos en la que se comparan documentos completos.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &diffs)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| diferencias | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | La lista de diferencias. |

### ReturnValue

Una instancia de estadísticas.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) method


Crea un objeto de estadísticas para el resultado de una comparación de página de un documento PDF.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &diffs)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| diferencias | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\& | La lista de diferencias. |

### ReturnValue

Una instancia de estadísticas.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
