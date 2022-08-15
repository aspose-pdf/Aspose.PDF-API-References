---
title: PdfFileStamp
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase para agregar sellos marca de agua o fondo a archivos PDF.
type: docs
weight: 2580
url: /es/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Clase para agregar sellos (marca de agua o fondo) a archivos PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | Constructor de PdfFileStamp. El archivo de entrada y el archivo de salida se pueden especificar a través de las propiedades correspondientes. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Inicializa nuevo[`PdfFileStamp`](../pdffilestamp) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | Obtiene o establece el nombre del archivo adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como archivo adjunto. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. Valor posible: en línea / archivo adjunto. Valor predeterminado: en línea. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | Establece el formato de archivo PDF. El archivo de resultados se guardará en el formato de archivo especificado. Si no se especifica esta propiedad, el archivo se guardará en formato PDF predeterminado sin conversión. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Mantiene la seguridad si es verdadero. (Esta función se implementará en las próximas versiones). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Obtiene o establece el estilo de numeración de las páginas. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Obtiene o establece el indicador de optimización. Los flujos de recursos iguales en el archivo resultante se fusionan en un objeto PDF si se establece esta marca. Esto permite disminuir el tamaño del archivo resultante, pero puede provocar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Obtiene la altura de la primera página en el archivo fuente. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Obtiene o establece la rotación del número de página. La rotación es en grados. El valor predeterminado es 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Obtiene el ancho de la primera página en el archivo de entrada. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | Obtiene o establece el objeto Respuesta donde se almacenará el resultado de la operación. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Obtiene o establece opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | Id. de sello del siguiente sello agregado (incluidos encabezados de página/bocinas/números de página). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Obtiene o establece el número inicial de la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. Por ejemplo, si el Número inicial se establece en 100, las páginas del documento tendrán los números 100, 101, 102... |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Agrega pie de página a las páginas del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Agrega una imagen como pie de página. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Agrega imagen como pie de página a las páginas del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Agrega pie de página a las páginas del documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Agrega una imagen como pie de página. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Agrega imagen como pie de página de las páginas. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Agrega encabezado a la página. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Agrega imagen como encabezado en las páginas. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Agrega imagen como encabezado a las páginas del archivo. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Agrega encabezado a las páginas del archivo. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Agrega una imagen en la parte superior de la página. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Agrega imagen como encabezado en las páginas. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Agrega el número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página. El número de página se coloca en la parte inferior de la página, centrado horizontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Agregar número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Agrega el número de página a las páginas. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Agrega el número de página a las páginas. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Agrega el número de página en la posición especificada en la página. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Agrega el número de página en la posición especificada en la página. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Agrega el número de página a las páginas del documento. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Agrega el número de página a las páginas del documento. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Agrega sello al archivo. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inicializa la fachada. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Cierra los archivos abiertos y guarda los cambios. Advertencia. Si se especifican flujos de entrada o salida, no se cierran con el método Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Guarda el documento en el flujo especificado. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Guarda el resultado en el archivo especificado. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Posición inferior izquierda. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Posición media inferior. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Posición inferior derecha. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Posición izquierda. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Posición derecha. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Posición izquierda superior. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Posición media superior. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Posición superior derecha. |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
