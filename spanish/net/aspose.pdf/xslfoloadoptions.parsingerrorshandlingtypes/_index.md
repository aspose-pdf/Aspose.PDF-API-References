---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. El documento XSLFO de origen puede contener errores de formato. Este enum enumera las posibles estrategias para manejar dichos errores de formato.
type: docs
weight: 11540
url: /es/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## Enumeración XslFoLoadOptions.ParsingErrorsHandlingTypes

El documento XSLFO de origen puede contener errores de formato. Este enum enumera las posibles estrategias para manejar dichos errores de formato.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| TryIgnore | `0` | En este caso, se instruirá al convertidor para que intente continuar con la conversión e ignore los errores de formato encontrados. En este caso, el éxito no está garantizado, pueden ocurrir problemas graves más adelante en el convertidor, y en tal caso se lanzará una excepción con la lista de errores de formato encontrados. |
| ThrowExceptionImmediately | `1` | En este caso, la conversión se detendrá inmediatamente y se lanzará una excepción inmediatamente después de detectar el primer error de formato. |
| InvokeCustomHandler | `2` | Este es el método más ágil: el código personalizado debe proporcionar (en la propiedad WarningCallback) un controlador especial que se llamará cuando se detecte un error de formato. Ese controlador puede, por ejemplo, registrar o contar errores, etc., y proporcionará la decisión de si se puede continuar con el procesamiento para este o aquel error. |

### Ver También

* clase [XslFoLoadOptions](../xslfoloadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)