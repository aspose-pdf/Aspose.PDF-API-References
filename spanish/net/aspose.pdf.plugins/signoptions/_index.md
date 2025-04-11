---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.SignOptions. Representa las opciones de firma para el plugin de firma
type: docs
weight: 9250
url: /es/net/aspose.pdf.plugins/signoptions/
---
## Clase SignOptions

Representa las opciones de firma para el plugin [`Signature`](../signature/).

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Inicializa una nueva instancia del objeto `SignOptions` con opciones predeterminadas. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Inicializa una nueva instancia del objeto `SignOptions` con opciones predeterminadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Cierra los flujos de entrada después de que se complete la operación. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Cierra los flujos de salida después de que se complete la operación. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | El contacto de la firma. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Devuelve la colección de datos del plugin OrganizerOptions. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | La ubicación de la firma. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | El nombre del campo de firma existente. Nulo para crear un nuevo campo. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Obtiene la colección de objetivos añadidos para guardar los resultados de la operación. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | El número de página en la que se realiza la firma. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | La razón de la firma. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | El rectángulo de la firma. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | La visibilidad de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Añade una nueva fuente de datos a la colección de datos del plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Añade una nueva fuente de datos a la colección de datos del plugin PdfOrganizer. |

### Ver También

* clase [OrganizerBaseOptions](../organizerbaseoptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblaje [Aspose.PDF](../../)