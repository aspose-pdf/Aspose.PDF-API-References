---
title: "Clase Aspose::Pdf::PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::PdfFormatConversionOptions. representa un conjunto de opciones para convertir documentos PDF en C++."
type: docs
weight: 15000
url: /es/cpp/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class


representa un conjunto de opciones para convertir un documento PDF

```cpp
class PdfFormatConversionOptions : public System::Object
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [PuaProcessingStrategy](./puaprocessingstrategy/) | Algunos documentos PDF tienen símbolos unicode especiales, que pertenecen al Área de Uso Privado (PUA); vea la descripción en [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). Estos símbolos provocan errores de cumplimiento PDF/A como "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Esta enumeración declara estrategias que pueden usarse para manejar los símbolos PUA. |
| [RemoveFontsStrategy](./removefontsstrategy/) | Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que pueden usarse para optimizar el uso de fuentes. Cada estrategia de esta enumeración solo tiene sentido cuando la bandera [OptimizeFileSize](../) está activada. |
| [SegmentAlignStrategy](./segmentalignstrategy/) | Describe las estrategias usadas para alinear los segmentos de texto del documento. Actualmente solo se admite la estrategia para restaurar los segmentos a sus límites originales. En el futuro podrían añadirse otras estrategias. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AlignText](./get_aligntext/)() const | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión del documento no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes provoca superposición de texto o espacios adicionales en el documento convertido. Cuando esta bandera está activada se realizarán operaciones especiales de alineación. Esta bandera solo debe activarse para documentos que tengan problemas de texto superpuesto o espacios extra, ya que su uso disminuye el rendimiento y, en algunos casos, podría corromper el contenido del texto. |
| [get_AutoTaggingSettings](./get_autotaggingsettings/)() const | Obtiene la configuración para el etiquetado automático durante la conversión al formato PDF. |
| [get_ConvertSoftMaskAction](./get_convertsoftmaskaction/)() const | Acción para imágenes con máscara suave. |
| static [get_Default](./get_default/)() | Obtiene el objeto [PdfFormatConversionOptions](./) con los parámetros predeterminados. |
| [get_ErrorAction](./get_erroraction/)() const | Acción para objetos que no pueden convertirse. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() const | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro solo tiene sentido cuando la bandera [OptimizeFileSize](../) está establecida en true. Por defecto se usa la combinación de estrategias [SubsetFonts](./removefontsstrategy/) y [RemoveDuplicatedFonts](./removefontsstrategy/). |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() const | Opciones para los casos en que no es posible incrustar algunas fuentes en el documento PDF. |
| [get_Format](./get_format/)() const | Formato PDF. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() const | Obtiene el nombre de archivo del perfil ICC. En caso de null se usa el perfil ICC predeterminado. |
| [get_IsAsyncImageStreamsConversionMode](./get_isasyncimagestreamsconversionmode/)() const | Obtiene/establece la ejecución de flujos de imágenes en modo asíncrono. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() const | ¿Está habilitado el modo de conversión de bajo consumo de memoria? |
| [get_IsTransferInfo](./get_istransferinfo/)() const | Obtiene si se deben pasar datos de Info a [Metadata](../metadata/) al convertir a PDF 2.0. Verdadero por defecto. |
| [get_LogFileName](./get_logfilename/)() const | Ruta al archivo donde se almacenarán los comentarios. |
| [get_LogStream](./get_logstream/)() const | Flujo donde se almacenarán los comentarios. |
| [get_NonSpecificationCases](./get_nonspecificationcases/)() const | Contiene banderas para controlar el proceso de conversión a PDF/A en los casos en que el documento fuente no corresponde a la especificación PDF/A. |
| [get_NotAccessibleFonts](./get_notaccessiblefonts/)() | Esta propiedad es una propiedad de salida. Contiene todas las fuentes (nombres de fuentes) que no se encontraron en el equipo durante la última conversión a PDF/A. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() const | Obtiene una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido. Ahora esta bandera afecta la optimización de fuentes usadas en el documento PDF, posiblemente, en el futuro, esta bandera también se usará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo pero, al mismo tiempo, podría disminuir considerablemente el rendimiento de la conversión. |
| [get_OutputIntent](./get_outputintent/)() const | Obtiene el [Aspose::Pdf::OutputIntent](../outputintent/) para la conversión de formato PDF. |
| [get_PuaTextProcessingStrategy](./get_puatextprocessingstrategy/)() const | Estrategia para procesar símbolos del Área de Uso Privado (PUA) de Unicode. |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() const | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación. |
| [get_TransparencyAction](./get_transparencyaction/)() const | Acción para objetos de imagen enmascarados. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() const | Reglas para resolver problemas con el mapeo Unicode. Puede ser nulo. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat, ConvertErrorAction) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat, ConvertErrorAction) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, PdfFormat, ConvertErrorAction) | Constructor. |
| [set_AlignText](./set_aligntext/)(bool) | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión del documento no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes provoca superposición de texto o espacios adicionales en el documento convertido. Cuando esta bandera está activada se realizarán operaciones especiales de alineación. Esta bandera solo debe activarse para documentos que tengan problemas de texto superpuesto o espacios extra, ya que su uso disminuye el rendimiento y, en algunos casos, podría corromper el contenido del texto. |
| [set_AutoTaggingSettings](./set_autotaggingsettings/)(const System::SharedPtr\<Aspose::Pdf::AutoTaggingSettings\>\&) | Establece la configuración para el etiquetado automático durante la conversión de formato PDF. |
| [set_ConvertSoftMaskAction](./set_convertsoftmaskaction/)(Aspose::Pdf::ConvertSoftMaskAction) | Acción para imágenes con máscara suave. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Acción para objetos que no pueden convertirse. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro solo tiene sentido cuando la bandera [OptimizeFileSize](../) está establecida en true. Por defecto se usa la combinación de estrategias [SubsetFonts](./removefontsstrategy/) y [RemoveDuplicatedFonts](./removefontsstrategy/). |
| [set_Format](./set_format/)(PdfFormat) | Formato PDF. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(const System::String\&) | Establece el nombre de archivo del perfil ICC. En caso de ser nulo, se usa el perfil ICC predeterminado. |
| [set_IsAsyncImageStreamsConversionMode](./set_isasyncimagestreamsconversionmode/)(bool) | Obtiene/establece la ejecución de flujos de imágenes en modo asíncrono. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | ¿Está habilitado el modo de conversión de bajo consumo de memoria? |
| [set_IsTransferInfo](./set_istransferinfo/)(bool) | Establece si se deben pasar datos de Info a [Metadata](../metadata/) al convertir a PDF 2.0. Verdadero por defecto. |
| [set_LogFileName](./set_logfilename/)(const System::String\&) | Ruta al archivo donde se almacenarán los comentarios. |
| [set_LogStream](./set_logstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Flujo donde se almacenarán los comentarios. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Establece una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido. Ahora esta bandera afecta la optimización de fuentes usadas en el documento PDF, posiblemente, en el futuro, esta bandera también se usará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo pero, al mismo tiempo, podría disminuir considerablemente el rendimiento de la conversión. |
| [set_OutputIntent](./set_outputintent/)(const System::SharedPtr\<Aspose::Pdf::OutputIntent\>\&) | Establece el [Aspose::Pdf::OutputIntent](../outputintent/) para la conversión de formato PDF. |
| [set_PuaTextProcessingStrategy](./set_puatextprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Estrategia para procesar símbolos del Área de Uso Privado (PUA) de Unicode. |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(const System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>\&) | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación. |
| [set_TransparencyAction](./set_transparencyaction/)(ConvertTransparencyAction) | Acción para objetos de imagen enmascarados. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(const System::SharedPtr\<ToUnicodeProcessingRules\>\&) | Reglas para resolver problemas con el mapeo Unicode. Puede ser nulo. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
