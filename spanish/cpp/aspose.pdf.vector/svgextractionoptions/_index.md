---
title: "Aspose::Pdf::Vector::SvgExtractionOptions clase"
linktitle: "SvgExtractionOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Vector::SvgExtractionOptions clase. Representa una clase de opciones para extraer gráficos vectoriales de la página del documento pdf en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class


Representa una clase de opciones para extraer gráficos vectoriales de la página del documento PDF.

```cpp
class SvgExtractionOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AutoGrouping](./get_autogrouping/)() const | Obtiene y establece la opción para agrupar automáticamente los subpaths en imágenes. Esta opción excluye la opción [GroupStrength](../). |
| [get_ExtractEverySubPathToSvg](./get_extracteverysubpathtosvg/)() const | Obtiene y establece la opción para extraer cada subpath de un documento PDF a imágenes SVG separadas. |
| [get_ExtractionAreaBound](./get_extractionareabound/)() const | Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción SVG. |
| [get_GroupStrength](./get_groupstrength/)() const | Obtiene y establece una opción La fuerza de agrupar subpaths en imágenes. Permite configurar el grado de agrupación de subpaths. El rango de valores es de 0 a 1. Un valor de 0 corresponde a que la opción [ExtractEverySubPathToSvg](../) esté habilitada. Un valor de 1 creará una única imagen para todas las rutas vectoriales en la página. La opción tiene efecto cuando [AutoGrouping](../) es false. El valor predeterminado es **0.8**. |
| [get_MinStrokeWidth](./get_minstrokewidth/)() const | Obtiene el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF usa un ancho de trazo más delgado, será reemplazado por este ancho. El valor predeterminado es 0.5. |
| [get_StrictExtractionAreaBoundCheck](./get_strictextractionareaboundcheck/)() const | Obtiene y establece una opción para definir estrictamente si los subpaths están dentro del rectángulo especificado en [ExtractionAreaBound](../). Si se establece en false, los subpaths que no estén completamente incluidos en [ExtractionAreaBound](../) serán extraídos. El valor predeterminado es **True**. |
| [get_UnpackPageContentXForm](./get_unpackpagecontentxform/)() const | Obtiene y establece una bandera que determina si los XFrom encontrados en las páginas deben descompactarse o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Solo los XForms que son renderizados por sentencias Do del contenido de la página se descompactan. Los XForms anidados no se descompactan. |
| [get_UnpackXFormPredicate](./get_unpackxformpredicate/)() const | Obtiene y establece la opción para descompactar solo el [XForm](../../aspose.pdf/xform/) correspondiente al predicado especificado. |
| [set_AutoGrouping](./set_autogrouping/)(bool) | Obtiene y establece la opción para agrupar automáticamente los subpaths en imágenes. Esta opción excluye la opción [GroupStrength](../). |
| [set_ExtractEverySubPathToSvg](./set_extracteverysubpathtosvg/)(bool) | Obtiene y establece la opción para extraer cada subpath de un documento PDF a imágenes SVG separadas. |
| [set_ExtractionAreaBound](./set_extractionareabound/)(const System::SharedPtr\<Rectangle\>\&) | Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción SVG. |
| [set_GroupStrength](./set_groupstrength/)(double) | Obtiene y establece una opción La fuerza de agrupar subpaths en imágenes. Permite configurar el grado de agrupación de subpaths. El rango de valores es de 0 a 1. Un valor de 0 corresponde a que la opción [ExtractEverySubPathToSvg](../) esté habilitada. Un valor de 1 creará una única imagen para todas las rutas vectoriales en la página. La opción tiene efecto cuando [AutoGrouping](../) es false. El valor predeterminado es **0.8**. |
| [set_MinStrokeWidth](./set_minstrokewidth/)(double) | Establece el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF usa un ancho de trazo más delgado, será reemplazado por este ancho. El valor predeterminado es 0.5. |
| [set_StrictExtractionAreaBoundCheck](./set_strictextractionareaboundcheck/)(bool) | Obtiene y establece una opción para definir estrictamente si los subpaths están dentro del rectángulo especificado en [ExtractionAreaBound](../). Si se establece en false, los subpaths que no estén completamente incluidos en [ExtractionAreaBound](../) serán extraídos. El valor predeterminado es **True**. |
| [set_UnpackPageContentXForm](./set_unpackpagecontentxform/)(bool) | Obtiene y establece una bandera que determina si los XFrom encontrados en las páginas deben descompactarse o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Solo los XForms que son renderizados por sentencias Do del contenido de la página se descompactan. Los XForms anidados no se descompactan. |
| [set_UnpackXFormPredicate](./set_unpackxformpredicate/)(System::Predicate\<System::SharedPtr\<XFormPlacement\>\>) | Obtiene y establece la opción para descompactar solo el [XForm](../../aspose.pdf/xform/) correspondiente al predicado especificado. |
| [SvgExtractionOptions](./svgextractionoptions/)() | Crea una instancia de la clase [SvgExtractionOptions](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
