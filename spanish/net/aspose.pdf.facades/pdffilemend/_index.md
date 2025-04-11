---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileMend. Representa una clase para agregar textos e imágenes en las páginas de un documento PDF existente
type: docs
weight: 4530
url: /es/net/aspose.pdf.facades/pdffilemend/
---
## Clase PdfFileMend

Representa una clase para agregar textos e imágenes en las páginas de un documento PDF existente.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Constructor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfFileMend` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Establece un valor booleano que indica el ajuste de línea en los métodos AddText. Si el valor es verdadero, el texto en FormattedText se ajustará. Por defecto, el valor es falso. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Establece o obtiene la estrategia de posicionamiento del texto. [`PositioningMode`](../positioningmode/) El modo predeterminado es Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Establece o obtiene el algoritmo de ajuste de palabras. Ver WordWrapMode e IsWordWrap. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | No implementado. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | No implementado. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | No implementado. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Cierra el objeto PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Guarda el documento PDF en el flujo especificado. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Guarda el documento PDF en el archivo especificado. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)