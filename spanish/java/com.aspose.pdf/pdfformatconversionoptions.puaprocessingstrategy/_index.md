---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Algunos documentos PDF tienen símbolos unicode especiales, que pertenecen al Área de Uso Privado (PUA), vea la descripción en https://en.wikipedia.org/wiki/Private_Use_Areas. Estos símbolos."
type: docs
weight: 3750
url: /es/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Algunos documentos PDF tienen símbolos unicode especiales, que pertenecen al Área de Uso Privado (PUA); vea la descripción en https://en.wikipedia.org/wiki/Private_Use_Areas. Estos símbolos provocan errores de cumplimiento PDF/A como "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Esta enumeración declara estrategias que pueden usarse para manejar los símbolos PUA.

## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | Desactivar el procesamiento de símbolos PUA. Esta estrategia se usa por defecto para documentos PDF/A con conformidad de Nivel B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Esta estrategia funciona más lentamente que 'SurroundPuaTextWithEmptyActualText' pero puede eliminar errores compatibles con PUA en documentos que no pueden ser manejados correctamente por SurroundPuaTextWithEmptyActualText. Los símbolos PUA se sustituyen por el símbolo 'espacio' o por unicode especial (algunos símbolos PUA tienen análogos unicode). La sustitución se aplica no al texto del documento sino a los datos internos de la fuente ToUnicode, por lo que no afecta la visión del símbolo pero sí afecta su presentación en la operación de copiar/pegar del búfer del sistema. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Inserta un bloque de contenido marcado con una entrada ActualText que contiene texto vacío. Esta estrategia ofrece buenos resultados para documentos sin bloques de contenido marcado. Se usa por defecto para documentos PDF/A con conformidad de Nivel A. |

### None {#None}
```
public static final int None
```

Desactivar el procesamiento de símbolos PUA. Esta estrategia se usa por defecto para documentos PDF/A con conformidad de Nivel B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Esta estrategia funciona más lentamente que 'SurroundPuaTextWithEmptyActualText' pero puede eliminar errores compatibles con PUA en documentos que no pueden ser manejados correctamente por SurroundPuaTextWithEmptyActualText. Los símbolos PUA se sustituyen por el símbolo 'espacio' o por unicode especial (algunos símbolos PUA tienen análogos unicode). La sustitución se aplica no al texto del documento sino a los datos internos de la fuente ToUnicode, por lo que no afecta la visión del símbolo pero sí afecta su presentación en la operación de copiar/pegar del búfer del sistema.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Inserta un bloque de contenido marcado con una entrada ActualText que contiene texto vacío. Esta estrategia ofrece buenos resultados para documentos sin bloques de contenido marcado. Se usa por defecto para documentos PDF/A con conformidad de Nivel A.
