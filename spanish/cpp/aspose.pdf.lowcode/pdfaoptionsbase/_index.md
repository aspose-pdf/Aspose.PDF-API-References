---
title: "Clase Aspose::Pdf::LowCode::PdfAOptionsBase"
linktitle: "PdfAOptionsBase"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::PdfAOptionsBase. Representa la clase base para las opciones del complemento PdfAConverter. Esta clase proporciona propiedades y métodos para configurar el proceso de conversión y validación PDF/A en C++."
type: docs
weight: 5500
url: /es/cpp/aspose.pdf.lowcode/pdfaoptionsbase/
---
## PdfAOptionsBase class


Representa la clase base para las opciones del complemento [PdfAConverter](../pdfaconverter/). Esta clase proporciona propiedades y métodos para configurar el proceso de conversión y validación PDF/A.

```cpp
class PdfAOptionsBase : public Aspose::Pdf::LowCode::IPluginOptions,
                        public Aspose::Pdf::LowCode::IDataContainer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección. |
| [get_AlignText](./get_aligntext/)() | Obtiene un valor que indica si se requieren medios adicionales para preservar la alineación del texto durante el proceso de conversión PDF/A. |
| [get_ErrorAction](./get_erroraction/)() | Obtiene la acción a realizar para los objetos que no pueden convertirse. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() | Obtiene la estrategia para eliminar fuentes y minimizar el tamaño del archivo de salida durante el proceso de conversión PDF/A. |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() | Obtiene las opciones para procesar fuentes que no pueden incrustarse en el documento. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() | Obtiene el nombre de archivo del perfil ICC (Consorcio Internacional de [Color](../../aspose.pdf/color/)) que se utilizará para la conversión PDF/A en lugar del predeterminado. |
| [get_Inputs](./get_inputs/)() override | Obtiene la colección de fuentes de datos. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() | Obtiene un valor que indica si el modo de bajo consumo de memoria está habilitado durante el proceso de conversión PDF/A. |
| [get_LogOutputSource](./get_logoutputsource/)() const | Obtiene la fuente de datos para la salida del registro. |
| [get_NonSpecificationFlags](./get_nonspecificationflags/)() | Obtiene los indicadores que controlan la conversión PDF/A en casos en que el documento PDF de origen no corresponde a la especificación PDF. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() | Obtiene un valor que indica si se debe intentar reducir el tamaño del archivo durante el proceso de conversión PDF/A. |
| [get_PdfAVersion](./get_pdfaversion/)() const | Obtiene la versión del estándar PDF/A que se utilizará para la validación o conversión. |
| [get_PuaSymbolsProcessingStrategy](./get_puasymbolsprocessingstrategy/)() | Obtiene la estrategia para procesar los símbolos del Área de Uso Privado (PUA) en el documento PDF. |
| [get_SoftMaskAction](./get_softmaskaction/)() | Obtiene la acción a realizar durante la conversión de imágenes con máscaras suaves. |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() | Obtiene la estrategia para codificar fuentes simbólicas al convertir al formato PDF/A. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() | Obtiene las reglas para procesar tablas ToUnicode CMap que no están vinculadas a símbolos Unicode durante el proceso de conversión PDF/A. |
| [PdfAOptionsBase](./pdfaoptionsbase/)() |  |
| [set_AlignText](./set_aligntext/)(bool) | Establece un valor que indica si se requieren medios adicionales para preservar la alineación del texto durante el proceso de conversión PDF/A. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Establece la acción a realizar para los objetos que no pueden convertirse. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Establece la estrategia para eliminar fuentes y minimizar el tamaño del archivo de salida durante el proceso de conversión a PDF/A. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(const System::String\&) | Establece el nombre de archivo del perfil ICC (International [Color](../../aspose.pdf/color/) Consortium) que se utilizará para la conversión a PDF/A en lugar del predeterminado. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Establece un valor que indica si el modo de bajo consumo de memoria está habilitado durante el proceso de conversión a PDF/A. |
| [set_LogOutputSource](./set_logoutputsource/)(const System::SharedPtr\<IDataSource\>\&) | Establece la fuente de datos para la salida del registro. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Establece un valor que indica si se debe intentar reducir el tamaño del archivo durante el proceso de conversión a PDF/A. |
| [set_PdfAVersion](./set_pdfaversion/)(PdfAStandardVersion) | Establece la versión del estándar PDF/A que se utilizará para la validación o conversión. |
| [set_PuaSymbolsProcessingStrategy](./set_puasymbolsprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Establece la estrategia para procesar los símbolos del Área de Uso Privado (PUA) en el documento PDF. |
| [set_SoftMaskAction](./set_softmaskaction/)(ConvertSoftMaskAction) | Establece la acción a realizar durante la conversión de imágenes con máscaras suaves. |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(const System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>\&) | Establece la estrategia para codificar fuentes simbólicas al convertir al formato PDF/A. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(const System::SharedPtr\<ToUnicodeProcessingRules\>\&) | Establece las reglas para procesar las tablas ToUnicode CMap que no están vinculadas a símbolos Unicode durante el proceso de conversión a PDF/A. |
## Ver también

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
