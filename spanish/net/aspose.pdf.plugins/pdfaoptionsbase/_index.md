---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PdfAOptionsBase. Representa la clase base para las opciones del plugin PdfAConverter. Esta clase proporciona propiedades y métodos para configurar el proceso de conversión y validación de PDF/A.
type: docs
weight: 9010
url: /es/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## Clase PdfAOptionsBase

Representa la clase base para las opciones del plugin [`PdfAConverter`](../pdfaconverter/). Esta clase proporciona propiedades y métodos para configurar el proceso de conversión y validación de PDF/A.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Obtiene o establece un valor que indica si son necesarios medios adicionales para preservar la alineación del texto durante el proceso de conversión a PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Obtiene o establece la acción a tomar para los objetos que no se pueden convertir. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Obtiene o establece la estrategia para eliminar fuentes para minimizar el tamaño del archivo de salida durante el proceso de conversión a PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Obtiene las opciones para procesar fuentes que no se pueden incrustar en el documento. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Obtiene o establece el nombre del archivo del perfil ICC (Consorcio Internacional del Color) que se utilizará para la conversión a PDF/A en lugar del predeterminado. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Obtiene la colección de fuentes de datos |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Obtiene o establece un valor que indica si el modo de baja memoria está habilitado durante el proceso de conversión a PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Obtiene o establece la fuente de datos para la salida del registro. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Obtiene las banderas que controlan la conversión a PDF/A para los casos en que el documento PDF de origen no corresponde a la especificación PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Obtiene o establece un valor que indica si se debe intentar reducir el tamaño del archivo durante el proceso de conversión a PDF/A. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Obtiene o establece la versión del estándar PDF/A que se utilizará para la validación o conversión. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Obtiene o establece la estrategia para procesar símbolos del Área de Uso Privado (PUA) en el documento PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Obtiene o establece la acción a tomar durante la conversión de imágenes con máscaras suaves. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Obtiene o establece la estrategia para codificar fuentes simbólicas al convertir a formato PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Obtiene o establece las reglas para procesar tablas CMap ToUnicode y no vinculadas a símbolos Unicode durante el proceso de conversión a PDF/A. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección |

### Ver También

* interfaz [IPluginOptions](../ipluginoptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblaje [Aspose.PDF](../../)