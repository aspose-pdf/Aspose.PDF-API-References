---
title: EpubLoadOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Contiene opciones para cargar/importar un archivo EPUB en un documento pdf.
type: docs
weight: 2090
url: /es/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Contiene opciones para cargar/importar un archivo EPUB en un documento pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EpubLoadOptions](epubloadoptions#constructor)() | Crea opciones de carga predeterminadas para convertir un archivo EPUB en un documento pdf. Tamaño de página PDF predeterminado: A4 300 ppp 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions#constructor_1)(SizeF) | Crea opciones de carga con el tamaño de página especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Representa el formato de archivo que[`LoadOptions`](../loadoptions) describe. |
| [Margin](../../aspose.pdf/epubloadoptions/margin) { get; set; } | Obtiene la referencia del objeto que representa la información de margen. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize) { get; } | Obtiene o establece el tamaño de la página de salida para importar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Devolución de llamada para manejar cualquier advertencia generada. WarningHandler devuelve el elemento de enumeración ReturnAction especificando Continuar o Anular. Continuar es la acción predeterminada y la operación de carga continúa; sin embargo, el usuario también puede devolver Anular, en cuyo caso la operación de carga debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode) | Representa el modo de uso del área de márgenes: define el tratamiento de las instrucciones (si las hay) de CSS del documento importado relacionado con el uso de los márgenes. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode) | ¡ATENCIÓN! La función se implementó pero aún no se colocó en la API pública desde que se reveló un problema de bloqueo en la capa OSHARED para el documento de muestra. Representa el modo de uso del tamaño de la página durante la conversión. Formatos (como HTML, EPUB, etc.), por lo general tienen un diseño flotante , por lo tanto, permite ajustar el tamaño de página requerido . Pero a veces el contenido tiene posiciones horizontales especificadas o un tamaño que no permite colocar el contenido en el tamaño de página requerido. En tal caso, podemos definir qué se debe hacer en este caso (es decir, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido de resultado documento PDF). |

### Ver también

* class [LoadOptions](../loadoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
