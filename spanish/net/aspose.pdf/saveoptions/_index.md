---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.SaveOptions. El tipo SaveOptions mantiene un nivel de abstracción sobre las opciones de guardado individuales
type: docs
weight: 9870
url: /es/net/aspose.pdf/saveoptions/
---
## Clase SaveOptions

El tipo SaveOptions mantiene un nivel de abstracción sobre las opciones de guardado individuales

```csharp
public abstract class SaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de pdf a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de datos a guardar. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento del enum ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de guardado debe cesar. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)