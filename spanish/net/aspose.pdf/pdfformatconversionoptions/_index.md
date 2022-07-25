---
title: PdfFormatConversionOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: representa un conjunto de opciones para convertir documentos PDF
type: docs
weight: 6030
url: /es/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

representa un conjunto de opciones para convertir documentos PDF

```csharp
public class PdfFormatConversionOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Obtiene el objeto PdfFormatConversionOptions con los parámetros predeterminados |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión de documentos no afecta la alineación del texto y deja el texto como está. Pero en algunos casos, la sustitución de fuentes provoca la superposición de texto o espacios adicionales en el documento convertido. Cuando esta bandera se establece se realizarán operaciones especiales de alineación. Este indicador debe configurarse solo para documentos que tienen problemas con texto superpuesto o espacios de texto adicionales que hacen que el uso de este indicador disminuya el rendimiento y, en algunos casos, podría dañar el contenido del texto. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Acción para imágenes con máscara suave. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Acción para objetos que no se pueden convertir |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro tiene sentido solo cuando la bandera[`OptimizeFileSize`](./optimizefilesize) se establece en true. Por defecto combinación de estrategiasSubsetFonts y RemoveDuplicatedFonts se usa. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Opciones para casos en los que no es posible incrustar algunas fuentes en un documento PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | formato PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | Obtiene o establece el nombre de archivo del nombre de perfil icc. En caso de nulo, se utiliza el perfil icc predeterminado. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Obtiene/establece la ejecución de secuencias de imágenes en modo asíncrono. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | ¿Está habilitado el modo de conversión de poca memoria |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | Obtiene o establece si se pasan datos de información a metadatos cuando se convierte a PDF 2.0. Verdadero por defecto. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Ruta al archivo donde se almacenarán los comentarios. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Stream donde se almacenarán los comentarios. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Contiene indicadores para controlar el proceso de conversión de PDF/A en los casos en que el documento de origen no corresponde a la especificación de PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Esta propiedad está fuera de la propiedad. Contiene todas las fuentes (nombres de fuente) que no se encontraron en la computadora en la última conversión de PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Obtiene o establece un indicador que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con un tamaño de archivo reducido. Ahora, este indicador afecta la optimización de las fuentes utilizadas en el documento PDF; posiblemente, en el futuro, este indicador también se utilizará para activar la optimización para otras estructuras de datos, como un gráfico. El establecimiento de este indicador y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría disminuir significativamente el rendimiento de la conversión. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Estrategia para procesar símbolos del Área de uso privado (PUA) unicode. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Acción para objetos con máscara de imagen |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Reglas para resolver problemas con el mapeo Unicode. Puede ser nulo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera[`AlignText`](./aligntext) se establece en verdadero. |

### Ver también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
