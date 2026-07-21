---
title: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters clase"
linktitle: "ContentsResizeParameters"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters clase. Clase para especificar los parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales; márgenes Izquierda, Superior, Inferior y Derecha en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; Algunos valores pueden quedar nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores especificados explícitamente. Por ejemplo: si el ancho de la página = 100 y el nuevo ancho de página especificado es 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se usa en el método ResizeContents en C++."
type: docs
weight: 7300
url: /es/cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/
---
## ContentsResizeParameters class


Clase para especificar los parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales; [Left](../../../aspose.pdf/left/), Top, Bottom y [Right](../../../aspose.pdf/right/) márgenes en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; Algunos valores pueden quedar nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores especificados explícitamente. Por ejemplo: si el ancho de la página = 100 y el nuevo ancho de página especificado es 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se usa en el método ResizeContents.

```cpp
class ContentsResizeParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [ContentSize](./contentsize/)(double, double) | Crea parámetros de redimensionamiento con el tamaño de contenido especificado. |
| static [ContentSizePercent](./contentsizepercent/)(double, double) | Crea parámetros de redimensionamiento con el tamaño de contenido especificado en porcentajes del tamaño de página inicial. Los márgenes se calculan automáticamente. |
| [ContentsResizeParameters](./contentsresizeparameters/)() | Crea parámetros de redimensionamiento donde todos los valores se establecen en "auto". Más tarde se pueden especificar los márgenes y el tamaño del contenido si es necesario. |
| [ContentsResizeParameters](./contentsresizeparameters/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Crea parámetros de redimensionamiento con los valores de margen especificados y el tamaño del contenido. |
| [get_BottomMargin](./get_bottommargin/)() const | Obtiene el margen inferior en la página resultante. |
| [get_ChangeMediaBox](./get_changemediabox/)() const | Obtiene y establece si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. El valor predeterminado es **false** |
| [get_ContentsHeight](./get_contentsheight/)() const | Obtiene la altura del contenido de la página origen en la página resultante. |
| [get_ContentsWidth](./get_contentswidth/)() const | Obtiene el ancho del contenido de la página origen en la página resultante. |
| [get_LeftMargin](./get_leftmargin/)() const | Obtiene el margen izquierdo en la página resultante. |
| [get_RightMargin](./get_rightmargin/)() const | Obtiene el margen derecho en la página resultante. |
| [get_TopMargin](./get_topmargin/)() const | Obtiene el margen superior en la página resultante. |
| static [Margins](./margins/)(double, double, double, double) | Crea parámetros de redimensionamiento con el valor de los márgenes especificado. El tamaño del contenido se calcula automáticamente. |
| static [MarginsPercent](./marginspercent/)(double, double, double, double) | Crea parámetros de redimensionamiento. Los márgenes se especifican en porcentajes del tamaño de página inicial. |
| static [PageResize](./pageresize/)(double, double) | Crea parámetros de redimensionamiento para el redimensionamiento de página. |
| static [PageResizePct](./pageresizepct/)(double, double) | Crea parámetros de redimensionamiento para el redimensionamiento de página. Los nuevos tamaños se especifican en porcentaje. |
| [set_BottomMargin](./set_bottommargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Establece el margen inferior en la página resultante. |
| [set_ChangeMediaBox](./set_changemediabox/)(bool) | Obtiene y establece si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. El valor predeterminado es **false** |
| [set_ContentsHeight](./set_contentsheight/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Establece la altura del contenido de la página origen en la página resultante. |
| [set_ContentsWidth](./set_contentswidth/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Establece el ancho del contenido de la página origen en la página resultante. |
| [set_LeftMargin](./set_leftmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Establece el margen izquierdo en la página resultante. |
| [set_RightMargin](./set_rightmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Establece el margen derecho en la página resultante. |
| [set_TopMargin](./set_topmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Establece el margen superior en la página resultante. |
## Ver también

* Class [Object](../../../system/object/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
