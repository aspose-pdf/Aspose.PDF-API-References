---
title: "PKCS7"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, <br/>            PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5.<br/>            El resumen SHA1 del rango de bytes del documento está encapsulado en el campo SignedData de PKCS#7."
type: docs
weight: 190
url: /es/python-net/aspose.pdf.forms/pkcs7/
---

## PKCS7 class

Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, <br/>            PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5.<br/>            El resumen SHA1 del rango de bytes del documento está encapsulado en el campo SignedData de PKCS#7.

El tipo PKCS7 expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PKCS7() | Inicializa una nueva instancia de la clase [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/). |
| PKCS7(pfx, password) | Inicializa una nueva instancia de la clase PKCS7 |
| PKCS7(pfx, password) | Inicializa una nueva instancia de la clase PKCS7 |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| custom_appearance | Obtiene/establece la apariencia personalizada. |
| authority | El nombre de la persona o autoridad que firma el documento. |
| date | El momento de la firma. |
| location | El nombre del host de la CPU o la ubicación física de la firma. |
| reason | La razón de la firma, como (I agreeРІР‚В¦). |
| contact_info | Información proporcionada por el firmante para permitir que el destinatario contacte al firmante <br/>            para verificar la firma, p. ej. un número de teléfono. |
| byte_range | Una matriz de pares de enteros (desplazamiento de byte inicial, longitud en bytes) <br/>             que describirá el rango exacto de bytes para el cálculo del resumen. |
| timestamp_settings | Obtiene/establece la configuración de marca de tiempo. |
| ocsp_settings | Obtiene/establece la configuración OCSP. |
| use_ltv | Obtiene/establece la bandera de validación LTV. |
| show_properties | Forzar a mostrar/ocultar las propiedades de la firma.<br/>            En caso de que ShowProperties sea true, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar):<br/>            -------------------------------------------<br/>            Firmado digitalmente por {certificate subject}<br/>            Fecha: {signature.Date}<br/>            Motivo: {signature.Reason}<br/>            Ubicación: {signature.Location}<br/>            -------------------------------------------<br/>            donde {X} es un marcador de posición para el valor X. Además, la firma puede tener una imagen; en este caso, las cadenas listadas se colocan sobre la imagen.<br/>            ShowProperties es true por defecto. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| verify() | Verifica el documento respecto a esta firma y devuelve true si el documento es válido <br/>            o false en caso contrario. |

### Ver también

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

