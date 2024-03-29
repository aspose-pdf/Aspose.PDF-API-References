---
title: PdfSaveOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Guardar opciones para exportar a formato Pdf
type: docs
weight: 6080
url: /es/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Guardar opciones para exportar a formato Pdf

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtiene o establece un valor booleano que indica que el objeto de respuesta se cerrará después de que el documento se guarde en la respuesta. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname) { get; set; } | Nombre de fuente utilizado de manera predeterminada para fuentes que no están en la computadora. Cuando el documento PDF que se guarda en PDF contiene fuentes que no están disponibles en el documento mismo y en el dispositivo, la API reemplaza estas fuentes con la fuente predeterminada (si la fuente con[`DefaultFontName`](./defaultfontname) se encuentra en el dispositivo) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Formato de guardado de datos. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath) { get; set; } | Ruta para archivos temporales. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Devolución de llamada para manejar cualquier advertencia generada. WarningHandler devuelve el elemento de enumeración ReturnAction especificando Continuar o Anular. Continuar es la acción predeterminada y la operación Guardar continúa; sin embargo, el usuario también puede devolver Anular, en cuyo caso la operación Guardar debe cesar. |

### Ver también

* class [SaveOptions](../saveoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
