---
title: "SubmitFormAction"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que describe la acción submit-form."
type: docs
weight: 810
url: /es/python-net/aspose.pdf.annotations/submitformaction/
---

## SubmitFormAction class

Clase que describe la acción submit-form.

El tipo SubmitFormAction expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| SubmitFormAction() | Inicializa el objeto SubmitFormAction. |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| next | Acciones siguientes en la secuencia. |
| banderas | Obtiene o establece banderas de la acción de envío. |
| url | URL de destino. |
| EXCLUDE | Si está vacío, la matriz Fields especifica qué campos incluir en el envío. |
| INCLUDE_NO_VALUE_FIELDS | Si se establece, todos los campos designados por la matriz Fields y la bandera Include/Exclude se enviarán. |
| EXPORT_FORMAT | Si se establece, los nombres y valores de los campos se enviarán en formato de formulario HTML. |
| GET_METHOD | Si se establece, los nombres y valores de los campos se enviarán usando una solicitud HTTP GET. |
| SUBMIT_COORDINATES | Si se establece, las coordenadas del clic del ratón que provocó la acción submit-form se transmitirán como parte de los datos del formulario. |
| XFDF | Si se establece, los nombres y valores de los campos se enviarán como XFDF. |
| INCLUDE_APPEND_SAVES | Si se establece, el archivo FDF enviado incluirá el contenido de todas las actualizaciones incrementales. |
| INCLUDE_ANNOTATIONS | Si se establece, el archivo FDF enviado incluirá todas las anotaciones de marcado en el documento PDF subyacente. |
| SUBMIT_PDF | Si se establece, el documento se enviará como PDF, usando el tipo de contenido MIME application/pdf. |
| CANONICAL_FORMAT | Si se establece, cualquier valor de campo enviado que represente fechas se convertirá al formato estándar. |
| EXCL_NON_USER_ANNOTS | Si se establece, solo incluirá aquellas anotaciones de marcado cuyo registro T coincida con el nombre del usuario actual. |
| EXCL_F_KEY | Si se establece, el FDF enviado excluirá la entrada F. |
| EMBED_FORM | Si se establece, la entrada F del FDF enviado será una especificación de archivo que contiene un <br/>            flujo de archivo incrustado que representa el archivo PDF del cual se está enviando el FDF. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

