---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El documento XSLFO de origen puede contener errores de formato. Este enumerado enumera las posibles estrategias para manejar dichos errores de formato."
type: docs
weight: 5790
url: /es/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

El documento XSLFO de origen puede contener errores de formato. Este enumerado enumera las posibles estrategias para manejar dichos errores de formato.

## Campos

| Campo | Descripción |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Este es el método más ágil - el código personalizado debe proporcionar (en la propiedad WarningCallback) un controlador especial que será llamado cuando se detecte un error de formato. Ese controlador puede, por ejemplo, registrar o contar errores, etc., y proporcionará una decisión sobre si el procesamiento puede continuar para este u otro error. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | En este caso la conversión se detendrá inmediatamente y se lanzará una excepción inmediatamente después de detectar el primer error de formato. |
| [TryIgnore](#TryIgnore) | En este caso se instruirá al convertidor para intentar continuar con la conversión e ignorar los errores de formato encontrados. En este caso el éxito no está garantizado, pueden ocurrir problemas graves más tarde en el convertidor, y en tal caso se lanzará una excepción con la lista de errores de formato encontrados. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Este es el método más ágil - el código personalizado debe proporcionar (en la propiedad WarningCallback) un controlador especial que será llamado cuando se detecte un error de formato. Ese controlador puede, por ejemplo, registrar o contar errores, etc., y proporcionará una decisión sobre si el procesamiento puede continuar para este u otro error.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

En este caso la conversión se detendrá inmediatamente y se lanzará una excepción inmediatamente después de detectar el primer error de formato.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

En este caso se instruirá al convertidor para intentar continuar con la conversión e ignorar los errores de formato encontrados. En este caso el éxito no está garantizado, pueden ocurrir problemas graves más tarde en el convertidor, y en tal caso se lanzará una excepción con la lista de errores de formato encontrados.
