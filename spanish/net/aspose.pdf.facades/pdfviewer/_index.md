---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfViewer. Representa una clase para ver o imprimir un pdf
type: docs
weight: 4630
url: /es/net/aspose.pdf.facades/pdfviewer/
---
## Clase PdfViewer

Representa una clase para ver o imprimir un pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Inicializa un nuevo objeto `PdfViewer`. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfViewer`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Obtiene o establece un valor booleano que indica si el archivo se imprimirá con tamaño optimizado. Si es falso, imprime la página sin escalado. Si es verdadero, imprime la página con escalado para ajustarse al área imprimible. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Obtiene o establece un valor booleano que indica si el archivo se imprimirá con rotación automática. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Obtiene o establece un valor de AutoRotateMode que indica la dirección de rotación. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se utiliza por defecto. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Obtiene o establece un valor que indica la alineación horizontal. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Obtiene el conteo de páginas del archivo Pdf actual. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Obtiene o establece la contraseña del documento de entrada. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Obtiene o establece un valor booleano que indica si la página se está imprimiendo en escala de grises. Por defecto es falso. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Establece o obtiene un modo para que PdfViewer imprima como imagen. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Obtiene o establece el nombre del documento en la cola de impresión cuando se imprime el documento. El valor por defecto es el nombre del archivo. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Obtiene o establece un valor booleano que indica si se debe producir el diálogo de número de página al imprimir. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Obtiene el resultado del trabajo de impresión. Si tiene éxito, es nulo; de lo contrario, es un objeto de excepción. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Obtiene o establece la resolución durante la visualización y la impresión. Cuanto mayor sea la resolución, más lenta será la velocidad. El valor por defecto es 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Obtiene o establece un valor de punto flotante que indica el factor de escala. El valor por defecto es 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Obtiene/establece el uso de la conversión de la página pdf en un archivo png intermedio durante la impresión en modo archivo. Úselo cuando el tamaño del archivo de salida sea importante. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Obtiene o establece un valor que indica la alineación vertical. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Inicializa la fachada. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Inicializa la fachada. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Inicializa la fachada. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Cierra la fachada. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Obtiene las páginas del archivo pdf actual. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Decodifica una página de un archivo Pdf. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Libera los recursos de la fachada. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Obtiene la configuración de página predeterminada. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Obtiene la configuración de impresora predeterminada. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Imprime el documento Pdf utilizando la impresora predeterminada. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Imprime el documento Pdf con la configuración de la impresora. El tamaño de la página de salida se ajustará al tamaño de la primera página del documento. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Imprime el documento Pdf con configuraciones. Si el tamaño del documento no corresponde al tamaño de la página, se extenderá para ajustarse al tamaño de la página. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Imprime el documento Pdf con un diálogo de configuración. Elija una impresora utilizando el diálogo. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Abre e imprime un gran flujo de Pdf. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Abre e imprime un gran archivo Pdf. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Abre e imprime un gran flujo de Pdf con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Abre e imprime un gran archivo Pdf con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Abre e imprime un gran flujo de Pdf con la configuración de página y la configuración de impresora especificadas. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Abre e imprime un gran archivo Pdf con la configuración de página y la configuración de impresora especificadas. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Guarda el documento PDF resultante en un flujo. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Guarda el documento PDF resultante en un archivo. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Ocurre antes de que comience la impresión y permite proporcionar controladores de impresión personalizados en lugar del predeterminado. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Ocurre cuando termina la impresión de una página en el PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Agrega/elimina suscripción al evento de impresión de la última página. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Agrega/elimina suscripción al evento de impresión de la última página. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Ocurre antes de que comience a imprimirse una página. |

### Véase también

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)