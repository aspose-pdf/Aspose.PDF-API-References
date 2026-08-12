---
title: "Aspose::Pdf::PdfFormatConversionOptions::PuaProcessingStrategy enum"
linktitle: "PuaProcessingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PdfFormatConversionOptions::PuaProcessingStrategy enum. Algunos documentos PDF tienen símbolos unicode especiales que pertenecen al Área de Uso Privado (PUA), vea la descripción en . Estos símbolos causan errores de cumplimiento PDF/A como \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Esta enumeración declara estrategias que pueden usarse para manejar símbolos PUA en C++."
type: docs
weight: 4200
url: /es/cpp/aspose.pdf/pdfformatconversionoptions/puaprocessingstrategy/
---
## PuaProcessingStrategy enum


Algunos documentos PDF tienen símbolos unicode especiales, que pertenecen al Área de Uso Privado (PUA); vea la descripción en [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). Estos símbolos provocan errores de cumplimiento PDF/A como "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Esta enumeración declara estrategias que pueden usarse para manejar los símbolos PUA.

```cpp
enum class PuaProcessingStrategy
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Desactivar el procesamiento de símbolos PUA. Esta estrategia se usa por defecto para documentos PDF/A con conformidad de Nivel B. |
| SurroundPuaTextWithEmptyActualText | 1 | Inserta un bloque de contenido marcado con una entrada ActualText que contiene texto vacío. Esta estrategia ofrece buenos resultados para documentos sin bloques de contenido marcado. Se usa por defecto para documentos PDF/A con conformidad de Nivel A. |
| SubstitutePuaSymbols | 2 | Esta estrategia funciona más lentamente que 'SurroundPuaTextWithEmptyActualText' pero puede eliminar errores compatibles con PUA en documentos que no pueden ser manejados correctamente por SurroundPuaTextWithEmptyActualText. Los símbolos PUA se sustituyen por el símbolo 'espacio' o por unicode especial (algunos símbolos PUA tienen análogos unicode). La sustitución se aplica no al texto del documento sino a los datos internos de la fuente ToUnicode, por lo que no afecta la visualización del símbolo pero sí afecta su presentación en la operación de copiar/pegar del búfer del sistema. |

## Ver también

* Class [PdfFormatConversionOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
