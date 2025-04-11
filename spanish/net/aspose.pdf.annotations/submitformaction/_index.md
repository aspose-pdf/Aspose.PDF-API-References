---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.SubmitFormAction. Clase que describe la acción de submitform
type: docs
weight: 2640
url: /es/net/aspose.pdf.annotations/submitformaction/
---
## Clase SubmitFormAction

Clase que describe la acción de submit-form.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Inicializa el objeto SubmitFormAction. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Obtiene o establece las banderas de la acción de envío |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Acciones siguientes en secuencia. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL de destino. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Obtiene la cadena para la acción ECMAScript. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Si se establece, cualquier valor de campo enviado que represente fechas se convertirá al formato estándar. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Si se establece, la entrada F del FDF enviado será una especificación de archivo que contiene un flujo de archivo incrustado que representa el archivo PDF desde el cual se está enviando el FDF. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Si se establece, el FDF enviado excluirá la entrada F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Si se establece, incluirá solo aquellas anotaciones de marcado cuya entrada T coincida con el nombre del usuario actual. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Si se borra, el array de Campos especifica qué campos incluir en el envío. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Si se establece, los nombres y valores de los campos se enviarán en formato de formulario HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Si se establece, los nombres y valores de los campos se enviarán utilizando una solicitud HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Si se establece, el archivo FDF enviado incluirá todas las anotaciones de marcado en el documento PDF subyacente. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Si se establece, el archivo FDF enviado incluirá el contenido de todas las actualizaciones incrementales. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Si se establece, todos los campos designados por el array de Campos y la bandera Incluir/Excluir se enviarán. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Si se establece, las coordenadas del clic del mouse que causó la acción de submit-form se transmitirán como parte de los datos del formulario. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Si se establece, el documento se enviará como PDF, utilizando el tipo de contenido MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Si se establece, los nombres y valores de los campos se enviarán como XFDF. |

### Véase también

* clase [PdfAction](../pdfaction/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblado [Aspose.PDF](../../)