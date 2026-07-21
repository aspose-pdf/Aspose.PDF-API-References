---
title: "Enumeración Aspose::Pdf::XslFoLoadOptions::ParsingErrorsHandlingTypes"
linktitle: "ParsingErrorsHandlingTypes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración Aspose::Pdf::XslFoLoadOptions::ParsingErrorsHandlingTypes. El documento XSLFO de origen puede contener errores de formato. Esta enumeración enumera las posibles estrategias para manejar dichos errores de formato en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf/xslfoloadoptions/parsingerrorshandlingtypes/
---
## ParsingErrorsHandlingTypes enum


El documento XSLFO fuente puede contener errores de formato. Este enum enumera las posibles estrategias para manejar dichos errores de formato.

```cpp
enum class ParsingErrorsHandlingTypes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| TryIgnore | 0 | En este caso, se indicará al convertidor que intente continuar con la conversión e ignore los errores de formato encontrados. En este caso, el éxito no está garantizado; pueden ocurrir problemas graves más adelante en el convertidor, y en tal situación se lanzará una excepción con la lista de errores de formato encontrados. |
| ThrowExceptionImmediately | 1 | En este caso, la conversión se detendrá inmediatamente y se lanzará una excepción justo después de detectar el primer error de formato. |
| InvokeCustomHandler | 2 | Este es el método más ágil: el código personalizado debe proporcionar (en la propiedad WarningCallback) un controlador especial que se llamará cuando se detecte un error de formato. Ese controlador puede, por ejemplo, registrar o contar errores, etc., y proporcionará una decisión sobre si el procesamiento puede continuar para este u otro error. |

## Ver también

* Class [XslFoLoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
