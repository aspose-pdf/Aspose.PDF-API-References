---
title: "Clase Aspose::Pdf::HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::HtmlLoadOptions. Representa opciones para cargar/importar un archivo html en un documento pdf en C++."
type: docs
weight: 7200
url: /es/cpp/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class


Representa opciones para cargar/importar un archivo HTML en un documento PDF.

```cpp
class HtmlLoadOptions : public Aspose::Pdf::LoadOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | La ruta/base URL para el archivo html. |
| [get_CreateLogicalStructure](./get_createlogicalstructure/)() const | Obtiene un valor que indica si crear una estructura lógica en el documento PDF resultante. |
| [get_HtmlMediaType](./get_htmlmediatype/)() const | Obtiene los tipos de medios posibles utilizados durante la renderización. |
| [get_InputEncoding](./get_inputencoding/)() const | Obtiene el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [get_IsEmbedFonts](./get_isembedfonts/)() const | Obtiene la incrustación de fuentes en el documento resultante. |
| [get_IsPriorityCssPageRule](./get_isprioritycsspagerule/)() const |  |
| [get_IsRenderToSinglePage](./get_isrendertosinglepage/)() const | Obtiene la renderización de todo el documento en una sola página. |
| [get_PageInfo](./get_pageinfo/)() const | Obtiene información de la página del documento. |
| [get_PageLayoutOption](./get_pagelayoutoption/)() const | Obtiene la opción de diseño. |
| [HtmlLoadOptions](./htmlloadoptions/)() | Crea opciones de carga para convertir html en un documento pdf con ruta base vacía. |
| [HtmlLoadOptions](./htmlloadoptions/)(const System::String\&) | Crea opciones de carga para convertir html en un documento pdf con ruta base definida. |
| [set_CreateLogicalStructure](./set_createlogicalstructure/)(bool) | Establece un valor que indica si crear una estructura lógica en el documento PDF resultante. |
| [set_HtmlMediaType](./set_htmlmediatype/)(Aspose::Pdf::HtmlMediaType) | Establece los tipos de medios posibles utilizados durante la renderización. |
| [set_InputEncoding](./set_inputencoding/)(const System::String\&) | Establece el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [set_IsEmbedFonts](./set_isembedfonts/)(bool) | Establece la incrustación de fuentes en el documento resultante. |
| [set_IsPriorityCssPageRule](./set_isprioritycsspagerule/)(bool) |  |
| [set_IsRenderToSinglePage](./set_isrendertosinglepage/)(bool) | Establece la renderización de todo el documento en una sola página. |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Establece la información de la página del documento. |
| [set_PageLayoutOption](./set_pagelayoutoption/)(HtmlPageLayoutOption) | Establece la opción de diseño. |
## Ver también

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
