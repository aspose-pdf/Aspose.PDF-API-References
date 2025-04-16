---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFormatConversionOptionsPuaProcessingStrategy de Aspose.Pdf. Algunos documentos PDF tienen símbolos unicode especiales que pertenecen al Área de Uso Privado - PUA, consulte la descripción en https//en.wikipedia.org/wiki/Private_Use_Areas. Estos símbolos causan errores de conformidad PDF/A como "El texto está mapeado al Área de Uso Privado Unicode, pero no hay una entrada ActualText presente". Esta enumeración declara estrategias que se pueden utilizar para manejar símbolos PUA.
type: docs
weight: 8390
url: /es/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## Enumeración PdfFormatConversionOptions.PuaProcessingStrategy

Algunos documentos PDF tienen símbolos unicode especiales, que pertenecen al Área de Uso Privado (PUA), consulte la descripción en https://en.wikipedia.org/wiki/Private_Use_Areas. Estos símbolos causan errores de conformidad PDF/A como "El texto está mapeado al Área de Uso Privado Unicode, pero no hay una entrada ActualText presente". Esta enumeración declara estrategias que se pueden utilizar para manejar símbolos PUA.

```csharp
public enum PuaProcessingStrategy
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | `0` | Desactivar el procesamiento de símbolos PUA. Esta estrategia se utiliza por defecto para documentos PDF/A con conformidad de Nivel B. |
| RodearTextoPuaConTextoActualVacio | `1` | Inserta un bloque de contenido marcado con una entrada ActualText que contiene texto vacío. Esta estrategia da buenos resultados para documentos sin bloques de contenido marcados. Se utiliza por defecto para documentos PDF/A con conformidad de Nivel A. |
| SustituirSímbolosPua | `2` | Esta estrategia funciona más lentamente que 'RodearTextoPuaConTextoActualVacio', pero puede eliminar errores de conformidad PUA para documentos que no pueden ser manejados adecuadamente por RodearTextoPuaConTextoActualVacio. Los símbolos PUA se sustituyen por el símbolo 'espacio' o unicode especial (algunos símbolos PUA tienen análogos unicode). La sustitución se aplica no al texto del documento, sino a los datos internos de la fuente ToUnicode, por lo que no afecta la visión del símbolo, pero sí afecta la presentación del símbolo en el sistema de portapapeles de la operación de copiar/pegar. |

### Véase También

* clase [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)