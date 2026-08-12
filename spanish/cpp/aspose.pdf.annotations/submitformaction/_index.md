---
title: "Clase Aspose::Pdf::Annotations::SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::SubmitFormAction. Clase que describe la acción de envío de formulario en C++."
type: docs
weight: 11000
url: /es/cpp/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class


Clase que describe la acción de envío de formulario.

```cpp
class SubmitFormAction : public Aspose::Pdf::Annotations::PdfAction
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Flags](./get_flags/)() | Obtiene las banderas de la acción de envío. |
| [get_Url](./get_url/)() | URL de destino. |
| [set_Flags](./set_flags/)(int32_t) | Establece las banderas de la acción de envío. |
| [set_Url](./set_url/)(const System::SharedPtr\<FileSpecification\>\&) | URL de destino. |
| [SubmitFormAction](./submitformaction/)() | Inicializa el objeto [SubmitFormAction](./). |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [CanonicalFormat](./canonicalformat/) | Si está establecido, cualquier valor de campo enviado que represente fechas se convertirá al formato estándar. |
| static constexpr [EmbedForm](./embedform/) | Si está establecido, la entrada F del FDF enviado será una especificación de archivo que contiene un flujo de archivo incrustado que representa el archivo PDF del cual se envía el FDF. |
| static constexpr [ExclFKey](./exclfkey/) | Si está establecido, el FDF enviado excluirá la entrada F. |
| static constexpr [ExclNonUserAnnots](./exclnonuserannots/) | Si está establecido, solo incluirá aquellas anotaciones de marcado cuya entrada T coincida con el nombre del usuario actual. |
| static constexpr [Exclude](./exclude/) | Si está vacío, la matriz Fields especifica qué campos incluir en el envío. |
| static constexpr [ExportFormat](./exportformat/) | Si está establecido, los nombres y valores de los campos se enviarán en formato de formulario HTML. |
| static constexpr [GetMethod](./getmethod/) | Si está configurado, los nombres de campo y los valores se enviarán usando una solicitud HTTP GET. |
| static constexpr [IncludeAnnotations](./includeannotations/) | Si está configurado, el archivo FDF enviado debe incluir todas las anotaciones de marcado en el documento PDF subyacente. |
| static constexpr [IncludeAppendSaves](./includeappendsaves/) | Si está configurado, el archivo FDF enviado debe incluir el contenido de todas las actualizaciones incrementales. |
| static constexpr [IncludeNoValueFields](./includenovaluefields/) | Si está configurado, se enviarán todos los campos designados por la matriz Fields y la bandera Incluir/Excluir. |
| static constexpr [SubmitCoordinates](./submitcoordinates/) | Si está configurado, las coordenadas del clic del ratón que provocó la acción submit-form se transmitirán como parte de los datos del formulario. |
| static constexpr [SubmitPdf](./submitpdf/) | Si está configurado, el documento se enviará como PDF, usando el tipo de contenido MIME application/pdf. |
| static constexpr [Xfdf](./xfdf/) | Si está configurado, los nombres de campo y los valores se enviarán como XFDF. |
## Ver también

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
