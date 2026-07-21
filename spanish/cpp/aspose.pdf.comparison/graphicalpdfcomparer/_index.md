---
title: "Aspose::Pdf::Comparison::GraphicalPdfComparer clase"
linktitle: "GraphicalPdfComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::GraphicalPdfComparer clase. Representa una clase para comparar documentos PDF de forma gráfica. Debe usarse para buscar cambios pequeños, principalmente de naturaleza gráfica. Para comparar cambios en el contenido de texto, utilice otras clases de comparación de PDF en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class


Representa una clase para comparar gráficamente documentos PDF. Debe usarse para buscar cambios pequeños, principalmente de naturaleza gráfica. Para comparar cambios en el contenido de texto, utilice otras clases de comparación de PDF.

```cpp
class GraphicalPdfComparer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CompareDocumentsToImages](./comparedocumentstoimages/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Compara documentos gráficamente. El resultado de la comparación se coloca en imágenes. |
| [CompareDocumentsToPdf](./comparedocumentstopdf/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&) | Compara documentos gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [ComparePagesToImage](./comparepagestoimage/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Compara páginas gráficamente. El resultado de la comparación se coloca en una imagen. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [get_Color](./get_color/)() const | Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo. |
| [get_Resolution](./get_resolution/)() const | Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150 dpi. |
| [get_Threshold](./get_threshold/)() const | Obtiene y establece el valor umbral en porcentaje. Este valor le permite ignorar cambios pequeños si no son significativos para usted. El valor predeterminado es 0%. |
| [GetDifference](./getdifference/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&) | Obtiene diferencias entre imágenes de páginas. El resultado contiene una imagen de la primera página comparada y una matriz de diferencias. |
| [GraphicalPdfComparer](./graphicalpdfcomparer/)() | Crea una instancia de la clase [GraphicalPdfComparer](./). |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150 dpi. |
| [set_Threshold](./set_threshold/)(double) | Obtiene y establece el valor umbral en porcentaje. Este valor le permite ignorar cambios pequeños si no son significativos para usted. El valor predeterminado es 0%. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
