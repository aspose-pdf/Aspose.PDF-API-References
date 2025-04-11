---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PdfFormatConversionOptions. representa un conjunto de opciones para convertir documentos PDF
type: docs
weight: 8380
url: /es/net/aspose.pdf/pdfformatconversionoptions/
---
## Clase PdfFormatConversionOptions

representa un conjunto de opciones para convertir documentos PDF

```csharp
public class PdfFormatConversionOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Obtiene el objeto PdfFormatConversionOptions con parámetros predeterminados |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión del documento no afecta la alineación del texto y deja el texto tal como está. Pero en algunos casos, la sustitución de fuentes causa superposición de texto o espacios extra en el documento convertido. Cuando esta bandera está activada, se realizarán operaciones de alineación especiales. Esta bandera debe establecerse solo para documentos que tienen problemas con texto superpuesto o espacios de texto extra, ya que el uso de esta bandera disminuye el rendimiento y en algunos casos podría corromper el contenido del texto. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Acción para imágenes con máscara suave. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Acción para objetos que no se pueden convertir |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro tiene sentido solo cuando la bandera [`OptimizeFileSize`](./optimizefilesize/) está establecida en verdadero. Por defecto, se utiliza una combinación de estrategias SubsetFonts y RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Opciones para casos en los que no es posible incrustar algunas fuentes en el documento PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Formato PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Obtiene o establece el nombre del archivo del perfil icc. En caso de ser nulo, se utiliza el perfil icc predeterminado. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Obtiene/establece la ejecución de flujos de imágenes en modo asíncrono. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | ¿Está habilitado el modo de conversión de baja memoria? |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Obtiene o establece si se deben pasar datos de Info a Metadata al convertirse a PDF 2.0. Verdadero por defecto. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Ruta al archivo donde se almacenarán los comentarios. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Flujo donde se almacenarán los comentarios. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Contiene banderas para controlar el proceso de conversión a PDF/A para casos en los que el documento fuente no corresponde a la especificación PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Esta propiedad es una propiedad externa. Contiene todas las fuentes (nombres de fuentes) que no se encontraron en la computadora en la última conversión a PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Obtiene o establece una bandera que habilita/deshabilita un modo de conversión especial para obtener un documento PDF/A con un tamaño de archivo reducido. Ahora esta bandera impacta en la optimización de las fuentes utilizadas en el documento PDF, posiblemente, en el futuro, esta bandera también se utilizará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría disminuir significativamente el rendimiento de la conversión. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Obtiene o establece el [`OutputIntent`](../outputintent/) para la conversión de formato PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Estrategia para procesar símbolos del área de uso privado de unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una tabla de subcodificación. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Acción para objetos de imagen enmascarados |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Reglas para resolver problemas con el mapeo de unicode. Puede ser nulo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera [`AlignText`](./aligntext/) está establecida en verdadero. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)